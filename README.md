```
composer -sdev --prefer-dist create-project phpish/http-skeleton new_prj
cd new_prj
rm README.md
curl -sS https://getcomposer.org/installer | php
php composer.phar install
```