[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/cockatoo.svg)](https://hub.docker.com/r/rubygem/cockatoo/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/cockatoo.svg)](https://hub.docker.com/r/rubygem/cockatoo/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/cockatoo.svg)](https://hub.docker.com/r/rubygem/cockatoo/)
[![Gem Downloads](https://img.shields.io/gem/dt/cockatoo.svg)](https://rubygems.org/gems/cockatoo/)
# cockatoo

Auto-Generated Docker image for cockatoo to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/cockatoo`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/cockatoo`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/cockatoo`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/cockatoo/)
