<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

# Docker for PHP/Laravel and Vue.js
This is a Docker Environment for PHP/Laravel and Vue.js !


## Environments
* PHP 7.*
* Laravel 6.*
* node v10.*
* npm 6.*

## How to use

Make a directory and move to development directory (You can have own directory name if you want)
```
$ mkdir docker-laravel && cd docker-laravel
```

git clone
```
$ git clone https://github.com/masanori0117/DockerTestNew.git
```

Move to DockerTest directory
```
$ cd DockerTest
```

Build the containers
```
$ docker-compose build
```

Up the containers
```
$ docker-compose up -d
```

Create Laravel-Project (Only first time)
```
$ composer create-project --prefer-dist laravel/laravel:^6.0 .
```

You can See the Laravel Home Page in web browser
```
http://localhost:8000/
```

Command for Enter the app bash
```
$ docker-compose exec app bash
```

Command for down the container
```
$ docker-compose down
```

## Note
This is first time to make Docker environemnt. Please let me know if is there any thing wrong. Thanks!

## Author
[masanori0117](https://github.com/masanori0117)

## License
This code is under the [MIT license](https://opensource.org/licenses/MIT).