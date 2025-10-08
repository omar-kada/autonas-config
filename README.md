# AutoNAS-config

This is a configuration repository for the tool [AutoNAS](https://github.com/omar-kada/autonas), it allows to manage docker compose stacks in a homeserver through modifications in a git repository

## structure

the configuration is composed of two parts :

1. global yaml config file(s) which will contain global and service-specific variables
2. docker-compose yaml files (inside `services`) which define the different services that could be deployed
