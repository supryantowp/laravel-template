# laravel-template

A barebones Laravel App.

This application supports the [Getting Started with Laravel on Heroku](https://devcenter.heroku.com/articles/getting-started-with-laravel) article - check it out.

## Running Locally

Make sure you have [Laravel](https://laravel.com) and the [Heroku CLI](https://cli.heroku.com/) installed.

```sh
$ git clone git@github.com:supryantowp/laravel-template.git # or clone your own fork
$ cd laravel-template
$ composer install
$ cp .env.example .env
$ php artisan key:generate
$ npm install && npm run dev
$ npm start
```

Your app should now be running on [localhost:8000](http://localhost:8000/).

## Deploying to Heroku

```
$ heroku create
$ git push heroku master
$ heroku open
```

or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)
