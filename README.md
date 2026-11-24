<!-- 1. 顶部横幅：把自己的名字和方向填进 URL 参数；中文/空格要 URL 编码 -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1E3A8A,100:1D4ED8&height=200&section=header&text=Jiajun%20Wang&fontColor=ffffff&fontSize=52&fontAlignY=36&desc=Agent%20Development%20%C2%B7%20AI%20Applications&descSize=18&descAlignY=58&animation=fadeIn" alt="banner"/>

<!-- 2. 打字机效果：每条 lines 用分号分隔 -->
<p align="center">
  <a href="https://github.com/JaJum">
    <img src="https://readme-typing-svg.demolab.com?font=Nunito&weight=600&size=24&pause=1800&color=1D4ED8&center=true&vCenter=true&width=560&lines=Building+AI+Agents;Exploring+LLM+Applications;Open+Source+Learner" alt="typing"/>
  </a>
</p>

<!-- 3. 快速徽章：学校、方向、邮箱、GitHub -->
<p align="center">
  <img src="https://img.shields.io/badge/Student-%E4%B8%AD%E5%9B%BD%E8%AE%A1%E9%87%8F%E5%A4%A7%E5%AD%A6-1D4ED8?style=for-the-badge&logo=googlescholar&logoColor=white" alt="中国计量大学"/>
  <img src="https://img.shields.io/badge/Student-%E5%A5%A5%E5%85%8B%E5%85%B0%E7%90%86%E5%B7%A5%E5%A4%A7%E5%AD%A6-1D4ED8?style=for-the-badge&logo=googlescholar&logoColor=white" alt="奥克兰理工大学"/>
  <img src="https://img.shields.io/badge/Focus-Agent%20%2F%20LLM-5EEAD4?style=for-the-badge&logo=openai&logoColor=black" alt="focus"/>
  <a href="mailto:jajum@foxmail.com">
    <img src="https://img.shields.io/badge/Email-jajum%40foxmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="email"/>
  </a>
</p>

---

## 👋 About me

嗨，我是 **王家骏（Jiajun Wang）**，中国计量大学计算机科班在读（大三）👋。


---

## 🛠️ Tech Stack

<!-- 4. 技术栈图标：assets/tech-stack.svg（skillicons.dev 同款样式，每行 7 个；增删图标需重新生成该文件） -->
<p align="center">
  <img src="./assets/tech-stack.svg" alt="tech stack"/>
</p>

---

## 🌟 Spotlight — garmin-connect-mcp

<!-- 5. Spotlight：用表格把 Logo、简介、徽章放在同一行 -->
<table>
  <tr>
    <td width="150" align="center" valign="middle">
      <a href="https://github.com/JaJum/garmin-connect-mcp">
        <img src="https://raw.githubusercontent.com/JaJum/garmin-connect-mcp/main/logo.png" width="128" height="128" alt="project logo"/>
      </a>
    </td>
    <td valign="middle">
      <h3>garmin-connect-mcp · 原生直连 Garmin 手表的 MCP Server</h3>
      <p><b>A real MCP server that connects Garmin watches natively — 15 data tools for AI-driven training & health.</b><br/>
      基于 Python 与 FastMCP 的真实 MCP Server，提供活动、睡眠、压力、训练状态等 15 类数据工具，让 AI 直连你的 Garmin 手表。</p>
      <p>
        <a href="https://github.com/JaJum/garmin-connect-mcp/releases/latest"><img src="https://img.shields.io/github/v/release/JaJum/garmin-connect-mcp?sort=semver&style=flat-square&color=2268F7" alt="release"/></a>
        <img src="https://img.shields.io/badge/platform-Python-black?style=flat-square" alt="platform"/>
        <a href="https://github.com/JaJum/garmin-connect-mcp/stargazers"><img src="https://img.shields.io/github/stars/JaJum/garmin-connect-mcp?style=flat-square&color=5EEAD4" alt="stars"/></a>
      </p>
    </td>
  </tr>
</table>

**为什么值得一试？**

- 🧠 **核心能力** — 原生直连 Garmin 手表协议，15 类数据工具覆盖活动、睡眠、压力、训练状态。
- ⚡ **实际体验** — AI 直接读取你的真实训练与健康数据，让科学训练建议有据可依。
- 🔧 **工程细节** — 真实 MCP Server 实现，基于 Python 与 FastMCP 构建，易于扩展接入各类 AI 客户端。
- 🤖 **面向场景** — 面向用 AI 做科学训练的运动爱好者，以及关注健康生活的每一个人。

<p align="center">
  <a href="https://github.com/JaJum/garmin-connect-mcp"><b>⬇ Download / Try it</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/JaJum/garmin-connect-mcp"><b>⭐ Star on GitHub</b></a>
</p>

---

## 📌 Pinned Projects

三个自研项目，分别对应 Agent 编排、Agent 底层范式和 Java Web 全栈，都可以 clone 下来在本地跑通：

- **[agentic-rag-ecommerce](https://github.com/JaJum/agentic-rag-ecommerce)** — 可回放的 Agentic RAG 电商智能客服（FastAPI + Vue3）。用 LangGraph 状态机把问题分流到闲聊 / 快速 RAG / 多步工具 Agent，6 个业务工具覆盖知识检索、商品对比、订单查询、售后政策与转人工；每一步工具调用都落库并经 SSE 实时推送，历史会话可回放完整轨迹。配套 72 商品 / 164 chunks 的可复现数据集、48 条评测用例和 81 个后端测试，Lite 模式一条命令离线跑通（SQLite + BM25 + Mock LLM，不需要 API Key）。
- **[agentlab](https://github.com/JaJum/agentlab)** — 不用 Agent 框架、只用 OpenAI SDK 手写的范式实验场：ReAct 的核心循环、LLM 输出解析、工具执行器与 SerpApi 搜索工具，加上 Plan-and-Solve 的 Planner / Executor 拆分，以及流式与非流式两种模型调用封装，用来对照弄清「框架到底替你做了什么」。
- **[Huangshan-HTML](https://github.com/JaJum/Huangshan-HTML)** — Spring 6 + Spring MVC + MyBatis + MySQL 的 SSM 全栈站点（黄山家乡主题课程大作业）：注册登录与 Session 管理、美食 / 景点 / 文化三个模块的关键词搜索与分页、管理员后台 CRUD 和 role=ADMIN 权限隔离；Maven 打包成 war，JSP / JSTL 渲染，跑在 JDK 17 + Tomcat 10.1 上。

---

<p align="center"><sub>📫 <b>jajum@foxmail.com</b> · welcome to reach out!</sub></p>
