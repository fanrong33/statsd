# statsd


## PHP
```php
// SDK 自然转化劫持log记录
import('@.ORG.Util.StatsD');
$stats = new StatsD(C('STATSD_HOST'), C('STATSD_PORT'));
        
$cmd = "app.installs,package_name={$package_name},country_code={$country_code}:1|c";
$stats->send($cmd);
```


### TODO
不同场景图像类型，包括对应的cmd命令


