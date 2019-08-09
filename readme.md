## 微信小程序 - 服务器端

基于Laravel5.7 - Dingo Api - Jwt 开发的微信小程序服务器端快速开发接口

## 项目部署

1. `composer install`
2. `cp .env.example .env`
3. `php artisan key:generate`
4. `php artisan jwt:secret`
5. `php artisan vendor:publish --provider="Tymon\JWTAuth\Providers\LaravelServiceProvider"`
5. 配置 `.env` 文件中的微信小程序配置项以及数据库配置
6. 执行 `php artisan migrate`
7. `php artisan storage:link`

