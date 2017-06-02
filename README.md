# solumen

Swoole with lumen

## Depends On

- php >= 7.1.*
- laravel/lumen > 5.3.*
- ext-swoole >= 1.9.*


## 安装

```shell
 composer require ttmama/solumen
```

剪切本类库 `app` 目录下的 `Application.php` 到项目根目录 `app` 目录下，修改项目根目录 `bootstrap` 目录中的 `app.php` 

修改其中

```php
 $app = new \Laravel\Lumen\Application(
    realpath(__DIR__.'/../')
 );
```
为
```php
 $app = new App\Application(
    realpath(__DIR__.'/../')
 );
```
 

## 使用

```shell
 vendor/bin/solumen start | stop | reload | restart | quit
```

