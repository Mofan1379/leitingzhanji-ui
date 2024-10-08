<h1 align="center">雷霆战机 NEM Build 3</h1>

<p align="center">基于 <a href="https://go.dev/" target="_blank">Golang</a> + <a href="https://nodejs.org/zh-cn" target="_blank">Node</a> + <a href="https://vuejs.org/" target="_blank">Vue3</a> 构建。</p>

<div align="center">
<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/LauZzL/leitingzhanji-ui?style=for-the-badge">
<img alt="GitHub forks" src="https://img.shields.io/github/forks/LauZzL/leitingzhanji-ui?style=for-the-badge">
<img alt="GitHub Release" src="https://img.shields.io/github/v/release/LauZzL/leitingzhanji-ui?style=for-the-badge">
<br>
<img alt="Page Views" src="https://badges.toozhao.com/badges/01J7D1CAVCZQSZNWQZV9RHS37H/green.svg">
</div>

## 前言

本仓库仅用于存档代码，记录版本日志。

## 免责声明

本项目仅供学习交流，请勿用于任何非法用途。

## 下载

[Releases](https://github.com/LauZzL/leitingzhanji-ui/releases)

## 官方文档

[https://lauzzl.github.io/leitingzhanji-docs/](https://lauzzl.github.io/leitingzhanji-docs/)

## 支持功能

> 修改数据需要[`js-hook`](https://github.com/LauZzL/leitingzhanji-jshookserver)支持。

- 畅玩卡(月卡)特权
- 防检测
- 免广告
- 日常
  - 体力
  - 商城
  - 星际探索
  - 装备宝箱
  - 幸运转盘
- PVP
  - 一键攻打(金币场)
- 闯关
  - 英雄难度
  - 单关卡攻打
  - 自定义攻打
  - 一键材料
  - 3经验残骸自动双倍领取
- 无尽
  - 祝福修改
  - 一键BOSS宝箱
  - 一键海盗宝箱
  - 购买道具
- 活动关卡
- BOSS关卡
- 数值修改
  - 伤害修改
  - 生命修改
  - 分数修改
- 封包
  - HTTP API
  - 数据监听
  - 数据修改
  - 封包流程编辑
  - 封包编译发布(是否可编辑、密码、授权UID)
  - 执行/导入封包
- JavaScript 扩展
  - 脚本编辑器
  - 脚本执行
- 其他
  - 无敌
  - 使用核弹不消耗
  - 复活免钻石

## 封包

> 请勿加载或执行未知来源、功能的封包，他可能造成账号数据损失。

### 封包流程编辑

封包数据支持模板替换，使用`{template}`(template查看下方表格)作为占位符，提交封包时会自动替换。

| template | description |
| --- | --- |
| `uid` | 自动替换为当前登录的UID |
| `sid` | 自动替换为当前登录的SID |
| `cmdSequence` | 自动替换为随机cmdSequence，防止重复请求 |
| `timestamp` | 自动替换为当前时间戳 |

### 数据监听

支持监听数据，并支持修改请求、响应数据，特殊符号请使用`\`转义。


## 预览

#### 首页

![首页](https://s21.ax1x.com/2024/09/10/pAm0BKH.jpg)

#### 日常

![日常](https://s21.ax1x.com/2024/09/10/pAmW8N4.jpg)

#### 闯关

![闯关](https://s21.ax1x.com/2024/09/10/pAmWG4J.jpg)

#### 无尽

![无尽](https://s21.ax1x.com/2024/09/10/pAmWNg1.jpg)

#### BOSS关卡

![BOSS关卡](https://s21.ax1x.com/2024/09/10/pAm0C8S.jpg)

![BOSS关卡2](https://s21.ax1x.com/2024/09/10/pAmWdu6.jpg)

#### 活动关卡

![BOSS关卡](https://s21.ax1x.com/2024/09/10/pAm0Pgg.jpg)

#### 网络监听

![网络监听](https://s21.ax1x.com/2024/09/10/pAm0t56.png)

#### JS-HOOK-Server

![JS-Hook-Server](https://s21.ax1x.com/2024/09/22/pAMTEon.png)

#### 数据修改

![数据修改](https://s21.ax1x.com/2024/09/10/pAm0UPK.jpg)

#### 封包编辑

![封包编辑](https://s21.ax1x.com/2024/09/10/pAm0a8O.jpg)

#### 封包编译

![封包编译](https://s21.ax1x.com/2024/09/10/pAm0d2D.jpg)

#### 本地封包执行

![本地封包执行](https://s21.ax1x.com/2024/09/10/pAm0wxe.jpg)

#### JavaScript 脚本扩展

![JavaScript扩展脚本](https://iili.io/dQcTsK7.png)

#### 其他

![其他](https://s21.ax1x.com/2024/09/10/pAmWYC9.jpg)

## 参考

- [SunnyNet](https://github.com/qtgolang/SunnyNet)

## 鸣谢

- [@ASCIIX](https://github.com/ASCIIX)
- [@Mofan1379](https://github.com/Mofan1379)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=LauZzL/leitingzhanji-ui&type=Date)](https://star-history.com/#LauZzL/leitingzhanji-ui&Date)