---
home: true
icon: iconfont icon-home
title: Home
heroImage: /logo.svg
heroText: OpenList
tagline: 🗂️ 一个支持多种存储的文件列表程序</br>&emsp;&nbsp;&nbsp;使用 Gin 和 Solidjs 开发
heroStyle:
  min-height: 550px
actions:
  - text: 开始💡
    link: /zh/guide/
    type: primary

  - text: Github🌱
    link: https://github.com/OpenListTeam/OpenList

highlights:
- header: 为什么选择 OpenList
  features:
  - title: 使用简单
    icon: iconfont icon-light
    details: OpenList 从一开始就设计为易于安装，并且可以在所有平台上使用。

  - title: 多种存储
    icon: iconfont icon-storage
    details: OpenList 支持多个存储提供商，包括本地存储、阿里云盘、OneDrive、Google Drive 等，且易于拓展。

  - title: 支持 WebDAV
    icon: iconfont icon-waline
    details: OpenList 支持所有 WebDAV 存储，这是一种用于访问文件的标准。

  - title: 黑暗模式
    icon: iconfont icon-contrast
    details: 自由切换明暗模式

  - title: 受保护的路由
    icon: iconfont icon-token
    details: 为特定路径添加密码保护和身份验证

  - title: 文件预览
    icon: iconfont icon-preview
    details: 支持视频、音频、文档、PDF、图片预览等，甚至支持 ipa 安装

  - title: 打包下载/批量下载
    icon: iconfont icon-cache
    details: 使用浏览器的 stream api 支持打包下载，无需使用服务器 / 使用Aria2进行批量下载支持文件夹

  - title: 单点登录
    icon: font-icon icon fa-solid fa-repeat-1
    details: 使用单点登录快速登录OpenList

  - title: 自动注册OpenList帐号
    icon: fa-solid fa-file-user
    details: 使用单点登录自动注册为OpenList帐号快速注册

  - title: 离线下载
    icon: fa-solid fa-folder-arrow-down
    details: 将种子内容离线下载到指定的目录內,需要苛刻的网络环境

  - title: 保险箱加密/解密 文件
    icon: fa-solid fa-binary-lock
    details: 任何人都可以安全地将加密数据存储在远程存储提供商上。数据存储在保险箱中，提供商只能看到保险箱，看不到您的数据。

  - title: 更多新功能
    icon: iconfont icon-more
    details: 包括文本编辑器、README/HTML 渲染、文件永久链接、Cloudflare Workers 代理等

- header: 在 OpenList 中挂载你想要的网盘
  description: 我们使用了标准的网盘 API 规范，为你整合了这些网盘。</br>本软件及指南是一个开源项目，不持有以下任何商标。</br>所有商标均为其各自所有者的财产。
  image: 
  bgImage: /img/bg/9-light.svg
  bgImageDark: /img/bg/9-dark.svg
  features:
    - title: 阿里云盘
      icon: /img/storegeico/favicon-www.alipan.com-2-64x64.png
      # details: 分享链接
      link: /zh/guide/drivers/aliyundrive_open.md
    - title: 百度云盘
      icon: /img/storegeico/pan.baidu.com.png
      details: 
      link: /zh/guide/drivers/baidu.md
    - title: 123网盘
      icon: /img/storegeico/www.123pan.com.ico
      # details: 云盘/分享/直链
      link: /zh/guide/drivers/123.md
    - title: 夸克网盘
      icon: /img/storegeico/pan.quark.cn128.ico
      # details: TV 版
      link: /zh/guide/drivers/quark.md
    - title: OneDrive
      icon: /img/storegeico/odbfavicon.ico
      # details: 国际版 世纪互联
      link: /zh/guide/drivers/onedrive.md
    - title: GoogleDrive
      icon: /img/storegeico/drive.google.com32.png
      details: 
      link: /zh/guide/drivers/googledrive.md
    - title: Mega
      icon: /img/storegeico/mega.nz.ico
      details: 
      link: /zh/guide/drivers/mega.md
    - title: 115网盘
      icon: /img/storegeico/115.ico
      details: 
      link: /zh/guide/drivers/115_open.md
    - title: 电信天翼云盘
      icon: /img/storegeico/favicon-cloud.dlife.cn.ico
      details: 
      link: /zh/guide/drivers/189.md
    - title: 中国移动云盘
      icon: /img/storegeico/yun.139.com.png
      details: 
      link: /zh/guide/drivers/139.md
    - title: 中国联通云盘
      icon: /img/storegeico/pan.wo.cn.ico
      details: 
      link: /zh/guide/drivers/wopan.md
    - title: 四川电信魔盘
      icon: /img/storegeico/mopan.sc.189.cn.ico
      details: 
      link: /zh/guide/drivers/mopan.md
    - title: 迅雷网盘
      icon: /img/storegeico/pan.xunlei.ico
      # details: X / 浏览器
      link: /zh/guide/drivers/thunder.md
    - title: PikPak
      icon: /img/storegeico/pikpak.com.png
      # details: 分享链接
      link: /zh/guide/drivers/pikpak.md
    - title: 谷歌相册
      icon: /img/storegeico/photos.google.com96.png
      details: 
      link: /zh/guide/drivers/googlephotos.md
    - title: 一刻相册
      icon: /img/storegeico/photo.baidu.com.ico
      details: 
      link: /zh/guide/drivers/baidu.photo.md
    - title: 蓝奏云
      icon: /img/storegeico/up.woozooo.com.ico
      # details: 蓝奏云优享版
      link: /zh/guide/drivers/lanzou.md
    - title: UC网盘
      icon: /img/storegeico/drive.uc.cn.png
      # details: TV
      link: /zh/guide/drivers/uc.md
    - title: Dropbox
      icon: /img/storegeico/dropbox.comfavicon32.ico
      details: 
      link: /zh/guide/drivers/dropbox.md
    - title: 腾讯微云
      icon: /img/storegeico/www.weiyun.com.png
      details: 
      link: /zh/guide/drivers/weiyun.md
    - title: TeraBox
      icon: /img/storegeico/www.terabox.ico
      details: 
      link: /zh/guide/drivers/Terabox.md
    - title: Teambition
      icon: /img/storegeico/teambition.com.ico
      details: 
      link: /zh/guide/drivers/teambition.md
    - title: 分秒帧
      icon: /img/storegeico/www.mediatrack.cn.ico
      details: 
      link: /zh/guide/drivers/mediatrack.md
    - title: Yandex.Disk
      icon: /img/storegeico/360.yandex.com.png
      details: 
      link: /zh/guide/drivers/yandex.md
    - title: 小飞机网盘
      icon: /img/storegeico/www.feejii.com.ico
      details: 
      link: /zh/guide/drivers/feiji.md
    - title: 又拍云存储
      icon: /img/storegeico/www.upyun.com.png
      details: 
      link: /zh/guide/drivers/uss.md
    - title: Trainbit
      icon: /img/storegeico/teambition.com.ico
      details: 
      link: /zh/guide/drivers/Trainbit.md
    - title: 超星星小组盘
      icon: /img/storegeico/v9.chaoxing.com.png
      details: 
      link: /zh/guide/drivers/chaoxing.md
    - title: 曲奇云盘
      icon: /img/storegeico/quqi.com.ico
      details: 
      link: /zh/guide/drivers/quqi.md
    - title: 6盘
      icon: /img/storegeico/www.6pan.vip.png
      details: 
      link: /zh/guide/drivers/halalcloud.md
    - title: 网易云音乐云盘
      icon: /img/storegeico/music.163.com.ico
      details: 
      link: /zh/guide/drivers/163music.md
    - title: GitHub
      icon: /img/storegeico/favicon-github.com-3-32x32.svg
      details: 
      link: /zh/guide/drivers/github.md
- header: 或是这些自建存储
  description: 
  image: /assets/image/ui.svg
  bgImage: /img/bg/9-light.svg
  bgImageDark: /img/bg/9-dark.svg
  features:
    - title: 本地存储
      icon: icon-park-outline:cloud-storage
      details: 
      link: /zh/guide/drivers/local.md
    - title: FTP/SFTP
      icon: hugeicons:internet
      details: 
      link: /zh/guide/drivers/ftp.md
    - title: S3 对象存储
      icon: clarity:storage-solid-badged
      details: 
      link: /zh/guide/drivers/s3.md
    - title: SMB
      icon: clarity:storage-solid
      details: 
      link: /zh/guide/drivers/SMB.md
    - title: WebDAV
      icon: fluent-mdl2:internet-sharing
      details: 
      link: /zh/guide/drivers/webdav.md
    - title: IPFS
      icon: carbon:storage-request
      details: 
      link: 
    - title: 联想家庭储存
      icon: /img/storegeico/pc.lenovo.com.cn.png
      details: 
      link: /zh/guide/drivers/lenovonasshare.md
    - title: 多吉云
      icon: /img/storegeico/www.dogecloud.com.png
      details: 
      link: /zh/guide/drivers/s3.md#添加对象存储示例及官方文档
    - title: Seafile
      icon: /img/storegeico/www.seafile.com.png
      # details: 自建同步盘
      link: /zh/guide/drivers/Seafile.md
    - title: Cloudreve
      icon: /img/storegeico/cloudreve.org.ico
      # details: 自建备份盘
      link: /zh/guide/drivers/cloudreve_v4.md
    - title: Misskey
      icon: /img/storegeico/misskey-hub.net.svg
      # details: 去中心化平台
      link: /zh/guide/drivers/misskey.md
- header: 我们还有这些功能
  description: 
  image: 
  bgImage: /img/bg/9-light.svg
  bgImageDark: /img/bg/9-dark.svg
  highlights:
    - title: 别名（alias）
      icon: iconfont icon-state
      details: 将不同网盘的文件合并展示
      link: 
    - title: 加密（Crypt）
      icon: iconfont icon-state
      details: 云盘自动加解密
      link: 
    - title: 地址树（UrlTree）
      icon: iconfont icon-state
      details: 挂载单个文件链接
      link: /zh/guide/drivers/UrlTree.md

copyright: AGPL-3.0 Licensed | Copyright © 2022-present The OpenList Team
# footer: 
---