# Metabase with Docker Compose

Run [Metabase](https://www.metabase.com/) with Docker and Docker Compose,
using PostgreSQL as application database.

Based on official docker images for [PostgreSQL] and [Metabase].

## Usage

Clone this repository, then start services locally using Docker Compose:

```
docker-compose up
```

Metabase will be available at `http://localhost:3000`.

Metabase can connect to host (`host.docker.internal`) from static IP `172.16.200.30`,
(static IP can be used for authentication. e.g. in `pg_hba.conf`)

## References

https://www.metabase.com/docs/latest/operations-guide/running-metabase-on-docker.html
https://github.com/Cambalab/metabase-compose

[PostgreSQL]: https://hub.docker.com/_/postgres
[Metabase]: https://hub.docker.com/r/metabase/metabase