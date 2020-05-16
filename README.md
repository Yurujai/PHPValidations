# PHPValidations

Config files of PHPValidations for Symfony projects.

#### PHPCsFixer

Install PHPCSFixer with composer

```
composer require --dev friendsofphp/php-cs-fixer
```

You can show more install options on: [PHPCSFixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)

Copy the file inside PHPCSFixer folder on your root project folder.

Execute
```
php vendor/bin/php-cs-fixer fix src
```

#### PHPStan

Install PHPStan extensions with composer

```
composer require --dev phpstan/phpstan
composer require --dev phpstan/phpstan-symfony
composer require --dev phpstan/phpstan-doctrine
composer require --dev phpstan/phpstan-strict-rules
```

You can install extension for PHPUnit. Show [PHPStan](https://github.com/phpstan/phpstan-phpunit)

Copy the files inside PHPStan folder on your root project folder.

rules.neon file is necessary to use phpstan-strict-rules.

Show [Rules](https://github.com/phpstan/phpstan-strict-rules/tree/master/src/Rules) to activate someone of them.

