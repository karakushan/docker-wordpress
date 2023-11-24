# Docker  + Wordpress (APACHE) + WP_CLI + XDEBUG

## Beginning of work

1. Clone this repository into the root folder of your Wordpress project: ``git clone https://github.com/karakushan/docker-wordpress.git``
2. Copy the [docker-compose.yml](docker-compose.yml) file to the root of your project
3. Run the command ``docker-compose up -d``
4. After creating and running containers, your site should open at: http://localhost:8080

### Executing WP CLI commands

#### References

* https://developer.wordpress.org/cli/commands/

We get the name of the container in which the Wordpress image is running:

``docker ps``

In the console, in the NAMES column, copy the name

Next, execute the command we need:

``sudo docker exec -it %container_name% wp %command_and_parameters% --allow-root``



