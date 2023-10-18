# Local Dev

This project is a template for Docker + Postgres local dev environment for current and future applications.

### Prerequisite Steps

Install Docker from: 
https://docs.docker.com/desktop/install/mac-install/

TablePlus download from:
https://tableplus.com/download

### Spin Up Enviorment

From within the root dir, run `docker compose up`\
Terminal should log `database system is ready to accept connections` as final output

### Connect TablePlus to docker image running postgres

Use port: `5432`\
Username: `postgres`\
Password: `postgres`

Hit button `Connect`
