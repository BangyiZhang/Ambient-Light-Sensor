# LightSense Web

## 项目简介

**LightSense Web** 是一个使用环境光传感器 API (Device Light API) 的网站，能够实时报告您当前的环境光强度，并且具备收集一定时间段内环境光强度数据的功能。本项目旨在提供实时环境光数据，帮助用户了解其周围光线条件。

## 技术栈

- **Ambient Light Sensor API (Device Light API)**：用于获取设备周围的光线强度。
- **编程语言**：HTML5, JavaScript。
- **数据库**：MongoDB，用于存储光线数据。
- **后端框架**：Node.js，处理服务端逻辑和数据库交互。

## 安装指南

### 先决条件

确保您的机器已经安装了 Node.js 和 MongoDB。您可以从官方网站下载并安装它们：

- [Node.js 官网](https://nodejs.org/)
- [MongoDB 官网](https://www.mongodb.com/try/download/community)

### 安装步骤

1. **克隆或下载项目** 克隆项目仓库到本地：

   ```
   bashCopy code
   git clone https://github.com/BangyiZhang/Ambient-Light-Sensor.git
   cd Ambient-Light-Sensor
   ```

2. **安装依赖** 进入项目的 `server` 目录并安装必需的 npm 包：

   ```
   bashCopy code
   cd server
   npm install
   ```

3. **启动 MongoDB** 启动 MongoDB 数据库服务。根据您的操作系统，这可能涉及运行 `mongod` 命令或通过服务管理工具启动 MongoDB 服务。

4. **运行应用** 在 `server` 目录下，执行以下命令来启动 Node.js 服务器：

   ```
   bashCopy code
   node app.js
   ```

5. **访问前端应用** 在浏览器中打开文件 `index.html` 或通过设置的服务器地址访问，通常是 [http://localhost:3000](http://localhost:3000/)。

## 使用说明

- 打开网站后，页面会显示当前的环境光强度。
- 通过网站界面，您可以启动和停止数据收集功能，这将在后台数据库中存储光强度数据。
