# 互联网 Java 工程师进阶知识完全扫盲

[![actions status](https://github.com/doocs/advanced-java/workflows/Sync/badge.svg)](https://github.com/doocs/advanced-java/actions?query=workflow%3ASync)
[![actions status](https://github.com/doocs/advanced-java/workflows/Prettier/badge.svg)](https://github.com/doocs/advanced-java/actions?query=workflow%3APrettier)
[![license](https://badgen.net/github/license/doocs/advanced-java?color=green)](./LICENSE)
[![PRs Welcome](https://badgen.net/badge/PRs/welcome/green)](http://makeapullrequest.com)
[![doocs](https://badgen.net/badge/organization/join%20us/green)](https://doocs.github.io/#/?id=how-to-join)
[![github](https://badgen.net/badge/⭐/GitHub/blue)](https://github.com/doocs/advanced-java)
[![gitee](https://badgen.net/badge/⭐/Gitee/blue)](https://gitee.com/doocs/advanced-java)
[![stars](https://badgen.net/github/stars/doocs/advanced-java)](https://github.com/doocs/advanced-java/stargazers)
[![forks](https://badgen.net/github/forks/doocs/advanced-java)](https://github.com/doocs/advanced-java/network/members)
[![contributors](https://badgen.net/github/contributors/doocs/advanced-java)](./docs/from-readers#contributors)
[![original](https://badgen.net/badge/original/%E4%B8%AD%E5%8D%8E%E7%9F%B3%E6%9D%89/orange)](https://github.com/doocs/advanced-java)
[![notice](https://badgen.net/badge/notice/%E7%BB%B4%E6%9D%83%E8%A1%8C%E5%8A%A8/orange)](./docs/extra-page/rights-defending-action.md)
[![wechat-group](https://badgen.net/badge/chat/%E5%BE%AE%E4%BF%A1%E4%BA%A4%E6%B5%81/cyan)](#公众号)
[![coding](https://badgen.net/badge/leetcode/%E5%88%B7%E9%A2%98%E5%B0%8F%E9%98%9F/cyan)](https://github.com/doocs/leetcode)

本项目大部分内容来自中华石杉，版权归作者所有，内容涵盖[高并发](#高并发架构)、[分布式](#分布式系统)、[高可用](#高可用架构)、[微服务](#微服务架构)、[海量数据处理](#海量数据处理)等领域知识。我对这部分知识做了一个系统的整理，方便学习查阅。

本项目已开通 [Discussions](https://github.com/doocs/advanced-java/discussions) 功能。学习之前，先来看看 [Discussions 讨论区](https://github.com/doocs/advanced-java/discussions/9)的技术面试官是怎么说的吧。本项目欢迎各位开发者朋友到 [Discussions 讨论区](https://github.com/doocs/advanced-java/discussions)分享自己的一些想法和实践经验。也不妨 Star 关注 [doocs/advanced-java](https://github.com/doocs/advanced-java)，随时追踪项目最新动态。

本项目基于 [Docsify](https://docsify.js.org) 进行构建，并同步部署（这里用到 [Gitee Pages Action](https://github.com/yanglbme/gitee-pages-action) 自动部署工具，非常好用的一个开源工具，欢迎 Star 关注）在以下三个站点：

- Netlify: https://adjava.netlify.app
- Gitee Pages: https://doocs.gitee.io/advanced-java
- GitHub Pages: https://doocs.github.io/advanced-java

如果你同时希望在本地查看，请按照以下步骤进行操作：

1. 安装 NodeJS 环境：https://nodejs.org/zh-cn/
2. 安装 Docsify：`npm i docsify-cli -g`
3. 使用 Git 克隆([HTTPS / SSH / GitHub CLI](https://docs.github.com/en/free-pro-team@latest/github/using-git/which-remote-url-should-i-use))本项目到你的本地环境：`git clone git@github.com:doocs/advanced-java.git`
4. 进入 advanced-java 根目录：`cd advanced-java`
5. 执行命令，启动一个本地服务器：`docsify serve`
6. 浏览器访问地址：http://localhost:3000

## 高并发架构

### [消息队列](./docs/high-concurrency/mq-interview.md)

- [为什么使用消息队列？消息队列有什么优点和缺点？Kafka、ActiveMQ、RabbitMQ、RocketMQ 都有什么优点和缺点？](./docs/high-concurrency/why-mq.md)
