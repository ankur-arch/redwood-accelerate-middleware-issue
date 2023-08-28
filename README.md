# Getting started

Create a .env file with Accelerate and Direct database URL
```
DATABASE_URL=
DIRECT_URL=
```

## Run the app

```bash
yarn install
yarn rw prisma migrate dev
yarn rw prisma generate --accelerate
yarn redwood dev
```
