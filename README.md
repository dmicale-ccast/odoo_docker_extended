About this Repo
======

This is the Git repo of the official Docker image for [Odoo](https://registry.hub.docker.com/_/odoo/). See the Hub page for the full readme on how to use the Docker image and for information regarding contributing and issues.

The full readme is generated over in [docker-library/docs](https://github.com/docker-library/docs), specifically in [docker-library/docs/odoo](https://github.com/docker-library/docs/tree/master/odoo).


=====

How to build it? 

- Go to the version you want to build
- Ensure that the Dockerfile contains patches (TODO: Build the patches)
- docker image build -t odoo-docker-extended:TAGNAME .