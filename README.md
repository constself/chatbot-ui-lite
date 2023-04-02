# Chatbot UI Lite

一个简单的聊天机器人起始套件，使用Next.js、TypeScript和Tailwind CSS作为OpenAI聊天模型的支持。

查看[演示]( https://twitter.com/mckaywrigley/status/1634549098954248193?s=46&t=AowqkodyK6B4JccSOxSPew )。



![Chatbot UI Lite](./public/screenshot.png)

## 特点

Chatbot UI Lite提供了一个简单、完全功能的聊天界面，您可以使用它开始构建自己的由OpenAI支持的聊天机器人应用程序。

它具有您需要的一切，可以立即开始。

在`components/Chat`中修改聊天界面。

在`utils/index.ts`中调整系统提示。

在`pages/index.tsx`中调整助手提示。

## 部署

**Vercel**

使用Vercel托管Chatbot UI Lite的实时版本。

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fmckaywrigley%2Fchatbot-ui-lite&env=OPENAI_API_KEY&envDescription=OpenAI%20API%20Key%20needed%20for%20chat.&envLink=https%3A%2F%2Fopenai.com%2Fproduct&project-name=chatbot-ui-lite&repository-name=chatbot-ui-lite)

**Replit**

在Replit上分叉Chatbot UI[这里]( https://replit.com/@MckayWrigley/chatbot-ui )。

## 本地运行

**1. 克隆Repo**

```bash
git clone https://github.com/mckaywrigley/chatbot-ui-lite.git
```

**2. 安装依赖项**

```bash
npm i
```

**3. 提供OpenAI API密钥**

在repo的根目录中创建一个.env.local文件，并提供您的OpenAI API密钥:

```bash
OPENAI_API_KEY=<YOUR_KEY>
```

**4.  运行应用程序 **

```bash
npm run dev
```

**5. 开始构建 **

您应该能够开始与机器人聊天了。

现在，去构建任何您想要的聊天机器人应用程序！
