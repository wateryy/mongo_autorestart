##mongo自动重启脚本

* shell脚本
* 需要定时任务

```
  # crontab -e
  # 每分钟执行一次
  */1 * * * * /usr/local/mongo/mongo_autorestart.sh
```
