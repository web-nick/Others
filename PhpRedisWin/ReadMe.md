###Модуль PhpRedis (php_redis.dll) для PHP 7 под Win

На данный момент не нашел готовый, рабочий, модуль PhpRedis (https://github.com/phpredis/phpredis) для PHP 7 под Win.

Своя сборка.

На выходе php_redis.dll.

Конфигурация:
 - PhpRedis: 2.2.8-devphp7;
 - PHP 7.0 VC14 x64 Thread Safe;
 
Флаги компиляции: --enable-redis=shared --enable-redis-session --enable-redis-igbinary 

Проверялось под Windows 10, с указанным выше PHP


