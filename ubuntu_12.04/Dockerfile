FROM         ubuntu:12.04
MAINTAINER   Jordan Wesolowski <jrwesolo@gmail.com>

RUN echo 'Etc/UTC' > /etc/timezone && dpkg-reconfigure --f noninteractive tzdata

RUN apt-get update -y
RUN apt-get upgrade -y
RUN apt-get install -y curl lsof passwd sudo
RUN apt-get clean

RUN curl -L https://www.opscode.com/chef/install.sh | bash
