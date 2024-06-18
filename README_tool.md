# Awesome-AGI

欢迎来到 **Awesome-AGI**，这是一个精心整理的人工通用智能（AGI）项目和资源列表。

觉得有用请点个 Star 吧！

## 目录
- [Awesome-AGI](#awesome-agi)
  - [目录](#目录)
  - [工具](#工具)
    - [run-llama/create-llama 构建 ](#run-llamacreate-llama-构建-)
    - [AutomaApp/automa 工具 ](#automaappautoma-工具-)
    - [CopilotKit/CopilotKit 交互 ](#copilotkitcopilotkit-交互-)
    - [szkane/PopclipGemini 交互 ](#szkanepopclipgemini-交互-)
    - [mendableai/firecrawl 抽取 ](#mendableaifirecrawl-抽取-)
    - [mendableai/firecrawl-py 抽取 ](#mendableaifirecrawl-py-抽取-)
    - [josStorer/chatGPTBox 浏览器插件 ](#josstorerchatgptbox-浏览器插件-)
    - [⭐️ continuedev/continue IDE插件 ](#️-continuedevcontinue-ide插件-)
    - [NaiboWang/EasySpider 爬虫框架 ](#naibowangeasyspider-爬虫框架-)
    - [langchain-ai/langchain-nextjs-template 构建工具 ](#langchain-ailangchain-nextjs-template-构建工具-)
    - [slidevjs/slidev PPT ](#slidevjsslidev-ppt-)
    - [weibocom/rill-flow 工作流 ](#weibocomrill-flow-工作流-)
    - [xszyou/Fay 数字人 ](#xszyoufay-数字人-)
    - [OpenTalker/video-retalking 视频合成 ](#opentalkervideo-retalking-视频合成-)
    - [streamlit/streamlit](#streamlitstreamlit)
    - [BasedHardware/OpenGlass 智能硬件 ](#basedhardwareopenglass-智能硬件-)
    - [modelscope/data-juicer 数据处理 ](#modelscopedata-juicer-数据处理-)
    - [Avdpro/ai2apps 应用构建 ](#avdproai2apps-应用构建-)
    - [Kanaries/pygwalker 数据可视化 ](#kanariespygwalker-数据可视化-)
    - [e-p-armstrong/augmentoolkit 数据集构建 ](#e-p-armstrongaugmentoolkit-数据集构建-)
    - [AgentOps-AI/agentops 监控 ](#agentops-aiagentops-监控-)
    - [nocobase/nocobase 无代码 ](#nocobasenocobase-无代码-)
    - [wanglin2/mind-map 思维导图 ](#wanglin2mind-map-思维导图-)
    - [aieditor-team/AiEditor 富文本 ](#aieditor-teamaieditor-富文本-)
    - [VikParuchuri/surya 抽取 ](#vikparuchurisurya-抽取-)
    - [quickwit-oss/tantivy 搜索 ](#quickwit-osstantivy-搜索-)
    - [VikParuchuri/surya 抽取 ](#vikparuchurisurya-抽取--1)
    - [360AILAB-NLP/360LayoutAnalysis 抽取 ](#360ailab-nlp360layoutanalysis-抽取-)
    - [PawanOsman/ChatGPT 代理 ](#pawanosmanchatgpt-代理-)
    - [VikParuchuri/surya	](#vikparuchurisurya)
    - [Dataherald/dataherald ](#dataheralddataherald-)
    - [zhayujie/chatgpt-on-wechat 微信接入 ](#zhayujiechatgpt-on-wechat-微信接入-)
    - [lipku/metahuman-stream 数字人 ](#lipkumetahuman-stream-数字人-)
    - [TMElyralab/MuseTalk: MuseTalk数字人 ](#tmelyralabmusetalk-musetalk数字人-)
    - [facefusion/facefusion 数字人 ](#facefusionfacefusion-数字人-)




 ## 工具

### [run-llama/create-llama](https://github.com/run-llama/create-llama) 构建 ![GitHub stars](https://img.shields.io/github/stars/run-llama/create-llama?style=social)

 是一个开源项目，提供了一个简单的 CLI 工具，用于快速搭建基于 LlamaIndex 的应用程序，支持多种后端框架和数据源，并且提供了丰富的文档和社区支持。

**摘要**

run-llama/create-llama 项目旨在通过一个命令行工具 create-llama，简化使用 LlamaIndex 构建应用程序的过程。该工具支持三种后端框架：Next.js、Express 和 Python FastAPI，并且提供了一个基于 shadcn/ui 的 Next.js 前端界面。用户可以选择不同的数据源，如 PDF、文本、CSV、Markdown、Word 和 HTML 文件，并且可以通过 npm run generate 或者 poetry run generate 命令对数据进行索引。项目支持多种大型语言模型，默认使用 OpenAI 的 gpt-4-turbo 和 text-embedding-3-large，但也支持其他 LLMs。项目遵循 MIT 许可证，并且在 GitHub 上有详细的文档和社区支持，包括问题跟踪和反馈机制。项目仓库包含了多个文件夹和文件，如 .github、helpers、scripts 等，每个文件夹和文件都有明确的功能和提交记录。

**特点**
- 易用性: create-llama 工具旨在让开发者能够快速启动并运行一个基于 LlamaIndex 的项目，无论是全栈 Next.js 应用、传统的 Node.js Express 应用还是 Python FastAPI 应用。
- 灵活性: 项目支持多种数据源和大型语言模型，允许开发者根据需求选择合适的技术栈和工具。
- 社区参与: 项目鼓励社区成员的参与，提供了详细的文档和反馈渠道，同时通过 GitHub 的机制（如 Issue、Pull Request）促进社区成员之间的交流和协作。
- 持续集成和部署: 项目配置了自动化工具，如 GitHub Actions，以实现持续集成和部署，确保代码的质量和稳定性。
- 跨平台支持: 项目支持在不同的操作系统上运行，包括 macOS、Linux 和 Windows，增加了它的可访问性和适用性。
- 开源许可: 采用 MIT 许可证，使得项目的使用和贡献更加便捷，无论是个人开发者还是商业组织。
- 文档和支持: 项目提供了详尽的文档和支持资源，包括 README、CONTRIBUTING 指南和 CHANGELOG，帮助用户理解和使用项目。

 ###  [AutomaApp/automa](https://github.com/AutomaApp/automa) 工具 ![GitHub stars](https://img.shields.io/github/stars/AutomaApp/automa?style=social)

 

**摘要**

AutomaApp/automa 是一个开源的浏览器扩展程序，它允许用户通过连接不同的块来自动化网页上的重复性任务，例如自动填写表单、执行定时任务、截图或抓取网页数据。用户可以在 Automa 的市场中分享和下载工作流程。此外，Automa Chrome Extension Builder（Automa CEB）提供了一个生成基于 Automa 工作流程的独立 Chrome 扩展程序的工具。该项目的代码在 GNU Affero General Public License (AGPL) 或 Automa Commercial License 下获得许可。

**特点**
- 自动化功能: Automa 提供了自动化浏览器操作的能力，用户可以通过连接和配置不同的块来完成各种自动化任务。
- 市场共享: Automa 提供了一个市场平台，用户可以在其中分享自己的工作流程，并下载他人创建的工作流程。
- 跨浏览器支持: Automa 支持 Chrome 和 Firefox 浏览器，确保广泛的用户群体可以使用。
- 开发者工具: Automa CEB 允许开发者将 Automa 工作流程转换为独立的 Chrome 扩展程序。
- 项目贡献: 项目鼓励社区贡献，包括提交问题、提出建议以及帮助改进项目。
- 许可证: 项目代码采用 AGPL 或 Automa Commercial License 许可，为用户提供了不同的使用和贡献选项。
- 项目活跃度: 项目拥有大量的星标和叉子，以及活跃的观察者和贡献者，显示了其在社区中的流行度和活跃度。
- 安装方式: 提供了详细的本地安装指南，包括如何在开发者模式下加载扩展程序。
- 编程语言: 项目主要使用 Vue 和 JavaScript 编写，Vue 占据了 59.4%，JavaScript 占据了 40.0%。

### [CopilotKit/CopilotKit](https://github.com/CopilotKit/CopilotKit) 交互 ![GitHub stars](https://img.shields.io/github/stars/CopilotKit/CopilotKit?style=social)

是一个开源框架，用于构建定制的 AI 协同助手，包括应用内 AI 聊天机器人、AI 代理和 AI 驱动的文本区域。

**摘要**

CopilotKit/CopilotKit 项目旨在帮助开发者创建能够与用户交互的 AI 协同助手，这些助手能够理解和操作应用程序的状态，并与第三方服务（如 Salesforce、Dropbox 等）进行交互。该框架提供了多种组件，包括 ```<CopilotChat />``` 用于构建应用感知的 AI 聊天机器人，```<CopilotTextarea /> ```作为普通 ```<textarea />``` 的增强替代品，提供 AI 辅助的文本生成功能，以及基于 LangChain 的应用内代理（Agent），这些代理能够实时访问应用上下文并在应用内执行操作。此外，项目还提供了一系列的快速入门模板、详细的文档和示例，以及一个明确的安装和使用指南。项目遵循 MIT 许可证，并且积极维护。


**特点**
- 定制化 AI 协同助手: 项目支持构建完全定制的 AI 协同助手，适应不同的应用场景和需求。
- 应用内交互: AI 协同助手能够与应用的前端和后端交互，甚至与第三方服务集成。
- 多样化的 UI 组件: 提供了一系列内置的 UI 组件，如 ```<CopilotSidebar>```、```<CopilotPopup>``` 和 ```<CopilotChat>```，以及自定义 UI 组件的支持。
- 开源和社区驱动: 项目鼓励社区贡献，并通过 Issues 标签页允许社区成员对未来功能进行投票。
- 跨平台和多语言支持: 目前支持 React，未来计划支持 Vue、Svelte 和 Swift（Mac + iOS）等框架和语言。
- 持续的发展和支持: 项目拥有一个公开的路线图，并且定期发布新版本，确保项目的持续发展和支持。
- 易于上手: 提供了详细的快速入门指南和示例，帮助开发者快速集成和使用框架。
- 强大的后端支持: 通过 CopilotRuntime 提供服务器端运行时，以及 useCopilotReadable、useMakeCopilotDocumentReadable 等钩子函数，使得 AI 协同助手能够理解和操作应用状态。
- 用户参与和透明度: 项目允许用户通过 useCopilotChain 等工具提供特定的语言模型链，以及通过 useEditCopilotMessage 等功能编辑未发送的用户消息，增加了用户的参与度和透明度。
- 丰富的文档和资源: 项目提供了 README、文档、示例和其他资源，以帮助开发者理解和有效使用框架。 


### [szkane/PopclipGemini](https://github.com/szkane/PopclipGemini) 交互 ![GitHub stars](https://img.shields.io/github/stars/szkane/PopclipGemini?style=social)

szkane/PopclipGemini 是一个基于 Google Gemini AI 的 Popclip 扩展，旨在提供包括改善写作、扩展文本、简化文本、拼写和语法检查以及翻译等功能。

**概述**

szkane/PopclipGemini 是一个开源项目，提供了一个 Popclip 应用程序的扩展，利用 Google Gemini AI 技术来辅助写作。该扩展包括以下几个功能：改善写作、使文本更长、使文本更短、拼写和语法检查以及翻译服务。用户需要先安装 Popclip 应用在 Mac 上，然后通过选择并安装相应的扩展文件来使用这些功能。项目的文件和文件夹结构包括了各个功能的 JavaScript 实现文件，如 `ImproveWriting.js`、`MakeLonger.js` 等，以及 `LICENSE` 文件和 `README.md` 文件。

项目在 GitHub 上有 66 颗星和 7 个叉子，表明有一定的社区关注和参与。该项目的开发历史记录了从尝试创建 Popclip 扩展到添加模型选项和支持最新版本的 Gemini 的发展过程。然而，作者在最新的更新中提到，由于发现了更优秀的免费应用和扩展，将不再更新该项目。作者建议感兴趣的用户可以访问 `openai-translator` 链接获取更好的工具。

**特点**

- **AI 辅助写作**: 该扩展通过 Google Gemini AI 提供多种写作辅助功能，如改善写作质量、调整文本长度、校对拼写和语法错误，以及提供翻译服务。
- **用户交互**: 用户需要通过安装 Popclip 应用和相应的扩展文件来启用这些 AI 功能。
- **开源性和社区参与**: 项目是开源的，鼓励社区成员的参与和贡献，这 reflected 在 GitHub 上的 star 和 fork 数量上。
- **项目维护**: 作者已经决定停止对该项目的更新，因为他发现了更好的替代品，这可能影响用户对该扩展的未来使用和支持。
- **技术支持和文档**: 项目提供了详细的 `README.md` 文件，包括安装指南、功能描述和更新日志，以及如何获取 Google Gemini API 密钥的信息。
- **许可证**: 该项目使用 Apache-2.0 许可证，这对于想要使用或贡献到项目的开发者提供了一定的法律保障和指导。

### [mendableai/firecrawl](https://github.com/mendableai/firecrawl.git) 抽取 ![GitHub stars](https://img.shields.io/github/stars/mendableai/firecrawl?style=social)

Firecrawl 是一个由 Mendable.ai 和社区共同开发的网络爬虫服务，能够将网站内容转换为适用于大型语言模型（LLM）的标记语言或结构化数据。

**摘要**
Firecrawl 是一个提供 API 服务的爬虫工具，可以通过给定的 URL 抓取整个网站并将其转换成 LLM 友好的标记语言或结构化数据。该工具不需要网站的站点地图，能够抓取所有可访问的子页面，并提供每个页面的清晰数据。Firecrawl 提供了一个易于使用的 API，支持 Python 和 Node 环境的 SDK，并且支持与 Langchain、Llama Index 和 Langchain JS 的集成。用户可以通过 API 密钥来使用这些功能，并且可以选择本地运行或使用 Firecrawl 提供的托管服务。此外，Firecrawl 还支持搜索功能，可以搜索网页并返回相关的标记语言内容，同时还提供了智能提取功能，可以从抓取的页面中提取结构化数据。

Firecrawl 的使用示例包括如何安装 Python 和 Node SDK、如何爬取和抓取网站内容、如何提取结构化数据以及如何进行搜索操作。同时，Firecrawl 鼓励用户贡献代码，并提供了贡献指南。Firecrawl 强调用户在使用工具时必须遵守网站的隐私政策和使用条款，并且默认情况下会尊重网站的 robots.txt 文件指令。

**特点**
Firecrawl 的主要观点是提供一个高效、易于使用的爬虫工具，使得用户能够轻松地将网站内容转换为 LLM 可以处理的格式，无论是标记语言还是结构化数据。该工具的设计理念是简化网站数据的提取过程，使得开发者和数据科学家能够更专注于数据的分析和应用。Firecrawl 的开发团队致力于不断改进工具的功能，包括智能提取和搜索功能，并且致力于与开发者社区合作，鼓励用户参与到项目的贡献中来。同时，Firecrawl 也强调了在使用爬虫工具时的道德和法律责任，提醒用户在使用前要了解并遵守相关网站的政策。


### [mendableai/firecrawl-py](https://github.com/mendableai/firecrawl-py) 抽取 ![GitHub stars](https://img.shields.io/github/stars/mendableai/firecrawl-py?style=social)
 是一个 Python 库的 GitHub 仓库，用于网站抓取和转换，将网站内容抓取并转换为适用于语言模型的清晰格式。

**摘要**
Firecrawl Python SDK 是一个简化网站抓取和爬虫操作的库，它允许用户通过 Firecrawl API 轻松地获取和处理网站数据。用户可以通过 pip 安装该 SDK，并通过获取 API 密钥来使用它。SDK 提供了 scrape_url 和 crawl_url 两个主要方法，分别用于抓取单个网址和爬取整个网站。scrape_url 方法返回指定 URL 的抓取数据。crawl_url 方法允许用户设置爬取参数，如排除规则、包含规则和页面限制，并可以选择是否等待爬取任务完成。如果选择等待，方法将在任务完成后返回结果，如果任务失败或被停止，将抛出异常。用户还可以通过 check_crawl_status 方法手动检查爬取任务的状态。Firecrawl Python SDK 支持错误处理，并且是开源的，遵循 MIT 许可证。该项目鼓励社区贡献，并提供了关于如何参与的指南。

**特点**
- 开源与社区贡献: Firecrawl Python SDK 是开源项目，鼓励用户提交问题和改进建议，欢迎社区成员通过提交问题或拉取请求来参与项目的发展。
- 易用性: SDK 提供了简单直观的接口，使得与 Firecrawl API 的交互变得容易，即使是对于初学者。
- 功能性: 提供了网站抓取和爬虫的核心功能，包括对单个页面的抓取和对整个网站的爬取，以及对爬取任务状态的检查。
- 灵活性: 用户可以根据需要设置爬取参数，如排除和包含规则，以及是否等待爬取任务完成。
- 错误处理: SDK 能够处理 API 返回的错误，并提供了异常处理机制。
- 适用性: 该库特别适用于需要将网站内容转换为适合语言模型使用的格式的场景。
- 语言与环境: 该 SDK 是用 Python 编写的，并且可以通过 pip 在 Python 环境中轻松安装。
- 许可证: Firecrawl Python SDK 遵循 MIT 许可证，这是一个宽松的许可证，允许代码的自由使用、复制、修改、合并、出版、分发、再授权和 / 或出售。



### [josStorer/chatGPTBox](https://github.com/josStorer/chatGPTBox) 浏览器插件 ![GitHub stars](https://img.shields.io/github/stars/josStorer/chatGPTBox?style=social)
是一个开源项目，旨在深度集成 ChatGPT 到浏览器中，提供多种功能，如搜索引擎集成、悬浮窗口、会话分支、常用网站集成、选择工具、独立会话页面、Git 分析、右键菜单、视频摘要、移动设备支持和设置选项。

**摘要**

josStorer/chatGPTBox 项目是一个免费的浏览器扩展，它允许用户在浏览网页时与 ChatGPT 进行交互。该扩展支持多种语言，包括英语、印度语、简体中文、日语和土耳其语。项目的特点包括与搜索引擎的集成、使用悬浮窗口和会话分支、支持常用网站的集成、提供选择工具、有独立的会话页面、可以进行 Git 分析、提供右键菜单、能够总结视频内容、支持移动设备和提供丰富的设置选项。此外，项目确保不会收集用户数据，除非用户明确触发请求。用户可以通过查看代码中的 fetch( 和 XMLHttpRequest( ) 调用来验证这一点。项目鼓励使用自定义模型模式与 LLM API 一起使用，并提供了安装指南、预览、开发和贡献指南、视频演示和致谢信息。项目基于 josStorer/chatGPT-search-engine-extension，后者源自 wong2/chat-gpt-google-extension，并受到 ZohaibAhmed/ChatGPT-Google 的启发。该扩展程序已有 9.6k 个星标、52 个观察者和 715 个叉子。最新版本为 v2.5.5，于 2024 年 5 月 16 日发布。

**特点**
- 隐私保护: 该扩展程序强调不会收集用户数据，除非用户主动触发。用户可以通过代码审查来验证这一点。
- 多功能性: ChatGPTBox 提供了多种功能，使得与 ChatGPT 的交互变得更加便捷和多样化。
- 开源和社区驱动: 项目是开源的，鼓励社区成员的参与和贡献，并提供了详细的开发和贡献指南。
- 跨语言和跨平台支持: 扩展程序支持多种语言，并且可以在不同的浏览器和设备上使用。
- 灵活的 API 集成: 用户可以利用自定义模型模式与不同的 LLM API 集成，包括但不限于 ChatGLM、Ollama 和 openrouter.ai。
- 项目基础和灵感: ChatGPTBox 项目的开发受到了其他相关项目的启发和贡献，这表明了开源项目之间的协作和继承。
- 社区反馈和透明度: 项目欢迎用户反馈，并通过公开的问题跟踪和更新来保持透明度。

### ⭐️ [continuedev/continue](https://github.com/continuedev/continue) IDE插件 ![GitHub stars](https://img.shields.io/github/stars/continuedev/continue?style=social)
 是一个开源项目，提供了 VS Code 和 JetBrains 插件，旨在帮助开发者创建自己的模块化人工智能软件开发系统。

**摘要**
continuedev/continue 项目的 GitHub 页面展示了该项目的基本信息和操作指南。用户可以通过创建列表来组织自己星标的仓库，列表可以添加名称和描述，并且可以通过输入 : 来添加表情符号。该项目目前处于 Beta 阶段，鼓励用户提供反馈和报告错误。

项目公开了其在 GitHub 上的活动，包括 11.7k 的星标数量、742 的叉子数量，以及 62 名观察者。项目采用 Apache-2.0 许可证，并且提供了 28 个分支和 43 个标签的信息。用户可以选择在 iOS 或 Android 上接收推送通知，并且可以关注、叉子或取消星标该项目。

此外，页面提供了链接到项目的文档网站 continue.dev/docs，以及如何在 github.dev 或 Codespace 中打开项目的选项。页面还列出了项目的文件和文件夹结构，包括每个文件的最后提交信息和日期。

**特点**
- continuedev/continue 项目旨在通过提供 VS Code 和 JetBrains 插件，简化 AI 软件开发系统的创建过程。
- 项目鼓励社区参与，通过 Beta 版本的测试和反馈来改进项目。
- 提供了详细的文档和多种在线工具的集成，以便开发者能够更容易地理解和使用该项目。
- 项目的许可证为 Apache-2.0，这表明它是开源的，允许商业和非商业使用，以及修改和分发。
- 通过提供推送通知选项，项目让用户能够及时了解最新动态。
- 项目的 GitHub 页面设计直观，方便用户快速浏览项目结构和活动。


### [NaiboWang/EasySpider](https://github.com/NaiboWang/EasySpider) 爬虫框架 ![GitHub stars](https://img.shields.io/github/stars/NaiboWang/EasySpider?style=social)

**EasySpider** 是一个免费的开源可视化爬虫软件，允许用户通过图形化界面设计和执行网页数据采集任务，同时支持命令行执行，便于集成到其他系统中。
**摘要**

EasySpider 是一个基于浏览器的自动化测试和数据采集工具，它允许用户无需编写代码即可进行爬虫任务的设计和执行。用户可以通过在网页上选择内容并按照提示操作来完成任务。软件支持图形界面操作和命令行模式，适用于各种级别的用户。GitHub 上的 EasySpider 项目已经有超过 27.7k 的星标和 3.2k 的叉子，表明其在开源社区中的流行度。此外，EasySpider 还支持嵌入式执行，可以很容易地集成到其他系统中。软件的开发和维护完全依赖于作者的热情和社区的支持，因此鼓励用户通过 GitHub Sponsors、支付宝、微信或 PayPal 等方式赞助作者。EasySpider 还提供了详细的文档和视频教程，帮助用户学习如何使用软件进行数据采集。用户还可以从项目的 Examples 文件夹中下载示例任务，并将其导入到 EasySpider 中进行学习和实践。软件的使用应遵守相关法律法规，不得用于违法操作，且对于政府和军事机构网站的爬取，作者不提供答疑支持。同时，软件的商业使用需要通过邮件与作者联系获取授权。EasySpider 还提供了一个答疑 QQ 群，供用户交流和解决问题。最后，EasySpider 在学术领域也有所贡献，其相关研究成果被 The Web Conference (WWW) 2023 接受，并获得了国家知识产权局的发明专利。

**特点**

- **易用性**: EasySpider 强调其无需编码的特点，使得即使是非技术用户也能轻松设计和执行爬虫任务。
- **多功能性**: 软件不仅提供图形界面操作，还支持命令行模式，适应了不同用户的需求。
- **社区支持**: EasySpider 得到了广泛的社区支持，反映在其高星标和叉子数量上。
- **开源精神**: 作者鼓励用户通过赞助来支持软件的持续开发和维护。
- **教育资源**: 提供了丰富的文档和视频教程，帮助用户更好地理解和使用软件。
- **法律合规**: 明确提出用户在使用软件时必须遵守法律法规，尤其是针对政府和军事机构网站的爬取行为。
- **商业授权**: 对于商业使用，需要通过邮件与作者联系获取授权，保护了软件的合法商业利益。
- **学术贡献**: EasySpider 在学术界也有显著的影响，通过研究成果的发表和专利申请，展示了其在技术和学术上的创新。
- 
### [langchain-ai/langchain-nextjs-template](https://github.com/langchain-ai/langchain-nextjs-template) 构建工具 ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langchain-nextjs-template?style=social)
 是一个结合了 LangChain 和 Next.js 的起始模板，用于展示如何使用和组合 LangChain 模块以实现多种使用案例，包括简单聊天、结构化输出、解答复杂问题、增强检索等。

**摘要**
该网页是一个 GitHub 仓库，提供了一个使用 LangChain 和 Next.js 的起始模板，旨在展示如何通过 LangChain 模块组合使用来实现不同的应用场景。该模板包括以下几个示例：

简单聊天: 展示如何实现基本的聊天功能。
结构化输出: 通过 OpenAI Functions 让模型按照特定的模式返回输出。
解答复杂问题: 使用代理（agents）来回答多步骤问题。
增强检索生成（RAG）: 使用链（chains）和向量存储（vector stores）进行文档检索和生成回答。
代理增强检索: 使用代理和向量存储结合进行文档检索和回答问题。
该模板支持 Vercel 的 AI SDK，可以流式传输代币到客户端并显示传入的消息。模板还包括一个示例，展示了如何使用 Supabase 作为向量存储，并提供了如何设置数据库和使用环境变量的说明。此外，还提供了关于如何部署到 Vercel 的信息，以及如何使用 @next/bundle-analyzer 分析捆绑包的大小。最后，提供了 LangChain.js 的文档链接，以及如何联系团队的方式。

**特点**
- 易用性: 该模板旨在为开发者提供一个简单易用的起点，以便他们可以快速开始使用 LangChain 和 Next.js 构建应用程序。
- 多样性: 提供了多种使用案例的示例，展示了 LangChain 的多功能性和灵活性。
- 优化: 强调了模板的代码包大小优化，特别是 LangChain 的核心包在压缩和分割块后的大小，以适应 Vercel 的免费层边缘函数的总量限制。
- 社区和支持: 鼓励用户在遇到问题时通过 Twitter 或 Discord 与团队联系，并提供了加入 Discord 服务器的链接。
- 开源和协作: 作为一个公共模板仓库，它鼓励社区贡献和协作，同时提供了 MIT 许可证，使得代码的使用和修改具有较大的自由度。


### [slidevjs/slidev](https://github.com/slidevjs/slidev) PPT ![GitHub stars](https://img.shields.io/github/stars/slidevjs/slidev?style=social)

slidevjs/slidev 是一个为开发者设计的演示文稿工具，支持 Markdown 和 Vue 组件，并提供了多种特性和技术栈，如 Vite、Vue 3、UnoCSS 等，以及代码高亮、录制和绘图功能。

**概述**

slidevjs/slidev 是一个开源项目，旨在为开发者提供强大的演示文稿制作工具。项目使用 Vite 作为前端构建工具，结合 Vue 3 和 Markdown 语法，使得编写演示文稿既方便又强大。UnoCSS 提供了即用型的 CSS 引擎，方便样式的编写。该工具支持 Shiki 和 Monaco Editor，提供了优秀的代码高亮和即时编码功能。RecordRTC 支持演示文稿的录制和摄像头视图。此外，还集成了 VueUse 生态系列、Iconify 图标集合、Drauu 绘图工具和 KaTeX LaTeX 数学渲染等功能。项目文档支持多种语言，包括英文、中文、法语、西班牙语、俄语和葡萄牙语（巴西）。该项目由 Anthony Fu 创建和维护，遵循 MIT 许可证，并得到了多达 229 位贡献者的支持。项目拥有超过 31.5k 的星标和 1.2k 的叉子，表明其在开发者社区中的流行度。

**特点**

- **为开发者设计**: slidevjs/slidev 专为开发者提供了一个强大的演示文稿工具，支持 Markdown 和 Vue 组件的编写。
- **技术栈**: 项目采用了最新的前端技术栈，包括 Vite、Vue 3、UnoCSS 等，以确保性能和开发效率。
- **代码高亮与即时编码**: 通过集成 Shiki 和 Monaco Editor，slidev 提供了高质量的代码高亮和即时编码功能。
- **多媒体功能**: 内置的 RecordRTC 允许用户录制演示文稿和使用摄像头视图，增强了演示的互动性。
- **贡献者与社区支持**: 项目得到了大量贡献者的支持，并在 GitHub 上拥有大量的星标和叉子，反映了其在开发者社区的受欢迎程度。
- **国际化**: 项目文档支持多种语言，便于全球开发者的使用和理解。
- **开源许可**: slidevjs/slidev 遵循 MIT 许可证，鼓励开源社区的参与和贡献。
- **演示文稿制作**: 提供了一个在线演示文稿制作平台，以及本地初始化项目的方法，使得创建演示文稿变得简单快捷。
- **扩展功能**: 集成了 VueUse 生态系列、Iconify、Drauu 和 KaTeX 等工具，为演示文稿提供了额外的功能和美化效果。



### [weibocom/rill-flow](https://github.com/weibocom/rill-flow) 工作流 ![GitHub stars](https://img.shields.io/github/stars/weibocom/rill-flow?style=social)

Rill Flow 是一个高性能、可扩展的分布式工作流程编排引擎，支持大规模任务执行、分布式系统的协调调度、可视化流程编排、云原生部署以及大型语言模型（LLM）服务的快速集成。

**摘要**

Rill Flow 是一个开源的工作流程编排引擎，专为分布式工作负载和大型语言模型（LLM）设计，具备高性能和可扩展性。它能够支持每日执行数十万个任务，任务执行延迟低于 100ms，并且能够在异构的分布式系统中进行工作流程的协调和调度。Rill Flow 提供了直观的可视化流程编排工具和插件接入，方便用户使用。同时，它支持云原生的容器部署和函数编排，并且能够快速集成 LLM 模型服务。用户可以通过 GitHub 获取 Rill Flow 的源代码，并使用 Docker-Compose 在本地环境部署服务。项目的文档和中文文档都已提供，以帮助用户了解和使用 Rill Flow。此外，Rill Flow 遵循 Apache License 2.0，鼓励社区贡献。

**特点**

- **高性能与可扩展性**: Rill Flow 能够处理数十万的任务，并保持低延迟的执行。
- **分布式系统支持**: 能够在多种分布式环境中进行工作流程的编排和调度。
- **易用性**: 提供了可视化的流程编排和插件化的接入方式，简化了用户的操作流程。
- **云原生**: 支持容器化部署和云原生的函数编排，适应现代云环境的需求。
- **LLM 集成**: 能够快速集成大型语言模型服务，为工作流程编排提供强大的能力。
- **开源与社区**: 作为一个开源项目，Rill Flow 鼓励社区成员的参与和贡献，并提供了详细的文档支持。
- **许可证**: 项目采用 Apache License 2.0 许可，确保了软件的开放性和可商业化。


### [xszyou/Fay](https://github.com/xszyou/Fay) 数字人 ![GitHub stars](https://img.shields.io/github/stars/xszyou/Fay?style=social)

xszyou/Fay 项目的 `fay-sales-edition` 分支是一个开源的数字人框架，专门针对带货版本，用于构建虚拟主播、商品推销和导购等应用场景。该框架具有模块化设计，支持声音来源、语音识别、情绪分析、自然语言处理、情绪语音合成等多个模块的轻松替换。

**摘要**

xszyou/Fay 项目的 `fay-sales-edition` 分支是一个开源的数字人框架，旨在为虚拟主播、商品推销和导购等应用场景提供技术支持。该框架的模块化设计使得声音来源、语音识别、情绪分析、自然语言处理、情绪语音合成等模块之间的耦合度非常低，易于更换和定制。项目提供了详细的安装和使用说明，包括环境配置、依赖安装、应用配置和启动方法。此外，还提供了与直播平台（如抖音、B站）相关的监测源码和操作教程，以及商务QQ 和公众号等联系方式供技术交流。项目遵循 GPL-3.0 许可证，并在 GitHub 上有 8.2k 个星标和 1.7k 个叉子。

**特点**

- **模块化设计**: Fay 框架的核心优势在于其高度模块化的架构，允许用户根据需求轻松替换和定制各个功能模块。
- **多场景应用**: 该框架支持多种数字人应用场景，包括虚拟主播、商品推销、商品导购等。
- **详细的文档和支持**: 项目提供了详细的安装、配置和使用说明，以及相关的监测源码和操作教程，确保用户能够顺利部署和使用。
- **社区和交流**: 项目鼓励社区参与和交流，提供了商务QQ 和公众号等联系方式，以及微信技术交流群的加入方式。
- **开源许可**: Fay 框架遵循 GPL-3.0 许可证，促进了开源社区的贡献和分享。
- **项目活跃度**: 通过 GitHub 上的星标和叉子数量，可以看出该项目具有较高的社区关注度和活跃度。
  

### [OpenTalker/video-retalking](https://github.com/OpenTalker/video-retalking) 视频合成 ![GitHub stars](https://img.shields.io/github/stars/OpenTalker/video-retalking?style=social)
**OpenTalker/video-retalking** 是一个基于 SIGGRAPH Asia 2022 的项目，提供了一种基于音频的嘴唇同步技术，用于在野外（In the Wild）编辑说话头视频。

**摘要**

该项目托管在 GitHub 上，名为 `video-retalking`，由 OpenTalker 团队维护。项目主要用于在视频编辑中实现嘴唇同步，适用于任意音频和头部视频。项目目前有 5.8k 个星标和 853 个叉子，表明其在社区中有较高的关注度。项目遵循 Apache-2.0 许可证，并且遵循一项行为准则。项目的最新提交包括代码修正和功能更新，如修复了类型错误，以及使项目与 Mac M1 电脑兼容。项目包含文档、示例、模型、第三方库和工具，以及其他辅助文件。此外，项目还包括一个自动化脚本 `inference_videoretalking.sh`，用于快速演示和测试。

**特点**

- **项目创新性**: `video-retalking` 项目提供了一种创新的方法来解决视频编辑中的嘴唇同步问题，这在视频后期制作和人物模拟等领域非常有用。
- **社区参与**: 项目的高星标和叉子数量表明社区对该项目有很大的兴趣和参与度。
- **跨平台兼容性**: 项目的更新显示，开发者致力于提高项目的兼容性，包括支持 Mac M1 电脑，这有助于吸引更广泛的用户群体。
- **易用性**: 项目提供了详细的文档和示例，这有助于开发者和研究人员快速上手和使用该技术。
- **开源许可和行为准则**: 采用 Apache-2.0 许可证和行为准则，为项目提供了清晰的合法框架和社区规范，这有助于维护一个健康的开源环境。


### [streamlit/streamlit](https://github.com/streamlit/streamlit) 

streamlit/streamlit 仓库是一个用于快速构建和分享数据应用程序的开源工具。

**概述**

GitHub 上的 streamlit/streamlit 仓库是 Streamlit 项目的官方代码仓库，该项目旨在提供一种更快的方式来构建和分享数据应用程序。用户可以通过创建列表来组织自己星标的仓库，并为这些列表添加名称和描述，甚至可以通过输入冒号 `:` 来添加表情符号。该仓库目前处于 Beta 阶段，鼓励用户提供反馈和报告错误。

Streamlit 公共仓库提供了关注（Watch）、叉子（Fork）和取消星标（Unstar）的功能。用户可以通过 fork 仓库来创建自己的副本，并且可以选择接收 iOS 或 Android 上的推送通知。此外，仓库还包括 Apache-2.0 许可证、行为准则和安全策略。截至目前，该仓库有 32.4k 个星标、2.8k 个叉子和 316 个关注者。

最新的提交信息显示，LukasMasuch 在 2024 年 5 月 25 日移除了遗留的缓存逻辑，该更改通过拉取请求 #8737 合并到了主分支。该仓库共有 6,353 个提交，记录了项目的完整历史。

**特点**

- Streamlit 是一个开源工具，用于简化数据应用程序的开发和分享过程。
- GitHub 仓库提供了与社区互动的功能，如创建列表、星标、关注和叉子，以及反馈和错误报告。
- Streamlit 遵循 Apache-2.0 许可证，并遵循明确的行为准则和安全策略。
- 仓库的活跃性和社区参与度可以通过星标、叉子和关注者的数量来衡量。
- 项目历史和更新记录通过提交历史和最新的提交信息来展示，反映了项目的持续发展和维护。

### [BasedHardware/OpenGlass](https://github.com/BasedHardware/OpenGlass) 智能硬件 ![GitHub stars](https://img.shields.io/github/stars/BasedHardware/OpenGlass?style=social)
BasedHardware/OpenGlass 项目旨在通过使用不到 $25 的普通零件，将任何眼镜转换为可黑客的智能眼镜，功能包括生活录制、识别人物和物品、翻译文本等。

**摘要**

BasedHardware/OpenGlass 是一个开源项目，它允许用户通过集成少量低成本的电子组件，如 Seeed Studio XIAO ESP32 S3 Sense、EEMB LP502030 3.7v 250mAH 电池和3D 打印的眼镜支架壳体，将普通眼镜升级为智能眼镜。这些智能眼镜能够录制生活、识别人物和物品、翻译文本等。项目的 GitHub 仓库提供了详细的硬件和软件安装指南，包括如何使用 Arduino IDE 编程和如何配置必要的 API 密钥。用户可以通过克隆仓库并安装依赖项来开始使用，同时还可以选择购买预制的版本。OpenGlass 支持使用 Groq 和 OpenAI 的 API，并且对于 Ollama 服务，用户需要自行托管 REST API。该项目遵循 MIT 许可证，并且在 GitHub 上拥有 2k 个星标和 35 个观察者。

**特点**

- **开源智能眼镜**: OpenGlass 项目提供了一个开源解决方案，使得任何人都能通过低成本的方式制作智能眼镜。
- ** DIY 定制**: 项目鼓励 DIY 精神，提供了详细的指南和文件，让用户可以自行定制和升级他们的智能眼镜。
- **社区支持**: 项目拥有一个活跃的社区，用户可以通过 Based Hardware Discord 频道获取帮助和贡献指南。
- **技术要求**: 用户需要具备一定的技术知识，如使用 Arduino IDE 进行编程、配置 ESP32 开发板和管理 API 密钥。
- **多功能应用**: OpenGlass 支持多种功能，如生活录制、人物识别、物品识别和文本翻译，这些功能由集成的 AI 技术提供支持。
- **预制版本**: 对于不想自己组装的用户，项目计划提供有限数量的预制版本。
- **许可和参与**: 项目采用 MIT 许可证，鼓励社区成员的参与和贡献，目前已有 7 名贡献者。
- **编程语言**: 项目主要使用 C、TypeScript 和 C++ 等编程语言开发。
- **项目活跃度**: 截至目前，项目在 GitHub 上有 2k 个星标、35 个观察者和 219 个叉子，表明项目具有较高的社区兴趣和活跃度。

### [modelscope/data-juicer](https://github.com/modelscope/data-juicer) 数据处理 ![GitHub stars](https://img.shields.io/github/stars/modelscope/data-juicer?style=social)

Data-Juicer 是一个一站式的多模态数据处理系统，旨在提高数据质量，使其更适合大型语言模型（LLMs）的消化。

**摘要**

Data-Juicer 是一个专门为大型语言模型设计的一站式多模态数据处理系统，它提供了80多种核心操作符（OPs）、20多个可重用的配置食谱和20多个功能丰富的专用工具包，以支持高效的数据处理流程。该系统支持数据和模型的协同开发，包括数据反馈循环、可视化和多维度自动评估功能。Data-Juicer 优化了数据处理流程，减少了内存和CPU的使用，并支持并行处理。它提供了多种数据预处理配方，适用于预训练、微调等多种场景，并且支持多种数据格式和自定义OPs。用户可以通过命令行工具、Docker或直接从源代码安装Data-Juicer。此外，Data-Juicer 还提供了详细的文档和演示，以及一个在线播放器，让用户可以直接在浏览器中体验数据处理和可视化。

**特点**

- **系统化与可重用性**: Data-Juicer 提供了一个系统化的库，包含多种操作符和配置食谱，以及专用的工具包，这些都是为了提高数据处理的效率和质量。
- **数据反馈与沙盒环境**: 该系统支持数据和模型的协同开发，允许快速迭代和评估，帮助用户更好地理解和改进数据和模型。
- **高效的数据处理**: Data-Juicer 通过并行处理流程和内存优化，提供了高效的数据处理能力，支持多种Python版本和第三方库。
- **灵活性与扩展性**: 该系统支持多种数据格式，并允许用户自定义OPs，以实现灵活的数据处理。
- **易用性**: Data-Juicer 提供了易于理解的配置选项和全面的文档，以及演示配置和在线播放器，以便用户轻松上手。
- **社区与支持**: Data-Juicer 鼓励用户参与贡献，提供了Slack频道和DingDing群组，以促进LLM数据开发和研究的交流。
- **持续更新**: Data-Juicer 正在积极维护和更新，定期增加新功能、数据食谱和数据集。
  
### [Avdpro/ai2apps](https://github.com/Avdpro/ai2apps) 应用构建 ![GitHub stars](https://img.shields.io/github/stars/Avdpro/ai2apps?style=social)


AI2Apps 是一个旨在快速开发实用 AI 代理应用的平台，提供基于 Tab-OS 的完整的基于 Web 的可视化开发工具集，支持通过拖放操作快速构建 AI 代理项目，并直接发布为应用。

**概述**

AI2Apps 是一个专注于快速开发实用 AI 代理应用的平台。它基于 Tab-OS，提供了一套完整的基于 Web 的可视化开发工具集，允许开发者通过拖放操作快速构建自己的 AI 代理，并直接将其打包成可发布的应用。AI2Apps 支持在网页上直接使用或在本地部署，使用本地部署可以使用自己的 OpenAI Key。本平台提供了强大且易于使用的 AI 控件，支持直接将开发的 AI 代理打包成独立的 Web/移动应用，或将其集成到现有网站/应用中。AI2Apps 还提供了强大的调试功能，如断点、逐步执行和 GPT Cheat 等，以及多语言支持和更简单的产品维护方式。此外，AI2Apps 允许通过插件进行功能扩展，并计划在未来支持更多的大型语言模型（LLM）和其他类型的 AI 模型。

**特点**

- **快速原型设计**: AI2Apps 通过拖放操作绘制拓扑图迅速设计代理逻辑，自动同步代理代码，节省大量编程时间。
- **直接打包为应用**: 开发完成的 AI 代理可以直接打包成独立的 Web/移动应用，或集成到现有系统中。
- **强大的调试功能**: AI2Apps 提供了断点、逐步执行、GPT Cheat 等调试功能，有助于快速定位问题并优化代理性能。
- **更高效的用户交互**: AI2Apps 提供了多种 UI 控件，支持开发者创建与专业应用相似的交互方式。
- **本地化支持**: 利用 AI2Apps 中的 AI 功能，可以轻松地开发多语言版本的代理，提高开发效率。
- **易于维护**: AI2Apps 的“同时设计和编码”模式确保代码和设计始终同步，便于后续维护。
- **通过插件扩展功能**: AI2Apps 允许开发者根据需要创建自己的插件，扩展平台功能。
- **未来计划**: AI2Apps 计划支持更多的 LLM 模型，如 Llama-2、MPT、Falcon 和 Pythia，以及绘图和语音识别/合成的 AI 模型，并开发浏览器插件和更多文档和示例。
- 
### [Kanaries/pygwalker](https://github.com/Kanaries/pygwalker) 数据可视化 ![GitHub stars](https://img.shields.io/github/stars/Kanaries/pygwalker?style=social)

**pygwalker** 是一个开源项目，旨在通过转换 pandas 数据框架为交互式 UI，帮助用户进行数据可视化分析。

**概述**

**pygwalker** 项目的 GitHub 仓库由 Kanaries 维护，目前拥有 10.3k 的星标和 513 个叉子。项目的最新提交包括添加了一个 web 服务器模式，以及更新了 dsl_parser 的版本。项目遵循 Apache-2.0 许可证，并且提供了多种方式来关注项目的更新，包括通知设置和在 iOS 或 Android 设备上接收推送通知。此外，仓库还包含了一系列的文件夹和文件，如 `.github`、`app`、`bin`、`docs`、`examples`、`pygwalker`、`pygwalker_tools` 和 `scripts`，每个部分都有最近的提交记录和消息，展示了项目的不同方面，包括文档、示例代码、工具和测试用例。项目的开发历史可以追溯到 527 个提交，表明这是一个积极维护的项目。

**特点**

- **pygwalker** 项目通过将 pandas 数据框架转换为交互式 UI 来简化数据可视化和分析过程。
- 项目拥有活跃的社区支持，这从星标和叉子的数量以及历史提交次数中可以看出。
- 项目遵循 Apache-2.0 许可证，这为用户和开发者提供了使用和修改的灵活性。
- 通过提供不同的文件夹和文件，项目为用户和贡献者提供了详细的文档、示例和工具，以便更好地理解和使用 pygwalker。
- 项目的最新更新包括新的 web 服务器模式和 API 的添加，这表明项目正在不断进步和扩展其功能。
- GitHub 仓库提供了多种方式来关注项目动态，包括通知设置和移动设备推送通知，这有助于用户及时了解项目的最新进展。


### [e-p-armstrong/augmentoolkit](https://github.com/e-p-armstrong/augmentoolkit) 数据集构建 ![GitHub stars](https://img.shields.io/github/stars/e-p-armstrong/augmentoolkit?style=social)



`augmentoolkit` 是一个开源工具，用于将原始文本转换为高质量的领域特定的指令数据集，支持使用本地模型或多种API（如Mistral, Together.ai, Groq, OpenAI）进行数据生成，适用于不同规模的计算资源，特别适合AI SAAS初创公司创建专业的大型语言模型训练数据集。

**概述**

`augmentoolkit` 项目由 `e-p-armstrong` 在GitHub上维护，旨在通过本地模型简化数据收集过程，创建高质量的数据集。该工具支持多种开源模型API，包括Mistral、Together.ai和Groq，以及OpenAI API。它不需要高端计算机，甚至可以使用免费的API服务提供商的积分来创建数据集。`augmentoolkit` 具有异步运行的能力，可以快速生成数据集，并且支持通过YAML配置文件自定义选项，而不需要修改代码。该工具支持聊天和完成式提示，允许用户通过配置文件管理输出和原始文本输入路径，并且可以轻松切换不同的提示。项目已经进行了代码重构，以便更容易地进行自定义修改，同时提供了一个Discord社区用于讨论数据集生成。此外，`augmentoolkit` 还提供了专业的咨询服务，帮助企业根据需要定制数据集和数据生成工具。

**特点**

- **开源与便捷性**: `augmentoolkit` 是一个开源工具，旨在提供一个简单、便捷的方式来生成领域特定的数据集，无论是使用本地模型还是外部API。
- **适用性广泛**: 该工具适用于不同规模的计算资源，包括普通计算机和高性能计算机，同时也支持使用API服务。
- **成本效益**: 用户可以利用API服务提供商的免费积分来创建数据集，降低了数据生成的成本。
- **易于自定义**: 通过YAML配置文件，用户可以轻松自定义数据集生成的选项，而无需深入代码。
- **异步运行**: `augmentoolkit` 支持异步运行，使得数据集的生成过程更加高效。
- **社区支持**: 用户可以在Discord社区中获得支持，与其他用户和开发者交流使用经验和最佳实践。
- **专业咨询服务**: 对于需要定制数据集和数据生成工具的企业，`augmentoolkit` 提供了专业的咨询服务，帮助企业快速实现其目标。


### [AgentOps-AI/agentops](https://github.com/AgentOps-AI/agentops) 监控 ![GitHub stars](https://img.shields.io/github/stars/AgentOps-AI/agentops?style=social)


AgentOps-AI/agentops 是一个开源的 Python SDK，用于监控 AI 代理（agent），追踪大型语言模型（LLM）的成本，进行评估和基准测试，并与多数 LLM 和代理框架（如 CrewAI、Langchain 和 Autogen）集成。

**概述**

AgentOps-AI/agentops 是一个在 GitHub 上开源的 Python SDK，旨在帮助开发者构建、评估和监控 AI 代理。它提供了一系列工具，包括会话回放分析和调试、LLM 成本管理、代理基准测试、合规性和安全性检测以及与多个代理框架的集成。该项目支持通过 Beta Lists 功能组织和分享星标仓库列表，并且鼓励用户反馈和报告错误。项目包含多个文件夹和文件，如 `.github`、`agentops`、`docs`、`examples`、`tests` 等，每个部分都有最近的提交记录和消息。

AgentOps 提供了快速启动指南，展示了如何使用 pip 安装 agentops，并通过几行代码初始化 AgentOps 客户端、记录特定函数的执行情况，以及结束会话。它还支持与 CrewAI、Langchain、Cohere 和 LlamaIndex 等多个平台和框架的集成，并提供了相应的使用示例和文档链接。此外，AgentOps 还在路线图上规划了时间旅行调试、代理竞技场等功能，以及详细的评估和调试路线图，包括性能测试、环境测试、LLM 测试和推理测试等。

AgentOps 的使命是将 AI 代理从原型推向生产环境，它是评估、打分和测试代理的最简单方式。项目鼓励社区通过 issues 标签提出新功能请求，并承诺将其纳入未来的路线图。AgentOps 提供了 MIT 许可证和行为准则，并且在 GitHub 上有 755 颗星标和 53 个叉子，表明它在社区中有一定的关注度和参与度。

**特点**

- **监控和评估 AI 代理**: AgentOps-AI/agentops 提供了一套完整的工具，用于监控和评估 AI 代理的性能，包括会话回放分析、LLM 成本追踪和代理基准测试。
- **集成和兼容性**: 该 SDK 设计了与多个 LLM 和代理框架（如 CrewAI、Langchain 和 Autogen）的集成能力，使得开发者能够轻松地将 AgentOps 集成到现有的代理开发环境中。
- **开源和社区驱动**: AgentOps-AI/agentops 是开源项目，鼓励社区成员参与贡献，并通过 GitHub 的 issues 功能来收集用户反馈和功能请求。
- **易于使用**: 提供了详细的快速启动指南和集成示例，使得开发者能够迅速上手并将 AgentOps 应用于他们的项目中。
- **持续发展**: 项目拥有一个明确的功能发展路线图，包括即将推出的时间旅行调试、代理竞技场等功能，以及对代理代理的全面评估和调试支持。
- **关注生产环境**: AgentOps 的目标是帮助开发者将 AI 代理从实验室环境推向生产环境，确保代理在实际应用中的可靠性和效率。

### [nocobase/nocobase](https://github.com/nocobase/nocobase) 无代码 ![GitHub stars](https://img.shields.io/github/stars/nocobase/nocobase?style=social)

**NocoBase** 是一个开源的无代码/低代码平台，旨在构建企业级业务应用程序，强调可扩展性。

**概述**

**NocoBase** 是一个开源项目，提供了一个无代码/低代码的解决方案，用于构建企业级的业务应用程序。该平台注重可扩展性，适用于不同规模的企业解决方案。用户可以通过创建列表来组织自己的收藏仓库，并可以对仓库进行观察、分叉或取消收藏。目前该项目在 GitHub 上拥有超过 9.3k 的星标和 1k 的分叉，表明其在开发者社区中的相关性和普及度。NocoBase 提供了一个官方网站 `www.nocobase.com` 供用户了解更多信息。此外，项目遵循 AGPL-3.0 许可协议，并提供了安全策略。GitHub 仓库中包含了 4,970 个提交，显示了项目的活跃性和开发进度。最新的提交记录显示在 2024 年 5 月 26 日，修复了表单链接规则中数字字段显示问题。项目还包括如 `.github` 和 `.vscode` 的配置文件夹，这些文件夹包含了与项目构建和测试相关的配置。

**特点**

- **NocoBase** 是一个专注于可扩展性的无代码/低代码平台，适用于构建各种规模的企业业务应用程序。
- 项目的流行和社区支持可以通过 GitHub 上的星标和分叉数量来体现。
- 项目遵循 AGPL-3.0 许可协议，这对于用户理解如何使用和贡献代码至关重要。
- 项目的安全策略表明对于代码安全性和漏洞处理的重视。
- 项目的活跃性和持续更新反映了其维护团队的专业性和对项求的承诺。
- 最新的提交和配置文件夹展示了项目的具体技术细节和开发实践。

### [wanglin2/mind-map](https://github.com/wanglin2/mind-map) 思维导图 ![GitHub stars](https://img.shields.io/github/stars/wanglin2/mind-map?style=social)

**wanglin2/mind-map** 是一个在GitHub上开源的项目，提供了一个相对强大的Web思维导图工具，包括一个JS库和一个基于Vue2.x和ElementUI开发的Web应用，支持本地文件操作和多平台客户端下载，并提供了多种插件扩展功能。

**概述**

该项目由两部分组成：一是一个不依赖任何框架的JS思维导图库，用于快速开发Web思维导图产品；二是一个基于该库开发的Web思维导图应用，支持本地文件操作，并可以自部署和二次开发。提供了在线访问地址和多平台客户端下载。项目还提供了多种插件，如RichText、Select、Drag等，以及一些特性，如键盘导航、小地图、水印、触摸事件支持等。但也有一些特性不会实现，如自由节点和概要节点后续添加节点。项目使用MIT协议开源，欢迎star和贡献，并提供了微信交流群和请作者喝咖啡的方式以支持项目。

**特点**

- **开源项目**: wanglin2/mind-map 是一个开源项目，鼓励社区参与和贡献。
- **跨平台**: 提供了跨平台的客户端下载，支持Windows、Mac和Linux。
- **插件化**: 项目采用插件化设计，允许用户根据需求选择性引入所需插件。
- **易于使用和集成**: 提供了详细的开发文档和示例，方便开发者快速集成和使用。
- **限制的特性**: 项目明确指出不会支持自由节点和概要节点后续添加节点的特性，提醒用户在选择时考虑。
- **社区支持**: 提供了微信交流群作为技术支持和交流平台，同时也接受用户的财务支持。
- **版权和商业化**: 项目采用MIT协议，允许商业使用，但需保留版权声明，如需去除版权声明，需与作者联系。
- **持续更新**: 项目近期有更新记录，表明项目仍在积极维护和更新中。


### [aieditor-team/AiEditor](https://github.com/aieditor-team/AiEditor) 富文本 ![GitHub stars](https://img.shields.io/github/stars/aieditor-team/AiEditor?style=social)

AiEditor 是一个面向 AI 的下一代富文本编辑器，支持多种前端框架，提供丰富的文本编辑功能，适用于 PC 和移动端，并支持定制化配置。

**概述**

AiEditor 是一个基于 Web Component 的富文本编辑器，专为 AI 设计，兼容 Vue、React、Angular 和 Svelte 等前端框架。它提供了两种主题——浅色和深色，并支持 PC Web 和移动端使用。AiEditor 的功能包括基础文本编辑（如标题、段落、字体样式、超链接、代码片段等），增强功能（如撤销、重做、格式刷、清除格式、待办事项列表、背景颜色、表情、对齐、行高等），附件处理（如图片、视频和文件功能，支持多种上传方式），代码编辑（如内联代码、代码块、AI 注释和解释等），表格操作（如单元格合并与分割），Markdown 支持（如标题、引用、表格、图片、代码块等），以及 AI 相关功能（如 AI 续写、优化、校对、翻译等）。此外，AiEditor 还支持国际化（i18n）、主题切换、移动端适配、全屏编辑和提及功能。项目的快速开始指南位于其官方网站，用户可以通过 QQ 群进行交流。AiEditor 遵循 LGPL-2.1 许可证，目前有 383 颗星标、4 个观察者和 43 个分支。最新版本为 v1.0.0-rc.9，发布于 2024 年 3 月 24 日。

**特点**

- **多框架支持**: AiEditor 设计为基于 Web Component 的编辑器，因此几乎兼容所有现代前端框架。
- **丰富的编辑功能**: AiEditor 提供了包括基础文本编辑、增强功能、附件处理、代码编辑、表格操作、Markdown 支持和 AI 相关功能在内的全面编辑功能。
- **适应性强**: 编辑器支持浅色和深色主题，适用于 PC Web 和移动端，具有良好的适应性。
- **定制化配置**: 开发者可以通过 AiEditor 的灵活配置来轻松开发任何文本编辑应用程序。
- **AI 集成**: AiEditor 特别强调了 AI 功能的集成，如 AI 续写、优化、校对和翻译，以及自定义 AI 菜单和提示。
- **社区和文档支持**: 项目提供了 QQ 群作为交流平台，并在官方网站上提供了详细的文档和快速开始指南。
- **开源许可**: AiEditor 遵循 LGPL-2.1 许可证，促进了开源社区的贡献和使用。
- **项目活跃度**: 通过 GitHub 上的星标、观察者和分支数量，可以看出项目具有较高的活跃度和社区兴趣。


### [VikParuchuri/surya](https://github.com/VikParuchuri/surya) 抽取 ![GitHub stars](https://img.shields.io/github/stars/VikParuchuri/surya?style=social)


VikParuchuri/surya 是一个支持 90 多种语言的文档 OCR 工具包，提供 OCR、文本行检测、版面分析和阅读顺序检测功能。

**摘要**

VikParuchuri/surya 是一个开源的文档 OCR 工具包，能够在 90 多种语言中进行 OCR，并且在 OCR 性能、文本行检测、版面分析和阅读顺序检测方面与云服务相比具有较高的准确性和性能。该工具包支持多种文档类型，如书籍、报纸、学术论文等，并且提供了一个交互式的 Streamlit 应用程序供用户体验。

对于商业使用，surya 提供了 cc-by-nc-sa-4.0 许可证，但对于收入和资金限制的组织，可能会豁免该限制。安装 surya 需要 Python 3.9+ 和 PyTorch，并且提供了详细的使用指南和性能优化建议。用户可以通过命令行或 Python 代码来使用 surya 的不同功能，如文本识别、文本行检测、版面分析和阅读顺序检测。此外，surya 还提供了详细的基准测试结果，展示了其与其他 OCR 工具如 Tesseract 和 Google Cloud Vision 相比的优势。

开发者可以通过手动安装和运行基准测试来进一步评估 surya 的性能。surya 的训练过程使用了 NVIDIA 的 Segformer 和 Naver 的 Donut 等开源 AI 工作的贡献。

**特点**

- **OCR 性能**: surya 在 OCR 方面表现出色，与 Tesseract 和 Google Cloud Vision 相比，具有更高的文本相似性和更快的处理速度。
- **文本行检测**: surya 的文本行检测精度和召回率优于 Tesseract，且具有更快的处理速度。
- **版面分析**: surya 在 Publaynet 数据集上的版面分析表现良好，精确度和召回率均高于 90%。
- **阅读顺序**: surya 在阅读顺序检测方面达到了 75% 的平均准确率，且处理速度快。
- **性能优化**: surya 提供了多种性能优化建议，包括调整批处理大小和使用 GPU 加速等。
- **开源贡献**: surya 的开发受益于开源 AI 社区的贡献，包括 Segformer、Donut、transformers 和 CRAFT。
- **商业使用限制**: surya 的商业使用受到一定限制，但对于小型组织提供了豁免条款。
- **安装和使用**: surya 提供了详细的安装指南和使用示例，方便开发者和用户快速上手。
- **基准测试**: surya 提供了基准测试脚本，允许用户在自己的硬件上评估性能。
- **训练细节**: surya 的文本检测和识别模型通过使用多个 A6000 GPU 进行了数天到数周的训练。

###  [quickwit-oss/tantivy](https://github.com/quickwit-oss/tantivy) 搜索 ![GitHub stars](https://img.shields.io/github/stars/quickwit-oss/tantivy?style=social)

网页主要是 `quickwit-oss/tantivy` 仓库的 GitHub 页面，展示了一个名为 Tantivy 的全文搜索引擎库，它受到 Apache Lucene 的启发，并以 Rust 编程语言编写。

**概述**

`quickwit-oss/tantivy` 仓库的 GitHub 页面提供了关于 Tantivy 搜索引擎库的信息和代码。Tantivy 是一个用 Rust 编写的全文搜索引擎库，受到 Apache Lucene 的启发。页面上展示了仓库的基本信息，包括仓库的名称、描述、许可证（MIT）、星标数量（10.8k）、叉子数量（604）、关注者数量（142）、分支数量（191）、标签数量（60）以及最近的提交记录。此外，还可以在页面上进行一些操作，如创建列表、收藏仓库、关注、叉子仓库、查看通知、赞助项目等。页面还列出了仓库中的文件和文件夹，包括源代码、示例、基准测试、文档等，并显示了每个文件或文件夹的最后提交信息和日期。页面上还有一些关于如何贡献代码、报告问题和使用指南的说明。

**特点**

- **Tantivy 是一个功能强大的全文搜索引擎库，适用于 Rust 生态系统。**
- **它受到 Apache Lucene 的启发，但是使用 Rust 语言重新实现，可能提供了更好的性能和安全性。**
- **项目活跃，持续更新，有大量的贡献者和社区支持。**
- **GitHub 页面提供了详细的文档和示例，方便开发者学习和使用 Tantivy。**
- **用户可以通过 GitHub 的交互功能（如星标、叉子、关注、赞助等）参与到项目中来。**
- **仓库中的 CHANGELOG.md 文件记录了每次发布的变更，便于用户跟踪项目的进展。**
- **项目遵循 MIT 许可证，这是一个非常宽松的开源许可证，允许代码的自由使用、复制、修改、合并和发布。**
- **通过 GitHub 的议题跟踪和拉取请求功能，项目保持开放的贡献和反馈机制。**


### [VikParuchuri/surya](https://github.com/VikParuchuri/surya) 抽取 ![GitHub stars](https://img.shields.io/github/stars/VikParuchuri/surya?style=social)



是一个开源的文档OCR工具包，支持90+种语言的OCR、文本行检测、布局分析和阅读顺序检测。

**概述**

**Surya** 是一个由VikParuchuri开发的文档OCR工具，主要功能包括：

- **OCR识别**: 支持90+种语言的文本识别，性能优于云服务。
- **文本行检测**: 能够在任何语言中检测文本行。
- **布局分析**: 识别表格、图片、标题等布局元素。
- **阅读顺序检测**: 确定文档中的阅读顺序。

Surya 适用于多种类型的文档，包括书籍、报纸、学术论文等，并且提供了一个交互式的Streamlit应用程序，用于测试和演示。此外，Surya 还提供了一系列的命令行工具和Python API，以便开发者能够轻松集成到自己的项目中。

对于商业使用，Surya 提供了两种许可证选项：免费的 `cc-by-nc-sa-4.0` 许可证，适用于研究和个人使用，以及针对年收入超过500万美元或总融资超过500万美元的组织的商业许可证。

Surya 还提供了一个布局分析的API服务，当前处于测试阶段，正在进行速度优化。

安装 Surya 需要Python 3.9+和PyTorch环境，并且提供了详细的安装和使用指南。用户可以通过调整环境变量来优化性能，例如调整OCR和检测模型的批处理大小。

Surya 的性能基准测试表明，它在文本行检测、布局分析和阅读顺序检测方面与其他工具相比具有较高的精度和召回率。Surya 的训练使用了多个NVIDIA A6000 GPU进行，并且依赖于开源AI社区的多个项目。

**特点**

- **开源与免费**: Surya 是一个开源项目，鼓励研究和个人使用，同时为商业使用提供了灵活的许可选项。
- **多语言支持**: Surya 支持超过90种语言的OCR识别，覆盖了广泛的语言群体。
- **高性能**: Surya 在OCR识别、文本行检测、布局分析和阅读顺序检测等方面表现出色，且具有与云服务相当甚至更好的性能。
- **易用性**: 提供了交互式应用程序和详细的文档，使得用户能够轻松安装、使用和集成Surya。
- **性能优化**: 用户可以通过调整批处理大小等方式，根据自己的硬件配置优化Surya的性能。
- **社区支持**: Surya 的开发依赖于开源AI社区的贡献，并且鼓励社区参与讨论和改进。
- **商业模式**: 对于商业用户，Surya 提供了商业许可证选项，以支持项目的持续开发和维护。

### [360AILAB-NLP/360LayoutAnalysis](https://github.com/360AILAB-NLP/360LayoutAnalysis) 抽取 ![GitHub stars](https://img.shields.io/github/stars/360AILAB-NLP/360LayoutAnalysis?style=social)





**360AILAB-NLP/360LayoutAnalysis** 是一个开源项目，提供了一系列文档分析模型和数据集，旨在进行文档版式分析，特别是针对论文和研报的细粒度版面分析，以及相应的标签体系。

**概述**

**360LayoutAnalysis** 项目由360 AI研究院开发，旨在通过深度学习技术提高文档版式分析的准确性。该项目针对两个特定场景：论文和研报，提供了轻量化的模型权重和细粒度的数据集标注。项目使用`yolov8`进行训练和预测，能够识别文档中的段落、标题、图片、表格等元素，并区分它们的边界和类别。项目的源码遵循Apache 2.0开源许可证，商用时需要通过邮件联系申请。项目目前还没有发布版本，但已有两名贡献者参与。

**特点**

- **文档版式分析的重要性**：在数字化时代，准确的文档版式分析对于信息提取和文档理解至关重要。
- **深度学习在文档版式分析中的应用**：深度学习技术通过训练数据集，提高了对文档结构理解的能力。
- **数据集标注的重要性**：精细化的标注对于提升模型性能至关重要，尤其是对于段落的标注。
- **论文和研报场景的特殊性**：在论文和研报的版式分析中，对段落和其他布局元素的细粒度识别和区分是关键。
- **模型的优异性能**：开源的模型在封闭测试集上表现出色，能够准确识别和区分文档中的不同元素。
- **开源许可和商业使用**：项目源码和模型开源，但商业使用需要通过邮件申请，并遵守《360LayoutAnalysis模型开源模型许可证》。


### [PawanOsman/ChatGPT](https://github.com/PawanOsman/ChatGPT) 代理 ![GitHub stars](https://img.shields.io/github/stars/PawanOsman/ChatGPT?style=social)



PawanOsman/ChatGPT 项目为用户提供了一个开源的 ChatGPT（gpt-3.5-turbo）API 反向代理，允许用户免费自行托管或通过其预托管的 API 访问 OpenAI 的高级人工智能功能，无需使用 API 密钥。

**概述**

PawanOsman/ChatGPT GitHub 仓库介绍了一个免费的 ChatGPT（gpt-3.5-turbo）API 反向代理服务。该项目允许用户不使用 OpenAI API 密钥即可访问 ChatGPT 服务。项目支持多种安装方式，包括使用 Docker 或 Docker Compose 运行，也可以在个人电脑或服务器上手动安装。对于 Android 用户，还提供了通过 Termux 安装的指南。此外，项目维护者提供了一个预托管的 API 服务，用户可以通过加入项目的 Discord 社区并获取 API 密钥来免费使用。该服务兼容 OpenAI 的官方 API 端点，并支持流式响应。项目采用 AGPL-3.0 许可证，并且欢迎社区贡献。

**特点**

- **免费访问**: 项目提供了一种免费的方式来使用 ChatGPT，这对于那些不想或不能直接从 OpenAI 购买 API 密钥的用户来说是一个显著的优势。
- **易于安装和使用**: 通过支持 Docker、PC/服务器、Termux 等多种平台和环境，项目 lowered the barrier to entry，使得更多的用户能够轻松地自托管 ChatGPT API 反向代理。
- **兼容性和流式响应**: 该反向代理与 OpenAI 的官方 API 端点兼容，允许无缝集成，并且支持流式响应，使得用户可以即时接收到 AI 的响应。
- **社区支持**: 项目鼓励用户参与，提供了 Discord 社区以便用户交流和获取支持，同时也为项目提供了一个捐款途径。
- **开源许可**: 项目的开源性质（AGPL-3.0 许可证）允许用户自由地使用、修改和分发代码，促进了社区的协作与创新。
### [VikParuchuri/surya](https://github.com/VikParuchuri/surya)	![GitHub stars](https://img.shields.io/github/stars/VikParuchuri/surya?style=social)


**VikParuchuri/surya** 是一个开源的文档OCR工具包，支持90+种语言的OCR、文本行检测、版面分析和阅读顺序检测。

**概述**

**VikParuchuri/surya** 是一个位于GitHub上的公开仓库，提供了一个全面的文档OCR工具包，名为“Surya”。该工具包能够在90+种语言中进行OCR识别，并且在性能上与云服务相媲美。它还支持任意语言的文本行检测、版面分析（包括表格、图片、标题等元素检测）以及阅读顺序检测。Surya的特点是能够处理各种类型的文档，如日语、中文、印地语、阿拉伯语等多种语言的文档，以及报纸、科学论文、扫描文档、教科书等不同格式的文档。

Surya提供了多种安装和使用方式，包括命令行工具和Python库。用户可以通过设置不同的环境变量来优化性能，例如调整OCR和检测模型的批处理大小。此外，Surya还提供了一个交互式的Streamlit应用程序，允许用户直观地尝试OCR功能。

在商业使用方面，Surya的模型权重采用了`cc-by-nc-sa-4.0`许可证，但对于收入和资金限制的组织，作者提供了一些例外。同时，Surya还提供了一个托管的API服务，供用户进行OCR处理。

Surya的开发依赖于PyTorch，并且支持多种编程语言的接口。开发者可以通过GitHub手动安装Surya，以便进行二次开发或贡献。

此外，Surya还提供了一系列的基准测试结果，展示了其在OCR识别、文本行检测、版面分析和阅读顺序检测等方面的性能优于Tesseract和Google Cloud Vision等其他解决方案。

**特点**

- **OCR性能**: Surya在OCR识别方面表现出色，其平均相似度达到0.97，超过了Tesseract和Google Cloud Vision。
- **文本行检测**: Surya的文本行检测精度和召回率均优于Tesseract，且具有更快的处理速度。
- **版面分析**: Surya在版面分析方面的精度和召回率在不同类型的文档元素（如图片、表格、文本和标题）上均达到了高水平。
- **阅读顺序**: Surya在检测阅读顺序方面的平均准确率达到了75%，且处理速度快。
- **资源使用**: Surya的模型在GPU上运行时，可以通过调整批处理大小来优化VRAM的使用。
- **开源与商业使用**: Surya鼓励广泛的访问和个人使用，但对于商业使用有一定的限制。作者提供了双重许可选项，以支持项目的持续开发。
- **基准测试**: Surya的基准测试展示了其在多个方面的性能优势，并且提供了方法论和数据集信息，以便用户可以自行运行基准测试。
- **开发与贡献**: Surya依赖于开源社区的贡献，并且感谢了参与其开发的各个开源项目。

### [Dataherald/dataherald](https://github.com/Dataherald/dataherald) ![GitHub stars](https://img.shields.io/github/stars/Dataherald/dataherald?style=social)



Dataherald/dataherald 是一个开源项目，提供了一个自然语言到 SQL 的查询引擎，用于企业级关系数据库的问答系统，支持用户通过自然语言查询数据库。

**概述**

Dataherald/dataherald 项目旨在通过自然语言处理技术，将问题转换为 SQL 查询，实现对关系型数据库的直接交互。该项目的代码仓库托管在 GitHub 上，采用 Apache-2.0 许可证。项目包含四个主要组件：Engine（核心自然语言到 SQL 引擎）、Enterprise（应用 API 层）、Admin-console（前端配置和可观测性界面）和 Slackbot（允许 Slack 频道用户与 Dataherald 交互的机器人）。这些组件位于 `/services` 目录下，每个组件都有自己的 `docker-compose.yml` 文件，以便在本地运行。

用户可以通过克隆项目并设置环境变量来本地运行 Dataherald。项目鼓励社区贡献，包括新功能、基础设施改进或文档优化。Dataherald 支持多种用途，如允许业务用户直接从数据仓库获取洞察，而不需要数据分析师的帮助，或者在 SaaS 应用程序中启用对生产数据库的问答功能，以及创建基于用户专有数据的 ChatGPT 插件。

**特点**

- **自然语言到 SQL 查询**: Dataherald/dataherald 项目的核心是一个自然语言处理引擎，它能够将用户的自然语言问题转换成 SQL 查询，从而使用户能够直接通过自然语言与 SQL 数据库进行交互。
- **企业级应用**: 该项目设计用于企业级应用，提供了一个完整的解决方案，包括认证、组织和用户管理等业务逻辑。
- **前端配置和监控**: 项目包含一个管理控制台组件，提供图形用户界面，方便用户进行配置和监控。
- **集成和扩展**: Dataherald 支持与其他平台如 Slack 集成，并且可以扩展为 SaaS 应用程序的一部分，或者作为 ChatGPT 插件。
- **社区驱动和贡献**: 作为一个开源项目，Dataherald 鼓励社区成员的参与和贡献，以推动项目的发展和改进。
- **本地运行和文档**: 项目提供了详细的文档和本地运行指南，使得开发者和用户能够更容易地启动和使用 Dataherald。
- **多语言支持**: 项目主要使用 Python 和 TypeScript 编写，同时支持其他编程语言和技术栈。



### [zhayujie/chatgpt-on-wechat](https://github.com/zhayujie/chatgpt-on-wechat) 微信接入 ![GitHub Repo stars](https://img.shields.io/github/stars/zhayujie/chatgpt-on-wechat?style=social)



 基于大模型搭建的聊天机器人，同时支持 微信公众号、企业微信应用、飞书、钉钉 等接入，可选择GPT3.5/GPT-4o/GPT4.0/ Claude/文心一言/讯飞星火/通义千问/ Gemini/GLM-4/Claude/Kimi/LinkAI，能处理文本、语音和图片，访问操作系统和互联网，支持基于自有知识库进行定制企业智能客服。



**zhayujie/chatgpt-on-wechat** 项目是一个基于大模型的聊天机器人，支持微信公众号、企业微信、飞书、钉钉等多平台接入，可配置多种大模型如GPT-3.5、GPT-4、Claude等，具备处理文本、语音、图片的能力，能够访问操作系统和互联网，并支持基于自有知识库的企业智能客服定制。

**概述**

**zhayujie/chatgpt-on-wechat** 项目是一个开源的智能对话机器人，它基于大模型构建，支持多端部署，包括微信公众号、企业微信、飞书和钉钉等。项目支持多种大模型选择，如GPT-3.5、GPT-4、Claude、文心一言、讯飞星火、通义千问、Gemini、GLM-4、Kimi和LinkAI等。该机器人能够处理文本、语音和图片，并且可以通过插件访问操作系统和互联网资源。用户可以通过上传知识库文件来定制自己的企业智能客服。

项目提供了详细的文档和社区支持，用户可以通过小助手的微信加入开源项目交流群。同时，项目还提供了企业服务，LinkAI平台聚合了多模态大模型、知识库、Agent插件、工作流等能力，支持一键接入主流平台并进行管理。

项目的更新日志显示，它不断更新和优化，增加了新的模型和功能，如Kimi模型、语音识别和回复、图像处理能力等。项目还提供了快速开始的指南，包括账号注册、运行环境准备、配置和运行等步骤。此外，还支持Docker和Railway的部署方式，方便用户快速部署和使用。

**特点**

- **多平台支持**: 该项目强调了对多个聊天平台的支持，使得机器人可以广泛应用于不同的业务场景。
- **多模型选择**: 用户可以根据需求选择不同的大模型，以适应不同的应用场景和性能要求。
- **多模态交互**: 机器人不仅能够处理文本，还支持语音和图片的交互，提供了更加丰富的用户体验。
- **知识库定制**: 通过上传知识库文件，企业可以定制属于自己的智能客服，提高服务的个性化和专业化。
- **开源和社区支持**: 项目鼓励社区贡献，提供了详细的文档和交流群，以帮助用户解决问题并共享最佳实践。
- **企业服务**: LinkAI平台提供了一站式的AI应用解决方案，帮助企业更容易地整合和使用AI技术。
- **持续更新**: 项目团队致力于不断更新和改进产品，确保技术的先进性和应用的广泛性。
- **便捷部署**: 支持多种部署方式，包括本地运行、服务器部署、Docker和Railway，降低了技术门槛，使得更多用户能够快速使用该机器人。

### [lipku/metahuman-stream](https://github.com/lipku/metahuman-stream) 数字人 ![GitHub Repo stars](https://img.shields.io/github/stars/lipku/metahuman-stream?style=social)




**lipku/metahuman-stream** 项目旨在实现实时交互式数字人流媒体，支持多种数字人模型、声音克隆、多种音频特征驱动、全身视频拼接、rtmp和webrtc协议、视频编排以及大模型对话等功能。

**概述**

**lipku/metahuman-stream** 是一个开源项目，专注于实现实时交互式数字人流媒体。该项目支持多种数字人模型，包括ernerf、musetalk和wav2lip，并且支持声音克隆功能。项目利用wav2vec和hubert等音频特征驱动技术，实现了全身视频拼接，同时支持rtmp和webrtc协议，以及在数字人静默时播放自定义视频的功能。此外，该项目还支持大模型对话，可以通过LLM模型进行数字人对话，支持Chatgpt、Qwen和GeminiPro。项目提供了详细的安装指南和快速启动指南，包括如何安装依赖、运行rtmp服务器、启动数字人、设置背景图片、进行音视频特征提取和拼接等。项目还提供了Docker运行方式，方便用户快速部署和使用。最后，项目还提供了性能分析，包括帧率和延迟的测试结果，并对未来可能的改进方向进行了说明。

**特点**

- **多模型支持**: 项目支持多种数字人模型，包括ernerf、musetalk和wav2lip，满足不同需求。
- **声音克隆**: 通过gpt-sovits和xtts等技术，实现了声音克隆功能。
- **音频特征驱动**: 项目支持wav2vec和hubert等音频特征驱动，提高了音视频同步的精度。
- **全身视频拼接**: 提供了全身视频拼接的方法，使数字人的表现更加自然。
- **协议支持**: 支持rtmp和webrtc协议，确保了数字人流媒体的兼容性和低延迟。
- **视频编排**: 在数字人静默时，可以播放自定义视频，提升了用户体验。
- **大模型对话**: 通过LLM模型，实现了数字人与用户的对话功能。
- **性能优化**: 项目对帧率和延迟进行了分析，并提出了优化建议。
- **易于部署**: 提供了详细的安装和运行指南，以及Docker镜像，简化了用户的部署过程。
- **社区和协作**: 项目鼓励社区成员的参与和贡献，并提供了知识星球和微信公众号等沟通渠道。


### [TMElyralab/MuseTalk: MuseTalk](https://github.com/TMElyralab/MuseTalk)数字人 ![GitHub Repo stars](https://img.shields.io/github/stars/TMElyralab/MuseTalk?style=social)

**概述**

**MuseTalk** 是一个实时高质量的语音驱动唇形同步模型，能够对输入的音频进行编码，并在潜空间中对未见脸部进行修改，以生成与音频同步的唇部动画。



**MuseTalk** 项目由腾讯音乐娱乐的Lyra实验室开发，是一个实时高质量的语音驱动唇形同步模型，能够在每秒30帧以上的速度上在NVIDIA Tesla V100显卡上运行。该模型支持多种语言的音频输入，包括中文、英文和日文，并且可以通过调整面部区域遮罩的中心点来显著影响生成结果。MuseTalk使用了与Stable Diffusion类似的架构，但它并不是一个扩散模型，而是通过潜空间中的单步修补（inpainting）来工作。该项目还提供了一个Gradio演示，以及一个实时推理的管道，可以用于生成虚拟人物的视频。用户可以通过阅读提供的教程来安装和使用MuseTalk，该教程包括了Python环境的准备、第三方集成、安装、快速开始等内容。此外，项目还提供了模型的下载、配置文件的使用以及如何通过调整`bbox_shift`参数来获得可调节的结果。MuseTalk还可以与MuseV结合使用，以生成虚拟人物的完整解决方案。

**特点**

- **MuseTalk** 能够实现实时的高质量唇形同步，对于虚拟人物的动画生成具有重要意义。
- 该模型支持多种语言，具有较好的泛化能力。
- MuseTalk通过在潜空间中进行单步修补，而不是采用传统的扩散模型，这在技术上提供了一种新的解决方案。
- 项目提供了详细的安装和使用教程，方便用户快速上手。
- MuseTalk的实时推理能力使得其在生成虚拟人物视频方面具有高效率。
- 通过调整`bbox_shift`参数，用户可以对生成结果进行微调，以获得更好的视觉效果。
- MuseTalk与MuseV的结合，为虚拟人物的端到端生成提供了一个完整的框架。
- 项目鼓励社区的参与和贡献，同时也强调了对开源组件的感谢和对AI驱动视频生成领域的积极影响。
- 尽管MuseTalk在解决度和细节保留方面取得了进步，但仍存在一些局限性，如在保持身份特征的同时提高分辨率，以及减少单帧生成带来的抖动等问题。


### [facefusion/facefusion](https://github.com/facefusion/facefusion) 数字人 ![GitHub Repo stars](https://img.shields.io/github/stars/facefusion/facefusion?style=social)



<facefusion/facefusion 是一个开源项目，提供了下一代的面部交换和增强工具。>

**概述**

facefusion/facefusion 项目是一个在 GitHub 上公开的仓库，它提供了面部交换和增强的高级工具。项目的主页允许用户通过 GitHub Sponsors 赞助项目作者 henryruhs，并提供了外部资金链接，如 buymeacoffee.com/henryruhs 和 paypal.me/henryruhs。用户可以选择观察项目更新，或者 Fork 项目来创建自己的副本。项目拥有 16k 的星标和 2.3k 的 Fork，表明其在社区中有较高的认可度。此外，项目还提供了通过 iOS 或 Android 设备接收推送通知的选项。

项目的最新提交（57016d7）是在 2024 年 6 月 17 日，标记为 2.6.1 版本。在 .github 目录中，有关于项目的 CI 现代化、安装程序改进、依赖更新等多项更新和修复的记录。.install 目录包含了安装相关的文件，最后一次提交也是在 2024 年 6 月 17 日，标记为 2.6.1 版本。facefusion 目录包含了项目的主要代码，同样最后一次提交是在 2024 年 6 月 17 日，标记为 2.6.1 版本。tests 目录包含了项目的测试代码，最后一次提交是在 2024 年 6 月 17 日，关于跳过某些测试。此外，项目还包含了 .editorconfig 文件，用于保持代码风格的一致性，其初始提交时间未知。

**特点**

- facefusion/facefusion 项目是一个领先的面部交换和增强工具，得到了广泛的社区支持和参与。
- 项目提供了多种赞助方式，鼓励用户对项目作者 henryruhs 的工作进行资助。
- 项目的代码库经过活跃的维护和更新，包括对安装程序的改进、依赖更新和测试代码的维护。
- 项目的最新版本是 2.6.1，在 2024 年 6 月发布，显示了项目的持续发展和迭代。
- 通过提供通知设置和外部链接，项目增强了用户参与度和社区互动。