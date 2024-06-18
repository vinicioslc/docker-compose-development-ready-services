# Docker Compose Preset Files Ready to Use

# About Structure

Every service should use a unique port to avoid conflicts and allow spinup all services
to make easy this is a list about services using ports.

| Name    | port  | user | password |
| :------ | :---: | :---:| --- |
| mariadb | 3306  | root | root |
| redis   | 6379  |   | root |
| mongodb | 27017  |root | root |

## Objective

This repo its indeed to have ready to use docker-compose.yaml files for development purposes of any service needed from database to fake email servers just spinup in some folder and use

## About Contribution ? Well... keep free to send PRs

The amount of folders can become unmaintainable in future... but we will keep adding.
