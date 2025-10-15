# 🤖 CTW智能入职指引（AI版）

这是一个聊天机器人式的入职指引页面，通过AI助手帮助新员工完成CTW的入职流程。

## 📁 项目文件说明

- `index.html` - 首页入口（自动跳转到主页面）
- `onboarding-chatbot.html` - 主要的入职指引页面
- `vercel.json` - Vercel 部署配置文件
- `README.md` - 项目说明文档

## 📋 入职流程步骤（共7步）

1. **P系统资料填写** - 填写个人信息（手机、身份证、银行卡等）
2. **A系统（任务管理）** - 任务与计时管理系统
3. **W系统（内部文档）** - 查看内部文档资料
4. **E系统（仅限美术）** - 美术素材制作与管理
5. **钉钉入组** - 加入团队钉钉群组
6. **点餐系统** - 易点吃点餐系统注册与使用
7. **完成入职** - 签署劳动合同，查看员工手册

## 🚀 本地预览

在项目文件夹中运行：
```bash
cd /Users/ctw/Desktop/sh-onboarding-project
python3 -m http.server 8000
```

然后在浏览器打开：`http://localhost:8000`

## 📦 部署到 GitHub + Vercel

### 方法一：网页上传（推荐）
1. 在 GitHub 创建新仓库（如 `SH-onboarding2`）
2. 将所有文件上传到仓库根目录
3. 登录 vercel.com，Import Git Repository
4. Framework Preset: **Other**
5. Build Command: **留空**
6. Output Directory: **留空**
7. 点击 Deploy

### 方法二：命令行推送
```bash
cd /Users/ctw/Desktop/sh-onboarding-project
git add .
git commit -m "更新入职指引"
git push origin main
```

## ✨ 功能特点

- 🤖 AI聊天机器人式交互
- 📝 7个入职步骤卡片式展示
- 💾 自动保存进度到浏览器（LocalStorage）
- 📊 实时进度条显示完成情况
- 🔗 所有系统链接可点击跳转
- 📱 响应式设计，支持移动端
- ✅ 点击"标记为完成"自动进入下一步
- 🎉 完成后自动清空卡片，显示祝贺信息

## 🌐 在线访问

- **GitHub 仓库**: https://github.com/yubinbin199/SH-onboarding2
- **Vercel 部署**: https://sh-onboarding2.vercel.app/
- **本地预览**: http://localhost:8000/

## 🛠️ 技术栈

- 纯 HTML + CSS + JavaScript
- 无需任何框架或构建工具
- 使用 LocalStorage 保存进度
- 响应式设计，兼容各种设备

## 📝 更新日志

### v2.0 - 2025.10.14
- 更新为CTW智能入职指引AI版
- 优化步骤内容，从9步精简为7步
- 更新系统链接和联系人信息
- 增加E系统（美术专用）
- 优化点餐系统说明
- 更新劳动合同签署方式为腾讯电子签

### v1.0 - 2025.10.14
- 初始版本发布
- 实现聊天机器人式交互
- 9个入职步骤
- 进度保存功能

---

💡 **小白贴士**：本项目无需任何安装，直接用浏览器打开 HTML 文件即可使用！
