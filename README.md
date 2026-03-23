<p align="center">
<img src="./docs/images/LOGO.png" height="80"/>
</p>

<div align="center">

[![主仓库](https://img.shields.io/badge/主仓库-ZCShou%2FGoGoGo-2ea44f?style=for-the-badge&logo=github)](https://github.com/ZCShou/GoGoGo)
[![本分支](https://img.shields.io/badge/本分支-qwe123535%2FGoGoGo-blue?style=for-the-badge&logo=github)](https://github.com/qwe123535/GoGoGo)
[![版本号](https://img.shields.io/github/v/release/qwe123535/GoGoGo?style=for-the-badge&logo=git&label=版本)](https://github.com/qwe123535/GoGoGo/releases)
[![Stars 人气](https://img.shields.io/github/stars/qwe123535/GoGoGo?style=for-the-badge&logo=github&color=ff9f00)](https://github.com/ZCShou/GoGoGo/stargazers)
[![协议](https://img.shields.io/github/license/qwe123535/GoGoGo?style=for-the-badge&logo=gnu&label=协议)](https://github.com/ZCShou/GoGoGo/blob/master/LICENSE)
[![文档规范](https://img.shields.io/badge/文档-standard--readme-9cf?style=for-the-badge&logo=markdown)](https://github.com/RichardLitt/standard-readme)

</div>

<div align="center">

[![构建状态](https://img.shields.io/github/actions/workflow/status/qwe123535/GoGoGo/build-check.yml?style=for-the-badge&logo=githubactions&label=构建)](https://github.com/qwe123535/GoGoGo/actions)
[![代码质量](https://img.shields.io/github/actions/workflow/status/qwe123535/GoGoGo/codeql-analysis.yml?style=for-the-badge&logo=codeql&label=代码扫描)](https://github.com/qwe123535/GoGoGo/actions)

</div>

<div align="center">
<b>影梭独立实验分支</b> | 已完全移除百度地图 | 仅高德地图引擎 | 不定期维护 | Android 8.0+ 免 ROOT 虚拟定位
</div>

---

### 🔗 分支生态与相关链接
<div align="center">

[![官方文档](https://img.shields.io/badge/官方文档-GoGoGo-007ACC?style=for-the-badge&logo=gitbook)](https://github.com/ZCShou/GoGoGo)
[![社区 Wiki](https://img.shields.io/badge/社区文档-Wiki-2196F3?style=for-the-badge&logo=docs)](https://github.com/qwe123535/GoGoGo/wiki)
[![问题反馈](https://img.shields.io/badge/问题反馈-Issues-FF4444?style=for-the-badge&logo=github)](https://github.com/qwe123535/GoGoGo/issues)
[![提交PR](https://img.shields.io/badge/提交贡献-PR-00C853?style=for-the-badge&logo=github)](https://github.com/qwe123535/GoGoGo/pulls)
[![GPLv3 协议](https://img.shields.io/badge/开源协议-GPLv3-FF5722?style=for-the-badge&logo=gnu&logoColor=white)](https://www.gnu.org/licenses/gpl-3.0.html)

</div>

## 简介
&emsp;&emsp;影梭是一个基于 Android 调试 API + 百度地图及定位 SDK 实现的安卓定位修改工具，并且同时实现了一个可以自由控制移动的摇杆。使用影梭，不需要 ROOT 权限就可以随意修改自己的当前位置以及模拟移动。

1. 源码仓库：[Github](https://github.com/ZCShou/GoGoGo)（推荐）、[Gitee](https://gitee.com/itexp/gogogo)（镜像）
2. 下载地址：[Github](https://github.com/ZCShou/GoGoGo/releases)（推荐）、[Gitee](https://gitee.com/itexp/gogogo/releases)（镜像）

警告一
 
本分支为独立实验性版本，已完全移除百度地图相关所有代码、依赖及接口调用，仅保留高德地图作为唯一定位引擎，任何基于其他地图SDK的功能均已彻底剔除，不再提供相关兼容与支持。
 
警告二
 
本项目仅进行不定期维护，不承诺定位精度、运行稳定性、机型兼容性及持续更新，不提供任何形式的技术保障与使用承诺，使用风险由使用者自行承担。
 
警告三
 
本项目全部源码仅限用于 Android 开发技术学习与高德地图定位接口研究，严禁用于任何形式的作弊、违规定位修改、绕过平台规则及其他违反平台用户协议的行为。
 
警告四
 
本项目未针对任何第三方应用（包括但不限于运动打卡类、游戏类、社交类应用）进行适配，因使用本项目导致的一切后果，均与本项目开发者无关。
 
警告五
 
本项目基于 GPLv3 开源协议 开源，所有二次修改、分发、衍生版本必须严格遵守协议条款，完整开放修改后源码并保留原版权声明，违者将视为违反开源协议。
 
GPLv3 协议原文地址：
https://www.gnu.org/licenses/gpl-3.0.html

## 功能
1. 定位修改
2. 摇杆控制移动
3. 历史记录
4. 位置搜索
5. 直接输入坐标

## 截图
![joystick.jpg](./docs/images/joystick.jpg)
![search_history.jpg](./docs/images/search_history.jpg)
![map.jpg](./docs/images/map.jpg)

# 用法
1. 下载 APK 直接安装
2. 启动影梭，赋予相关权限
3. 单击地图位置，然后点击启动按钮

## 文档
&emsp;&emsp;由于本人并不是做移动开发的，很多功能代码写的都比较差。我也第一次写  Android APP，目前还处在学习中。。。此外，就一个简单的 APP，应该也不需要啥文档，开发过程中遇到的一些问题，我一般都会记录在个人博客中，具体参见：https://blog.csdn.net/zcshoucsdn/category_10559121.html

&emsp;&emsp;如果有疑问可以直接搜索 ISSUE 或者 在上面直接提交问题。

## 参考
&emsp;&emsp;由于本人也是个新手，纯属业余瞎搞，因此，在写影梭的过程中，参考了很多网友分享的技术文章、示例代码等。包括但不限于以下列出的几个：
1. https://github.com/Hilaver/MockGPS
2. https://github.com/bxxfighting/together-go
3. https://github.com/P72B/Mocklation

&emsp;&emsp;还有些 CSDN 上的文章，目前不记得地址了，如果您发现其中有直接引用或借鉴您的地方，请与我联系，我会再第一时间进行处理，谢谢！

## FAQ
**Q：本分支支持最低 Android 版本是多少？**
A：本分支已完成底层兼容优化，最低支持 **Android 5.0** 及以上系统设备。

**Q：项目是否会持续维护与更新？**
A：会持续进行 **BUG 修复、功能优化、稳定性提升** 等维护工作，保证项目正常稳定运行。

**Q：本分支与原仓库有哪些区别？**
A：本分支**已完全移除百度地图**相关代码与依赖，仅保留高德地图引擎，并对整体稳定性做了增强。

**Q：使用过程中出现闪退、异常如何处理？**
A：可尝试重启应用、重新授权相关权限；如问题复现，欢迎提交 Issue 反馈，我会尽快修复。

**Q：是否支持鸿蒙系统？**
A：经测试，本分支不可在鸿蒙系统上正常安装与运行。

**Q：定位功能是否支持所有应用？**
A：本项目仅用于技术学习与研究，因各应用风控策略不同，无法保证在所有应用中均生效。

**Q：编译时出现报错该如何解决？**
A：请检查 Android Studio、Gradle、Java 环境是否配置正确，完整同步依赖后重试。

**Q：是否可以二次开发与分发？**
A：本项目基于 GPL-3.0 协议开源，允许二次开发与分发，但需遵守协议并保留相关版权声明。

## 如何贡献
1. FORK -> PR
2. 加入影梭开发，共同完善

## 许可证
GPL-3.0-only © ZCShou

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FZCShou%2FGoGoGo.svg?type=large&issueType=license)](https://app.fossa.com/projects/git%2Bgithub.com%2FZCShou%2FGoGoGo?ref=badge_large&issueType=license)
