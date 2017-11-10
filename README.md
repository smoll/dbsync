# dbsync
Tiny utility for backing up Postgres or MySQL databases and safely populating a local DB

## Goals

1. Small, statically linked binary that you can run anywhere that `pg_dump` or `mysqldump` is installed
2. Tell user what it is about to do before doing something potentially destructive
3. Give simple recipes/examples for using this with dockerized DBs
