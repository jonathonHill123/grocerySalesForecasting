# README #

Welcome!

### What is this repository for? ###

* Common research environment

### How do I get set up? ###

For the setup to work, you will need to have Docker installed. If you don't have it you can get it here https://www.docker.com. Download and install a version for your OS.

1. ```git clone repo```
2. ```cd repo```
3. ```mkdir data```
4. ```mkdir notebooks```
5. ```docker-compose up -d```
6. ```docker ps -a```, this step will list all the available containers. Get the 'container_id' to use in step 7 from here.
7. ```docker logs -f 'container_id'```, then click the link; should bring up notebook server in browser
8. get data from kaggle https://www.kaggle.com/c/favorita-grocery-sales-forecasting/data and put it into data directory you created in step 3.
