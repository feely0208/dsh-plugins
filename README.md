# 深鲸 DSH 插件索引 · DeepWhale DSH Plugins

深鲸出品的 DSH 插件总览 —— 装在任意支持 DSH 的载体上，**不绑定桌面端**。每个插件各管一件事，按需安装。
共 **50** 个插件，全部免费开源（MIT）。

- 插件市场（可搜索 / 分类 / 一键装）：https://deepwhale.org.cn/plugins.html
- 官网：https://deepwhale.org.cn · 桌面端：https://github.com/feely0208/deepwhale-desktop
- 索引数据（供市场客户端读取）：[`plugin-market.json`](./plugin-market.json)

## 插件一览

| 插件 | 包名 | 说明 |
|---|---|---|
| [dsh-agent-scope](https://github.com/feely0208/dsh-agent-scope) | `@deepwhale-cn/dsh-agent-scope` | 查 agent 的工具/文件/网络权限有没有声明、是不是过宽 —— agent 的权限就是它的爆炸半径 |
| [dsh-ai-output-trust](https://github.com/feely0208/dsh-ai-output-trust) | `@deepwhale-cn/dsh-ai-output-trust` | 检查代码有没有直接执行 AI 输出 —— eval/exec/SQL/文件路径，这是 agent 里风险很高的一类 |
| [dsh-alert-relay](https://github.com/feely0208/dsh-alert-relay) | `@deepwhale-cn/dsh-alert-relay` | 检查告警链路：有没有告警、发到哪、有没有把敏感信息一起发出去 |
| [dsh-algorithm-filing](https://github.com/feely0208/dsh-algorithm-filing) | `@deepwhale-cn/dsh-algorithm-filing` | 查算法推荐服务有没有备案、有没有告知、有没有【关闭选项】—— 第 17 条是硬要求 |
| [dsh-badge](https://github.com/feely0208/dsh-badge) | `@deepwhale-cn/dsh-badge` | 给用深鲸桌面产出的文档 / PR 加「powered by dwh」署名徽章（skill，装上即可用；121×20、胶囊圆角） |
| [dsh-bundle-cn-skills](https://github.com/feely0208/dsh-bundle-cn-skills) | `@deepwhale-cn/dsh-bundle-cn-skills` | DSH 中文合规与工程技能集（7 个技能）的组合包。本文件同时作为仓库根清单，供插件市场识别包名并核对 npm 包。 |
| [dsh-ci-guard](https://github.com/feely0208/dsh-ci-guard) | `@deepwhale-cn/dsh-ci-guard` | 扫 GitHub Actions 工作流，找出可被利用的配置 —— 供应链攻击的主要入口 |
| [dsh-cn-ai-labeling](https://github.com/feely0208/dsh-cn-ai-labeling) | `@deepwhale-cn/dsh-cn-ai-labeling` | AI 生成合成内容标识合规自检：对照《人工智能生成合成内容标识办法》与强制性国标 GB 45438—2025，逐条核对显式/隐式标识落实情况，并给出防误伤边界。 |
| [dsh-cn-appstore-preflight](https://github.com/feely0208/dsh-cn-appstore-preflight) | `@deepwhale-cn/dsh-cn-appstore-preflight` | 国内应用市场上架预检：App 备案、隐私政策可达性、权限使用场景说明、账号注销入口、未成年人保护、第三方 SDK 清单 —— 从上架材料角度做一次体检，并生成材料清单骨架。 |
| [dsh-cn-compliance](https://github.com/feely0208/dsh-cn-compliance) | `@deepwhale-cn/dsh-cn-compliance` | 中国大陆对外内容合规红线审核：扫描网络工具用语、广告法极限词、绝对化承诺、内部文件公网暴露，并给出修复原则。 |
| [dsh-cn-data-export](https://github.com/feely0208/dsh-cn-data-export) | `@deepwhale-cn/dsh-cn-data-export` | 查代码与配置里的境外数据出口：境外端点、个人信息外发、缺安全评估说明 |
| [dsh-cn-doc-formatter](https://github.com/feely0208/dsh-cn-doc-formatter) | `@deepwhale-cn/dsh-cn-doc-formatter` | 中文公文排版：按 GB/T 9704-2012 生成 .docx / .pdf / .txt，附输出自检。不含字体文件，字体由用户自备。 |
| [dsh-cn-filing](https://github.com/feely0208/dsh-cn-filing) | `@deepwhale-cn/dsh-cn-filing` | 查应用里有没有展示 ICP/APP 备案号、隐私政策入口、运营者信息 —— 都是法定义务 |
| [dsh-cn-log-retention](https://github.com/feely0208/dsh-cn-log-retention) | `@deepwhale-cn/dsh-cn-log-retention` | 检查日志是否开启、是否记录了该记的、是否留够法定 6 个月 |
| [dsh-cn-mlps](https://github.com/feely0208/dsh-cn-mlps) | `@deepwhale-cn/dsh-cn-mlps` | 按 GB/T 22239-2019 逐项对照代码与配置里可静态发现的等保项 |
| [dsh-cn-pipl-check](https://github.com/feely0208/dsh-cn-pipl-check) | `@deepwhale-cn/dsh-cn-pipl-check` | 个人信息保护合规：核对「隐私政策里承诺的」与「代码里真做的」是否一致 —— 权限、第三方 SDK、用户权利入口、敏感信息单独同意、数据跨境与留存。 |
| [dsh-consent-guard](https://github.com/feely0208/dsh-consent-guard) | `@deepwhale-cn/dsh-consent-guard` | 查同意机制是否合规：默认勾选、捆绑同意、没有撤回入口 —— 个保法有明确要求 |
| [dsh-content-trust](https://github.com/feely0208/dsh-content-trust) | `@deepwhale-cn/dsh-content-trust` | 查 agent 有没有把外部内容（网页/文件/邮件）当指令信 —— 间接提示注入的入口 |
| [dsh-data-classify](https://github.com/feely0208/dsh-data-classify) | `@deepwhale-cn/dsh-data-classify` | 查数据有没有分级标注与清单 —— 数据安全法 21 条要求建立分类分级制度 |
| [dsh-data-rights](https://github.com/feely0208/dsh-data-rights) | `@deepwhale-cn/dsh-data-rights` | 查查阅/复制/删除权有没有真的实现 —— 个保法第 45/47 条是明文要求 |
| [dsh-data-scan](https://github.com/feely0208/dsh-data-scan) | `@deepwhale-cn/dsh-data-scan` | 扫出代码和配置里的身份证、银行卡、手机号 —— 带校验位验证，不误报 |
| [dsh-dep-audit](https://github.com/feely0208/dsh-dep-audit) | `@deepwhale-cn/dsh-dep-audit` | 检查依赖树的投毒与风险面：装包即执行的脚本、过宽版本、非 registry 来源 |
| [dsh-design-line](https://github.com/feely0208/dsh-design-line) | `@deepwhale-cn/dsh-design-line` | 深鲸工序 · 设计插件线：PS / AutoCAD / 3ds Max / Blender 四条完整工序流水线（意图→工序→落盘审阅→执行→校验→回执），也是框架 —— 写一个适配器就能接入新软件 |
| [dsh-guard-core](https://github.com/feely0208/dsh-guard-core) | `@deepwhale-cn/dsh-guard-core` | 深鲸守护 · 通用检查引擎。扫描目录、执行规则、生成报告（文本/HTML/JSON）—— 供 guard 系列插件复用。 |
| [dsh-incident-package](https://github.com/feely0208/dsh-incident-package) | `@deepwhale-cn/dsh-incident-package` | 查出了事能不能拿出证据：预案、联系人、日志保全、上报流程 —— 平时不备，事到临头就晚了 |
| [dsh-key-rotate](https://github.com/feely0208/dsh-key-rotate) | `@deepwhale-cn/dsh-key-rotate` | 查密钥与证书多久没换了、有没有轮换制度 —— 长期不换的密钥往往没人注意，却是实打实的风险 |
| [dsh-least-privilege](https://github.com/feely0208/dsh-least-privilege) | `@deepwhale-cn/dsh-least-privilege` | 查权限过宽：容器跑 root、IAM 通配、CORS 全开、令牌申请 admin —— 权限过宽是入侵的放大器 |
| [dsh-license-guard](https://github.com/feely0208/dsh-license-guard) | `@deepwhale-cn/dsh-license-guard` | 开源许可合规检查：扫描依赖树，找出 GPL/AGPL 传染、许可未知等风险 —— 发布前、开源前、被审计时跑一遍。 |
| [dsh-mcp-audit](https://github.com/feely0208/dsh-mcp-audit) | `@deepwhale-cn/dsh-mcp-audit` | 审计 MCP 配置：未锁定的远端包、明文端点、可执行本地服务 —— MCP 是 agent 的新攻击面 |
| [dsh-minor-guard](https://github.com/feely0208/dsh-minor-guard) | `@deepwhale-cn/dsh-minor-guard` | 查不满 14 周岁个人信息有没有监护人同意、专门规则、年龄门槛 —— 个保法 31 条有硬要求 |
| [dsh-phishing-guard](https://github.com/feely0208/dsh-phishing-guard) | `@deepwhale-cn/dsh-phishing-guard` | agent 读到的内容里，有没有人在给它下命令 |
| [dsh-pipia](https://github.com/feely0208/dsh-pipia) | `@deepwhale-cn/dsh-pipia` | 查是否按个保法 55 条做了影响评估、按 56 条留存三年 —— 敏感信息处理必须事前评估 |
| [dsh-release-selfcheck](https://github.com/feely0208/dsh-release-selfcheck) | `@deepwhale-cn/dsh-release-selfcheck` | 软件发布前的自检：产物清单比对（防止把无关文件一起上传）、版本一致性、平台与架构正确性、上传内容过滤、上线前逐链接 404 检查、发布纪律与现场清理。 |
| [dsh-sbom](https://github.com/feely0208/dsh-sbom) | `@deepwhale-cn/dsh-sbom` | 你的产物里到底有谁，清单说了算 |
| [dsh-secret-scan](https://github.com/feely0208/dsh-secret-scan) | `@deepwhale-cn/dsh-secret-scan` | 密钥与敏感信息扫描：提交前、发布前把代码里的 API Key、令牌、私钥、凭据文件、内部域名找出来 —— 输出默认打码，可作为 pre-commit / CI 卡口。 |
| [dsh-session-artifacts](https://github.com/feely0208/dsh-session-artifacts) | `@deepwhale-cn/dsh-session-artifacts` | 会话产物归拢与命名：每个会话一个专属文件夹，收尾按实际内容改名并刷新索引 —— 解决「产物散落满目录」和「过段时间记不清是什么」。附三个不依赖 DSH 的纯 bash 脚本。 |
| [dsh-shell-canvas](https://github.com/feely0208/dsh-shell-canvas) | `@deepwhale-cn/dsh-shell-canvas` | 把一段文字变成能发的视频。贴一段稿子、选几张素材，点一下出横竖双版成片；稿子、素材、成片都在你自己的电脑上，不上传、不联网。免费版即可用，授权后去水印。 |
| [dsh-tool-vet](https://github.com/feely0208/dsh-tool-vet) | `@deepwhale-cn/dsh-tool-vet` | 装第三方插件之前，先看它会动什么 |

## 安装与使用

1. 安装 DSH（随深鲸桌面，或 `npx @deepseek-ai/dsh`）；
2. 在 DSH 的插件/市场入口安装对应包（或 `dsh plugin add <包名>`，以插件自己 README 为准）；
3. 插件按各自说明提供命令、技能或面板，不绑定桌面端。

## 分类

- **国内合规**：cn-compliance / cn-pipl-check / cn-filing / cn-ai-labeling / cn-mlps / cn-data-export / cn-log-retention / cn-appstore-preflight …
- **AI 与 Agent 治理**：agent-scope / agent-policy / ai-output-trust / content-trust / tool-vet …
- **数据与凭据**：data-classify / data-rights / data-scan / secret-scan / key-rotate / dep-audit / sbom / pipia …
- **供应链**：ci-guard / release-selfcheck / license-guard …
- **权限与应急**：least-privilege / incident-package / consent-guard / phishing-guard / minor-guard / alert-relay …
- **能力类**：design-line（设计工序）/ shell-canvas（画布）/ doc-formatter（公文排版）/ session-artifacts / badge（署名徽章）…

## License

MIT © 温州深鲸智能科技有限公司
