# KCTwitterBot
A bot to forward @KanColle_STAFF's tweets to QQ groups
众所周知天朝的舰C邪教基本都混各种舰C群，而舰C信息的官方发布平台是推特@KanColle_STAFF。这个Python程序自动将@KanColle_STAFF的推文转发至QQ群，方便作为公告&无法翻墙的玩家阅览
推文的采集使用Python库twitter，发送使用Python库qqbot
推文的采集使用Python2，发送使用Python3
附带有一个Shell编写的简易脚本，在crontab里写入* * * * * bash 脚本路径即可运行
使用方法：

