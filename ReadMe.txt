-----------------------------Step to run backend locally------------------------------------
step 1: install docker on your PC. Link:https://docs.docker.com/desktop/install/windows-install ( use youtube if confused by steps in the link)
step 2: once docker is properly installed create a network by opening CMD or gitbash paste : docker network create --driver bridge local-diskie-net

--------------------------------create database containers------------------------------------
step 1: go inside the individual folders inside folder DBs.
step 2: for each folder with a file named docker-compose run the command 'docker-compose up -d' using cmd.
step 3: repeat step 2 for all other folders like (Drivers)
step 4: repeat step 2 for back-end folder but with command 'docker-compose up --build -d' (running 'discover-server' first).


