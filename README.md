## About
This is test package

## Install

```
$ composer config repositories.akmktz/hello vcs https://github.com/akmktz/package
$ composer require akmktz/hello:dev-master
```

## Use
```
use HelloWorld\SayHello;

ini_set('display_errors', 1);
error_reporting(E_ALL);

require_once __DIR__ . '/vendor/autoload.php'; // Autoload files using Composer autoload

echo SayHello::world();
```
