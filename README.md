## dto

```php 
composer require guanhui07/carbon dev-main
```

## usage

```php
Carbon::now()->toDateTimeString();
Carbon::now()->subDays(1)->startOfDay()->toDateTimeString();
Carbon::now()->getTimestamp();
Carbon::now()->format('Y-m-d');
Carbon::now()->endOfDay()->getTimestamp();
```