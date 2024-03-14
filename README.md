loucxf@loucxf-Latitude-5590:~/work/flyway_migration$ docker run --rm -v $(pwd)/sql:/flyway/sql -v $(pwd)/conf:/flyway/conf flyway/flyway migrate
WARNING: Storing migrations in 'sql' is not recommended and default scanning of this location may be deprecated in a future release
WARNING: This version of Flyway is out of date. Upgrade to Flyway 10.10.0: https://rd.gt/3rXiSlV

Flyway OSS Edition 10.9.1 by Redgate

See release notes here: https://rd.gt/416ObMi
Database: jdbc:postgresql://172.17.0.3:5432/postgres (PostgreSQL 16.2)
Successfully validated 2 migrations (execution time 00:00.034s)
Current version of schema "public": 2
Schema "public" is up to date. No migration necessary.
