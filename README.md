# Ubuntu with Chef

This is a docker image based on the official [Ubuntu](https://registry.hub.docker.com/_/ubuntu/) docker image. The changes to the image are:

* Time zone is set to UTC
* Updated system using apt
* Installation of a few core packages
* Installation of chef-client (latest)

Currently, there are tags for:

* Ubuntu 12.04
* Ubuntu 14.04

These match up to the existing tags in the official [Ubuntu](https://registry.hub.docker.com/_/ubuntu/tags/manage/) docker repository.
