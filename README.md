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
### APP
```sh
docker compose -f app.yaml up # monitoring
docker compose -f app.yaml up -d # background
```