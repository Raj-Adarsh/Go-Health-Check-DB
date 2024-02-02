# Golang-Health-Check
Simple Golang web application to implement health check for Postgres Database Connection

Useful Commands:
PG_CTL is used to start,stop server
psql is used for queries in database inside postgres shell

To login PSQL:
> sudo -u postgres psql(username - postgres)

> Start server:
1. sudo -u postgres pg_ctl -D /Library/PostgreSQL/16/data start
2. pgctl start

> Stop Server:
pgctl stop

> Status of Server:
pgctl status


Reference - https://medium.com/@venu-prasanna/developing-a-restful-api-with-go-gin-and-gorm-part-1-router-setup-db-configuration-a31a74ad416d