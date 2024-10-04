在 /etc/network/interfaces 下新增
```
post-up /sbin/ethtool -s eno1 wol g
```
重新啟動

執行
systemctl suspend 
或安排於 crontab


喚醒:
使用 client 端 以 Macaddress 喚醒



