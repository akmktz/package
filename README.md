##About
This is test package

## Install

```
$ composer config repositories.smtpcheck path ../test
$ composer require akmktz/hello:dev-master --prefer-source
```

## Use
```
use HelloWorld\SayHello;

ini_set('display_errors', 1);
error_reporting(E_ALL);

require_once __DIR__ . '/vendor/autoload.php'; // Autoload files using Composer autoload

echo SayHello::world();
```
