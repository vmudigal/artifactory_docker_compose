
### Artifactory OSS with PostgreSQL
Artifactory OSS installation using docker compose.

```bash
$ sudo docker-compose -f artifactory-oss-postgresql.yml up -d
```
**IMPORTANT:** Make sure to prepare the needed [storage for persistent data](#persistent-storage)!

This example starts the following containers

- Artifactory OSS exposed on port 80
- PostgreSQL database serving Artifactory   

Artifactory uses the PostgreSQL database running in another container.

