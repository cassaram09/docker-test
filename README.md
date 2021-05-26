Dockerized website, with a NextJS frontend, Strapi powered headless CMS, and Nginx proxy server.

# Installation & Quickstart

1. Install Docker
2. `docker-compose up` to build and run

# Deployment

## client

Deployed to Zeit/Vercel. Push to master.

## strapi

Deployed to heroku. Push to heroku remote.

## nginx

Development only.

# Application Structure

## strapi

Strapi CMS

## bin

Executable utilities - eg pg_backup for making database volume backups.

## client

NextJS frontend

## nginx

Nginx proxy server for client and api during development

## postgres

Stores PG backups
