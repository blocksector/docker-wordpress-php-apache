# Pseudo-Opinionated docker base for wordpress + php + apache

A port of Docker Wordpress image that allows the user to dynamically change PHP, Apache and Wordpress version as they suits them. It does not have MySQL database service allowing this container to connect to any MySQL container in your Docker.

**Not yet tested for Kubernetes or Swarms


## To use

1. Copy .env.sample as .env (do not commit .env file) 
2. Set your environment variables to .env file NOT to .env.sample
3. Create database // TODO: a guide for spawning MySQL instance
4. run $ docker-compose up -d

## Change Logs

07-28-2023: Initial commit. Base Docker compose file consuming .env variables
