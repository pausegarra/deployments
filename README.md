# Services Deployments

This repository is used to handle deployments of my projects to an AWS server with SSL and Docker.

It utilizes the following components:

- **nginx-proxy**: Serves as the entry point and main proxy to other containers.
- **nginxproxy/docker-gen**: Generates the nginx configuration based the provided tmpl file.
- **nginxproxy/acme-companion**: Manages all SSL certificates using Let's Encrypt.

## Mentions

- [Pablo Fredrikson](https://github.com/pablokbs)