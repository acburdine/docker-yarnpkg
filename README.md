# docker-yarnpkg
Docker builds for the [Yarn package manager](https://yarnpkg.com)

## Reasoning
There already exists a great docker image for yarn [here](https://hub.docker.com/r/kkarczmarczyk/node-yarn/). However, it uses `npm` to install yarn, which is currently deprecated. This repo follows all of the public node docker versions, and installs Yarn using the recommended methods on the yarn website.

