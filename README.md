# 68-s1-cybersec--s6602041610062-kmutnb.ac.th
# CYBER SECURITY
## INFORMATION
- SARAWUT BOONPRAKRONG
- 6602041610062
- s6602041610062@kmutnb.ac.th

## Environment
``` sh
cp env.simple .env
```

## Running services
### Database
```sh
docker compose -f db.yaml up # monitoring
docker compose -f db.yaml up -d # background
```
### PG ADMIN 4
```sh
docker compose -f admin.yaml up # monitoring
docker compose -f admin.yaml up -d # background
```