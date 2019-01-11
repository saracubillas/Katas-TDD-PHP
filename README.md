# Katas TDD PHP

Well hi there! This repository holds the code and script
for the [Katas-TDD-PHP]

If you've just downloaded the code, congratulations!

## Setup if you have PHP installed 

If you have PHP installed to get it working, follow these steps:

**Download Composer dependencies**

Make sure you have [Composer installed](https://getcomposer.org/download/)
and then run:

```
composer install
```

You may alternatively need to run `php composer.phar install`, depending
on how you installed Composer.

**Start testing**

  * Run:
```
vendor/bin/phpunit tests
```
If everything is fine you should see 1 test passing

Have fun!

## Setup if you do not have PHP installed 

You have two options:

a ) You can install PHP (http://php.net/manual/en/install.php) and follow the above steps.

b ) You can use a Docker image.  
        * Install Docker (https://www.docker.com/).
        * Run:
        
**Download Composer dependencies**

```
docker run  --rm -v $PWD:/app -it thomsch98/php7-composer composer install
```

**Start testing**
 
```
docker run  --rm -v $PWD:/app -it thomsch98/php7-composer vendor/bin/phpunit tests
```

If everything is fine you should see 1 test passing

Have fun!

## Have Ideas, Feedback or an Issue?

If you have suggestions or questions, please feel free to
open an issue on this repository 

## Thanks!

<3
