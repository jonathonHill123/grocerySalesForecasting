# README #

Welcome!

### What is this repository for? ###

* Common research environment - doesn't support version controlling notebooks yet

### How do I get set up? ###

1. git clone repo
2. cd repo
3. mkdir data
4. mkdir notebooks
5. docker-compose up -d
6. docker logs -f 'container_name', then click the link; should bring up notebook server in browser
7. get data from kaggle https://www.kaggle.com/c/favorita-grocery-sales-forecasting/data and put it into data directory you created in step 3.