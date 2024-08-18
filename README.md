# Clean Architecture

Example of clean architecture for a file system

## Files

This repository contains the following files:

### `index.js`

This is the entry point of the application. It serves as the main file that initializes and starts the file system API.

### `src/server.js`

This file is responsible for setting up the server.

### `src/models`

This directory contains the data models used in the application. (mongoDB)

### `src/usescases`

This directory contains the use cases or business logic of the application.

### `src/routes`

This directory contains the route handlers (express) for different API endpoints.

### `src/lib`

This directory contains utility functions or helper modules used throughout the application.

### `src/middlewares`

This directory contains the middleware functions used in the application.

### `scripts`

To start the application in production mode, you can run the following command:

```shell
npm start
```

To start the application in development mode, you can run the following command:

```shell
npm run dev
```
