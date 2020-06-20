---
文章标题:	易筑家百度小程序开发文档及说明文件
关键字 :	易筑家,逐浪,小程序
文章分类:	笔记
创建时间:	2020-6-9
---

<!-- TOC -->

- [Zoomla!逐浪CMS卓越出品](#zoomla逐浪cms卓越出品)
    - [逐浪官方开源精品全站项目050：易筑家精品地产教育二合一百度小程序全站源码](#逐浪官方开源精品全站项目050易筑家精品地产教育二合一百度小程序全站源码)
    - [本项目介绍](#本项目介绍)
- [开放性说明](#开放性说明)
    - [使用说明](#使用说明)
- [源码结构](#源码结构)
- [系统运行效果图](#系统运行效果图)

<!-- /TOC -->



# Zoomla!逐浪CMS卓越出品

## 逐浪官方开源精品全站项目050：易筑家精品地产教育二合一百度小程序全站源码



Zoomla!逐浪CMS：中文业界alexa排名第一的CMS系统|专注.net与windows平台企业级研发，集成内容管理、webfont、商城、店铺、黄页、教育、考试、3D、三维全景、混合现实、CRM、ERP、OA、论坛、贴吧等为一体，打造国内高端的CMS产品典范。

官网：www.z01.com

免费下载：www.z01.com/mb

视频教程：www.z01.com/mtv

模板资源：www.z01.com/mb

逐浪字库： http://f.ziti163.com

zico中文图标库：http://ico.z01.com


QQ交流群号：
[![加入QQ群](https://img.shields.io/badge/一群-541450128-blue.svg?style=for-the-badge&logo=appveyor)](https://jq.qq.com/?_wv=1027&k=5qIayyX)  [![加入QQ群](https://img.shields.io/badge/二群-541450128-blue.svg?style=for-the-badge&logo=appveyor)](https://jq.qq.com/?_wv=1027&k=5Ephzpq)   [![加入QQ群](https://img.shields.io/badge/三群-601781959-blue.svg?style=for-the-badge&logo=appveyor)](https://jq.qq.com/?_wv=1027&k=50a28BK) 


官方QQ客服：
[![官方QQ客服1](https://img.shields.io/badge/官方QQ客服1-524979923-red.svg?style=for-the-badge&logo=appveyor)](http://wpa.qq.com/msgrd?v=3&uin=745151353&site=qq&menu=yes)  [![官方QQ客服2](https://img.shields.io/badge/官方QQ客服2-1799661890-red.svg?style=for-the-badge&logo=appveyor)](http://wpa.qq.com/msgrd?v=3&uin=1799661890&site=qq&menu=yes) 

## 本项目介绍

一个服务于地产行业的精品小程序


这是山东上格科技（逐浪软件MVP伙伴），基于Zoomla!逐浪CMS技术栈开发的百度小程序项目。
其特征有：
- 项目启动快
- 基于百度小程序协议，可以大面积提升百度的收取
- 基于逐浪技术栈，很好的与逐浪CMS完美结合
- 提供接口与webview两种模式嵌入开发
- 良好的扩展性，融合视频、文字、表单多种方式提交。


# 开放性说明
本项目基于Zoomla!逐浪CMS接口开发，如果您不需要其中的远程提交表单（访客留言）则可以单独编译，忽略逐浪CMS接口部份，依然可以正常运行，非常方便。
有道是：

- 建网站,选逐浪。
- 易上手,功能棒。
- 质量好,服务善。
- 高性能,最划算。



## 使用说明

- 1.下载全站源码
- 2.使用百度开发工具进行开发
- 3.注意百度开发者ID需要设置正确，或使用体验号。
- 4.接口部份可以访问help.z01.com获取。


# 源码结构
```
|-- undefined
    |-- app.css
    |-- app.js
    |-- app.json
    |-- pkginfo.json
    |-- project.swan.json
    |-- README.md
    |-- crypto-js
    |   |-- aes.js
    |   |-- bower.json
    |   |-- cipher-core.js
    |   |-- core.js
    |   |-- enc-base64.js
    |   |-- enc-hex.js
    |   |-- enc-latin1.js
    |   |-- enc-utf16.js
    |   |-- enc-utf8.js
    |   |-- evpkdf.js
    |   |-- format-hex.js
    |   |-- format-openssl.js
    |   |-- hmac-md5.js
    |   |-- hmac-ripemd160.js
    |   |-- hmac-sha1.js
    |   |-- hmac-sha224.js
    |   |-- hmac-sha256.js
    |   |-- hmac-sha3.js
    |   |-- hmac-sha384.js
    |   |-- hmac-sha512.js
    |   |-- hmac.js
    |   |-- index.js
    |   |-- lib-typedarrays.js
    |   |-- md5.js
    |   |-- mode-cfb.js
    |   |-- mode-ctr-gladman.js
    |   |-- mode-ctr.js
    |   |-- mode-ecb.js
    |   |-- mode-ofb.js
    |   |-- package.json
    |   |-- pad-ansix923.js
    |   |-- pad-iso10126.js
    |   |-- pad-iso97971.js
    |   |-- pad-nopadding.js
    |   |-- pad-pkcs7.js
    |   |-- pad-zeropadding.js
    |   |-- pbkdf2.js
    |   |-- rabbit-legacy.js
    |   |-- rabbit.js
    |   |-- rc4.js
    |   |-- ripemd160.js
    |   |-- sha1.js
    |   |-- sha224.js
    |   |-- sha256.js
    |   |-- sha3.js
    |   |-- sha384.js
    |   |-- sha512.js
    |   |-- tripledes.js
    |   |-- x64-core.js
    |-- pages
        |-- accazs
        |   |-- index.css
        |   |-- index.js
        |   |-- index.json
        |   |-- index.swan
        |-- bbzl
        |   |-- index.css
        |   |-- index.js
        |   |-- index.json
        |   |-- index.swan
        |-- bkzn
        |   |-- bkzn.css
        |   |-- bkzn.js
        |   |-- bkzn.json
        |   |-- bkzn.swan
        |-- component
        |   |-- component.css
        |   |-- component.js
        |   |-- component.json
        |   |-- component.swan
        |-- detail
        |   |-- detail.css
        |   |-- detail.js
        |   |-- detail.json
        |   |-- detail.swan
        |-- dlbm
        |   |-- index.css
        |   |-- index.js
        |   |-- index.json
        |   |-- index.swan
        |-- ep
        |   |-- ep.css
        |   |-- ep.js
        |   |-- ep.json
        |   |-- ep.swan
        |-- images
        |   |-- 1.png
        |   |-- banner.png
        |   |-- banner1.jpg
        |   |-- bbzl.jpg
        |   |-- bkzn.jpg
        |   |-- book.png
        |   |-- dlbm.jpg
        |   |-- dora.png
        |   |-- ep.jpg
        |   |-- gm.png
        |   |-- icon1.png
        |   |-- icon2.png
        |   |-- icon3.png
        |   |-- icon4.png
        |   |-- icon5.png
        |   |-- icon6.png
        |   |-- icon7.png
        |   |-- icon8.png
        |   |-- index.png
        |   |-- jcgm.jpg
        |   |-- jqxx.jpg
        |   |-- jt.png
        |   |-- kc2.jpg
        |   |-- kcst.jpg
        |   |-- michelle.png
        |   |-- mike.png
        |   |-- mkcx.jpg
        |   |-- naipingpng.png
        |   |-- sdanvi.png
        |   |-- sean.png
        |   |-- searchproblem.png
        |   |-- tae_banner.png
        |   |-- tel.png
        |   |-- wx.png
        |   |-- xqpg.jpg
        |   |-- zhanwe.png
        |   |-- zn1.png
        |   |-- zn2.png
        |-- index
        |   |-- index.css
        |   |-- index.js
        |   |-- index.json
        |   |-- index.swan
        |-- jcgm
        |   |-- index.css
        |   |-- index.js
        |   |-- index.json
        |   |-- index.swan
        |-- jqxx
        |   |-- index.css
        |   |-- index.js
        |   |-- index.json
        |   |-- index.swan
        |-- kf
        |   |-- index.css
        |   |-- index.js
        |   |-- index.json
        |   |-- index.swan
        |-- logs
        |   |-- logs.css
        |   |-- logs.js
        |   |-- logs.json
        |   |-- logs.swan
        |-- mkcx
        |   |-- index.css
        |   |-- index.js
        |   |-- index.json
        |   |-- index.swan
        |-- sibo
        |   |-- sibo.css
        |   |-- sibo.js
        |   |-- sibo.json
        |   |-- sibo.swan
        |-- stkc
        |   |-- index.css
        |   |-- index.js
        |   |-- index.json
        |   |-- index.swan
        |-- stkcDetail
        |   |-- index.css
        |   |-- index.js
        |   |-- index.json
        |   |-- index.swan
        |-- stkcdora
        |   |-- index.css
        |   |-- index.js
        |   |-- index.json
        |   |-- index.swan
        |-- stkcmich
        |   |-- index.css
        |   |-- index.js
        |   |-- index.json
        |   |-- index.swan
        |-- stkcmike
        |   |-- index.css
        |   |-- index.js
        |   |-- index.json
        |   |-- index.swan
        |-- stkcsdanvi
        |   |-- index.css
        |   |-- index.js
        |   |-- index.json
        |   |-- index.swan
        |-- xqpg
        |   |-- index.css
        |   |-- index.js
        |   |-- index.json
        |   |-- index.swan
        |-- z01-com
            |-- z01-com.css
            |-- z01-com.js
            |-- z01-com.json
            |-- z01-com.swan

```



# 系统运行效果图
![系统效果图1](demo-show-系统效果图/01.jpg)
![系统效果图2](demo-show-系统效果图/02.jpg)
![系统效果图3](demo-show-系统效果图/03.jpg)
![系统效果图4](demo-show-系统效果图/04.jpg)
![系统效果图4](demo-show-系统效果图/05.jpg)
![系统效果图4](demo-show-系统效果图/06.jpg)
![系统效果图4](demo-show-系统效果图/07.jpg)
![系统效果图4](demo-show-系统效果图/08.jpg)
