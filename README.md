# Chatbot UI Lite

一个简单的聊天机器人起始套件，使用 Next.js、TypeScript 和 Tailwind CSS 作为 OpenAI 聊天模型的支持。

查看[演示](https://chatbot-ui-lite.pages.dev/)。

![Chatbot UI Lite](./public/screenshot.png)

## 特点

Chatbot UI Lite 提供了一个简单、完全功能的聊天界面，您可以使用它开始构建自己的由 OpenAI 支持的聊天机器人应用程序。

它具有您需要的一切，可以立即开始。

在`components/Chat`中修改聊天界面。

在`utils/index.ts`中调整系统提示。

在`pages/index.tsx`中调整助手提示。

## 部署

**cloudflare**

使用 cloudflare 托管 Chatbot UI Lite 的实时版本。



## 本地运行

**1. 克隆 Repo**

```bash
git clone https://github.com/constself/chatbot-ui-lite.git
```

**2. 安装依赖项**

```bash
npm i
```

**3. 提供 OpenAI API 密钥**

在 repo 的根目录中创建一个.env.local 文件，并提供您的 OpenAI API 密钥:

```bash
OPENAI_API_KEY=<YOUR_KEY>
```

**4. 运行应用程序 **

```bash
npm run dev
```

## 环境变量

配置本地或者部署的环境变量

| 名称                  | 描述                                  | 默认                     |
| :-------------------- | ------------------------------------- | ------------------------ |
| `OPENAI_API_KEY`      | 你的 OpenAI API Key                   | `null`                   |
| `OPENAI_API_BASE_URL` | 请求 OpenAI API 的自定义 Base URL.    | `https://api.openai.com` |
| `NODE_VERSION`        | 在部署cloudflare添加,指定node版本`17` | `12`                     |

**5. 开始构建 **

您应该能够开始与机器人聊天了。

现在，去构建任何您想要的聊天机器人应用程序！
