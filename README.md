# 🚀 Getting started with Strapi

Strapi comes with a full featured [Command Line Interface](https://docs.strapi.io/dev-docs/cli) (CLI) which lets you scaffold and manage your project in seconds.

### `develop`

Start your Strapi application with autoReload enabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-develop)

```
npm run develop
# or
yarn develop
```

### `start`

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-start)

```
npm run start
# or
yarn start
```

### `build`

Build your admin panel. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-build)

```
npm run build
# or
yarn build
```

### `Data export`

The strapi export command is used to export data from a local Strapi instance. [Learn more](https://docs.strapi.io/dev-docs/data-management/export)

```
npm run strapi export
# or
yarn strapi export
```

### `Data import`

The strapi import command is used to import data from a file. [Learn more](https://docs.strapi.io/dev-docs/data-management/import)

```
npm run strapi import -f export_20221213105643.tar.gz.enc --key my-encryption-key
# or
yarn strapi import -f export_20221213105643.tar.gz.enc --key my-encryption-key
```