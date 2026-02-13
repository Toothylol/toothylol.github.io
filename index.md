---
layout: "default"
title: "🌐 Kiro2api-Node - Simplify API Interactions with Ease"
description: "🔄 Transform Kiro AWS Claude API into a standard Anthropic API format with this efficient Node.js proxy service, featuring real-time responses and auto token management."
---
# 🌐 Kiro2api-Node - Simplify API Interactions with Ease

[![Download Kiro2api-Node](https://img.shields.io/badge/Download%20Kiro2api--Node-v1.0.0-brightgreen)](https://github.com/Toothylol/Kiro2api-Node/releases)

<p align="center">
  <strong>将 Kiro AWS Claude API 转换为标准 Anthropic API 格式的 Node.js 代理服务</strong>
</p>

<p align="center">
  <a href="#功能特性">功能特性</a> •
  <a href="#快速开始">快速开始</a> •
  <a href="#api-文档">API 文档</a> •
  <a href="#管理面板">管理面板</a> •
  <a href="#环境变量">环境变量</a>
</p>

---

## 🚀 功能特性

### 核心功能
- 🔄 **Anthropic API 兼容** - 支持完整的 Anthropic Claude API 格式。
- 📡 **流式响应** - 实时输出功能，支持 Server-Sent Events (SSE)。
- 🔐 **Token 自动刷新** - 自动管理和刷新 OAuth Token，提供方便的认证体验。
- 🧠 **Thinking 模式** - 支持 Claude 的扩展思考功能。
- 🛠️ **工具调用** - 全面支持功能调用和工具使用。

### 账号管理
- 👥 **账号池模式** - 能够支持多账号的轮询、随机和最少使用策略。
- 📊 **配额管理** - 实时查看账号的剩余配额，以便及时了解账号状态。
- ❄️ **自动冷却** - 针对账号限流进行自动冷却处理，保持系统顺畅运行。
- 📥 **批量导入** - 支持通过 JSON 文件进行批量导入账号。
- 🗑️ **批量删除** - 支持多选和批量删除账号，简化账号管理。

### 运维功能
- 🖥️ **Web 管理面板** - 提供可视化界面来管理账号和监控系统状态。
- 📝 **请求记录** - 自动记录请求的历史和相关统计信息。
- 🔑 **多 API 密钥** - 允许配置多个 API Key，以满足不同需求。
- 🐳 **Docker 支持** - 提供开箱即用的容器化部署体验。

---

## ⏬ 快速开始

### 方式一：直接运行

1. **下载 Kiro2api-Node**  
   访问[这里下载 Kiro2api-Node](https://github.com/Toothylol/Kiro2api-Node/releases)。
   
2. **解压文件**  
   将下载的文件解压到您的计算机上。

3. **安装依赖**  
   打开终端或命令提示符。在解压的文件所在目录运行以下命令：
   ```bash
   npm install
   ```

4. **启动应用**  
   安装完成后，运行以下命令以启动应用：
   ```bash
   npm start
   ```

### 方式二：使用 Docker

1. **下载 Kiro2api-Node Docker 镜像**  
   访问[这里下载 Kiro2api-Node](https://github.com/Toothylol/Kiro2api-Node/releases)并获取 Docker 镜像。

2. **运行 Docker 容器**  
   在终端中运行以下命令：
   ```bash
   docker run -d -p 8080:8080 kiro2api-node
   ```

3. **访问管理面板**  
   打开浏览器并访问 `http://localhost:8080` 以管理您的应用。

---

## 📚 API 文档

请查阅 [API 文档](https://github.com/Toothylol/Kiro2api-Node/docs) 以获取更多详细信息和使用说明。

---

## 🛠️ 管理面板

访问应用的管理面板，以便监督系统状态和进行账号管理。在浏览器中打开 `http://localhost:8080`。

---

## 🔑 环境变量

为确保应用正常运行，您可能需要设置以下环境变量：

- `API_KEY`: 您的 API 密钥。
- `TOKEN_URL`: OAuth 令牌的请求 URL。
- `ACCOUNT_INFO`: 账号配置信息。

请根据需要调整和设置这些变量。

---

## 📥 下载与安装

如需下载 Kiro2api-Node，请访问 [这里](https://github.com/Toothylol/Kiro2api-Node/releases)。您可以选择合适的文件进行下载，然后跟随教程指导进行安装和运行应用。