# Quick reference

-    **Maintained by**:  
      [georchestra.org](https://www.georchestra.org/)

-    **Where to get help**:  
     the [Georchestra Github repo](https://github.com/georchestra/georchestra), [IRC chat](https://kiwiirc.com/nextclient/irc.libera.chat/georchestra), Stack Overflow

# Featured tags

- `latest`, `23.0.x`

# Quick reference

-	**Where to file issues**:  
     [https://github.com/georchestra/georchestra/issues](https://github.com/georchestra/georchestra/issues)

     [https://github.com/geonetwork/geonetwork-microservices/issues](https://github.com/geonetwork/geonetwork-microservices/issues)

-	**Supported architectures**:   
     [`amd64`](https://hub.docker.com/r/amd64/docker/)

-	**Source of this description**:  
     [docs repo's directory](https://github.com/georchestra/geonetwork-microservices/blob/geor-main/DOCKER_HUB_searching.md)

# What is `georchestra/gn-cloud-searching`

**Gn-cloud-searching** is a module for geOrchestra which offers :
- a search service is an Elasticsearch proxy taking care of user privileges

# How to use this image

As for every other geOrchestra webapp, its configuration resides in the data directory ([datadir](https://github.com/georchestra/datadir)), typically something like /etc/georchestra, where it expects to find a geonetwork/microservices/ogc-api-records sub-directory.

It is recommended to use the official docker composition: https://github.com/georchestra/docker.


## Where is it built

This image is build using the Dockerfile : `Dockerfile-searching` in the repo https://github.com/georchestra/geonetwork-microservices/.

# License

View [license information](https://www.georchestra.org/software.html) for the software contained in this image.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

[//]: # (Some additional license information which was able to be auto-detected might be found in [the `repo-info` repository's georchestra/ directory]&#40;&#41;.)

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
