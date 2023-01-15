# Vmess for Daki

* * *

# 目录

- [项目特点](README.md#项目特点)
- [部署](README.md#部署)
- [鸣谢下列作者的文章和项目](README.md#鸣谢下列作者的文章和项目)
- [免责声明](README.md#免责声明)

* * *

## 项目特点:
* 本项目用于在 [Daki](https://daki.cc/) 免费服务上部署 VMESS
* 集成哪吒探针，可以自由选择是否安装
* 部署完成如发现不能上网，请检查域名是否被墙，可使用 Cloudflare CDN 或者 worker 解决。

## 部署:
* 注册 [Daki](https://daki.cc/)
* config.json 的 13 行修改 UUID
* server.js 的 04行改服务器提供的端口，106 行修改自己的 URL， 44 行修改哪吒参数
* 部署成功后 vmess ws 的路径为: /api，如要修改，可以寻找并替换 server.js 的 90、96、97 行里的 api
* 需要应用的 js
  | 命令 | 是否必须 | 说明 |
  | ------------ | ------ | ------ |
  | <URL>/start | 是 | 运行 vmess |
  | <URL>/nezha | 否 | 运行哪吒 | 以 / 开头 |
  | <URL>/api | 否 | 查看 vmess 运行结果 Bad Request 即是 OK |
  | <URL>/status | 否 | 查看后台进程  |
  
![image](https://img.urlnode.com/file/be68e06d9c9b29a8284e3.png)
  
![image](https://img.urlnode.com/file/ec8180df1d2c272f9c3a8.png)

![image](https://img.urlnode.com/file/a249951f1a9a100542c91.png)
  
![image](https://img.urlnode.com/file/b03dc77949f7894270be1.png)
  
![image](https://img.urlnode.com/file/0f84e4fed59f129be7166.jpg)
  
![image](https://img.urlnode.com/file/efd7a64dfd6675034ce6d.png)

<img width="577" alt="image" src="https://user-images.githubusercontent.com/92626977/212469959-f2762c30-5cb1-4a31-9f77-0dad6319bd90.png">

<img width="477" alt="image" src="https://user-images.githubusercontent.com/92626977/212470037-58621fe0-9f45-452e-97b4-419565920d61.png">

<img width="593" alt="image" src="https://user-images.githubusercontent.com/92626977/212469999-af9685ff-3392-42f1-88bb-0e615a61ab9b.png">

<img width="512" alt="image" src="https://user-images.githubusercontent.com/92626977/212470068-609dedea-2bfd-4ccf-80b2-6ed2a82e3dc5.png">

<img width="1140" alt="image" src="https://user-images.githubusercontent.com/92626977/212470157-77b77f8c-dcb8-425e-81a4-83bc1881126c.png">
  
![image](https://img.urlnode.com/file/0dc618210e7e38707e3d8.png)

## 鸣谢下列作者的文章和项目:
大佬 fscarmen2 的Glitch项目，https://github.com/fscarmen2/X-for-Glitch ，在此基础上作修改。

## 免责声明:
* 本程序仅供学习了解, 非盈利目的，请于下载后 24 小时内删除, 不得用作任何商业用途, 文字、数据及图片均有所属版权, 如转载须注明来源。
* 使用本程序必循遵守部署免责声明。使用本程序必循遵守部署服务器所在地、所在国家和用户所在国家的法律法规, 程序作者不对使用者任何不当行为负责。
