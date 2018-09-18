# Requirements:
* [docker](https://docs.docker.com/engine/installation/) installed
* [docker-compose](https://docs.docker.com/compose/install/) installed

# Setup

## Step
1. `git clone https://github.com/maplerichie/docker-compose-postgres-pgadmin4.git`
2. `cd compose-postgres`
3. change respective service's environment parameters at `docker-compose.yml`
3. `docker-compose up`

## Default
* postgres running on 5432
  * user: `postgres`
  * password: `postgres`
* pgadmin4 running on 5050
  * email: `pgadmin@mail.com`
  * password: `pgadmin`
