# MaskWechat / 微信密友模块

[![LSPosed](https://img.shields.io/badge/LSPosed-supported-green)](https://modules.lsposed.org/)
[![Android](https://img.shields.io/badge/Android-8.0+-blue)](https://www.android.com/)
[![Telegram](https://img.shields.io/badge/Telegram-Channel-blue.svg)](https://t.me/MaskWechat3)

这是一个 **微信 Xposed / LSPosed 模块**，用于保护隐私，将指定联系人设置为“密友”，并在微信各处隐藏其存在。

---

## 📲 使用方法

1. 安装本模块  
2. 在 **LSPosed / Xposed** 中勾选 **微信**
3. 重启手机或重启微信
4. 打开微信 → **我 → 设置 → 更多 → 关怀模式**
5. 长按「开启」即可进入密友管理界面

📢 官方频道：[https://t.me/MaskWechat3](https://t.me/MaskWechat3)

---

## ✨ 功能特性

| 功能 | 说明 |
|----|----|
| 🔒 隐藏指定好友 | 将指定联系人从会话列表、通讯录、搜索结果中彻底隐藏 |
| 🚫 隐藏朋友圈 | 屏蔽指定好友的朋友圈入口及动态 |
| 📞 拦截语音通话 | 阻止指定联系人的语音通话请求 |
| 📹 拦截视频通话 | 阻止指定联系人的视频通话请求 |
| 🔍 隐藏主页搜索 | 禁止通过微信首页搜索找到指定联系人 |
| 💬 隐藏聊天记录 | 在全局聊天记录搜索中屏蔽指定联系人的消息 |
| 🧩 快速添加密友 | 聊天页面输入命令即可管理 |

---

## 💬 快捷命令（聊天页面输入）

| 命令 | 功能 |
|----|----|
| `#add` | 将当前聊天对象加入密友列表 |
| `#del` | 从密友列表中移除 |
| `#hide` | 临时隐藏聊天记录（离开聊天页面即失效） |
| `#show` | 临时显示聊天记录 |


> 也可在微信首页界面长按联系人直接操作。

---

## 📦 适配微信版本

✅ 8.0.70  
✅ 8.0.71  
✅ 8.0.72  

其他版本未测试，可能无法正常工作。

---

## 🙏 特别鸣谢

- [Mingyueyixi/MaskWechat](https://github.com/Mingyueyixi/MaskWechat)

## 📢 官方群组
- [MaskWechat](https://t.me/MaskWechat2)

- 本模块目前完全免费使用

- 如果你是付费购买的，请联系售后退款
  
---

## ⚠️ 注意事项

- 支持 **Root + LSPosed**
- 不同微信构建版本可能导致功能异常
- 若无法使用，请确认微信版本号及 SHA1 是否匹配官方包
