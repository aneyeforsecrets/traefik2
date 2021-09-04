# A treafik2 based docker VPS configuration

Generalised docker environment for a VPS, aiming for simple addition of new docker-compose based applications.

## Description

This is primarily for private purposes, but it may help someone else set up something similar. The goal is to have an easily understandable and extendable docker stack that can run on a server of your choice.

## Getting Started

### Dependencies

* Docker
* Docker-compose
* Traefik2

### Installing

* Cloning the repository and running `docker-compose up -d` on the desired apps should do the trick.
* Folders should be owned by $user:docker to avoid permission issues.

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

[Dennis Irrgang](www.irrgang.dev/contact)

## License

This project is licensed under the GNU GPLv3 License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [make-my-server](https://github.com/tomMoulard/make-my-server/tree/master/traefik)
* [nextcloud-docker](https://github.com/nextcloud/docker/blob/master/.examples/docker-compose/with-nginx-proxy/postgres/apache/docker-compose.yml)
* [rafrasenberg](https://rafrasenberg.com/posts/docker-container-management-with-traefik-v2-and-portainer/)
