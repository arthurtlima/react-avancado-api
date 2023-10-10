<h1 align="center">
     <img title="Icone dt money" src="https://github.com/arthurtlima/react-avancado-api/assets/12513621/754bc2b1-321c-4592-b795-e3de07a832b9" width="500" height="100" alt="React avançado">
</h1>

<p align="center">
  This is one of the applications developed in the <a href="https://reactavancado.com.br/">React Avançado</a> course.
</p>

<h4 align="center">
	🚧 Completed 🚀 🚧
</h4>

## Requirements

This project uses [PostgreSQL](https://www.postgresql.org/), so, in order to make it working, install in your local machine or use Docker.

The configuration to the Database can be found on [config/database.js](config/database.js)

## Development

After cloning this project, install the dependencies:

```
yarn install
```

And run using:

```
yarn develop
```

The urls to access are:

- `http://localhost:1337/admin` - The Dashboard to create and populate data
- `http://localhost:1337/graphql` - GraphQL Playground to test your queries

The first time to access the Admin you'll need to create an user.

## Dump data

This project uses `Postgres` and if you want all the data previously, unzip the [data.zip](data.zip), copy the `uploads` folder to [public/uploads](public/uploads) and restore the data from the `local.dump` file inside the zip.
