## Riona-AI-Agent 🌸
中文测试

Riona-AI-Agent is an AI-powered automation tool designed for **Instagram** to automate social media interactions such as posting, liking, and commenting. It leverages advanced AI models to generate engaging content, automate interactions, and manage Instagram accounts efficiently.

Before using the automation features, you can personalize the agent by training with the following, including:

- **YouTube Video URL** 🎥
- **Audio File** 🎙️
- **Portfolio or Website Link** 🌐
- **File Formats Supported**: PDF, DOC, DOCX, TXT 📄

## Features

- **Instagram Automation**: Automatically log in, post photos, like posts, and leave thoughtful comments.
- **AI-Powered Content Generation**: Use Google Generative AI to create engaging captions and comments.
- **Proxy Support**: Use proxies to manage multiple accounts and avoid rate limits.
- **Cookie Management**: Save and load cookies to maintain sessions across restarts.

**Upcoming Features:**

- **Twitter Automation**: (Coming soon) Automatically tweet, retweet, and like tweets.
- **GitHub Automation**: (Coming soon) Automatically manage repositories, issues, and pull requests.

## Installation

1. **Clone the repository**:

   ```嘘
   git克隆https://github.com/david-patrick-chuks/Riona-AI-Agent.git
   CD Riona-AI-代理
   ```

2. **安装依赖项**:

   ```嘘
   npm安装
   ```

3. **设置环境变量**:
重命名[. env .示例](http://_vscodecontentref_/1)文件到[。包封/包围（动词envelop的简写）](http://_vscodecontentref_/1)并添加您的Instagram凭据。请参考[. env .示例](http://_vscodecontentref_/2)所需变量的文件。
   ```dotenv # Instagram凭证
   iguser name = your _ insta gram _ username
   ig password = your _ insta gram _ password
   
   Xusername= #Twitter用户名
   Xpassword= #Twitter密码

   URI蒙哥数据库= #蒙哥数据库

```

##用法

1.**运行Instagram代理* *:
``嘘
npm开始
   ```

**即将推出的功能:**

- **运行Twitter代理**(即将推出):

  ```嘘
  npm运行开始:twitter
  ```

- **运行GitHub代理**(即将推出):
  ```嘘
  npm运行开始:github
  ```

##项目结构

- **src/客户**:包含与Instagram等社交媒体平台交互的主要逻辑。
- **src/config**:配置文件，包括记录器设置。
- **src/utils**:用于处理错误、cookies、数据保存等的实用功能。
- **src/代理**:包含AI代理逻辑和训练脚本。
- **服务代表/代理/培训**:人工智能代理的训练脚本。
- **src/模式**:AI生成的内容和数据库模型的模式定义。
- **src/测试**:包含测试数据和脚本，比如示例tweets。

##伐木

该项目使用自定义记录器来记录信息、警告和错误。日志保存在[日志](http://_vscodecontentref_/3)目录。

##错误处理

设置流程级错误处理程序是为了捕获未处理的承诺拒绝、未捕获的异常和流程警告。使用自定义记录器记录错误。

##贡献的

欢迎投稿！请派生存储库并提交包含您的更改的拉请求。

##许可证

这个项目是在麻省理工学院的许可下进行的。有关详细信息，请参见许可证文件。

##承认

- [谷歌生成人工智能](https://ai.google/tools/)提供人工智能模型。
- [操纵木偶的人](https://github.com/puppeteer/puppeteer)用于浏览器自动化。
- [木偶师-额外](https://github.com/berstend/puppeteer-extra)获得额外的插件和增强功能。
