# Checkpoint 6 - Technical Documentation 

**What does the services: block do?**
The `services:` block defines the containers in your multi-tier application. It tells Docker exactly what to build. In this deployment, it defines the MariaDB database and the Nextcloud app. It also holds their configurations, like image names, open ports, and environment variables. 

**How did the Nextcloud app container know how to find the database container?**
Nextcloud finds the database using the `MYSQL_HOST=database` environment variable. The word `database` exactly matches the service name of the MariaDB container in the YAML file. Docker Compose automatically creates a network that links the containers together. It lets them talk to each other using their service names.

**What is the difference between docker run and docker-compose up -d?**
You use `docker run` to deploy a single container manually. You use `docker-compose up -d` to deploy an entire multi-container stack simultaneously. Docker Compose uses a YAML file as Infrastructure as Code (IaC) to handle all configurations at once. The `-d` flag runs the process in the background.