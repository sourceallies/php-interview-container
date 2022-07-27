# php-interview-container

A simple unittest enabled PHP 8 devcontainer with Apache and Node 16

This is based on the dev container here: https://github.com/microsoft/vscode-dev-containers/tree/main/containers/php

It is recommended to run this as a dev container for easy of use. See the docs here: https://code.visualstudio.com/docs/remote/containers

## Running Tests In Dev Container

1. `composer install`
2. `vendor/bin/phpunit --testdox test/unit`
