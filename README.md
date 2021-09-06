# <sub><sup>@thedigbee/</sup></sub> actions

Github actions relating to the Digbee ecosystem

## publish-image

First, it builds & publishes the Docker image of a specific service to the Github's Docker registry.

Then, it recreates and restarts the associated Docker container s that the new image takes effect.

### Example usage in a workflow file

```yml
on:
  push:
    branches:
      - develop
      - main
      - master

jobs:
  build_and_publish_docker_image:
    name: Build & push Docker image and restart its associated service
    runs-on: ubuntu-latest
    permissions:
      packages: write
      contents: read

    steps:
      - if: github.ref == 'refs/heads/develop'
        name: Staging build (develop)
        uses: thedigbee/actions/publish-image@master
        with:
          github-token: ${{ secrets.GITHUB_TOKEN }}
          ssh-server: ${{ secrets.MY_STAGING_SERVER }}
          ssh-user: ${{ secrets.MY_STAGING_USER }}
          ssh-key: ${{ secrets.MY_STAGING_PRIVATE_KEY }}
          docker-compose-path: /home/user/docker-compose.yml,/home/user/docker-compose.staging.yml

      - if: github.ref != 'refs/heads/develop'
        name: Production build (main/master)
        uses: thedigbee/actions/publish-image@master
        with:
          github-token: ${{ secrets.GITHUB_TOKEN }}
          ssh-server: ${{ secrets.MY_PRODUCTION_SERVER }}
          ssh-user: ${{ secrets.MY_PRODUCTION_USER }}
          ssh-key: ${{ secrets.MY_PRODUCTION_PRIVATE_KEY }}
          docker-compose-path: /home/user/docker-compose.yml,/home/user/docker-compose.production.yml
```

## Relevant links

- [Release managment for actions](https://docs.github.com/en/actions/creating-actions/about-actions#using-release-management-for-actions)
- [`if` aren't supported with `uses`](https://github.community/t/composite-action-if-isnt-supported-with-uses/199797)
- [Support for `[skip ci]`](https://github.blog/changelog/2021-02-08-github-actions-skip-pull-request-and-push-workflows-with-skip-ci/)
- [Actions in private repos release expected for Q4](https://github.com/github/roadmap/issues/74)
