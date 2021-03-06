### [0.6.1](https://github.com/thedigbee/actions/compare/v0.6.0...v0.6.1) (2022-07-06)


### Bug Fixes

* remove no longer used input ([fc98fa5](https://github.com/thedigbee/actions/commit/fc98fa51e8722e8138fd7cbba1547572df7fd6e4))

## [0.6.0](https://github.com/thedigbee/actions/compare/v0.5.3...v0.6.0) (2022-07-06)


### New Features

* add job to restart a given service ([bb6aae7](https://github.com/thedigbee/actions/commit/bb6aae7e7713aaf1392ddb5e1f8647b8c13ae163))

### [0.5.3](https://github.com/thedigbee/actions/compare/v0.5.2...v0.5.3) (2022-04-06)


### Bug Fixes

* receive full image tag from params instead of building it from repo name + short image tag ([51bc3cd](https://github.com/thedigbee/actions/commit/51bc3cd9a6481053c917e321b39e564a41506c3a))

### [0.5.2](https://github.com/thedigbee/actions/compare/v0.5.1...v0.5.2) (2022-04-06)


### Bug Fixes

* remove 'all' keyword for simplicity of the script ([fba9a1b](https://github.com/thedigbee/actions/commit/fba9a1b6b4219063f6ef94f645f93173534acf09))

### [0.5.1](https://github.com/thedigbee/actions/compare/v0.5.0...v0.5.1) (2022-04-06)


### Bug Fixes

* syntactic issues ([b26673d](https://github.com/thedigbee/actions/commit/b26673d308e12e3af743ea164f69b6e21f5cdb0c))

## [0.5.0](https://github.com/thedigbee/actions/compare/v0.4.14...v0.5.0) (2022-04-06)


### New Features

* support 'all' as value for docker-service-name ([066b4b4](https://github.com/thedigbee/actions/commit/066b4b40efb9cf6dae49d3080067761af77586a1))

### [0.4.14](https://github.com/thedigbee/actions/compare/v0.4.13...v0.4.14) (2022-04-05)


### Bug Fixes

* variable undefined ([e7854d0](https://github.com/thedigbee/actions/commit/e7854d041794e31be1d13f21637b5cc8ac78198d))

### [0.4.13](https://github.com/thedigbee/actions/compare/v0.4.12...v0.4.13) (2022-04-05)


### Bug Fixes

* bad condition ([0d10480](https://github.com/thedigbee/actions/commit/0d1048040f2dff973c3ca8486e81da81e5bd57c2))

### [0.4.12](https://github.com/thedigbee/actions/compare/v0.4.11...v0.4.12) (2022-04-05)


### Styles

* empty line ([eea50b0](https://github.com/thedigbee/actions/commit/eea50b0feb48cb29e0e2d9e653bafeb8462a4c17))

### [0.4.11](https://github.com/thedigbee/actions/compare/v0.4.10...v0.4.11) (2022-04-05)


### Bug Fixes

* don't do any replacement if DOCKER_IMAGE_TAG is empty ([aa2d65b](https://github.com/thedigbee/actions/commit/aa2d65b4fefa72e54b9eff92ec4997de88d650be))

### [0.4.10](https://github.com/thedigbee/actions/compare/v0.4.9...v0.4.10) (2022-04-05)


### Bug Fixes

* remove useless Docker logging commands ([864e191](https://github.com/thedigbee/actions/commit/864e191dfdd73b6203765709cedd8e640921fd4d))

### [0.4.9](https://github.com/thedigbee/actions/compare/v0.4.8...v0.4.9) (2022-04-05)


### Bug Fixes

* bad image tag ([7a6d587](https://github.com/thedigbee/actions/commit/7a6d587620a5f1a38675c40b024d829067eb8fd8))

### [0.4.8](https://github.com/thedigbee/actions/compare/v0.4.7...v0.4.8) (2022-04-05)


### Bug Fixes

* bad 'file exists' condition PLUS organization spelling ([4ce43d1](https://github.com/thedigbee/actions/commit/4ce43d1a7483b60cbe8b19789a1a50cc42406de5))

### [0.4.7](https://github.com/thedigbee/actions/compare/v0.4.6...v0.4.7) (2022-04-05)


### Bug Fixes

* change approach to trigger-image-deploy (see body) ([e14d024](https://github.com/thedigbee/actions/commit/e14d0246fc9fc56974676b0eabc2331bd4053b63))
* rename 'docker-compose-override-file-name' to 'docker-compose-path-override' ([29d8b6f](https://github.com/thedigbee/actions/commit/29d8b6fbc0110124ef357e68e4a7a4a8c39b6d39))

### [0.4.6](https://github.com/thedigbee/actions/compare/v0.4.5...v0.4.6) (2022-04-05)


### Bug Fixes

* uncomment tag logic, use echo instead of heredoc due to YAML limitations ([4555016](https://github.com/thedigbee/actions/commit/4555016c27180785264cde6acc6f056209688b49))

### [0.4.5](https://github.com/thedigbee/actions/compare/v0.4.4...v0.4.5) (2022-04-05)


### Bug Fixes

* uncomment tag logic, use echo instead of heredoc due to YAML limitations ([fd9b7d7](https://github.com/thedigbee/actions/commit/fd9b7d73625f6853daabf9f45d02dc6ca113f811))

### [0.4.4](https://github.com/thedigbee/actions/compare/v0.4.3...v0.4.4) (2022-04-05)


### Bug Fixes

* comment out docker-image-tag feature from trigger-image-deploy ([320cc40](https://github.com/thedigbee/actions/commit/320cc40ec11f3d2bf1ae0ed695f0f24be5201d20))

### [0.4.3](https://github.com/thedigbee/actions/compare/v0.4.2...v0.4.3) (2022-04-05)


### Bug Fixes

* use <<-EOF because of indent issues ([8afcf4e](https://github.com/thedigbee/actions/commit/8afcf4e0840b3db9b2c11d094f61406e25a4a3c0))

### [0.4.2](https://github.com/thedigbee/actions/compare/v0.4.1...v0.4.2) (2022-04-05)


### Bug Fixes

* override image tag logic in trigger-image-deploy ([8911d59](https://github.com/thedigbee/actions/commit/8911d59413e6b20cabe17fd97c7b9fff08cc3635))

### [0.4.1](https://github.com/thedigbee/actions/compare/v0.4.0...v0.4.1) (2022-04-04)


### Bug Fixes

* docker-image-tag description ([876f490](https://github.com/thedigbee/actions/commit/876f490c5bee38d41d4e78ceb77dd154ef8d7ea0))

## [0.4.0](https://github.com/thedigbee/actions/compare/v0.3.1...v0.4.0) (2022-04-04)


### New Features

* support for specifying image tag in trigger-image-deploy ([7c89f03](https://github.com/thedigbee/actions/commit/7c89f03eefe8d257f5069c401878acdf67fdc783))

### [0.3.1](https://github.com/thedigbee/actions/compare/v0.3.0...v0.3.1) (2022-04-04)


### Bug Fixes

* normalize trigger-image-deploy definition ([83fa7b2](https://github.com/thedigbee/actions/commit/83fa7b22fae37d99264265316417b4e2d7a428d4))

## [0.3.0](https://github.com/thedigbee/actions/compare/v0.2.6...v0.3.0) (2022-04-04)


### New Features

* trigger-image-deploy action ([3f4c00a](https://github.com/thedigbee/actions/commit/3f4c00a7a908c30ef661336b2c279859d58535f3))

### [0.2.6](https://github.com/thedigbee/actions/compare/v0.2.5-beta-build-add-build-args.1...v0.2.6) (2021-10-20)

### [0.2.5-beta-build-add-build-args.1](https://github.com/thedigbee/actions/compare/v0.2.5-beta-build-add-build-args.0...v0.2.5-beta-build-add-build-args.1) (2021-10-20)


### Miscellaneous Chores

* add reference link to docker-build-args comment ([36b00c7](https://github.com/thedigbee/actions/commit/36b00c7792731d398dc0ca13aa9668debc7db6c7))

### [0.2.5-beta-build-add-build-args.0](https://github.com/thedigbee/actions/compare/v0.2.4...v0.2.5-beta-build-add-build-args.0) (2021-10-19)


### Build System

* add ability to provide build-args to the image building process ([cd7d67f](https://github.com/thedigbee/actions/commit/cd7d67f807f0b74a7e0e8339896e80d7de25a0d8))

### [0.2.4](https://github.com/thedigbee/actions/compare/v0.2.3-beta-fix-docker-pull-and-image-build.0...v0.2.4) (2021-10-13)

### [0.2.3-beta-fix-docker-pull-and-image-build.0](https://github.com/thedigbee/actions/compare/v0.2.2...v0.2.3-beta-fix-docker-pull-and-image-build.0) (2021-10-13)


### Bug Fixes

* changes to how Docker images are pulled and built ([edc0085](https://github.com/thedigbee/actions/commit/edc0085fe9cfaa4e5edd48db81c8e366f96ce243))

### [0.2.2](https://github.com/thedigbee/actions/compare/v0.2.0...v0.2.2) (2021-10-12)


### Bug Fixes

* upgrade deps to remove dep warnings ([36cd85c](https://github.com/thedigbee/actions/commit/36cd85c2b9be12267cc9e95d0ac8fbd7a6f3c4f2))

## [0.2.0](https://github.com/thedigbee/actions/compare/v0.1.13...v0.2.0) (2021-09-29)


### New Features

* bump deps to prevent security warning ([46566e6](https://github.com/thedigbee/actions/commit/46566e669c4f3032d3bed0e4d0af91ac1793df72))
* running npm install with npm 7 ([f601b42](https://github.com/thedigbee/actions/commit/f601b42872f6109c67831e89e7a383a8dbc4d770))

### [0.1.13](https://github.com/thedigbee/actions/compare/v0.1.12-beta-fix-backup-in-publish-image.0...v0.1.13) (2021-09-24)

### [0.1.12-beta-fix-backup-in-publish-image.0](https://github.com/thedigbee/actions/compare/v0.1.11...v0.1.12-beta-fix-backup-in-publish-image.0) (2021-09-24)


### New Features

* add backup db step at the beggining in publish-image action ([2480fcf](https://github.com/thedigbee/actions/commit/2480fcf21566805a64ce73f4b7cee38268ba9126))

### [0.1.11](https://github.com/thedigbee/actions/compare/v0.1.10...v0.1.11) (2021-09-15)


### Bug Fixes

* missing double quotes in bump-prerelease action ([7e30481](https://github.com/thedigbee/actions/commit/7e30481e10b2276a5c12c3aca8d7f0d5f91e5468))

### [0.1.10](https://github.com/thedigbee/actions/compare/v0.1.9...v0.1.10) (2021-09-15)


### Bug Fixes

* absolute reference to sanitize action ([cf29cb4](https://github.com/thedigbee/actions/commit/cf29cb4a1ddac366f7139725ba6a8f387ed1a3ae))

### [0.1.9](https://github.com/thedigbee/actions/compare/v0.1.8...v0.1.9) (2021-09-15)


### Bug Fixes

* output prerelease-tag from bump-prerelease actio ([460a6ea](https://github.com/thedigbee/actions/commit/460a6eae6fc59291f13a054e96902af465660886))

### [0.1.8](https://github.com/thedigbee/actions/compare/v0.1.7...v0.1.8) (2021-09-15)


### Bug Fixes

* param 'branch-ref' in bump-prerelease action ([02379d9](https://github.com/thedigbee/actions/commit/02379d9d1089d72fa3322fb571a04396ee2b209b))

### [0.1.7](https://github.com/thedigbee/actions/compare/v0.1.6-beta-fix-publish-image.0...v0.1.7) (2021-09-09)

### [0.1.6-beta-fix-publish-image.0](https://github.com/thedigbee/actions/compare/v0.1.5...v0.1.6-beta-fix-publish-image.0) (2021-09-09)


### Bug Fixes

* publish-image ([e79bd9c](https://github.com/thedigbee/actions/commit/e79bd9cc5e3a4336b312c3464fc89d8134b7537c))

### [0.1.5](https://github.com/thedigbee/actions/compare/v0.1.4...v0.1.5) (2021-09-08)


### Bug Fixes

* revert author-name ([c547fd2](https://github.com/thedigbee/actions/commit/c547fd2e81ffb90e36716e2973423db73cebd129))

### [0.1.4](https://github.com/thedigbee/actions/compare/v0.1.3...v0.1.4) (2021-09-08)


### Bug Fixes

* change default author-name ([ce17c54](https://github.com/thedigbee/actions/commit/ce17c5461386bd2c5dab395765a0a3855956d8d1))

### [0.1.3](https://github.com/thedigbee/actions/compare/v0.1.2-beta-testing.1...v0.1.3) (2021-09-08)

### [0.1.2-beta-testing.1](https://github.com/thedigbee/actions/compare/v0.1.2-beta-testing.0...v0.1.2-beta-testing.1) (2021-09-08)


### Bug Fixes

* test merge to master ([52ba67c](https://github.com/thedigbee/actions/commit/52ba67cb72155174bd1285a56b3e029d60b6fb3b))
* test skipping [skip ci] ([ad25e6f](https://github.com/thedigbee/actions/commit/ad25e6fd792256316185009bf162fbe97123f5d6))

### [0.1.2-beta-testing.0](https://github.com/thedigbee/actions/compare/v0.1.1...v0.1.2-beta-testing.0) (2021-09-08)


### Bug Fixes

* surround with double quotes bump-release author/email defaults ([8ca122a](https://github.com/thedigbee/actions/commit/8ca122a8d5c1e5302030f3884764e79d90c52bdb))

### [0.1.1](https://github.com/thedigbee/actions/compare/v0.1.0...v0.1.1) (2021-09-08)


### Bug Fixes

* amendment to README.md ([10601d2](https://github.com/thedigbee/actions/commit/10601d2496182dd9f90dd7752228967ab42d4f4d))

## [0.1.0](https://github.com/thedigbee/actions/compare/5cc3320e24b35a8743ba6f7fa34dbec4cba37382...v0.1.0) (2021-09-08)


### New Features

* initial commit ([5cc3320](https://github.com/thedigbee/actions/commit/5cc3320e24b35a8743ba6f7fa34dbec4cba37382))

