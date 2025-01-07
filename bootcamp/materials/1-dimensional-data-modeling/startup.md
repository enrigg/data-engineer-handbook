cd .\bootcamp\materials\1-dimensional-data-modeling\
1. docker compose up -d
2. en docker desktop
3. my-postgres-container terminal
4. pg_restore -U $POSTGRES_USER -d $POSTGRES_DB docker-entrypoint-initdb.d/data.dump
 or
   pg_restore -U $POSTGRES_USER -d $POSTGRES_DB data.dump

5. http://localhost:5050/browser/
6. Create server
7. data_expert_data_modelling
8. host.docker.internal
9.docker compose down -v


https://www.dataexpert.io/lessons