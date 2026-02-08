# Cyber Security

## Information
* ###### Nareerat Juntana
* 6702041510067
* s6702041510067@email.kmutnb.ac.th

## Environment
```sh
cp env.simple .env
```

## Running Service

### Database
```sh
docker compose -f db.yaml up # monitoring
docker compose -f db.yaml up -d # background
```

### pgAdmin4
```sh
docker compose -f admin.yaml up # monitoring
docker compose -f admin.yaml up -d # background
```

### Strapi App
```sh
docker compose -f app.yaml up     # monitoring
docker compose -f app.yaml up -d  # background
```