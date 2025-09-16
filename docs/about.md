# 关于知识树

## 项目介绍

知识树是一个基于AI的本地知识树生成工具，旨在帮助用户更好地学习和理解复杂概念。

## 系统要求

- **Node.js**: v14.0.0 或更高版本
- **操作系统**: Windows 10+, macOS 10.14+, 或 Linux (Ubuntu 18.04+)
- **内存**: 至少 4GB RAM
- **网络**: 需要互联网连接以访问AI API

## 安装和运行

### 1. 下载项目
```bash
git clone https://github.com/mark7399/KnowledgeTree.git
```

### 2. 安装依赖
```bash
npm install
```

### 3. 启动应用
```bash
npm start
```
或者以Web模式运行：
```bash
npm run start:web
```

## API配置

目前已支持DeepSeek R1和DeepSeek V3模型，您需要：

1. 前往 [DeepSeek官网](https://platform.deepseek.com/) 注册账号
2. 获取API Key
3. 在应用的API设置中填入您的API Key

## 使用方法

- **单击节点**：查看该概念的文档
- **右键节点**：编辑节点名称或删除节点
- **选中文字右键**：将选中的文字创建为新节点

## 许可证

MIT License