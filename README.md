This is a fork of [MariaDB's NoSQL Listener example](https://github.com/mariadb-corporation/dev-example-nosql-listener)
that replaces MariaDB MaxScale and MariaDB Community Server with
[FerretDB](https://github.com/FerretDB/FerretDB) and PostgreSQL.

# Quickstart

```sh
git clone https://github.com/FerretDB/example.git
cd example
docker compose pull
docker compose up -V
```

Then open [http://localhost:8888/](http://localhost:8888/) and use that example application.
