# PHP project with docker compose


### How to start
In order to start the  environment you need to copy the `./.docker/docker-compose` directory to a folder in your computer. 
For example using this command `cp -rv ./.docker/docker-compose /home/containers/project/`

After that you need to edit `/home/containers/project/docker-compose/docker-compose.yml` and set the correct project paths.

Start the environment by running `docker-compose up -d`
