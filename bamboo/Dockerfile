FROM centos
MAINTAINER Viktor Farcic, "viktor.farcic@everis.com"

# General
RUN /usr/sbin/useradd --create-home --home-dir /usr/local/bamboo --shell /bin/bash bamboo

# JDK
RUN yum install java-1.7.0-openjdk