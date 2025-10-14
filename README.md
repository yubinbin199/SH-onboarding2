# 上海地区入职指引系统

这是一个聊天机器人式的入职指引页面，帮助新员工完成入职流程。

## 📁 项目文件说明

- `index.html` - 首页入口（自动跳转到主页面）
- `onboarding-chatbot.html` - 主要的入职指引页面
- `vercel.json` - Vercel 部署配置文件
- `README.md` - 项目说明文档

## 🚀 本地预览

在项目文件夹中运行：
```bash
python3 -m http.server 8000
```

然后在浏览器打开：`http://localhost:8000`

## 📦 部署到 GitHub + Vercel

### 1. 上传到 GitHub
- 在 GitHub 创建新仓库（如 `SH-onboarding`）
- 将所有文件上传到仓库根目录

### 2. 部署到 Vercel
- 登录 vercel.com
- Import Git Repository，选择你的仓库
- Framework Preset: Other
- Build Command: 留空
- Output Directory: 留空或 `.`
- 点击 Deploy

## ✨ 功能特点

- 🤖 聊天机器人式交互
- 📝 9个入职步骤卡片
- 💾 自动保存进度到浏览器
- 📊 实时进度条显示
- 📱 响应式设计，支持移动端

