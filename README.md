# ChatCanvas Releases

ChatCanvas（语布）的**安装包与自动更新清单**发布仓库。

> 这里只有构建产物，**不含源代码**，源码仓库不公开。

## 下载

| 平台 | 安装包 |
| --- | --- |
| Windows x64 | [ChatCanvas 2.2.2 安装包](../../releases/download/v2.2.2/ChatCanvas_2.2.2_x64-setup.exe) |
| macOS (Apple Silicon) | 稍后补充（当前 macOS 版不参与自动更新） |

所有安装包均带 minisign 签名；客户端更新时会校验签名，签名不匹配不会安装。

## 自动更新

应用内更新器读取下面这个固定地址（每次发版只替换其中的 `latest.json`）：

```
https://github.com/kriswyl/chatcanvas-releases/releases/download/updater/latest.json
```

`latest.json` 由发布流程生成，请勿手动修改。

## 说明

- 本仓库由发布流程维护，Release 资产请不要手动替换。
- 安装包对应的版本改动见源码仓库的 CHANGELOG。
