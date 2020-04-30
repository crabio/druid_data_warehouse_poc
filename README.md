# druid_data_warehouse_poc
Data warehouse based on Druid Proof Of Concept

## Init

1. `git submodule update --init  --recursive`
2.  Create folder for data: `mkdir storage; chmod 777 storage`
3.  Create folder for jupyterlab: `mkdir jupyterlab; chmod 777 jupyterlab`
4.  Create folder for zeppelin: `mkdir zeppelin; chmod 777 zeppelin`

## Run

1. Remove previous containers: `docker-compose down --remove-orphans`
2. Run all containers: `docker-compose up -d`