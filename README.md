# <sub><sup>@thedigbee/</sup></sub> actions

Github Action used to accomplish two things:

1. Build & push the Docker image of a Digbee service to the Github's Docker registry.
2. Rebuild and restart the service container to use the new image.

## Relevant links

- [Release managment for actions](https://docs.github.com/en/actions/creating-actions/about-actions#using-release-management-for-actions)
- [`if` aren't supported with `uses`](https://github.community/t/composite-action-if-isnt-supported-with-uses/199797)
