# Docker  + Wordpress + WP_CLI +

## Executing WP CLI commands

### References

* https://developer.wordpress.org/cli/commands/

We get the name of the container in which the wordpress image is running:

``docker ps``

In the console, in the NAMES column, copy the name

Next, execute the command we need:

``sudo docker exec -it %container_name% wp %command_and_parameters% --allow-root``



