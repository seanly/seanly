<h1 align="center">Hi 👋，我是 永胜</h1>
<h3 align="center">SRE · 可靠性与平台工程 | <a href="https://github.com/seanly/dmr">DMR</a> 作者 | 开源与插件生态</h3>

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=seanly&label=Profile%20views&color=0e75b6&style=flat" alt="seanly" />
</p>

### DMR（Decide, Monitor, Review）

我是 **[DMR](https://github.com/seanly/dmr)** 的创造者：一个用 Go 编写的、**插件优先**的 AI Agent 框架，强调 **Tape** 可审计、**OPA** 策略治理与人机审批。  
> *In dmr we trust, but verify.*

另见 **dmr-plugin-*** 等扩展，把工具、策略与审批都做成可插拔能力，和我在交付链路上做平台化、自动化的思路是一致的。

### 对 AI 的看法（个人）

我相信 AI 更适合定位为 **协作者与可调度的能力**，而不是不可解释的黑箱。工程上我倾向：**用策略约束权限边界**、**用审计留痕支撑复盘与合规**、在关键路径保留 **人机确认**。  
落地时和做 SRE 一样：**可观测、可验证、可回滚** 比「看起来聪明」更重要。

---

- 🔭 **SRE 视角**：关注稳定性、变更风险、自动化与可观测；把重复劳动沉淀成平台能力与流水线
- 🛠️ **技术栈**：熟悉 **Go**、Python、Java；活跃于 **Kubernetes** 与交付/安全工具链；主打开源方向见下方 **DMR** 与插件生态
- 🌱 持续补齐前端、AI 工程化与 DevOps 相关实践，让「跑得快」和「跑得稳」能同时成立
- 🚀 维护并参与多个开源项目，欢迎访问我的 [GitHub 仓库](https://github.com/seanly?tab=repositories)
- 💬 欢迎交流 **SRE / 平台与自动化**、**插件与策略化 Agent**、云原生与 AI 工程
- 📫 联系方式：seanly@opsbox.dev

---

<h3 align="left">🚀 开源项目（DMR 与插件）</h3>

<p align="left">
  <a href="https://github.com/seanly/dmr" target="_blank">
    <img src="https://img.shields.io/badge/DMR-Core-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="DMR" />
  </a>
  <a href="https://github.com/seanly/dmr-plugin-cron" target="_blank">
    <img src="https://img.shields.io/badge/dmr--plugin--cron-Schedule-326CE5?style=for-the-badge" alt="dmr-plugin-cron" />
  </a>
  <a href="https://github.com/seanly/dmr-plugin-feishu" target="_blank">
    <img src="https://img.shields.io/badge/dmr--plugin--feishu-Feishu-3370FF?style=for-the-badge" alt="dmr-plugin-feishu" />
  </a>
  <a href="https://github.com/seanly/dmr-plugin-gitlab" target="_blank">
    <img src="https://img.shields.io/badge/dmr--plugin--gitlab-GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" alt="dmr-plugin-gitlab" />
  </a>
  <a href="https://github.com/seanly/dmr-plugin-web" target="_blank">
    <img src="https://img.shields.io/badge/dmr--plugin--web-Web-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="dmr-plugin-web" />
  </a>
  <a href="https://github.com/seanly/dmr-plugin-weixin" target="_blank">
    <img src="https://img.shields.io/badge/dmr--plugin--weixin-Weixin-07C160?style=for-the-badge" alt="dmr-plugin-weixin" />
  </a>
</p>

**DMR** — [Decide, Monitor, Review](https://github.com/seanly/dmr)：Go 编写的插件化 AI Agent 框架；Tape 审计、OPA 策略、交互式审批；OpenAI 兼容多模型。

**dmr-plugin-cron** — 定时外部插件：从存储加载任务，在 `dmr serve` 下按调度触发 `RunAgent`（无内联 jobs YAML）。

**dmr-plugin-feishu** — 飞书/Lark 私聊接入：消息驱动 Agent，审批与 Tape 联动，回复可走线程或会话。

**dmr-plugin-gitlab** — 接收 GitLab Merge Request Webhook，走 Agent 做代码审查，结果以评论与行内 discussion 回写。

**dmr-plugin-web** — 浏览器侧审批（SSE）与 AI 对话，反向 RPC 接入 DMR Agent；React 前端 `go:embed` 单二进制。

**dmr-plugin-weixin** — 微信 ilink/bot 网关接入：长轮询收消息、`RunAgent` 回复，可实现 `ProvideApprover` 与 OPA 审批流。

---

<h3 align="left">编程语言和工具:</h3>
<p align="left">
  <a href="https://golang.org" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" width="40" height="40"/>
  </a>
  <a href="https://kubernetes.io" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/>
  </a>
  <a href="https://www.python.org" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/>
  </a>
  <a href="https://www.jenkins.io/" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/>
  </a>
  <a href="https://www.java.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/>
  </a>
</p>

---

<p>
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=seanly&show_icons=true&locale=en" alt="seanly" />
</p>
<p>
  <img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=seanly&" alt="seanly" />
</p>
