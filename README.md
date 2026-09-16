<div align="center">

<img src="assets/images/logo.png" width="88" alt="小黑日报助手 Logo" />

# 小黑日报助手 · Xiaohei Daily Assistant

**你的 AI 工作记忆与复盘助手**

自动理解你每天做了什么，让复盘、汇报和下一步计划更轻松。

**简体中文** · [English](README.en.md)

[官方网站](https://www.xiaoheiribao.com/) · [下载最新版本](https://github.com/shjiyue/xiaoheiribao/releases/latest) · [小黑 Bot](https://www.xiaoheiribao.com/bot/) · [使用手册](https://www.xiaoheiribao.com/docs/) · [全部版本](https://github.com/shjiyue/xiaoheiribao/releases)

</div>

---

小黑日报助手是一款面向 **Windows 和 macOS** 的 AI 桌面工作助手。它将自动记录、AI 理解、日报周报、待办和小黑 Bot 连接起来，帮助你把零散的工作过程整理成可回顾的事实、可交付的报告和可以继续推进的行动。

**本仓库提供产品介绍、使用指引与下载入口。所有安装包下载链接均直接指向业务发布仓库 [shjiyue/xiaoheiribao](https://github.com/shjiyue/xiaoheiribao/releases) 的 Release 附件，本仓库不重复托管安装包。**

> 版本与资料核对日期：**2026-09-16（北京时间）**。当前最新正式版为 **v1.7.2**。固定版本链接适合下载指定版本，后续新版本请查看[最新 Release](https://github.com/shjiyue/xiaoheiribao/releases/latest)。官网标注的微信小程序仍为“即将上线”。

## 目录

- [下载与安装](#download)
- [最新更新：v1.7.2](#updates)
- [产品能力](#features)
- [小黑 Bot：你的 AI 工作伙伴](#bot)
- [完整工作流程与使用场景](#workflow)
- [界面预览](#screenshots)
- [隐私、数据与权限](#privacy)
- [首次使用](#getting-started)
- [常见问题](#faq)
- [历史版本与附件说明](#history)
- [关于我们与官方资源](#about)

<a id="download"></a>

## 下载与安装

**最新正式版：v1.7.2 · 发布于 2026-09-15 18:07（北京时间 / UTC+8）**

[查看该版本完整发布说明](https://github.com/shjiyue/xiaoheiribao/releases/tag/v1.7.2) · [始终查看最新版本](https://github.com/shjiyue/xiaoheiribao/releases/latest)

### 推荐安装包

按你的操作系统和 Mac 芯片选择一个安装包即可。大小使用 MiB（1 MiB = 1,048,576 字节），四舍五入到小数点后一位。

| 平台 | 下载文件 | 大小 |
| --- | --- | --- |
| Windows | [XiaoheiDailyAssistant-Setup-1.7.2.exe](https://github.com/shjiyue/xiaoheiribao/releases/download/v1.7.2/XiaoheiDailyAssistant-Setup-1.7.2.exe) | 165.1 MiB |
| macOS · Apple 芯片（M 系列） | [XiaoheiDailyAssistant-1.7.2-mac-arm64.dmg](https://github.com/shjiyue/xiaoheiribao/releases/download/v1.7.2/XiaoheiDailyAssistant-1.7.2-mac-arm64.dmg) | 297.1 MiB |
| macOS · Intel 芯片 | [XiaoheiDailyAssistant-1.7.2-mac-x64.dmg](https://github.com/shjiyue/xiaoheiribao/releases/download/v1.7.2/XiaoheiDailyAssistant-1.7.2-mac-x64.dmg) | 305.0 MiB |

- **Windows：** 下载 `.exe` 后运行安装程序，按向导完成安装。
- **Mac Apple 芯片：** 选择 `mac-arm64.dmg`。适用于“关于本机”中显示 Apple M 系列芯片的 Mac。
- **Mac Intel 芯片：** 选择 `mac-x64.dmg`。适用于“关于本机”中显示 Intel 处理器的 Mac。
- **查看 Mac 芯片：** 点击屏幕左上角  →“关于本机”→ 查看“芯片”或“处理器”。打开对应 DMG 后按安装窗口提示完成安装。

### ZIP 格式安装包

如果希望下载压缩包，可使用以下附件。**下载后先解压，再运行其中的 `.exe` 或打开 `.dmg`。**

| 平台 | 下载文件 | 大小 |
| --- | --- | --- |
| Windows | [XiaoheiDailyAssistant-Setup-1.7.2.exe.zip](https://github.com/shjiyue/xiaoheiribao/releases/download/v1.7.2/XiaoheiDailyAssistant-Setup-1.7.2.exe.zip) | 164.8 MiB |
| macOS · Apple 芯片（M 系列） | [XiaoheiDailyAssistant-1.7.2-mac-arm64.dmg.zip](https://github.com/shjiyue/xiaoheiribao/releases/download/v1.7.2/XiaoheiDailyAssistant-1.7.2-mac-arm64.dmg.zip) | 296.3 MiB |
| macOS · Intel 芯片 | [XiaoheiDailyAssistant-1.7.2-mac-x64.dmg.zip](https://github.com/shjiyue/xiaoheiribao/releases/download/v1.7.2/XiaoheiDailyAssistant-1.7.2-mac-x64.dmg.zip) | 304.2 MiB |

### 下载完整性校验

- 原始安装包及相关附件：[SHA256SUMS.txt](https://github.com/shjiyue/xiaoheiribao/releases/download/v1.7.2/SHA256SUMS.txt)。
- 上述三份安装包 ZIP：[INSTALLER-ZIP-SHA256SUMS.txt](https://github.com/shjiyue/xiaoheiribao/releases/download/v1.7.2/INSTALLER-ZIP-SHA256SUMS.txt)。

<details>
<summary>查看推荐安装包的 SHA-256 与校验命令</summary>

以下校验值来自该 Release 的 GitHub 附件元数据。

| 文件 | SHA-256 |
| --- | --- |
| `XiaoheiDailyAssistant-Setup-1.7.2.exe` | `6a8dd72d264f703fbcc31686073e924b09c60a461795aba59cbb3be1aca30ec6` |
| `XiaoheiDailyAssistant-1.7.2-mac-arm64.dmg` | `fc4c57b0b35bd06621ee4527048e3a393887f4b4b51d354c3e9719afd4e5c418` |
| `XiaoheiDailyAssistant-1.7.2-mac-x64.dmg` | `8b442e2af6148cc6ace35db5f70e5e035cee5e53cac4176e814b783827426835` |

Windows PowerShell（在下载目录执行）：

```powershell
Get-FileHash .\XiaoheiDailyAssistant-Setup-1.7.2.exe -Algorithm SHA256
```

macOS（以 Apple 芯片安装包为例，在下载目录执行）：

```bash
shasum -a 256 XiaoheiDailyAssistant-1.7.2-mac-arm64.dmg
```

将输出值与上表或对应校验文件对照；ZIP 文件应使用 ZIP 校验清单。

</details>

<a id="updates"></a>

## 最新更新：v1.7.2

以下内容同步自业务仓库的 [v1.7.2 发布说明](https://github.com/shjiyue/xiaoheiribao/releases/tag/v1.7.2)。

- **更新由你确认：** 发现新版本后先提醒，点击“立即更新”才下载安装；更新失败会显示原因并停止，等待你手动重新下载，减少反复下载带来的流量消耗。
- **新增 Bot 公共空间：** 可在 Bot 设置中选择公共文件夹，让同一账号下的多个 Bot 共享工作资料；支持编辑公共说明、查看历史版本，并保留各自的私人聊天和记忆。
- **长对话衔接更顺畅：** 优化长时间聊天和旧会话继续使用的体验，保留历史消息，并支持按需查找当前会话更早的内容。
- **Bot 角色与回复更清楚：** 优化角色头像的回复动效与状态展示，修复默认角色重复添加、已有角色被意外覆盖的问题。
- **新增网站记录排除：** 可按网站或具体页面设置不记录，也能为同一网站保留允许记录的页面；切换到其他页面或应用后恢复正常记录。
- **录制设置更易上手：** 完善首次录制欢迎和记录偏好引导，优化启用录制、账号切换及暂停原因提示。
- **模型与截图识别更稳定：** 改善旧版模型设置的保留与切换体验，优化 DeepSeek 截图识别兼容性和识别异常处理。
- **报告查看更顺畅：** 报告生成完成后自动进入历史列表，对话式生成的报告也更方便接着查看，生成进度和完成提示更清楚。
- **待办好友更好找：** 支持给好友设置仅自己可见的备注，完善最近联系人和待办搜索，选择协作对象更方便。
- **新增小黑成长陪伴：** 可从记录页进入成长计划和入门教程，在聊天、报告、时间线、待办和统计页面看到对应的小黑形象，成长奖励明细也更清楚。
- 修复和优化了一些已知问题。

<a id="features"></a>

## 产品能力

### 自动记录与智能理解

小黑在你工作时记录屏幕和应用活动，并通过所选 AI 能力识别工作内容、生成摘要和分类。截图、文本、剪贴板、图片与音视频等内容都可以成为整理工作事实的素材；也可以手动补录屏幕之外的会议、沟通与成果。

- 设置记录间隔、参与记录的显示器和闲置暂停规则。
- 跳过未变化的画面，减少重复记录。
- 排除敏感应用；v1.7.2 还支持按网站或页面排除，并设置允许记录的例外页面。
- 在“我的资料”中补充角色、组织、项目、职责和常见协作者，帮助 AI 更准确理解工作背景。

### 日报、周报、月报与可视化报告

根据真实时间线，按天、周、月或自定义时间范围生成报告。你可以选择模板市场中的模板、使用自定义模板、补充生成要求，或通过支持的网页 AI 对话继续整理内容。

报告支持保存到历史列表、编辑、复制与导出，也支持 HTML 可视化报告。生成前可以修正原始记录，生成后核对事实、项目名、数字与完成状态，再用于汇报。

### 工作时间线与效率洞察

时间线把自动识别、文字补录、图片、音频转写、导入和 Agent 写入的工作记录放在一起，支持回看、筛选、编辑、删除和导出。

结合应用使用统计、活跃与空闲时间、专注时段、应用切换、小时与日期趋势、热力图、分类分布和词云，你可以看清时间投入，并为复盘找到具体依据。

### 待办与协作

从工作记录中提取下一步事项，并结合后续记录辅助评估完成情况。待办支持列表、看板和甘特视图，可维护状态、优先级、日期、项目、描述、子任务、进度、附件、负责人和关注人，也支持重复规则与桌面悬浮待办。

v1.7.2 新增好友私人备注，并优化最近联系人和待办搜索，让协作对象更容易找到。

### 开放 API 与本地 Agent

通过官网介绍的 **Lobster 本地服务 /“接入 Agent”**，在授权范围内让外部 Agent 查询今日工作、时间线、历史报告、应用统计、热力图和个人资料，并按支持的接口使用待办或补充工作记录等能力。

本地服务的开放范围由你决定。具体配置、鉴权方式和可用能力请参阅[核心功能手册](https://www.xiaoheiribao.com/docs/manual/chapter-3)与 [Agent 与工具接口说明](https://www.xiaoheiribao.com/docs/manual/chapter-11)。

### 工具箱

官网使用手册还介绍了集中在桌面端的内容与文件工具：AI 图片与视频生成、声音克隆与语音合成、Markdown 阅读与编辑、白板、本地图片与 PDF 压缩、里程碑，以及多平台视频发布准备。

其中本地图片压缩、PDF 压缩和里程碑等工具不消耗积分；AI 生成能力可能按页面展示的价格或积分计费。多平台发布准备可协助上传和填写信息，最终发布由用户确认。

### 微信小程序（即将上线）

官网规划的小程序将支持查看时间线、报告、应用统计和热力图，搜索记录、处理待办与分享成果。**截至本 README 核对日期，官网仍标注“即将上线”，这里不提供已上线移动客户端的下载承诺。**

<a id="bot"></a>

## 小黑 Bot：你的 AI 工作伙伴

小黑 Bot 将工作记录、资料、对话、工具和任务连接起来。可以用一句话描述职责，或从常用角色中添加助手，让写作、研究、编程和日常工作各有分工。

| 能力 | 你可以怎样使用 |
| --- | --- |
| 查询真实工作 | 在对话里查询时间线、历史报告与应用统计，回顾某个项目或一段时间的进展。 |
| 生成报告 | 根据已有工作记录整理日报、周报、月报，并在明确要求下保存至历史报告。 |
| 处理待办与记录 | 用自然语言创建、修改、完成待办，或把明确交代的工作补充到时间线。 |
| 多 Bot 协作 | 将不同专长的 Bot 加入群聊，用 `@` 指定回答；也可授权 Bot 创建助手、组建团队、分派任务或咨询其他 Bot。 |
| 图片与文件 | 发送图片和文件帮助 Bot 理解资料；开启完全访问后，在权限范围内读写本地文件、运行命令，协助处理文档与代码。 |
| 独立记忆 | 每个 Bot 保存自己的重要事实与长期偏好，供后续单聊和群聊使用；记忆条目可以查看、修改和删除。 |
| 定时任务 | 在单聊中安排单次、每天、每周、每月或间隔任务，查看执行记录。电脑需在线，桌面客户端需保持运行。 |
| 模型与权限 | 按任务配置默认云模型或自定义模型、工作目录与访问权限，选择仅聊天或完全访问。 |
| 公共空间（v1.7.2） | 同一账号下多个 Bot 共享指定文件夹和公共说明，支持说明历史版本，同时保留各自的私人聊天与记忆。 |

例如，你可以这样开始：

> 根据本周工作记录，按项目整理周报，分为成果、问题和下周计划。先给我草稿，再列出建议跟进的待办。

> 请记住，我的周报按项目分组，先写成果，再写下一步。

> 每周五 18 点帮我整理本周工作，把结果放回当前会话。

了解更多：[小黑 Bot 产品页](https://www.xiaoheiribao.com/bot/) · [小黑 Bot 使用指南](https://www.xiaoheiribao.com/docs/manual/chapter-4)。

<a id="workflow"></a>

## 完整工作流程与使用场景

**自动记录 → 理解与整理 → 复盘与汇报 → 推进下一步**

1. **自动记录：** 持续积累屏幕、应用活动，以及主动添加的文字、图片、音视频等素材。
2. **理解与整理：** AI 结合工作背景、个人资料与分类设置，形成可以回看的工作时间线。
3. **复盘与汇报：** 按日期范围和模板汇总成果，生成日报、周报、月报或可视化报告。
4. **推进下一步：** 提取待办、分配协作事项，并结合后续工作记录继续跟进。

| 使用场景 | 小黑如何帮助你 |
| --- | --- |
| 下班前写日报 | 从已经整理好的时间线生成日报，减少回忆和拼凑材料的时间。 |
| 周会前做复盘 | 对照时间线、应用统计、热力图和分类分布，梳理成果、投入与问题。 |
| 工作中管理待办 | 把记录中的行动项补上负责人、截止时间、子任务与附件，持续跟踪。 |
| 写作、调研与编程 | 让不同角色的 Bot 结合资料处理任务，并在授权范围内使用文件与工具。 |
| 重复性工作 | 把例行整理安排成定时任务，在桌面端持续运行时自动执行。 |
| 连接现有 Agent | 让可信的本地 Agent 查询工作记忆，按明确要求补充记录或调用已开放能力。 |

<a id="screenshots"></a>

## 界面预览

以下图片来自官网展示素材，已保存在本仓库中；具体界面以安装版本为准。

![小黑日报助手：今日工作概览](assets/images/overview.png)

<details>
<summary>展开查看时间线、报告、待办、统计与 Bot 界面</summary>

### 工作时间线

![工作时间线](assets/images/work-timeline.png)

### 生成报告

![日报、周报与月报生成](assets/images/report-generation.png)

### 待办管理

![待办管理](assets/images/tasks.png)

### 应用记录

![应用使用统计](assets/images/app-activity.png)

### 热力图

![工作热力图](assets/images/heatmap.png)

### 小黑 Bot

![创建你的 AI 工作伙伴](assets/images/bot-creation.png)

![小黑 Bot 常用角色推荐](assets/images/bot-roles.png)

</details>

<a id="privacy"></a>

## 隐私、数据与权限

小黑采用**本地优先**的数据策略。工作时间线和报告默认保存在本机数据库，支持导出、备份、恢复和清理。Bot 会话与权限配置也主要保存在本机。

- **控制采集范围：** 可暂停记录、排除应用或网站、选择显示器，以及关闭详细上下文记录。
- **控制原始截图：** 官网说明截图默认在分析后删除；如果主动开启原始截图保留，应自行管理保存位置与清理周期。
- **选择 AI 方式：** 可按支持的功能选择默认云模型、自定义接口、本地模型或网页账号。**使用云模型时，必要的截图或文本上下文会发送给所选服务进行处理；本地优先不等于所有 AI 处理都离线。**
- **按需同步：** 报告同步等能力按你的选择启用；官网的小程序同步仍标注即将上线。
- **控制 Bot 权限：** 根据任务选择仅聊天或完全访问，管理其工作目录、文件和工具使用范围。
- **控制 Agent 接入：** 决定本地服务是否开放、是否允许局域网访问，并管理鉴权与请求日志。

详细规则见[政策与使用规范](https://www.xiaoheiribao.com/docs/manual/chapter-8)及[用户协议](https://www.xiaoheiribao.com/legal/user-agreement.html)。

<a id="getting-started"></a>

## 首次使用

1. **下载并安装：** 在上方选择对应系统与芯片的安装包。
2. **完成初始设置：** 按客户端引导登录、选择模型并完成必要的系统权限授权。自动屏幕记录需要相应的屏幕录制 / 识别权限；其他权限按启用功能配置。
3. **设定记录范围：** 配置间隔、显示器、排除软件与网站、闲置暂停规则，再开启记录。
4. **确认记录正常：** 正常工作一段时间后，在“今日工作”和“工作时间线”检查记录、摘要和分类。
5. **生成第一份报告：** 选择日期范围、模板、语言和模型，核对结果后保存、复制或导出。
6. **创建小黑 Bot：** 选择角色，说明任务和输出要求；需要共享资料时，可在 Bot 设置中配置公共空间。

完整教程：[快速入门](https://www.xiaoheiribao.com/docs/manual/chapter-2) · [核心功能操作指南](https://www.xiaoheiribao.com/docs/manual/chapter-3) · [实践教程](https://www.xiaoheiribao.com/docs/manual/chapter-5)。

<a id="faq"></a>

## 常见问题

### 下载后应该打开哪个文件？

Windows 打开 `.exe`；macOS 打开与你的芯片匹配的 `.dmg`。如果下载的是 `.exe.zip` 或 `.dmg.zip`，先解压。Release 中的 `Source code` 是 GitHub 自动生成的仓库源码归档，不是桌面安装程序；`.yml`、`.blockmap` 也不需要手动安装。

### 如何更新到最新版本？

v1.7.2 的更新流程会先提示新版本，点击“立即更新”后才下载安装。失败时会显示原因并停止，等待你手动重新下载。也可以从[业务仓库最新 Release](https://github.com/shjiyue/xiaoheiribao/releases/latest)下载与你的平台匹配的安装包。

### GitHub 下载较慢怎么办？

可以到[官网下载区域](https://www.xiaoheiribao.com/#download)查看当时可用的下载渠道。本 README 中列出的具体安装包链接始终直接指向 `shjiyue/xiaoheiribao` 的 GitHub Release 附件。

### 是完全免费的吗？

应用可以免费下载并体验。订阅权益、模型额度与积分规则以客户端实时展示为准；AI 模型、图片、视频和语音等能力可能消耗积分或产生所选服务的费用。详情见[购买指南](https://www.xiaoheiribao.com/docs/manual/chapter-6)。

### 关闭电脑后，Bot 定时任务还能执行吗？

官网说明定时执行需要电脑在线且桌面客户端保持运行。请根据任务需要安排设备在线时间。

### 没有新工作记录怎么办？

依次检查记录开关、系统权限、闲置状态、排除规则、显示器选择，以及所选模型的网络与额度状态。详见[常见问题与故障排查](https://www.xiaoheiribao.com/docs/manual/chapter-7)。

<a id="history"></a>

## 历史版本与附件说明

### v1.7.1

业务仓库还保留 **v1.7.1（2026-09-15 发布）**。新安装建议优先使用 v1.7.2；如需指定旧版，可使用以下原始附件。

| 平台 | 下载文件 | 大小 |
| --- | --- | --- |
| Windows | [XiaoheiDailyAssistant-Setup-1.7.1.exe.zip](https://github.com/shjiyue/xiaoheiribao/releases/download/v1.7.1/XiaoheiDailyAssistant-Setup-1.7.1.exe.zip) | 163.4 MiB |
| macOS · Apple 芯片（M 系列） | [XiaoheiDailyAssistant-1.7.1-mac-arm64.dmg.zip](https://github.com/shjiyue/xiaoheiribao/releases/download/v1.7.1/XiaoheiDailyAssistant-1.7.1-mac-arm64.dmg.zip) | 267.7 MiB |
| macOS · Intel 芯片 | [XiaoheiDailyAssistant-1.7.1-mac-x64.dmg.zip](https://github.com/shjiyue/xiaoheiribao/releases/download/v1.7.1/XiaoheiDailyAssistant-1.7.1-mac-x64.dmg.zip) | 275.7 MiB |

[查看 v1.7.1 发布页](https://github.com/shjiyue/xiaoheiribao/releases/tag/v1.7.1) · [v1.7.1 ZIP 校验清单](https://github.com/shjiyue/xiaoheiribao/releases/download/v1.7.1/SHA256SUMS.txt) · [查看所有历史 Release](https://github.com/shjiyue/xiaoheiribao/releases)

### v1.7.2 其他附件

除推荐的 DMG 与 EXE 外，Release 还提供以下 macOS ZIP 附件，供需要对应分发格式的用户使用。普通安装优先选择上面的 DMG。

| 平台 | 下载文件 | 大小 |
| --- | --- | --- |
| macOS · Apple 芯片 | [XiaoheiDailyAssistant-1.7.2-mac-arm64.zip](https://github.com/shjiyue/xiaoheiribao/releases/download/v1.7.2/XiaoheiDailyAssistant-1.7.2-mac-arm64.zip) | 284.8 MiB |
| macOS · Intel 芯片 | [XiaoheiDailyAssistant-1.7.2-mac-x64.zip](https://github.com/shjiyue/xiaoheiribao/releases/download/v1.7.2/XiaoheiDailyAssistant-1.7.2-mac-x64.zip) | 292.7 MiB |

自动更新相关文件为 [latest.yml](https://github.com/shjiyue/xiaoheiribao/releases/download/v1.7.2/latest.yml)、[latest-mac.yml](https://github.com/shjiyue/xiaoheiribao/releases/download/v1.7.2/latest-mac.yml)、[latest-mac-x64.yml](https://github.com/shjiyue/xiaoheiribao/releases/download/v1.7.2/latest-mac-x64.yml)，以及与安装包对应的 `.blockmap`。这些文件供客户端更新流程使用，普通用户无需逐个下载。

<a id="about"></a>

## 关于我们与官方资源

**让每一天的工作都能被记录、理解和继续推进。**

根据官网介绍，上海听悟智能科技有限公司是上海暨岳信息技术有限公司的下属全资子公司，成立于 2023 年，专注于 AI 应用层产品。自 2026 年起，公司聚焦小黑日报助手的研发与服务，帮助用户沉淀工作成果、完成复盘汇报，并继续推进重要事项。

| 团队成员 | 主要职责 |
| --- | --- |
| Leo | 创始人；产品、架构与增长 |
| Miranda | 产品经理；AI 产品与用户体验 |
| Ariza | 核心开发；全栈开发与架构实现 |
| Wayne | 核心开发；桌面端开发与建设 |

官网展示了[电子版权认证证书](assets/images/software-copyright-certificate.jpg)与[软件著作权认证证书](assets/images/software-copyright-blockchain.jpg)。

| 官方入口 | 链接 |
| --- | --- |
| 官网 | [www.xiaoheiribao.com](https://www.xiaoheiribao.com/) |
| 小黑 Bot | [产品介绍](https://www.xiaoheiribao.com/bot/) |
| 使用手册 | [完整操作指南](https://www.xiaoheiribao.com/docs/) |
| 产品白皮书 | [飞书白皮书](https://mcnhmlyyd69x.feishu.cn/wiki/N55CwztFlif60pknkkecEdM6n6e?from=from_copylink) |
| 博客 | [产品动态与文章](https://www.xiaoheiribao.com/blog.php) |
| 小黑大使 | [官网活动入口](https://www.xiaoheiribao.com/ambassador/) |
| 安装包与更新 | [业务发布仓库 Releases](https://github.com/shjiyue/xiaoheiribao/releases) |
| 联系与反馈 | 通过[官网](https://www.xiaoheiribao.com/)“联系我们”或客户端客服入口联系团队。 |

本 README 的产品介绍依据官网首页、小黑 Bot 产品页及官方使用手册整理；版本信息与安装包链接依据业务发布仓库的公开 Releases 核对。产品能力、服务权益与版本发布会继续变化，请结合官网、客户端和对应 Release 的最新说明使用。
