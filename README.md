# finexv1-config
This repo contains the Spring Boot application configuration yaml files for the services deployed for finex system in https://github.com/hthakkar275/finexv1. The Configuration Service in https://github.com/hthakkar275/finexv1 uses Spring Cloud Configuation Server so the configuration files in this repository follow the Spring Cloud Configuration naming convention. 

There is one yaml configuration file per service per profile. For example, if the finex system supports product service with `localhost` and `aws` Spring profile, this repository will contain two yaml files for the product service: finex-product-localhost.yml and finex-product-aws.yml. 

This repository already contains the template for the configuraiton files for all application services for `aws` profile deployed in https://github.com/hthakkar275/finexv1

For further details refer to https://github.com/hthakkar275/finexv1/blob/master/README.md.
