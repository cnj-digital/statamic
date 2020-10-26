<p align="center"><img src="https://statamic.com/assets/branding/Statamic-Logo+Wordmark-Rad.svg" width="400" alt="Statamic Logo" /></p>

# Statamic v3 CNJ Starter

Statamic 3 is the very latest and greatest version of Statamic, a uniquely powerful CMS built on [Laravel](https://laravel.com) and designed to make building and managing bespoke websites radically efficient and enjoyable.

For more information visit the [Statamic core package repository][https://github.com/statamic/cms].

## Documentation

The offical documentation for v3 is available [here](https://statamic.dev/). Due to lack of information please revise the [v2 docs](https://docs.statamic.com/) as well, as they share some similarities.

You can find more code snippets and common solutions to problems by visiting the Statamic Handbook (WIP).

## Installation

```
composer create-project cnj/statamic project-name
```

At the last prompt, select `Y`, to remove the included git files.

### Add a new user

```
php please make:user
```

### Link storage

```
php artisan storage:link
```

### Edit the .env

Enter the `APP_URL` and `APP_NAME`

```
vi .env
```

### Setup git

```
git init
```

Add the appropriate remote GitHub repository

-   commond backend commands
-   frontend build commands

## Development

### Frontend

Latest TailwindCSS is already included. Purge in production is set up.

```
npm run watch
```

## Deployment

WIP
