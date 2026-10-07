# Checkpoint 6 - Technical Documentation 

## Mission Overview
In this mission, I stepped into the role of a Cloud Operations Engineer (Site Reliability Engineer) at CloudNova Technologies. The goal was to establish a performance baseline for a Linux server, deploy a containerized Nginx application, generate artificial web traffic, and hunt down performance metrics and system logs to prove the application is healthy and ready for a massive traffic surge.

## Objectives
* Utilize native Linux command-line tools to monitor host CPU, Memory, and Disk capacity.
* Deploy a web container and track its real-time performance using Docker metrics.
* Generate web traffic and extract application access logs for analysis.
* Translate raw performance data into a readable technical report using Markdown.

## Monitoring Commands Executed
* `free -h` : Checked the server's current memory (RAM) usage.
* `df -h` : Checked the server's available disk storage.
* `top` : Viewed active running processes and CPU load.
* `docker logs client-website` : Retrieved application logs to find HTTP 200 and HTTP 404 responses.
* `docker stats` : Viewed a live dashboard of container CPU and Memory consumption.

## Skills Learned
* Establishing hardware performance baselines using Linux CLI tools.
* Simulating web traffic and intentionally triggering HTTP errors for testing.
* Extracting and analyzing containerized application logs.
* Verifying container resource efficiency using real-time Docker metrics.
* Documenting observability metrics and system health accurately in Markdown.