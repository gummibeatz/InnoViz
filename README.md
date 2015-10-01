# InnoViz
Interactive visualization of the innovation space

## PostgreSQL setup courtesy of [digital ocean](https://www.digitalocean.com/community/tutorials/how-to-use-postgresql-with-your-django-application-on-ubuntu-14-04)
`>psql`
`CREATE DATABASE innoviz;`
`CREATE USER innovizuser WITH PASSWORD 'password';`
`ALTER ROLE innovizuser SET client_encoding TO 'utf8';`
`ALTER ROLE innovizuser SET default_transaction_isolation TO 'read committed';`
`ALTER ROLE innovizuser SET timezone TO 'UTC';`
`'GRANT ALL PRIVILEGES ON DATABASE innoviz TO innovizuser;`

