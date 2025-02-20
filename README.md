# WordPress Docker Setup for AWS EC2

This repository contains a Bash script to automate the installation and setup of WordPress using Docker on an AWS EC2 instance.

## Features
- Installs Docker and Docker Compose.
- Configures WordPress and MySQL using a `docker-compose.yml` file.
- Prompts for secure database credentials.
- Persists data using Docker volumes.

## Prerequisites
- An AWS EC2 instance (e.g., Amazon Linux 2).
- Security group allowing inbound traffic on port `80` (HTTP).

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/wordpress-docker-ec2.git
   cd wordpress-docker-ec2
