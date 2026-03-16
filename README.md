# 婚礼邀请函 - 管理后台

这是一个简单的管理后台，用于查看和统计婚礼邀请函的 RSVP 回复数据。

## 功能特性

- 📊 **实时统计数据** - 显示总回复数、参与人数、住宿需求等
- 📍 **地点统计** - 按婚礼地点统计参与情况
- 🏨 **住宿统计** - 按房间类型统计住宿需求
- 📋 **详细回复列表** - 显示所有回复的详细信息
- 🔄 **自动刷新** - 每 30 秒自动刷新一次数据

## 访问方式

访问 GitHub Pages：`https://tingwen44.github.io/wedding-admin/`

## 技术栈

- 纯 HTML + CSS + JavaScript
- 无需构建工具，直接在 GitHub Pages 上部署

## 数据来源

数据来自后端 API：`https://wedding-backend-production-6728.up.railway.app`

## 配置

如需修改后端 URL 或 ADMIN_TOKEN，请编辑 `index.html` 中的以下部分：

```javascript
const BACKEND_URL = 'https://wedding-backend-production-6728.up.railway.app';
const ADMIN_TOKEN = 'Silentmafia001';
```
