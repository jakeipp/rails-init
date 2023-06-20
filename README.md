# Rails-Init

## Creating a new rails project

Use this repo as a template.

```bash
cd init
```

```bash
docker compose run --build --rm init rails new .
```

```bash
cd ..
```

Change the UID:GID to your user.

```bash
sudo chown -R 1000:1000 *
```

```bash
docker compose up --build -d
```
