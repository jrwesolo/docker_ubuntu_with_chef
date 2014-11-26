# Ubuntu with Chef

This is a docker image based on the official [Ubuntu](https://registry.hub.docker.com/_/ubuntu/) docker image. The changes to the image are:

* Timezone set to UTC
* Update system using apt
* Install a few core packages
* Install chef-client (latest)

Currently, there are tags for:

* Ubuntu 12.04
* Ubuntu 14.04
* latest

These match up to the existing tags in the official [Ubuntu](https://registry.hub.docker.com/_/ubuntu/tags/manage/) docker repository.
