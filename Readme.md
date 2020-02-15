# Laravel Docker

Create the necessary folders:
`./mysql`, `./src`

Modify Database credentials in docker-compose if needed.
After running `docker-compose up` install laravel app inside of
`./src` using composer.
Update env varaibles in `.env`.
Also `docker exec -it ${phpContainer}` and change ownership of `./storage` to www-data.
