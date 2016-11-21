# Minimal Docker Bitrise configuration example

You can use the [open source Bitrise CLI](https://github.com/bitrise-io/bitrise)
to run the `bitrise.yml` configuration of this repository.

If you execute `bitrise run docker-run`, it will build and run the docker
image with `docker` directly.

If you have `docker-compose` installed, you can run `bitrise run docker-compose-run`,
which does the same but uses `docker-compose` (and the `docker-compose.yml` configuration,
which you can find in this repository) to build and run the docker image
instead of `docker build` and `docker run` directly.
