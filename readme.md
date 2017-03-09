# Fc_Admin基于laravel5.4的后台脚手架

###安装步骤

***

>1、git克隆项目

    git clone https://github.com/flycorn/fc_admin.git fc_admin

>2、composer下载所需类库
    
    composer update
    
>3、修改配置
    
    cp .env.example .env
    根据自己情况修改.env配置,及config/fc_admin.php中的配置
    fc_admin.php配置中可设置后台样式、超级管理员的用户名及邮箱
    
    默认样式为：skin-green （skin-green、skin-green-light、skin-black、skin-black-light、skin-blue、skin-blue-light、skin-purple、skin-purple-light、skin-red、skin-red-light、skin-yellow、skin-yellow-light）
    
    默认超级管理员的用户名为：admin 邮箱为：admin@admin.com

    默认密码为：admin123
    
>4、初始化后台

    php artisan fc_admin:init
    
>5、OK......开启后台脚手架之旅吧!

<code>ps: 请将项目根目录指向到public目录。</code>

<code>ps: 如果500错误，请将storage目录权限设为777。</code>


###后台截图

***

![fc_admin](https://github.com/flycorn/fc_admin/blob/master/public/fc_admin/1.png?raw=true)
![fc_admin](https://github.com/flycorn/fc_admin/blob/master/public/fc_admin/2.png?raw=true)
![fc_admin](https://github.com/flycorn/fc_admin/blob/master/public/fc_admin/3.png?raw=true)
![fc_admin](https://github.com/flycorn/fc_admin/blob/master/public/fc_admin/4.png?raw=true)
![fc_admin](https://github.com/flycorn/fc_admin/blob/master/public/fc_admin/5.png?raw=true)
