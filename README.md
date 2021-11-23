# 宝塔ApiSdk


```php

<?php
require './vendor/autoload.php';
use Coly\Bt\Tools;

$bt = new Tools('http://159.75.103.200:3838','Z0ZifPKxgfpy018wjm9Hjq0MP3wNaurW');
echo json_encode($bt->WebAddDomain(46,'','test212.2smi1le.cnn')); //添加域名 {status=true}
echo json_encode($bt->WebDelDomain(46,'','test212.2smile.cnn','80'));//删除成功 {status=true}

```