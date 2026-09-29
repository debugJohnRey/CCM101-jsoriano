# Checkpoint 2 -  Research: Multi-Tier Architecture

A **Two-Tier Architecture** is a software architecture pattern where the presentation layer (client/web interface) and the data layer (database) are kept separate but communicate with each other to form a complete application. 

## The Web/Application Tier
The role of the Web/Application Tier is to act as the front-facing component of the system. It is responsible for serving the user interface, handling incoming HTTP requests from users' web browsers, and securely passing information back and forth between the user and the database. 

## The Database Tier
The role of the Database Tier is to act as the backend storage component. It is entirely responsible for storing persistent data, managing user credentials, and organizing file metadata so that information remains saved and accessible even after the system restarts.

## Why Separate Them?
Separating the web server and database improves overall security by isolating sensitive user data from the public-facing web interface. It also enhances reliability, ensuring that if the web server crashes or requires maintenance, your persistent data remains safely untouched in the separate database container. Furthermore, this separation makes the system much easier to update or scale independently based on the specific resource needs of each tier.