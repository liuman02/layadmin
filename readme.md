
## 安装步骤
- git clone  https://github.com/zhukang0704/layadmin.git
- 复制.env.example为.env
- 配置.env里的数据库连接信息
- composer update
- php artisan migrate
- php artisan db:seed
- php artisan key:generate
- 登录后台：host/admin   帐号：admin  密码：123456
