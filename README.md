# ChatCanvas Releases

ChatCanvas（语布）的**安装包与自动更新清单**发布仓库。

> 这里只有构建产物，**不含源代码**，源码不开源。

## 下载

最新版下载页：<https://github.com/kriswyl/chatcanvas-releases/releases/latest>

| 平台 | 安装包 |
| --- | --- |
| Windows x64 | [ChatCanvas 2.2.2 安装包](https://github.com/kriswyl/chatcanvas-releases/releases/download/v2.2.2/ChatCanvas_2.2.2_x64-setup.exe) |
| Windows 校验签名 | [`.exe.sig`](https://github.com/kriswyl/chatcanvas-releases/releases/download/v2.2.2/ChatCanvas_2.2.2_x64-setup.exe.sig) |
| macOS (Apple Silicon) | 稍后补充（当前 macOS 版不参与自动更新） |

安装包带 minisign 签名；客户端自动更新时会校验签名，签名不匹配不会安装。

## 自动更新

应用内更新器读取下面这个固定地址（每次发版只替换其中的 `latest.json`，地址本身不变）：

```
https://github.com/kriswyl/chatcanvas-releases/releases/download/updater/latest.json
```

`latest.json` 由发布流程生成，请勿手动修改。

## 说明

- 本仓库由发布流程维护，Release 资产请不要手动替换。
- 版本改动见源码仓库的 CHANGELOG。
