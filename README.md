# Rails-Init

## Creating a new rails project

Use this repo as a template.

```bash
cd init
```

```bash
docker compose run --build --rm init rails new .
```

Change the UID:GID to your user.

```bash
sudo chown -R 1000:1000 ../*
```

```bash
cd ..
```

```bash
docker compose up --build -d
```
