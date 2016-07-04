# Containerized Polymer Development Environment

This docker container contains the basic tools for Polymer development.

  - Node / NPM
  - Bower
  - Gulp-Cli
  - Polymer-Cli

You can also:
  - create Polymer applications and Polymer elements
  - test and serve the apps and elements
  - build and ship to producion

### Version
1.0

### Installation

```sh
docker run -it -d -p 8080:8080 -v yourprojectpath:node/yourprojectpath tobiashutterer/polymer-dev:latest
```
