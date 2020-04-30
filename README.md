# druid_data_warehouse_poc
Data warehouse based on Druid Proof Of Concept

## Init

1. `git submodule update --init  --recursive`
2.  Create folder for data: `mkdir storage & chown 777 storage`

## Run

1. Remove previous containers: `docker-compose down --remove-orphans`
2. Run all containers: `docker-compose up -d`