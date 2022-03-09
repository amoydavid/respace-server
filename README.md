# Laravel9-Template

一个使用国内镜像的模板项目，通过本项目可快速进行基础架构搭建。composer、npm、yarn均使用国内镜像。

## Quick start

开始前可以先设置好 `.env` 文件

```shell
docker-compose up -d
docker-compose exec laravel.test /bin/sh
composer install
docker-compose stop
sail up
```
## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
