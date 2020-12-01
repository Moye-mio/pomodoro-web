# 番茄工作法·改 Promodoro Web
## 介绍
- 基于web
- 番茄工作法计时与提醒
- 任务记录、计划记录
- 从AllocBlock处fork并稍作修改 https://github.com/AllocBlock/pomodoro-technique-web
## 注
- 因为浏览器安全策略，计时结束的气泡提醒，要页面保持在前端（可见）才会弹出！
- 导出的csv文件以逗号分隔，如果含汉字Excel直接打开可能会乱码，转存为ANSI编码即可解决
- 无需挂载服务器，运行html文件即可
- 数据存在localStorage中，localStorage的大小有限制（具体和浏览器有关），建议定期导出到文件存储并清空
- chrome可使用菜单-更多工具-创建快捷方式，可在桌面快捷方式以类似应用程序打开网站
- 所用框架均引用自BootCDN
