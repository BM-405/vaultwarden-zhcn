# vaultwarden-zhcn 简体中文翻译包

本项目基于 [vaultwarden-lang-zhcn](https://github.com/wcjxixi/vaultwarden-lang-zhcn) 进行修改，提供了 [dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden) 的简体中文翻译文件。

## 包含内容

### 电子邮件模板 (email)
提供了位于 `src/static/templates/email` 的电子邮件模板简体中文翻译。

当前版本：
- ⚠️ email - v1.32.4 适用于 [v1.33.2](https://github.com/dani-garcia/vaultwarden/releases/tag/1.33.2)
- ⚠️ email - v1.28.1 适用于 [v1.28.1](https://github.com/dani-garcia/vaultwarden/releases/tag/1.28.1)（经测试也适用于 [v1.29.0](https://github.com/dani-garcia/vaultwarden/releases/tag/1.29.0)）

翻译参考：[Translating the email templates](https://github.com/dani-garcia/vaultwarden/wiki/Translating-the-email-templates)

### 管理页面 (admin)
提供了位于 `src/static/templates/admin` 的管理页面简体中文翻译。

当前版本：
- ⚠️ admin - v1.32.6 适用于 [v1.33.2](https://github.com/dani-garcia/vaultwarden/releases/tag/1.33.2)
- ⚠️ admin - v1.30.5 适用于 [v1.30.5](https://github.com/dani-garcia/vaultwarden/releases/tag/1.30.5)

## 使用方法

请保持原有文件结构，将翻译文件放置于 Vaultwarden 对应的目录下。

### Docker 部署示例

如果您使用 Docker 方式部署，假设使用 `-v` 参数指定的宿主机文件夹为 `vaultwarden-data`：

+ 电子邮件模板：放置于宿主机的 `/vaultwarden-data/templates/email` 文件夹下
+ 管理后台模板：放置于宿主机的 `/vaultwarden-data/templates/admin` 文件夹下

完成后执行 `docker restart vaultwarden` 重启容器使翻译生效。

## 鸣谢

特别感谢 [vaultwarden-lang-zhcn](https://github.com/wcjxixi/vaultwarden-lang-zhcn) 项目提供的原始翻译基础。
