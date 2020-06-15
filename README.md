# huginn-single-process-simple-deployment

This is a simple repository containing all files needed to run huginn in the single process configuration with postgres. 
Futhermore, there are labels for Traefik reverse proxy.

> Keep in mind, if you use traefik, you do NOT need to expose port 3000!

## How to use
1. clone
2. modify postgres.env
3. modify secrets.env by providing your own secret.
4. ```docker-compose up -d```
