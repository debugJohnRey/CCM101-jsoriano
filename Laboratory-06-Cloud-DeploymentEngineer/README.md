# Checkpoint 6 - Technical Documentation 

## Mission Overview
The goal is to deploy a two-tier private cloud storage solution for a client. This mission replaces manual commands with Infrastructure as Code (IaC). It uses Docker Compose to deploy a Nextcloud web container and a MariaDB database container simultaneously.

## Objectives
* Explain the concept of a multi-tier application architecture.
* Understand the purpose and structure of a `docker-compose.yml` file.
* Use a Linux command-line text editor (nano) to create configuration files.
* Deploy a multi-container application (Nextcloud + Database) using Docker Compose.
* Document deployment procedures and Infrastructure as Code (IaC) principles using Markdown.

## Commands Executed
* `mkdir nextcloud-deployment` - Creates a new folder for the project.
* `cd nextcloud-deployment` - Moves inside the new folder.
* `nano docker-compose.yml` - Opens the Linux text editor to write the configuration file.
* `docker-compose up -d` - Deploys the multi-container stack in the background.
* `docker-compose ps` - Verifies that the deployed containers are running.
* `docker-compose down` - Shuts down and removes the entire container infrastructure.

## Skills Learned
* Infrastructure as Code (IaC) principles.
* Multi-tier application deployment.
* YAML file formatting and syntax.
* Docker Compose orchestration and networking.
* Markdown documentation.