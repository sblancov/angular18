# How To

## Create a new component

    ng generate component home

where `home` is the name of the new component.


## Create a new interface

    ng generate interface housinglocation

where `housinglocation` is the name of the new interface.


## Create a new service

    ng generate service housing --skip-tests

where `housing` is the name of the new service.

## Run development environment

### Run angular server

    cd first-app_01-hello-world
    ng serve

### Run json server

Execute the next command from the project root directory:

    json-server db.json

## Deployment

    ng deploy first-app --repo=git@github.com:sblancov/angular18.git --base-href=/angular18/
