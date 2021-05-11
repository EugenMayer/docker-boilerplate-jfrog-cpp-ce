# WAT

Simple, functional boilerplate to run the jFroga Cpp Conan Community edition:

- postrgresql as database (not embedded)
- volume setup

Either use this as a starter or even in production, be sure to use `.env` to define `DB_PASSWORD`


## Usage:

```
docker-compose up -d
```

The access via `http://localhost:8081` which will redirect you to `http://localhost:8082`

Default user: `admin`
Default password: `password`

### Configuration

Via `.env`

- DB_USER: set your desired DB user (defalts to `jfrog`)
- DB_PASSWORD: your DB password (defaults to `secret`)
- DB_NAME: your desired database name (defaults to `artifactory`)
