Demo mongodb by using docker

the sample inventory data is referenced from [here](https://raw.githubusercontent.com/mongodb/docs-assets/primer-dataset/inventory.crud.json)

## Step1 - install docker & run
1. install docker
2. `docker-compose up -d`

## Step2 - check import correctly
1. `docker exec -it your-mongo-container bash`
2. `show dbs`
3. `use test`
4. `db.inventory.find()`
