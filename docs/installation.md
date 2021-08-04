# How to install Poraoo

## Build Setup Backend

```php
git clone https://github.com/zakirsoft/poraoo-backend.git
# clone project from github

composer install
# install dependencies

php artisan key:generate
# generate application key

php artisan migrate
# run all migration file

php artisan serve
# serve laravel api
```

## Build Setup Frontend

```bash
git clone https://github.com/zakirsoft/poraoo-frontend.git
# project clone from github

# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```
