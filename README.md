感谢 vaultwarden-lang-zhcn
https://github.com/wcjxixi/vaultwarden-lang-zhcn/tree/main?tab=readme-ov-file#vaultwarden-lang-zhcn
电子邮件
dani-garcia/vaultwarden电子邮件模板（位于src/static/templates/email）的简体中文翻译，如下所述：https://github.com/dani-garcia/vaultwarden/wiki/Translated-the-email-templates。

⚠️email - v1.28.1 表示适用于v1.28.1（经测试 email - v1.28.1 也适用于v1.29.0）

行政
dani-garcia/vaultwarden管理页面（位于src/static/templates/admin）的简体中文翻译。

⚠️admin - v1.30.5 表示适用于v1.30.5，以此类推

使用方法
保持文件结构，放置于Vaultwarden对应的目录下。

Docker 例如，假设你配置的时候使用-v参数指定的一个机器文件夹为vaultwarden-data：

电子邮件模板文件放置在该机的/vaultwarden-data/templates/email文件夹下
管理后台模板文件放置在本机的/vaultwarden-data/templates/admin文件夹下
然后docker restart vaultwarden重新启动Vaultwarden容器。
