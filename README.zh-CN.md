# 精选 Agent Skills

[English](README.md) | **简体中文**

[![Skills](https://img.shields.io/badge/skills-133-4f46e5)](https://aibars.net/zh/skills)
[![License](https://img.shields.io/badge/list-MIT-green)](#协议)

为 Claude Code、Codex、Cursor、GitHub Copilot、Gemini CLI 等 AI 编程代理精选的 **133 个 Skills**。每个 Skill 上架前都经过检查，大多数真实试用过并附有运行演示，每个都标明来源、协议和风险。我们没有亲自试用过的，会明确标出。

**带演示和搜索的完整目录：[aibars.net/zh/skills](https://aibars.net/zh/skills)**

> Skill 是一个带 `SKILL.md` 的文件夹，教 AI 代理把某一类任务做好。本页是索引，每个链接会打开该 Skill 的页面，里面有演示、风险说明和安装命令。

## 我们怎么筛选

1. **核对协议。** 没有协议、专有协议或协议不明确的 Skill 不收录。
2. **读完源码。** 我们读完 `SKILL.md` 和随附的所有文件（包括脚本），查找有没有删除、覆盖、读取密钥，或下载并运行代码的行为。
3. **真实试用。** 在干净环境里用一个真实的请求运行每个 Skill。页面上的演示是原样记录的输出，没有修改。结果有错或只验证了一部分的，页面里会写明。
4. **标注风险。** 每个 Skill 都有风险说明，很多还标了等级（低、中、高）。会运行脚本、需要联网或凭据、或操控真实浏览器的，会在前面直接说明。
5. **如实说明没做到的。** 有 5 个 Skill 我们没能试用（比如需要真实的代码仓库、问题跟踪器或我们无法搭建的工具链），已标为 **⚠️ 未试用**。

审核和试用是由 AI 模型完成的，所以使用 Skill 之前请自己看一遍源码和风险说明。这里的内容不构成任何保证。

## 编辑精选

| Skill | 做什么 | 作者 | 协议 | 风险 | 试用 |
|---|---|---|---|---|---|
| [设计品味前端 Design Taste Frontend](https://aibars.net/zh/skills/896418145756254208) | 让智能体做出不像模板的落地页、作品集和改版：先读需求并给出“设计判断”，设定三个刻度，合适时选用真实设计系统，最后过一遍严格的发布前检查。 | Leonxlnx | MIT | 中 | ✅ |
| [前端设计 Frontend Design](https://aibars.net/zh/skills/894605620081332224) | 帮助 AI 做出有个性、不落俗套的界面设计：先出设计方案，对照需求自查后再动手实现。 | Anthropic | Apache-2.0 | — | ✅ |
| [主题工厂 Theme Factory](https://aibars.net/zh/skills/894605634199359488) | 为幻灯片、文档、报告或落地页套用 10 套现成的配色与字体主题，也可以现场生成新主题。 | Anthropic | Apache-2.0 | — | ✅ |
| [电商单位经济与定价 Unit Economics](https://aibars.net/zh/skills/895611922827972608) · 原创 | 算清一单到底赚多少：扣掉成本、运费、手续费、退货和广告之后，给出保本及目标 ROAS 或 CPA、达到目标利润率所需的价格，以及折扣最多能打到多深。 | AIBars | MIT | 低 | ✅ |
| [图像提示词写作 Image Prompt Writing](https://aibars.net/zh/skills/895622597725917184) · 原创 | 把模糊的想法写成 AI 绘图工具能听懂的清晰提示词：主体、场景、构图、光线、风格和色彩，按合理的顺序排好，并给出简短版、详细版和变体。 | AIBars | MIT | 低 | ✅ |
| [短视频脚本 Short Video Script](https://aibars.net/zh/skills/895769885358166016) · 原创 | 写出今天就能拍的 TikTok、Reels 或 Shorts 脚本：三个开头钩子、带画面、屏幕文字和口播台词的分镜表、行动号召、文案和拍摄清单。 | AIBars | MIT | 低 | ✅ |
| [社媒回复手册 Social Reply Playbook](https://aibars.net/zh/skills/895769901091000320) · 原创 | 冷静、诚实地回复评论、私信和公开评价：先给消息分类，选对回复套路，写出简短的公开回复和私下跟进，并知道哪些情况不能先回复、要先做决定。 | AIBars | MIT | 低 | ✅ |
| [内部沟通 Internal Comms](https://aibars.net/zh/skills/894605627295535104) | 按固定的公司格式写内部沟通文档：3P 周更、公司简报、FAQ 回复和一般通知。 | Anthropic | Apache-2.0 | — | ✅ |
| [安全威胁建模 Security Threat Model](https://aibars.net/zh/skills/895740488542588928) | 为代码仓库做威胁建模：信任边界、资产、攻击者能力、具体的攻击路径，以及对应到真实文件的缓解措施，最后写成一份简明的 Markdown 报告。 | OpenAI | Apache-2.0 | 中 | ✅ |
| [系统化调试 Systematic Debugging](https://aibars.net/zh/skills/895089901731844096) | 先找根因，再动手修：证据、模式、一次一个假设、带测试的修复，共四个阶段，并在失败三次后强制停下。 | Jesse Vincent | MIT | 中 | ✅ |
| [转化文案 Conversion Copywriting](https://aibars.net/zh/skills/895074689435832320) | 为首页、落地页、定价页和功能页写作和改写营销文案：清晰的标题、有力的 CTA、页面结构，以及一份必须避开的“AI 腔”严格清单。 | Corey Haines | MIT | 低 | ✅ |
| [转化率优化 CRO](https://aibars.net/zh/skills/895074761183596544) | 分析营销页面或表单，得到排好序的改进建议：价值主张、标题、CTA、信任信号、异议和阻力，附测试思路和文案备选。 | Corey Haines | MIT | 低 | ✅ |
| [Google SEO 审计](https://aibars.net/zh/skills/896036597110411264) · 原创 | 根据你提供的 HTML、robots.txt 和 Search Console 数据，从 Google 搜索的角度审计页面或站点：抓取与收录障碍、标题、内容质量、结构化数据和页面体验，给出按优先级排序的修复清单。 | AIBars | MIT | — | ✅ |
| [论文阅读 Paper Reading](https://aibars.net/zh/skills/896427684459188224) · 原创 | 分三遍批判性地读一篇论文：它主张什么、怎么检验、证据是否站得住，以及你能从中得到什么。关键主张附原文引用，文中没说的就写“未说明”。 | AIBars | MIT | 低 | ✅ |
| [学习计划 Study Plan](https://aibars.net/zh/skills/896427730831413248) · 原创 | 根据你的目标、现有水平和每周可用时间，做出一份切实可行的学习计划：可行性判断、带检查点的阶段、含间隔复习的每周安排，以及落后时的补救规则。 | AIBars | MIT | 低 | ✅ |

## 全部 Skills（按分类）

图例：**原创** = AIBars 原创 Skill（MIT）· **风险**：低 / 中 / 高，"—" 表示还没评级（请看页面里的风险说明）· **试用**：✅ 真实运行并有演示记录，⚠️ 未试用。

### 网页与界面设计（21）

| Skill | 做什么 | 作者 | 协议 | 风险 | 试用 |
|---|---|---|---|---|---|
| [设计品味前端 Design Taste Frontend](https://aibars.net/zh/skills/896418145756254208) | 让智能体做出不像模板的落地页、作品集和改版：先读需求并给出“设计判断”，设定三个刻度，合适时选用真实设计系统，最后过一遍严格的发布前检查。 | Leonxlnx | MIT | 中 | ✅ |
| [前端设计 Frontend Design](https://aibars.net/zh/skills/894605620081332224) | 帮助 AI 做出有个性、不落俗套的界面设计：先出设计方案，对照需求自查后再动手实现。 | Anthropic | Apache-2.0 | — | ✅ |
| [主题工厂 Theme Factory](https://aibars.net/zh/skills/894605634199359488) | 为幻灯片、文档、报告或落地页套用 10 套现成的配色与字体主题，也可以现场生成新主题。 | Anthropic | Apache-2.0 | — | ✅ |
| [算法艺术 Algorithmic Art](https://aibars.net/zh/skills/894631082325184512) | 把一个主题写成一段生成艺术宣言，再做成带种子切换、参数滑块和 PNG 导出的 p5.js 交互作品。 | Anthropic | Apache-2.0 | — | ✅ |
| [动画构建 Animate](https://aibars.net/zh/skills/896430456986406912) | 按正确的顺序从零构建一个动画：该不该动、目的是什么、用什么工具、动哪些属性、用什么曲线和时长、怎么被打断、怎么退出。它会写出代码，也会拒绝给不该动的东西加动画。 | Emil Kowalski | MIT | 低 | ✅ |
| [动画术语表 Animation Vocabulary](https://aibars.net/zh/skills/896430537978417152) | 用你自己的话描述一个动效，得到它的准确名称：“弹窗打开时那种弹一下的效果”是 Pop in，“iOS 那种拉到头会回弹的滚动”是 Rubber-banding。适合用来给设计师写需求或给 AI 写提示词。 | Emil Kowalski | MIT | 低 | ✅ |
| [破坏界面 Break UI](https://aibars.net/zh/skills/896430496840683520) | 用现实中最坏的数据给组件做压力测试：很长的姓名、没法折行的邮箱、一个字的名字、缺失字段、1284 个成员、空列表。它会报告什么坏了、为什么，以及每个问题的修法，并且在动手改之前先停下。 | Emil Kowalski | MIT | 低 | ✅ |
| [设计系统 Design System（令牌与幻灯片）](https://aibars.net/zh/skills/894877786756616192) | 搭建三层设计令牌（基础值、语义、组件）、编写组件规范，并生成符合令牌规范、带 Chart.js 图表的 HTML 幻灯片。 | claudekit | MIT | 中 | ✅ |
| [设计工程 Design Engineering（Emil Kowalski）](https://aibars.net/zh/skills/896430407678169088) | 用 Emil Kowalski 的设计工程手艺来评审和构建界面：什么时候不该做动画、用哪种缓动和时长、弹簧、clip-path、手势、性能与无障碍，并要求用“修改前 / 修改后 / 原因”的表格给出评审。 | Emil Kowalski | MIT | 低 | ✅ |
| [高端视觉设计 High-End Visual Design](https://aibars.net/zh/skills/896418275830009856) | 教智能体像高端设计机构那样做设计：用确切的字体、间距、阴影、嵌套卡片结构和动效曲线让网站显得“贵”，并附一份廉价 AI 默认写法的禁用清单。 | Leonxlnx | MIT | 低 | ✅ |
| [深浅色双主题 Light and Dark Theme](https://aibars.net/zh/skills/895472103242076160) · 原创 | 做出在两种主题下都正确的深色与浅色模式：语义颜色令牌、跟随系统设置加手动切换、加载时不闪错误主题，并在两种主题里分别核对对比度。 | AIBars | MIT | 低 | ✅ |
| [Penpot UI/UX 设计（通过 Penpot MCP）](https://aibars.net/zh/skills/894931597240045568) | 通过 Penpot 的 MCP 服务在 Penpot 里设计网页、移动端和桌面端界面，带有设计系统检查、组件与无障碍规则和各平台尺寸。 | awesome-copilot community | MIT | 中 | ✅ |
| [改版现有项目 Redesign Existing Projects](https://aibars.net/zh/skills/896418190912131072) | 在不重写的前提下，把现有网站或应用升级到高级质感：先扫描技术栈，再按字体、色彩、布局、状态和内容审计“AI 通用套路”，然后按优先级做有针对性的修复。 | Leonxlnx | MIT | 中 | ✅ |
| [响应式布局排查 Responsive Layout Debugging](https://aibars.net/zh/skills/895472114449256448) · 原创 | 找出在特定屏幕宽度下布局出问题的真正原因：横向滚动、溢出、不肯缩小的 flex 子项、不吸附的 sticky、手机上的 100vh，以及固定栏被浏览器界面遮住。 | AIBars | MIT | 低 | ✅ |
| [界面国际化适配 UI Internationalization](https://aibars.net/zh/skills/895472119838937088) · 原创 | 让界面不重新设计也能承载任何语言：消息文案库、按地区格式化、能适应不同文字长度的布局、中日韩和从右到左的支持，以及带规范网址的语言切换。 | AIBars | MIT | 低 | ✅ |
| [组件状态清单 UI States Checklist](https://aibars.net/zh/skills/895472127283826688) · 原创 | 列出一个界面或组件需要的每一种状态：加载、空、错误、部分成功、禁用、离线、无权限和极端内容，并为每种状态定好用户看到什么、能做什么。 | AIBars | MIT | 低 | ✅ |
| [界面样式 UI Styling（shadcn/ui + Tailwind）](https://aibars.net/zh/skills/894877751998418944) | 用 shadcn/ui 和 Tailwind CSS 搭建无障碍、响应式界面的指引，涵盖深色模式、主题定制，以及基于画布的视觉设计思路。 | claudekit | MIT | 中 | ✅ |
| [UI/UX 设计智库 UI/UX Pro Max](https://aibars.net/zh/skills/894877714409066496) | 可检索的界面设计知识库：风格、配色、字体搭配、UX 规范、图表和各技术栈的实现建议，动手前先确定视觉方向。 | NextLevelBuilder | MIT | 中 | ✅ |
| [无障碍检查 Web Accessibility Audit（WCAG 2.2 AA）](https://aibars.net/zh/skills/895472135974424576) · 原创 | 对照 WCAG 2.2 AA 级审查页面或组件：键盘、焦点、对比度、名称与标签、结构、表单、对话框、动态更新、缩放和点击目标大小，每条发现都对应到具体的成功标准。 | AIBars | MIT | 低 | ✅ |
| [网页产物构建器 Web Artifacts Builder](https://aibars.net/zh/skills/894637271385640960) | 使用 TypeScript、Tailwind CSS 与 shadcn/ui 构建复杂的独立 React 网页产物。 | Anthropic, PBC | Apache-2.0 | — | ✅ |
| [网页设计审查 Web Design Reviewer](https://aibars.net/zh/skills/894931631889190912) | 检查一个正在运行的网站的布局、响应式、无障碍和一致性问题，再用最小改动在源码里修复并复查。 | awesome-copilot community | MIT | 中 | ✅ |

### 电商运营（7）

| Skill | 做什么 | 作者 | 协议 | 风险 | 试用 |
|---|---|---|---|---|---|
| [电商单位经济与定价 Unit Economics](https://aibars.net/zh/skills/895611922827972608) · 原创 | 算清一单到底赚多少：扣掉成本、运费、手续费、退货和广告之后，给出保本及目标 ROAS 或 CPA、达到目标利润率所需的价格，以及折扣最多能打到多深。 | AIBars | MIT | 低 | ✅ |
| [运营周报与指标 E-commerce Weekly Review](https://aibars.net/zh/skills/895612367965261824) · 原创 | 把店铺数据变成一份简短的周报或月报：该看哪些指标、口径怎么定、销售额或转化率为什么变了、哪些是真信号哪些是噪音，以及下一步做什么。 | AIBars | MIT | 低 | ✅ |
| [库存与补货计划 Inventory Replenishment Planning](https://aibars.net/zh/skills/895612131565899776) · 原创 | 决定补什么货、补多少、什么时候补：补货点、安全库存、供货周期、可售天数、ABC 分类、滞销库存和现金限制，按单品用真实销售记录来规划。 | AIBars | MIT | 低 | ✅ |
| [商品详情页优化 Product Listing Optimization](https://aibars.net/zh/skills/895612026951569408) · 原创 | 让商品页既容易被找到、又让人放心：标题、卖点、描述、图片、规格和关键词，只用真实、能证明的说法，面向买家而不是算法来写。 | AIBars | MIT | 低 | ✅ |
| [促销活动规划 Promotion Campaign Planning](https://aibars.net/zh/skills/895612211542888448) · 原创 | 规划网店促销，让它赚的是利润而不只是订单：目标与利润底线、优惠方式、日历、库存与客服准备，以及活动后对照基线的复盘。 | AIBars | MIT | 低 | ✅ |
| [售后与退货处理 Returns and Refunds Playbook](https://aibars.net/zh/skills/895612293981933568) · 原创 | 公平且少亏地处理退货、退款、包裹破损或丢失、拒付和愤怒的客户来信：政策要点、案件处理流程、回复草稿、升级规则，以及找出退货率偏高的原因。 | AIBars | MIT | 低 | ✅ |
| [Shopify 评价分诊 Shopify Review Triage](https://aibars.net/zh/skills/894885799689195520) | 把你粘贴的 Shopify 应用商店公开低分评价整理成 P0~P3 简报，写明负责人、下一步，并为必须由人来读的条目单独设一类。 | Shopify App Review Brief (independent) | MIT | 低 | ✅ |

### 图文与视频（7）

| Skill | 做什么 | 作者 | 协议 | 风险 | 试用 |
|---|---|---|---|---|---|
| [图像提示词写作 Image Prompt Writing](https://aibars.net/zh/skills/895622597725917184) · 原创 | 把模糊的想法写成 AI 绘图工具能听懂的清晰提示词：主体、场景、构图、光线、风格和色彩，按合理的顺序排好，并给出简短版、详细版和变体。 | AIBars | MIT | 低 | ✅ |
| [图像提示词诊断与改写 Image Prompt Debugging](https://aibars.net/zh/skills/895622641216655360) · 原创 | 找出 AI 绘图提示词为什么出图混乱、不对或不稳定，并用最少的改动修好：自相矛盾、画面杂乱、风格混搭、细节被忽略、手画坏、文字乱码。 | AIBars | MIT | 低 | ✅ |
| [系列图一致性 Image Series Consistency](https://aibars.net/zh/skills/895622770577379328) · 原创 | 让一组 AI 图像看起来像同一套：可复用的风格表和角色表、每条提示词里的固定与可变部分、参考图工作流，以及检查跨页是否“跑偏”。 | AIBars | MIT | 低 | ✅ |
| [海报与设计稿提示词 Poster and Design Prompts](https://aibars.net/zh/skills/895622728336543744) · 原创 | 为海报、卡片、封面和社交媒体图写提示词，并决定哪些交给 AI 画、哪些自己排版：版式、层次、配色、给文字留的空白区域和必须一字不差的文案。 | AIBars | MIT | 低 | ✅ |
| [产品与电商图提示词 Product Image Prompts](https://aibars.net/zh/skills/895622685193932800) · 原创 | 为 AI 商品图写提示词并保持真实：纯色背景主图、场景图、平铺图、细节特写、尺寸对比图和样机图，全都要和真实商品对得上。 | AIBars | MIT | 低 | ✅ |
| [视频制作指南 Video](https://aibars.net/zh/skills/896451644534034432) | 帮你选择营销视频的制作方式：程序化（Hyperframes、Remotion）、AI 生成（Veo、Runway、Kling）、AI 数字人（HeyGen、Synthesia）或剪辑与二次利用，附模型对比、提示词技巧和现成流程。 | Corey Haines | MIT | 中 | ✅ |
| [视频工作室 Video Studio](https://aibars.net/zh/skills/896451707305988096) | 围绕本地 FFmpeg 的自动视频制作与剪辑：按 JSON 规格渲染文字卡片视频，去掉口播视频里的静音，烧录 SRT 字幕，并按平台规格打磨。说明为中文，命令里的路径需要换成你自己的。 | foryourhealth111-pixel | Apache-2.0 | 中 | ⚠️ 未试用 |

### 社交内容（8）

| Skill | 做什么 | 作者 | 协议 | 风险 | 试用 |
|---|---|---|---|---|---|
| [短视频脚本 Short Video Script](https://aibars.net/zh/skills/895769885358166016) · 原创 | 写出今天就能拍的 TikTok、Reels 或 Shorts 脚本：三个开头钩子、带画面、屏幕文字和口播台词的分镜表、行动号召、文案和拍摄清单。 | AIBars | MIT | 低 | ✅ |
| [社媒回复手册 Social Reply Playbook](https://aibars.net/zh/skills/895769901091000320) · 原创 | 冷静、诚实地回复评论、私信和公开评价：先给消息分类，选对回复套路，写出简短的公开回复和私下跟进，并知道哪些情况不能先回复、要先做决定。 | AIBars | MIT | 低 | ✅ |
| [内容再利用 Content Repurposing](https://aibars.net/zh/skills/895769896590512128) · 原创 | 把一篇长内容（文章、周刊、逐字稿、演讲）改成各平台的社交帖子，又不改变它的原意：要点、原话引用、形式规划、带来源对照的草稿和忠实度检查。 | AIBars | MIT | 低 | ✅ |
| [内容研究写作助手 Content Research Writer](https://aibars.net/zh/skills/894706733459705856) | 文章和通讯稿的写作搭档：列提纲、改开头、带引用的研究，以及逐段反馈。 | ComposioHQ community contributors | Apache-2.0 | — | ✅ |
| [LinkedIn 帖子排版 LinkedIn Post Formatter](https://aibars.net/zh/skills/894885868224122880) | 把零散的笔记变成一篇精致的 LinkedIn 帖子：有力的开头、带样式的标题、清晰的结构和话题标签，可直接复制粘贴。 | awesome-copilot community | MIT | 低 | ✅ |
| [Slack GIF 创作器](https://aibars.net/zh/skills/894637271385640961) | 使用 Python 和 Pillow 工具为 Slack 表情与消息制作紧凑的动态 GIF。 | Anthropic, PBC | Apache-2.0 | — | ✅ |
| [社交内容日历 Social Content Calendar](https://aibars.net/zh/skills/895769879054127104) · 原创 | 根据你的目标、受众和每周可用时间，排出一份能坚持下去的发布日历：几个内容支柱、每个平台的节奏、带选题和行动号召的带日期发布表、批量制作和复盘计划。 | AIBars | MIT | 低 | ✅ |
| [X 帖子与长串写作 X Thread Writer](https://aibars.net/zh/skills/895769892056469504) · 原创 | 为 X 写把一件事说清楚的帖子：一条有力的单帖、一串长帖、引用帖或回复，首帖能独立成立，每帖只讲一个点，并经过删去废话的编辑。 | AIBars | MIT | 低 | ✅ |

### 办公与文档（15）

| Skill | 做什么 | 作者 | 协议 | 风险 | 试用 |
|---|---|---|---|---|---|
| [内部沟通 Internal Comms](https://aibars.net/zh/skills/894605627295535104) | 按固定的公司格式写内部沟通文档：3P 周更、公司简报、FAQ 回复和一般通知。 | Anthropic | Apache-2.0 | — | ✅ |
| [Excel 转 Markdown](https://aibars.net/zh/skills/894931862445887488) | 把 .xlsx 工作簿转成 Markdown，并提取、链接其中的内嵌图片，方便读取、总结和检索表格内容。 | awesome-copilot community | MIT | 中 | ✅ |
| [Excel 工作簿生成 Excel Workbook Builder](https://aibars.net/zh/skills/896460010010447872) · 原创 | 用 Python 和 openpyxl 创建、修改和检查 Excel（.xlsx）工作簿：用实时公式而不是粘贴数值，输入单独放置，设置格式、图表，修改时保留原文件，并如实说明哪些结果算过、哪些没算。 | AIBars | MIT | 中 | ✅ |
| [文件整理助手 File Organizer](https://aibars.net/zh/skills/894706720520278016) | 分析杂乱的文件夹，提出更清晰的结构并找出重复文件，经你确认方案后才动手整理。 | ComposioHQ community contributors | Apache-2.0 | — | ✅ |
| [发票整理助手 Invoice Organizer](https://aibars.net/zh/skills/894706725737992192) | 读取一个装满发票和收据的文件夹，统一重命名、分类归档，并生成给会计用的 CSV 汇总。 | ComposioHQ community contributors | Apache-2.0 | — | ✅ |
| [MarkItDown 文件转 Markdown](https://aibars.net/zh/skills/895740598513045504) | 用微软的 MarkItDown 把 PDF、Word、PowerPoint、Excel、HTML 等文件转成整洁的 Markdown，方便搜索、分析和交给 AI 处理，默认只在本机安全地运行。 | K-Dense Inc. | MIT | 中 | ✅ |
| [Markdown 转 Word（.docx）](https://aibars.net/zh/skills/894931730967040000) | 用纯 JavaScript 脚本把 Markdown 文件转成带封面、目录、带样式表格和内嵌 PNG 图片的 Word 文档。 | awesome-copilot community | MIT | 中 | ✅ |
| [会议洞察分析 Meeting Insights Analyzer](https://aibars.net/zh/skills/894706738278961152) | 分析你的会议转录，找出回避冲突、含糊其辞、发言占比等沟通模式，附带时间戳的原话示例和更好的说法。 | ComposioHQ community contributors | Apache-2.0 | — | ✅ |
| [会议纪要 Meeting Minutes](https://aibars.net/zh/skills/894885833574977536) | 为一小时以内的内部会议写出简洁、可执行的纪要，决议和待办事项一定有负责人和截止日期。 | awesome-copilot community | MIT | 低 | ✅ |
| [PDF 工具箱 PDF Toolkit](https://aibars.net/zh/skills/896504209388867584) · 原创 | 用 Python 处理常见的 PDF 任务：提取文字和表格，合并、拆分、旋转页面，加水印，填写表单，生成报告。不覆盖原文件，并在保存后重新打开核对页数和文字。 | AIBars | MIT | 中 | ✅ |
| [PPT 演示文稿生成 PowerPoint Deck Builder](https://aibars.net/zh/skills/896504256717393920) · 原创 | 用 Python 和 python-pptx 创建、修改和检查 PowerPoint（.pptx）：真正的版式和占位符、表格、图表、演讲者备注，修改时保留原文件，并在保存后重新打开核对幻灯片和备注。 | AIBars | MIT | 中 | ✅ |
| [策略幻灯片 Slides（HTML 演示）](https://aibars.net/zh/skills/894881177427775488) | 规划并写出有说服力的 HTML 演示文稿：整体结构、每页版式、文案公式和 Chart.js 图表，自带键盘翻页。 | claudekit | MIT | 低 | ✅ |
| [电子表格 Spreadsheet Skill](https://aibars.net/zh/skills/895740561389260800) | 用 Python 创建、编辑、分析和排版 Excel 与 CSV 表格：用真正的公式而不是贴进去的结果，保留格式，布局合理，用之前先做检查。 | OpenAI | Apache-2.0 | 中 | ✅ |
| [定制简历生成器 Tailored Resume Generator](https://aibars.net/zh/skills/894706754812907520) | 根据具体的职位描述定制你的简历，把关键词和要求与你的真实经历对上。 | ComposioHQ community contributors | Apache-2.0 | — | ✅ |
| [Word 文档生成 Word Document Builder](https://aibars.net/zh/skills/896459965693431808) · 原创 | 用 Python 和 python-docx 创建、修改和检查 Word（.docx）文件：真正的样式、表格、页眉页脚和页码字段，修改时不动原文件，并在保存后重新打开检查结果。 | AIBars | MIT | 中 | ✅ |

### 开发提效（40）

| Skill | 做什么 | 作者 | 协议 | 风险 | 试用 |
|---|---|---|---|---|---|
| [安全威胁建模 Security Threat Model](https://aibars.net/zh/skills/895740488542588928) | 为代码仓库做威胁建模：信任边界、资产、攻击者能力、具体的攻击路径，以及对应到真实文件的缓解措施，最后写成一份简明的 Markdown 报告。 | OpenAI | Apache-2.0 | 中 | ✅ |
| [系统化调试 Systematic Debugging](https://aibars.net/zh/skills/895089901731844096) | 先找根因，再动手修：证据、模式、一次一个假设、带测试的修复，共四个阶段，并在失败三次后强制停下。 | Jesse Vincent | MIT | 中 | ✅ |
| [Claude Academy 指引](https://aibars.net/zh/skills/894633023834951681) | 当用户明确在学习 Claude 时，为回答补充高度匹配的 Claude Academy 学习资源。 | Anthropic, PBC | Apache-2.0 | — | ✅ |
| [头脑风暴 Brainstorming（从想法到获批的设计）](https://aibars.net/zh/skills/895089866633908224) | 在写任何代码之前，把想法变成经你批准的设计：先给任务分类、一次只问一个问题、对比方案，并在每个阶段获得你的确认。 | Jesse Vincent | MIT | 中 | ✅ |
| [Caveman 简洁回答](https://aibars.net/zh/skills/894685149437104128) | 让编程代理先给结论、去掉客套话，同时原样保留代码、命令、路径和报错信息。 | Julius Brussee | Apache-2.0 | — | ✅ |
| [Caveman 提交信息](https://aibars.net/zh/skills/894685158358388736) | 生成简短的 Conventional Commits 提交信息，讲清为什么改，而不是改了什么。 | Julius Brussee | Apache-2.0 | — | ✅ |
| [Caveman 记忆文件压缩](https://aibars.net/zh/skills/894685162250702848) | 压缩 CLAUDE.md 等记忆文件，减少每次加载消耗的输入 token；自动校验，并备份原文。 | Julius Brussee | Apache-2.0 | — | ✅ |
| [Caveman 代码审查](https://aibars.net/zh/skills/894685154373799936) | 把代码审查意见压缩成每个问题一行：位置、问题、修法，可附严重程度标记。 | Julius Brussee | Apache-2.0 | — | ✅ |
| [更新日志生成器 Changelog Generator](https://aibars.net/zh/skills/894706715524861952) | 把 git 提交改写成用户看得懂的更新日志，按新功能、改进、安全和修复分组。 | ComposioHQ community contributors | Apache-2.0 | — | ✅ |
| [Chrome DevTools 代理](https://aibars.net/zh/skills/894931664827060224) | 通过 Chrome DevTools MCP 控制并检查一个正在运行的 Chrome：导航、点击、填表、截图和快照、读取控制台和网络，并做性能分析。 | awesome-copilot community | MIT | 高 | ✅ |
| [代码评审（规范与需求）Code Review](https://aibars.net/zh/skills/896432990077587456) | 按两条互相独立的轴评审某个提交、分支或标签以来的改动：规范（是否符合仓库文档里的约定和一组常见代码异味基线）和需求（是否做了 issue 或需求文档要求的事），并行执行，并排报告。 | Matt Pocock | MIT | 中 | ⚠️ 未试用 |
| [诊断 Bug Diagnosing Bugs](https://aibars.net/zh/skills/894699006293446656) | 处理疑难 bug 的六阶段流程：先做出恰好能在这个 bug 上变红的复现，再缩小、验证排序后的假设，最后带回归测试修复。 | Matt Pocock | MIT | — | ✅ |
| [领域建模 Domain Modeling](https://aibars.net/zh/skills/894699033006968832) | 建立项目的共同词汇：质疑含糊的术语，用边界情况检验，并记录到 GLOSSARY.md 和 ADR 里。 | Matt Pocock | MIT | — | ✅ |
| [Draw.io 图表生成器](https://aibars.net/zh/skills/894931796616286208) | 用正确的 mxGraph XML 创建、编辑并校验 draw.io 图表文件：流程图、架构图、时序图、ER 图和 UML 类图，附模板和辅助脚本。 | awesome-copilot community | MIT | 中 | ✅ |
| [Draw.io 图表与 PNG 导出](https://aibars.net/zh/skills/894931763850383360) | 生成原生 .drawio 图表，并用随包的 Node.js 导出脚本导出为 PNG、SVG 或 PDF，同时嵌入可编辑的 XML。 | awesome-copilot community | MIT | 中 | ✅ |
| [Excalidraw 图表生成器](https://aibars.net/zh/skills/894931829675790336) | 把一段自然语言描述变成 Excalidraw 图表文件：流程图、思维导图、架构图、时序图、ER 图、类图和泳道图，附模板和辅助脚本。 | awesome-copilot community | MIT | 中 | ✅ |
| [完整输出强制 Full-Output Enforcement](https://aibars.net/zh/skills/896418233392041984) | 不让智能体偷工减料：不写占位代码，不说“其余同理”，不跳过章节。它会先数清交付物，逐个完整写出，遇到长度上限时干净地暂停。 | Leonxlnx | MIT | 低 | ✅ |
| [修复 GitHub CI 失败 Fix Failing GitHub CI](https://aibars.net/zh/skills/895740527281180672) | 调试拉取请求上失败的 GitHub Actions 检查：找出失败的检查、拉取日志、总结原因、起草修复方案，并且只有在你批准后才修改代码。 | OpenAI | Apache-2.0 | 中 | ⚠️ 未试用 |
| [追问到底 Grilling](https://aibars.net/zh/skills/894699000484335616) | 让代理按编号分轮次采访你，每个问题都附上推荐答案，直到计划里的每个决定都敲定。 | Matt Pocock | MIT | — | ✅ |
| [交接 Handoff](https://aibars.net/zh/skills/894699014652694528) | 把当前对话压缩成一份交接文档，让全新的代理会话能接着做。 | Matt Pocock | MIT | — | ✅ |
| [改进代码库架构 Improve Codebase Architecture](https://aibars.net/zh/skills/896433124773466112) | 扫描代码库，找出能把“浅模块”变成“深模块”的重构，用带前后对比图的可视化 HTML 报告呈现，再对你选中的那一个进行追问式讨论。 | Matt Pocock | MIT | 中 | ⚠️ 未试用 |
| [故障复盘 Incident Post-Mortem（无责）](https://aibars.net/zh/skills/894885971676631040) | 带领团队完成一次结构化的无责复盘：时间线、用 5 个为什么找根因、影响数据，以及有负责人和截止日期的改进事项。 | awesome-copilot community | MIT | 中 | ✅ |
| [先查原因 Investigate First](https://aibars.net/zh/skills/894685166356926464) | 让代理在改代码之前，先找到并证实 bug 的原因。 | Julius Brussee | Apache-2.0 | — | ✅ |
| [Markdown 与 Mermaid 写作](https://aibars.net/zh/skills/895740636475691008) | 用 Markdown 加 Mermaid 图来写工作流、数据结构、时间线和架构文档：21 种图的语法指南、文档模板、无障碍元数据和渲染检查。 | Clayton Young / Superior Byte Works | Apache-2.0 | 中 | ✅ |
| [MCP 构建指南 MCP Builder](https://aibars.net/zh/skills/894625433763713024) | 用 TypeScript 或 Python 构建高质量 MCP 服务器的指南：调研、设计、实现、测试和评估。 | Anthropic | Apache-2.0 | — | ✅ |
| [PR 描述 PR](https://aibars.net/zh/skills/894699018884747264) | Pull Request 正文模板：用最小的图示说明改了什么，给出前后证据，并标明合并风险。 | Matt Pocock | MIT | — | ✅ |
| [产品需求文档 PRD](https://aibars.net/zh/skills/894886006292221952) | 写出把业务目标与技术落地连起来的 PRD：问题、用户、可衡量的需求、非目标、技术规格、风险和分阶段路线图。 | awesome-copilot community | MIT | 低 | ✅ |
| [原型 Prototype](https://aibars.net/zh/skills/894699023003553792) | 做一个一次性原型来回答一个设计问题：逻辑问题做成可点击的 HTML 模型，界面问题做成多个可对比的界面方案。 | Matt Pocock | MIT | — | ✅ |
| [接收代码评审 Receiving Code Review](https://aibars.net/zh/skills/895090080384028672) | 用技术上的严谨来处理评审意见：先理解、再对照代码核实、不对就反驳、先澄清再动手，并且一次只改一条。 | Jesse Vincent | MIT | 中 | ✅ |
| [请求代码评审 Requesting Code Review](https://aibars.net/zh/skills/895090042102616064) | 把完成的工作交给一位“新鲜”的评审者：带着计划和精确 git 范围的评审提示、分级的发现，以及怎么处理这些发现的规则。 | Jesse Vincent | MIT | 低 | ✅ |
| [代码安全审查 Security Review](https://aibars.net/zh/skills/894885901493342208) | 像安全研究员一样审查代码库：追踪用户输入到危险调用点，找出注入、访问控制和密钥泄露问题，并给出供你审阅的补丁，绝不自动应用。 | awesome-copilot community | MIT | 高 | ✅ |
| [技能创作器 Skill Creator](https://aibars.net/zh/skills/894631087484178432) | 带你从一个想法做出完整的 Agent Skill：梳理需求、起草 SKILL.md、写测试提示词，还可以跑评测并优化触发描述。 | Anthropic | Apache-2.0 | — | ✅ |
| [精准修复 Surgical Patch](https://aibars.net/zh/skills/894685171004215296) | 只在负责出错的那一层修 bug，补上回归测试，不顺手做无关的清理。 | Julius Brussee | Apache-2.0 | — | ✅ |
| [测试驱动开发 TDD](https://aibars.net/zh/skills/894699010550665216) | 一次一小片的测试先行开发：先写会失败的测试，再让它通过，并且只在事先约定的切入点上测试。 | Matt Pocock | MIT | — | ✅ |
| [测试驱动开发 TDD](https://aibars.net/zh/skills/895089938880794624) | 先写失败的测试、看着它失败、写最少的代码让它通过、再重构：带严格规则和检查清单的红-绿-重构循环。 | Jesse Vincent | MIT | 中 | ✅ |
| [完成前先验证 Verification Before Completion](https://aibars.net/zh/skills/895090007650603008) | 先有证据再下结论：模型必须在同一轮里运行验证命令并读完输出，才能说工作已完成、已修复或测试通过。 | Jesse Vincent | MIT | 低 | ✅ |
| [验证即停 Verify and Stop](https://aibars.net/zh/skills/894685175584395264) | 检查工作是否满足验收条件，满足就停，不扩大范围。 | Julius Brussee | Apache-2.0 | — | ✅ |
| [网页应用测试 Web Application Testing](https://aibars.net/zh/skills/894633023834951680) | 为本地网页应用生成用于检查、测试和排障的 Playwright 自动化方案。 | Anthropic, PBC | Apache-2.0 | — | ✅ |
| [为代理写文档 Writing for Agents](https://aibars.net/zh/skills/894699028359680000) | 一份写给代理看的文档的写作参考，适用于 skill、CLAUDE.md、AGENTS.md，让代理的行为更可预测。 | Matt Pocock | MIT | — | ✅ |
| [编写实施计划 Writing Plans](https://aibars.net/zh/skills/895089973114703872) | 把规格文档变成别人能照着做的分步实施计划：精确的文件、接口、先写测试的步骤（含预期输出）和自查。 | Jesse Vincent | MIT | 中 | ✅ |

### 品牌与营销（27）

| Skill | 做什么 | 作者 | 协议 | 风险 | 试用 |
|---|---|---|---|---|---|
| [转化文案 Conversion Copywriting](https://aibars.net/zh/skills/895074689435832320) | 为首页、落地页、定价页和功能页写作和改写营销文案：清晰的标题、有力的 CTA、页面结构，以及一份必须避开的“AI 腔”严格清单。 | Corey Haines | MIT | 低 | ✅ |
| [转化率优化 CRO](https://aibars.net/zh/skills/895074761183596544) | 分析营销页面或表单，得到排好序的改进建议：价值主张、标题、CTA、信任信号、异议和阻力，附测试思路和文案备选。 | Corey Haines | MIT | 低 | ✅ |
| [Google SEO 审计](https://aibars.net/zh/skills/896036597110411264) · 原创 | 根据你提供的 HTML、robots.txt 和 Search Console 数据，从 Google 搜索的角度审计页面或站点：抓取与收录障碍、标题、内容质量、结构化数据和页面体验，给出按优先级排序的修复清单。 | AIBars | MIT | — | ✅ |
| [A/B 测试与实验 A/B Testing](https://aibars.net/zh/skills/895074798055723008) | 规划能得出有效结论的 A/B 测试：假设、样本量与时长、指标、变体和分析，另有带 ICE 评分和打法手册的增长实验体系。 | Corey Haines | MIT | 低 | ✅ |
| [广告投放分析 Ad Campaign Analyzer](https://aibars.net/zh/skills/894885732513222656) | 把广告投放数据导出变成明确的决策：该暂停什么、加码什么、测试什么，以及如何在渠道之间重新分配预算。 | GooseWorks | MIT | 中 | ✅ |
| [AI 搜索优化 AI SEO](https://aibars.net/zh/skills/894666349127929856) | 审计并改进产品内容在 AI 回答中的可发现性、可提取性和引用机会。 | Corey Haines | MIT | — | ✅ |
| [分析追踪 Analytics](https://aibars.net/zh/skills/894677603934539776) | 规划、审计和排查 GA4、GTM、UTM、转化与产品事件追踪。 | Corey Haines | MIT | — | ✅ |
| [营销归因 Marketing Attribution](https://aibars.net/zh/skills/895074935528230912) | 弄清楚究竟哪些营销带来了转化：选择并解读归因模型，对账广告平台、统计工具和 CRM 互相矛盾的数字，并搭建第一方归因。 | Corey Haines | MIT | 低 | ✅ |
| [品牌 Brand（语气、识别与一致性）](https://aibars.net/zh/skills/894881226626961408) | 定义并保持品牌一致：语气与口吻、视觉识别、信息框架、颜色与字体规则、素材命名与审批清单，附品牌指南起步模板。 | claudekit | MIT | 中 | ✅ |
| [防止流失 Churn Prevention](https://aibars.net/zh/skills/895074900270911488) | 降低订阅流失：设计取消流程和挽留方案、预测有流失风险的客户，并用催款方案、重试和邮件序列挽回支付失败的订阅。 | Corey Haines | MIT | 低 | ✅ |
| [冷邮件写作 Cold Email](https://aibars.net/zh/skills/895074831769538560) | 写出读起来像一个有心的真人写的 B2B 冷邮件和简短的跟进序列：有针对性、简短、只提一个低门槛的请求，附主题行写法和基准数据。 | Corey Haines | MIT | 低 | ✅ |
| [竞品广告情报 Competitor Ad Intelligence](https://aibars.net/zh/skills/894885766411587584) | 研究竞争对手公开的广告和落地页，找出他们的钩子、形式和弱点，再把空白点变成应对思路。 | GooseWorks | MIT | 中 | ✅ |
| [内容策略 Content Strategy](https://aibars.net/zh/skills/895074865365913600) | 规划该做什么内容以及为什么做：内容支柱与主题集群、按买家阶段做关键词研究、点子来源、排优先级的打分方法和 60/30/10 日历。 | Corey Haines | MIT | 低 | ✅ |
| [文案编辑 Copy Editing（七轮打磨）](https://aibars.net/zh/skills/895074725217439744) | 分七轮有针对性地编辑和改进现有营销文案：清晰度、语气、所以呢、证据、具体性、情感和风险，另有词句层面的检查和内容翻新流程。 | Corey Haines | MIT | 低 | ✅ |
| [客户研究](https://aibars.net/zh/skills/894677588361089024) | 将访谈、问卷、工单、评论和公开讨论综合为基于证据的客户洞察。 | Corey Haines | MIT | — | ✅ |
| [域名创意助手 Domain Name Brainstormer](https://aibars.net/zh/skills/894706749389672448) | 为你的项目生成多种后缀的域名创意，并在代理能查询时核对是否可注册。 | ComposioHQ community contributors | Apache-2.0 | — | ✅ |
| [定位策略 Positioning Strategy](https://aibars.net/zh/skills/894885590435368960) | 找到竞争对手难以复制的市场定位，并在重塑品牌之前，先用真实买家验证新的表述。 | Smit Patel | MIT | 低 | ✅ |
| [产品驱动增长 Product-Led Growth](https://aibars.net/zh/skills/894885625864654848) | 判断你的产品适合自助、销售驱动还是混合模式，并用简单规则衡量渠道回报、激活和增长。 | Smit Patel | MIT | 低 | ✅ |
| [技术产品定价 Technical Product Pricing](https://aibars.net/zh/skills/894885661042282496) | 在按席位、按用量和混合定价之间做选择，设定免费版上限，应对企业客户的报价沟通，并判断何时涨价。 | Smit Patel | MIT | 低 | ✅ |
| [落地页转化审计 Landing Page Conversion Audit](https://aibars.net/zh/skills/894885696479956992) | 审计落地页、销售页或结账页的转化漏点，得到按预期影响排序的简短修复清单，并在开头说明哪些内容无法核查。 | awesome-copilot community | MIT | 中 | ✅ |
| [发布策略 Launch Strategy](https://aibars.net/zh/skills/895075006248390656) | 规划产品或功能发布：ORB 渠道框架、就绪检查、分五个阶段推进、Product Hunt 打法、发布后的动作和检查清单。 | Corey Haines | MIT | 低 | ✅ |
| [潜在客户研究助手 Lead Research Assistant](https://aibars.net/zh/skills/894706744247455744) | 找出并排序与你的产品匹配的公司，并给出每家公司该联系的职位和量身定制的接触思路。 | ComposioHQ community contributors | Apache-2.0 | — | ✅ |
| [报价与优惠设计 Offer Design](https://aibars.net/zh/skills/895074971033014272) | 设计或改进你真正在卖的东西：价值呈现、赠品叠加、保证条款设计和诚实的稀缺性，配有价值方程和诊断循环。 | Corey Haines | MIT | 低 | ✅ |
| [定价策略 Pricing](https://aibars.net/zh/skills/894677614973947904) | 制定重视证据的定价、套餐、支付意愿研究和定价页审查方案。 | Corey Haines | MIT | — | ✅ |
| [程序化 SEO](https://aibars.net/zh/skills/894677623232532480) | 规划可扩展的数据驱动 SEO 页面，同时防范薄内容和索引风险。 | Corey Haines | MIT | — | ✅ |
| [SEO 审计](https://aibars.net/zh/skills/894677560510910464) | 生成包含优先级修复建议的技术、页面和多语言 SEO 审计。 | Corey Haines | MIT | — | ✅ |
| [服务端转化追踪 Server-Side Conversion Tracking](https://aibars.net/zh/skills/894931698423435264) | 解决广告转化少报的问题：捕获点击 ID、一路带到订单、把购买以服务器对服务器的方式发给 Facebook、TikTok、Google 和 Bing，再去重和核对。 | awesome-copilot community | MIT | 中 | ✅ |

### 研究与学习（8）

| Skill | 做什么 | 作者 | 协议 | 风险 | 试用 |
|---|---|---|---|---|---|
| [论文阅读 Paper Reading](https://aibars.net/zh/skills/896427684459188224) · 原创 | 分三遍批判性地读一篇论文：它主张什么、怎么检验、证据是否站得住，以及你能从中得到什么。关键主张附原文引用，文中没说的就写“未说明”。 | AIBars | MIT | 低 | ✅ |
| [学习计划 Study Plan](https://aibars.net/zh/skills/896427730831413248) · 原创 | 根据你的目标、现有水平和每周可用时间，做出一份切实可行的学习计划：可行性判断、带检查点的阶段、含间隔复习的每周安排，以及落后时的补救规则。 | AIBars | MIT | 低 | ✅ |
| [审慎追问 Discernment Nudge](https://aibars.net/zh/skills/894625433440751616) | 在你可能据此行动的实质性回答之后，附上 2 到 3 个具体的追问，帮你核对事实、检验推理、发现缺失的背景。 | Anthropic | Apache-2.0 | — | ✅ |
| [AI 输出核查 Doublecheck](https://aibars.net/zh/skills/894885936842936320) | 核查 AI 写的文字：提取每一条可验证的断言，找出你可以自己打开查看的来源，并在结构化报告里标出可能的幻觉。 | awesome-copilot community | MIT | 中 | ✅ |
| [闪卡与测验 Flashcards and Quiz](https://aibars.net/zh/skills/896427777283330048) · 原创 | 把你提供的学习材料做成闪卡和分级测验，用于主动回忆，附出处、解析、常见错误和间隔复习安排，不添加材料之外的任何内容。 | AIBars | MIT | 低 | ✅ |
| [文献综述 Literature Review](https://aibars.net/zh/skills/896427636820283392) · 原创 | 把你提供的论文和笔记整理成结构化的综述：主题、一致与分歧、研究方法、研究空白和来源对照，不编造引用，并说明每个主题的证据强度。 | AIBars | MIT | 低 | ✅ |
| [研究问题界定 Research Question Framing](https://aibars.net/zh/skills/896427823680720896) · 原创 | 把模糊的主题变成可研究的问题：先诊断哪里模糊，再一步步缩小范围，用清晰度、可行性和价值检验每个候选问题，最后给选中的问题定下定义、范围、假设和证据。 | AIBars | MIT | 低 | ✅ |
| [教学工作区 Teach](https://aibars.net/zh/skills/896432932938584064) | 把当前文件夹变成教学工作区，用多次会话学会一个主题：明确的学习目标、可信资料、简短的交互式 HTML 课程、速查文档，以及决定下一步教什么的学习记录。 | Matt Pocock | MIT | 中 | ⚠️ 未试用 |

## 安装 Skill

每个 Skill 页面都有适合你所用代理的完整命令。以 Claude Code 用户级为例（把 `<skill-key>` 换成页面上的 Skill 标识，例如 `frontend-design`）：

```bash
curl -fsSL https://skill.aibars.net/skills/<skill-key>.zip -o skill.zip \
  && mkdir -p ~/.claude/skills/<skill-key> \
  && unzip -oq skill.zip -d ~/.claude/skills/<skill-key> \
  && rm skill.zip
```

常见目录（以各代理的文档为准，可能变化）：

| 代理 | 用户级 | 项目级 |
|---|---|---|
| Claude Code | `~/.claude/skills/` | `.claude/skills/` |
| Codex | `~/.agents/skills/` | `.agents/skills/` |
| GitHub Copilot | `~/.copilot/skills/` | `.agents/skills/` |
| Cursor | `~/.cursor/skills/` | `.agents/skills/` |
| Gemini CLI | `~/.gemini/skills/` | `.agents/skills/` |
| Windsurf | `~/.codeium/windsurf/skills/` | `.windsurf/skills/` |

我们在 Claude Code 和 GitHub Copilot CLI（用户级）上实测过安装，其他目录来自各代理的文档或公开列表，我们没有在 Windows 上测试过。

## 推荐 Skill 或反馈问题

请提交一个 [issue](../../issues)，附上 Skill 的链接、它做什么以及为什么有用，或者出了什么问题。只有协议允许、并且我们能读完它全部文件的 Skill 才会收录。

## 协议

本列表和这份 README 以 MIT 协议发布。**每个 Skill 保留它自己的协议**，见表格和各自页面；标「原创」的是 AIBars 原创，协议为 MIT。Skill 是按原样提供的第三方内容，不附带任何担保。让代理运行 Skill 之前，请先审阅它。
