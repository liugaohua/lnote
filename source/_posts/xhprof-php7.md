---
title: xhprof.php7
date: 2019-05-22 18:19:10
tags:
---



### git clone https://github.com/tideways/php-xhprof-extension.git

```
phpize 
yum install autoconf
./configure
make
make install
```


git clone https://github.com/preinheimer/xhprof.git


nginx配置
fastcgi_param PHP_VALUE "auto_prepend_file=/home/xhprof/external/header.php";

