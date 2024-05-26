# Awesome-AGI

欢迎来到 **Awesome-AGI**，这是一个精心整理的人工通用智能（AGI）项目和资源列表。

觉得有用请点个 Star 吧！

## 目录

- [Awesome-AGI](#awesome-agi)
	- [目录](#目录)
	- [简介](#简介)
	- [应用项目](#应用项目)
		- [lobehub/lobe-chat ](#lobehublobe-chat-)
		- [QAnything ](#qanything-)
		- [open-webui/open-webui ](#open-webuiopen-webui-)
		- [QuivrHQ/quivr ](#quivrhqquivr-)
		- [rashadphz/farfalle 搜索 ](#rashadphzfarfalle-搜索-)
		- [truefoundry/cognita ](#truefoundrycognita-)
		- [toeverything/AFFiNE ](#toeverythingaffine-)
		- [rashadphz/farfalle ](#rashadphzfarfalle-)
		- [weaviate/Verba ](#weaviateverba-)
		- [vercel/ai-chatbot ](#vercelai-chatbot-)
		- [Bin-Huang/chatbox 客户端 ](#bin-huangchatbox-客户端-)
		- [mckaywrigley/chatbot-ui ](#mckaywrigleychatbot-ui-)
		- [langflow-ai/langflow ](#langflow-ailangflow-)
		- [Mintplex-Labs/anything-llm 客户端 ](#mintplex-labsanything-llm-客户端-)
		- [dissorial/doc-chatbot ](#dissorialdoc-chatbot-)
		- [wandb/openui 代码生成 ](#wandbopenui-代码生成-)
		- [⭐️ OpenDevin/OpenDevin 代码生成 ](#️-opendevinopendevin-代码生成-)
		- [stitionai/devika 代码生成 ](#stitionaidevika-代码生成-)
		- [OpenBMB/ChatDev代码生成 ](#openbmbchatdev代码生成-)
		- [khoj-ai/khoj AI助手 ](#khoj-aikhoj-ai助手-)
		- [weaviate/Verba ](#weaviateverba--1)
		- [stanford-oval/storm 报告 ](#stanford-ovalstorm-报告-)
	- [服务项目](#服务项目)
		- [ollama ](#ollama-)
		- [janhq/jan](#janhqjan)
		- [modelscope/swift  训练模型 ](#modelscopeswift--训练模型-)
		- [modelscope/DashInfer 推理 ](#modelscopedashinfer-推理-)
		- [unslothai/unsloth 微调 ](#unslothaiunsloth-微调-)
	- [多模态](#多模态)
		- [alibaba-damo-academy/FunClip视频剪辑 ](#alibaba-damo-academyfunclip视频剪辑-)
		- [MoneyPrinterTurbo 视频合成](#moneyprinterturbo-视频合成)
	- [智能体](#智能体)
		- [microsoft/autogen ](#microsoftautogen-)
		- [lobehub/lobe-chat-agents ](#lobehublobe-chat-agents-)
		- [cpacker/MemGPT ](#cpackermemgpt-)
		- [AgentScope/modelscope  ](#agentscopemodelscope--)
		- [joaomdmoura/crewAI ](#joaomdmouracrewai-)
		- [jgravelle/AutoGroq ](#jgravelleautogroq-)
	- [工具](#工具)
		- [run-llama/create-llama 构建 ](#run-llamacreate-llama-构建-)
		- [AutomaApp/automa 工具 ](#automaappautoma-工具-)
		- [CopilotKit/CopilotKit 交互 ](#copilotkitcopilotkit-交互-)
		- [szkane/PopclipGemini 交互 ](#szkanepopclipgemini-交互-)
		- [mendableai/firecrawl 抽取 ](#mendableaifirecrawl-抽取-)
		- [mendableai/firecrawl-py 抽取 ](#mendableaifirecrawl-py-抽取-)
		- [josStorer/chatGPTBox 浏览器插件 ](#josstorerchatgptbox-浏览器插件-)
		- [⭐️ continuedev/continue IDE插件 ](#️-continuedevcontinue-ide插件-)
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
	- [算法](#算法)
		- [naklecha/llama3-from-scratch ](#naklechallama3-from-scratch-)
	- [研究论文](#研究论文)
	- [教程和课程](#教程和课程)
	- [社区和会议](#社区和会议)

## 简介



人工通用智能（AGI）旨在创建能够执行任何人类可以进行的智力任务的智能代理。该仓库致力于收集和展示最有前景的 AGI 项目、研究、工具和资源。

## 应用项目

### [lobehub/lobe-chat](https://github.com/lobehub/lobe-chat) ![GitHub Repo stars](https://img.shields.io/github/stars/lobehub/lobe-chat?style=social)

 是一个开源的现代设计 LLMs/AI 聊天框架，支持多个 AI 提供商（如 OpenAI、Claude 3、Gemini 等）、多模态（视觉 / TTS）和插件系统，提供了一键免费部署私人 ChatGPT 聊天应用的功能。

**摘要**
lobehub/lobe-chat 项目是一个开放源码的现代设计的大型语言模型（LLMs）和 AI 聊天框架，它支持多种 AI 服务提供商，包括但不限于 OpenAI、Claude 3、Gemini、Ollama、Bedrock、Azure、Mistral 和 Perplexity。该框架还支持多模态功能，如视觉和语音合成（TTS），并且具备插件系统，允许用户扩展功能。此外，该项目提供了一键部署功能，使用户能够快速搭建和部署自己的私人 ChatGPT 聊天应用。

项目的 GitHub 页面提供了多种互动选项，包括关注、不再关注、加入收藏列表（目前处于测试阶段）、分享反馈和报告滥用行为。用户可以通过 GitHub Sponsors 或外部链接（如 Open Collective 和 IssueHunt）为项目提供资金支持。项目使用 MIT 许可证，并遵循行为准则。

项目的代码库包括了多个文件夹和文件，如 .github（用于 GitHub 特定配置）、.husky（用于 Git 钩子）、__mocks__（用于测试模拟）、contributing（用于贡献指南）、docs（用于文档）、locales（用于本地化）、public（用于公共资源）、scripts（用于脚本）、src（用于源代码）、tests（用于测试代码），以及配置文件如 .bunfig.toml、.changelogrc.js、.commitlintrc.js、.dockerignore、.editorconfig、.env.example、.eslintignore、.eslintrc.js 和 .gitignore。

项目的提交历史显示了持续的更新和维护，包括特性添加、代码修复、样式调整、测试添加、文档更新等。例如，最近的更新包括了对代码块显示问题的修复、对服务接口的重构、对多语言标签弹出窗口样式的更新等。

**特点**
- 开源和现代设计: lobehub/lobe-chat 强调了其开源性质和现代化的设计理念，旨在为用户提供一个易于使用和扩展的 AI 聊天框架。
- 多 AI 提供商支持: 该框架的一个关键特点是其对多个 AI 服务提供商的支持，这使得用户可以根据自己的需求选择合适的 AI 服务。
- 多模态和插件系统: 项目支持多模态交互，包括视觉和语音合成，同时提供了插件系统，以便用户可以自定义和增强框架的功能。
-  一键部署: 提供了一键部署功能，简化了用户搭建私人 ChatGPT 聊天应用的过程。
- 持续更新和维护: 通过提交历史和文件更新记录，可以看出项目团队对于持续改进和维护项目的承诺。
- 社区参与和支持: 项目鼓励社区参与，提供了多种方式让用户和开发者参与到项目中，包括贡献代码、报告问题、提供资金支持等。
- 文档和配置完善: 项目提供了详细的文档和配置文件，以帮助用户理解和使用框架。


### [QAnything](https://github.com/QAnything/QAnything) ![](https://img.shields.io/github/stars/QAnything/QAnything?style=social)
 是一个支持多种文件格式和数据库的本地知识库问答系统，可以断网使用，具备数据安全、跨语种问答、海量数据处理、高性能和易用性等特点。

**摘要**

QAnything 项目是一个基于任意格式文件或数据库的本地知识库问答系统，名为 QAnything（Question and Answer based on Anything），它允许用户将任何格式的本地文件导入，并提供准确、快速的问答服务。该系统支持多种文件格式，包括 PDF、Word、PPT、XLS、Markdown、电子邮件、TXT、图片、CSV 和网页链接等。

QAnything 的特点包括数据安全，支持全程拔网线安装使用；跨语种问答，无所谓文件是什么语种；支持海量数据问答，采用两阶段向量排序解决大规模数据检索退化问题；高性能生产级系统，适合企业应用；易用性，无需繁琐的配置，一键安装部署；支持选择多知识库问答。

该系统采用两阶段检索架构，使用 BCEmbedding 检索组件，具备强大的双语和跨语种能力。一阶段检索使用 embedding 模型，二阶段检索使用 rerank 模型，两者的评测结果显示 QAnything 的模型在多项指标上表现出色。

QAnything 的最新更新包括支持与 OpenAI API 兼容的其他 LLM 服务，提供优化后的 PDF 解析器，以及支持联网检索、FAQ、自定义 BOT、文件溯源等功能。项目提供了两种安装方式：python 版本和 docker 版本，适用于不同的使用场景和环境。

项目还提供了详细的安装文档、API 支持、常见问题解答、路线图、交流支持渠道等。QAnything 依照 Apache 2.0 协议开源，并欢迎社区的贡献。

**特点**

- 数据安全与隐私保护: QAnything 强调数据安全，支持断网安装和使用，确保用户数据不会泄露到外网。
- 跨语种问答能力: 系统支持中英文问答，能够处理不同语言的文件，无需用户区分语种。
- 海量数据处理: 通过两阶段检索机制，QAnything 能够有效处理大量数据的问答，保证检索效率和准确性不会因数据量增加而退化。
- 高性能与生产级应用: 该系统设计为高性能的生产级解决方案，可以直接部署到企业环境中。
- 易用性: QAnything 注重用户体验，提供了一键安装部署的便捷操作，减少了配置的复杂性。
- 多知识库支持: 用户可以选择多个知识库进行问答，增强了系统的灵活性和适用性。
- 开源与社区贡献: QAnything 作为一个开源项目，鼓励社区成员的参与和贡献，并提供了详细的文档和支持渠道。
- 持续更新与迭代: 项目团队致力于不断更新和改进系统，包括支持新的文件格式、优化问答效果、增加新功能等。

### [open-webui/open-webui](https://github.com/open-webui/open-webui) ![GitHub stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social)
 是一个用户友好的自托管 WebUI，支持多种大型语言模型（LLMs）运行器，包括 Ollama 和 OpenAI 兼容的 API。

**摘要**

open-webui/open-webui 项目是一个开源的 Web 界面，旨在提供一个易于使用、功能丰富且完全可以离线运行的平台。该项目曾名为 Ollama WebUI，现在更名为 Open WebUI，支持多种 LLMs 运行器，并提供了详细的文档和安装指南。用户可以通过 Docker 快速启动，支持 GPU 加速和 OpenAI API 的使用。项目还提供了一个社区版本，用户可以在其中分享和探索定制化的 Modelfiles。此外，项目还鼓励社区成员通过赞助和反馈来支持项目的发展。

**特点**

- 用户友好性: Open WebUI 设计了一个直观的界面，使得用户可以轻松地安装和使用。
- 离线运行: 该 WebUI 支持完全离线操作，适合对隐私和安全性有高要求的环境。
- 多运行器支持: 项目支持 Ollama 和 OpenAI 兼容的 API，提供了灵活性，以适应不同的用户需求。
- 社区驱动: 项目鼓励社区参与，提供了一个平台让用户可以分享自己的 Modelfiles，同时也接受赞助来支持项目的持续发展。
- 文档和支持: 项目提供了详细的安装文档、使用指南和故障排除信息，以帮助用户解决安装和使用过程中遇到的问题。
- 更新和维护: 项目提供了更新指南，帮助用户保持其 Docker 安装的最新状态。
- 迁移指南: 为了帮助从 Ollama WebUI 迁移到 Open WebUI，项目提供了迁移指南。
- 开发路线图: 项目在其文档中提供了未来功能的发展路线图，让用户了解即将推出的新特性。


### [QuivrHQ/quivr](https://github.com/QuivrHQ/quivr) ![](https://img.shields.io/github/stars/QuivrHQ/quivr?style=social)


QuivrHQ/quivr 是一个基于生成式人工智能（GenAI）的个人生产力助手，旨在作为一个第二大脑，帮助用户通过与文档（如 PDF、CSV 等）和应用程序的对话来组织和管理信息。它支持多种语言模型，如 Langchain、GPT 3.5/4 turbo、Anthropic、VertexAI、Ollama 和 Groq，并提供了一个本地和私有的替代方案，以此来替代 OpenAI 的 GPT 和 ChatGPT。

**摘要**

QuivrHQ/quivr 项目的 GitHub 页面提供了关于该项目的详细信息，包括它是如何作为一个个人生产力助手，利用检索增强生成（RAG）技术来帮助用户管理和查询信息。用户可以通过创建列表来组织自己的收藏仓库，并为列表添加名称和描述。该项目目前处于测试阶段，鼓励用户分享反馈和报告错误。

该项目使用 Apache-2.0 许可证，已经获得了 33.4k 的星标和 3.3k 的叉子。用户可以通过关注项目来接收推送通知，或者选择将项目的副本存储在自己的账户中。GitHub 页面还提供了项目的历史记录，包括最新的提交信息和日期，以及项目的文件和文件夹结构。

该项目的最新提交包括更新 AWS 服务的任务定义文件中的 CPU 和内存设置，以及更新开发容器配置文件。这些更新旨在提高项目的性能和资源利用率。

**特点**

- **本地和私有的 AI 助手**: QuivrHQ/quivr 提供了一个本地和私有的 AI 助手，这为用户提供了更高的数据隐私和安全性。
- **多语言模型支持**: 项目支持多种语言模型，包括但不限于 GPT 3.5/4 turbo、Anthropic、VertexAI 等，这使得用户可以根据自己的需求选择合适的语言模型。
- **检索增强生成技术**: Quivr 使用了 RAG 技术，这种技术结合了检索系统和生成模型，以提供更准确和相关的信息响应。
- **用户参与和反馈**: 项目鼓励用户参与测试，并提供反馈和错误报告，这有助于项目的持续改进和完善。
- **资源优化**: 通过增加 CPU 和内存资源的分配，项目提升了 AWS 服务的性能，这对于处理大型工作负载至关重要。
- **开发环境的便捷性**: 通过更新 `.devcontainer` 文件，项目提供了一个预配置的开发环境，这简化了开发者的设置过程，并确保了一致性的开发环境。

### [rashadphz/farfalle](https://github.com/rashadphz/farfalle) 搜索 ![GitHub stars](https://img.shields.io/github/stars/rashadphz/farfalle?style=social)

`rashadphz/farfalle` 是一个开源的 AI 搜索引擎项目，允许用户通过本地或云端的大型语言模型（LLMs）进行搜索和问题回答。

**概述**

`rashadphz/farfalle` 项目是一个类似 Perplexity 的 AI 搜索引擎，支持使用本地或云端的大型语言模型（如 llama3、gemma、mistral、phi3、Groq/Llama3、OpenAI/gpt4-o）来进行搜索和问题回答。项目的前端采用 Next.js，后端使用 FastAPI，搜索 API 可以选择 SearXNG 或 Tavily，日志管理使用 Logfire，限流采用 Redis，UI 组件使用 shadcn/ui。

项目提供了一个实时演示（farfalle.dev），展示了使用云端模型的搜索引擎功能。此外，项目还有一个技术路线图，计划添加对本地 LLMs 的支持，设置 Docker 部署，整合 Searxng 以及与 LiteLLM 协作。

要在本地启动和使用该项目，用户需要安装 Docker 和 Ollama，并且可能需要获取 Tavily、OpenAI 或 Groq 的 API 密钥。接下来，用户需要克隆仓库、配置环境变量、运行 Docker Compose 以及按照自定义设置指南进行操作。

部署时，用户需要将后端部署到 Render 并获取 Web 服务 URL，然后在 Vercel 上部署前端时使用该 URL。项目还提供了指导，教用户如何将 Farfalle 设置为默认搜索引擎。

该项目目前有 1.3k 个星标、10 个关注者和 97 个叉子。项目使用 Apache-2.0 许可证，并且还没有发布正式版本。项目的主要贡献者是 rashadphz 和 arsaboo。

**特点**

- **开源 AI 搜索引擎**: `rashadphz/farfalle` 是一个开源项目，旨在为用户提供一个由 AI 驱动的搜索引擎，可以使用本地或云端的大型语言模型进行搜索和问题解答。
- **技术栈**: 项目采用了现代化的技术栈，包括 Next.js、FastAPI、SearXNG/Tavily、Logfire 和 Redis，以及 shadcn/ui 组件库。
- **本地与云端模型支持**: 用户可以选择使用本地的大型语言模型或者云端服务进行搜索，提供了灵活的部署选项。
- **易于部署与使用**: 项目提供了详细的文档和步骤指南，使得用户能够容易地在本地或云端部署和使用搜索引擎。
- **定制化设置**: 项目支持自定义设置，包括配置不同的搜索提供商和环境变量，以及提供自定义部署指南。
- **社区与协作**: 项目鼓励社区参与和贡献，提供了问题跟踪和讨论平台，同时也展示了项目的贡献者列表。
- **许可与版本**: 项目遵循 Apache-2.0 许可证，并且还没有正式发布版本，表明项目可能仍在积极开发中。

### [truefoundry/cognita](https://github.com/truefoundry/cognita) ![GitHub stars](https://img.shields.io/github/stars/truefoundry/cognita?style=social)

`truefoundry/cognita` 是一个开源的 RAG（Retrieval Augmented Generation）框架，旨在帮助开发者构建模块化、可扩展的生产级应用程序。

**概述**

`truefoundry/cognita` 是由 TrueFoundry 开发的一个 RAG 框架，用于在生产环境中构建开源的、模块化的应用程序。该框架使用 Langchain/LlamaIndex 提供的抽象，使得在 Jupyter 笔记本上进行快速实验和原型设计变得容易，同时也支持在本地环境中轻松使用，并提供了一个无需编码的 UI 支持。Cognita 支持增量索引，并且具有模块化的组件结构，包括数据源、元数据存储、LLM Gateway、向量数据库（Vector DB）和索引作业等。用户可以通过本地运行或使用 TrueFoundry 的部署来体验 Cognita，并且可以通过自定义查询控制器（Query Controller）来实现问答系统。Cognita 的代码结构清晰，允许用户自定义数据加载器、嵌入模型、解析器和向量数据库等组件，以适应特定的使用场景。此外，Cognita 还支持多种文档检索器、嵌入模型、重排器以及增量索引功能。

**特点**

- **模块化和可扩展性**: Cognita 提供了一个组织良好的代码库，其中包含了可重用的解析器、加载器、嵌入模型和检索器，使得代码库易于测试和部署。
- **用户友好的 UI**: 非技术用户可以通过 UI 上传文档并执行问答任务，同时也支持 API 驱动，允许与其他系统集成。
- **生产就绪环境**: Cognita 支持本地设置和生产环境部署，提供了一个 FastAPI 服务器来处理用户查询并生成答案。
- **灵活的自定义选项**: 用户可以根据自己的需求自定义数据加载器、嵌入模型、解析器和向量数据库等组件。
- **增量索引**: Cognita 支持对文档进行增量索引，减少了计算负担，并且能够跟踪已索引的文档，防止重复索引。
- **问答系统**: 通过查询控制器，Cognita 能够处理用户的问题，并使用 LLM 模型生成答案，同时还可以选择性地丰富相关文档的元数据。
- **开源贡献**: Cognita 鼓励开源贡献，并提供了详细的文档和指南，帮助开发者参与到项目中来。

### [toeverything/AFFiNE](https://github.com/toeverything/AFFiNE.git) ![GitHub stars](https://img.shields.io/github/stars/toeverything/AFFiNE?style=social)
 是一个开源的下一代知识库，它结合了规划、分类和创作功能，注重隐私，高度可定制，并且已经准备好使用。

**摘要**
AFFiNE（发音为 [ə‘fain]）是一个开源的下一代知识库，它旨在超越 Notion 和 Miro。它提供了创建列表的功能，用于组织用户的星标仓库，允许用户为列表添加名称和描述，并通过输入冒号来添加表情符号。该项目目前处于测试阶段，鼓励用户提供反馈和报告错误。AFFiNE 还提供了通过 GitHub Sponsors 为项目提供资金的方式，以及通过 Fork 机制复制项目的选项。此外，AFFiNE 还提供了通知设置，用户可以在 iOS 或 Android 上接收推送通知。项目遵循 MIT 许可证，并有一项安全策略和行为准则。截至目前，AFFiNE 拥有 34.1k 的星标和 2.2k 的分支，以及 188 名观察者。项目还提供了通过 GitHub Codespaces 直接在浏览器中编辑代码的功能。

**特点**
- AFFiNE 定位为下一代知识库，旨在提供比现有工具如 Notion 和 Miro 更多的功能。
- 项目强调隐私优先，并且是开源的，鼓励社区参与和改进。
- 可定制性是 AFFiNE 的一个重要特点，用户可以根据自己的需求进行调整。
- AFFiNE 支持通知功能，用户可以在移动设备上接收推送通知。
- 项目采用MIT 许可证，保证了代码的开放性和可复用性。
- AFFiNE 提供了行为准则和安全策略，确保了项目的健康社区环境。
- 项目的受欢迎程度可以从其在 GitHub 上的星标和分支数量中看出。
- 通过GitHub Sponsors，用户可以为 AFFiNE 项目提供资金支持。
- GitHub Codespaces的集成，允许用户在云端环境中直接编辑和运行项目代码。

### [rashadphz/farfalle](https://github.com/rashadphz/farfalle) ![GitHub stars](https://img.shields.io/github/stars/rashadphz/farfalle?style=social)

 是一个开源的 AI 搜索引擎项目，支持使用本地 LLM（如 llama3、gemma、mistral、phi3）或云端模型（如 Groq/Llama3、OpenAI/gpt4-o）进行搜索和问题回答。

**摘要**
rashadphz/farfalle 项目是一个类似 Perplexity 的 AI 搜索引擎，允许用户通过本地或云端的大型语言模型（LLM）进行搜索。项目的技术栈包括前端使用 Next.js、后端使用 FastAPI、搜索 API 可选择 SearXNG 或 Tavily、使用 Logfire 进行日志记录以及 Redis 进行速率限制。项目支持多种搜索提供商和本地模型，同时提供了 Docker 部署的支持和设置指南。用户可以通过克隆仓库、配置环境变量、运行 Docker 容器来本地启动项目，并可以通过 Vercel 部署前端。项目还提供了如何将 Farfalle 设置为默认搜索引擎的说明。

**特点**
- 开源 AI 搜索引擎: rashadphz/farfalle 是一个开源项目，旨在提供一个 AI 驱动的搜索引擎，可以使用本地或云端的 LLM 进行搜索和问题解答。
- 支持多种 LLM: 项目支持多种本地和云端的大型语言模型，包括但不限于 llama3、gemma、mistral、phi3、Groq/Llama3、OpenAI/gpt4-o。
- 技术栈: 前端采用 Next.js，后端使用 FastAPI，搜索 API 可以选择 SearXNG 或 Tavily，同时使用 Logfire 进行日志记录和 Redis 进行速率限制。
- 部署和使用: 提供了详细的本地部署指南和云端部署说明，包括环境变量配置、Docker 容器运行等步骤。
- 搜索引擎集成: 用户可以将 Farfalle 设置为浏览器的默认搜索引擎，以便更方便地使用。
- 社区参与: 项目鼓励社区参与，提供了如何贡献代码和报告问题的指南。
- 项目活跃度: 项目在 GitHub 上有较高的星标和叉子数量，表明社区对其有一定的兴趣和参与度。
- 编程语言: 项目主要使用 TypeScript 和 Python 编写，同时也包含了 CSS 和 JavaScript。



### [weaviate/Verba](https://github.com/weaviate/Verba) ![GitHub stars](https://img.shields.io/github/stars/weaviate/Verba?style=social)

 是一个开源的 Retrieval Augmented Generation (RAG) 聊天机器人，由 Weaviate 支持，它提供了一个端到端的用户友好型界面，允许用户通过本地的 HuggingFace 和 Ollama，或者通过云服务提供商如 OpenAI、Cohere 和 Google 等轻松探索数据集并提取洞察。

**摘要**

Verba 是一个基于 Weaviate 的开源项目，它实现了一个基于 RAG 的聊天机器人，用户可以通过该机器人与数据进行交互，并从中提取信息。该项目支持多种模型和数据格式，包括 PDF 和 CSV/XLSX 文件，并且可以通过多种方式部署，包括直接安装、源代码构建或使用 Docker。Verba 支持的功能包括混合搜索、语义缓存、自动完成建议等，同时也提供了 API 密钥配置说明，以及如何通过 pip 部署 Verba。项目鼓励社区贡献，并提供了详细的技术和前端文档。

**特点**

- 模型和数据支持: Verba 支持多种 LLM 提供商的模型，如 OpenAI、Cohere、Google 和 HuggingFace，同时也支持不同类型的数据导入，包括 PDF 和 CSV/XLSX 文件。
- 部署灵活性: Verba 提供了多种部署方式，以适应不同的用户需求和环境，包括本地部署和云服务。
- 功能和特性: Verba 提供了诸如混合搜索、语义缓存和自动完成等高级功能，同时正在计划实现更多功能，如过滤、高级查询和结果重新排序。
- 开源和社区参与: Verba 鼓励开源贡献，并提供了详细的文档和社区支持，以帮助用户理解项目架构并参与到项目中。
- 配置和使用: 项目提供了详细的 API 密钥配置指南，以及通过 pip、源代码或 Docker 部署 Verba 的步骤说明。
- 已知问题和常见问题: 项目已经列出了一些已知问题，并提供了常见问题的解答，以帮助用户解决可能遇到的问题。


### [vercel/ai-chatbot](https://github.com/vercel/ai-chatbot) ![GitHub stars](https://img.shields.io/github/stars/vercel/ai-chatbot?style=social)

 的 AI 聊天机器人项目可以在本地环境中运行。

**摘要**
Vercel 的 AI 聊天机器人项目是一个基于 Next.js 构建的、功能全面且可定制的聊天机器人。对于开发者来说，项目提供了在本地环境中运行和测试的说明。这些指令通常包括克隆仓库、安装依赖、配置环境变量以及启动开发服务器等步骤。通过在本地运行，开发者可以更容易地理解项目结构，调试代码，以及进行个性化的开发。

**特点**
- 本地运行是开发和测试 AI 聊天机器人的重要步骤：开发者可以在不影响生产环境的情况下进行实验和迭代。
- 项目易于启动和配置：通过遵循文档中的步骤，开发者可以快速地在本地环境中搭建起整个聊天机器人系统。
- 本地环境的使用有助于提高开发效率：开发者可以即时看到代码变更的效果，便于调试和优化。
- 项目的可定制性：提供在本地运行的能力使得开发者能够根据自己的需求对聊天机器人进行定制和扩展。

### [Bin-Huang/chatbox](https://github.com/Bin-Huang/chatbox) 客户端 ![GitHub stars](https://img.shields.io/github/stars/Bin-Huang/chatbox?style=social)


Bin-Huang/chatbox 是一个用户友好的桌面客户端应用程序，用于与 AI 模型/大型语言模型（如 GPT、Claude、Gemini、Ollama 等）交互，支持 Windows、Mac 和 Linux 系统。

**概述**

Bin-Huang/chatbox 是一个开源项目，旨在提供一个简单易用的桌面客户端，用于与多种 AI 模型和大型语言模型进行交互。该项目支持多种操作系统，包括 Windows、MacOS 和 Linux。用户可以通过下载相应的安装包进行安装，并且还可以在 iOS 和 Android 设备上使用。项目的特点包括易用性、多平台支持以及社区驱动的持续开发和改进。项目创建者 Bin-Huang 最初是为了调试提示而开发 Chatbox，随着社区的反馈和贡献，该项目已经发展成为一个功能丰富的 AI 桌面应用程序，被用户用于各种场景，如日常聊天、专业工作辅助等。

项目的贡献方式包括提交问题、拉取请求、功能请求、错误报告、文档修订、翻译和其他形式的贡献。项目的构建指南、常见问题解答（FAQ）、支付方式（包括 Paypal、微信支付和支付宝）以及许可证信息（GPL-3.0）都在项目的 GitHub 页面上提供。此外，项目还提供了一个星标历史记录，以及通过 GitHub Releases 页面提供的所有版本的下载链接。截至目前，该项目有 19k 个星标、121 个关注者和 1.9k 个叉子。

**特点**

- **用户友好性**: Chatbox 旨在提供一个简单易用的界面，让用户能够轻松地与 AI 模型交互。
- **多平台支持**: 提供了针对 Windows、MacOS 和 Linux 的安装包，以及 iOS 和 Android 的支持。
- **社区驱动**: 项目的发展和改进依赖于社区的反馈和贡献。
- **开源精神**: Chatbox 是一个开源项目，鼓励各种形式的贡献，包括代码、文档和翻译等。
- **持续更新**: 项目定期发布新版本，并提供了一个详细的版本历史记录。
- **多功能性**: Chatbox 不仅可以用于开发和调试提示，还可以用于日常聊天和专业工作辅助。
- **支付方式**: 提供了多种支付方式以支持项目的发展，包括 Paypal、微信支付和支付宝。
- **许可证**: Chatbox 采用 GPL-3.0 许可证，确保了软件的自由传播和修改。


### [mckaywrigley/chatbot-ui](https://github.com/mckaywrigley/chatbot-ui) ![GitHub stars](https://img.shields.io/github/stars/mckaywrigley/chatbot-ui?style=social)
 是一个开源项目，旨在为每个 AI 模型提供聊天界面。

**摘要**

mckaywrigley/chatbot-ui 项目的 GitHub 页面展示了该项目的基本信息和代码仓库结构。该项目已有 26.8k 的星标和 7.4k 的叉子，有 243 名用户在关注该项目的变化。项目的最新提交是在 2024 年 5 月 16 日，提交内容包括修复图片 URL 参数问题。项目包含多个文件夹和文件，如 .github、 .husky、 __tests__、 app、 components、 context、 db、 lib、 public、 supabase、 types 和 worker 等，每个部分都有自己的功能和提交记录。例如，.husky 文件夹用于存储 API 密钥，components 文件夹包含项目的组件文件，而 public 文件夹包含项目的公共资源。项目还包括环境变量示例文件 .env.local.example、代码规范配置文件 .eslintrc.json、忽略文件配置 .gitignore、Node 版本管理文件 .nvmrc 和项目的 README 文件 README.md。此外，还有一个 components.json 文件用于组件配置，以及一个 i18nConfig.js 文件用于国际化配置。

**特点**
- 开源项目: mckaywrigley/chatbot-ui 是一个公开的、可以被社区成员免费使用和贡献的项目。
- 社区活跃度: 项目拥有大量的星标和叉子，以及活跃的关注者和贡献者，反映了该项目在 GitHub 上的高人气和活跃度。
- 持续更新: 项目经常接受新的提交和更新，表明项目维护者对其进行持续的维护和改进。
- 功能丰富: 项目包含多个组件和文件夹，涵盖了从前端到后端的各个方面，提供了一个完整的聊天界面解决方案。
- 跨平台支持: 项目支持跨平台功能，例如通过 iOS 或 Android 设备接收推送通知。
- 用户反馈和报告: 项目鼓励用户提供反馈和报告问题，这有助于改进项目并提高其质量。
- 环境配置: 通过 .env.local.example 文件提供了环境变量的示例，方便用户配置和部署项目。
- 代码规范: 项目使用 .eslintrc.json 文件来确保代码质量和一致性。
- 国际化支持: 通过 i18nConfig.js 文件，项目支持多语言，增强了其适用性和用户体验。



### [langflow-ai/langflow](https://github.com/langflow-ai/langflow) ![GitHub stars](https://img.shields.io/github/stars/langflow-ai/langflow?style=social)

`langflow-ai/langflow` 是一个开源项目，提供了一个动态图，其中每个节点都是一个可执行单元，旨在通过模块化和交互式设计促进快速实验和原型设计，推动创造力的边界。

**概述**

该网页是 `langflow-ai/langflow` 项目的 GitHub 页面，项目介绍指出 Langflow 是一个动态图，它通过模块化和交互式的设计，使得每个节点都成为一个可执行单元，从而促进了快速的实验和原型设计，推动了创新的边界。网页提供了创建列表的功能，用于组织个人星标的仓库，并允许用户为列表命名和描述。此外，网页还提供了反馈和报告错误的途径，因为列表功能目前处于测试阶段。项目的主页 `www.langflow.org` 提供了更多关于 Langflow 的信息。该项目采用 MIT 许可证，并有一项行为准则。截至目前，该项目有 18.2k 个星标、2.7k 个叉子和 157 个观察者。网页还展示了项目的分支和标签，并提供了通过 GitHub.dev 或 Codespace 打开项目的选项。用户可以通过 fork 项目来创建自己的副本，并且可以选择在 iOS 或 Android 设备上接收推送通知。

**特点**

- **Langflow 项目的核心是其动态图结构，它允许每个节点作为一个可执行单元，促进了高效的实验和原型设计。**
- 项目鼓励社区参与和反馈，特别是对于其新的列表功能，这表明项目团队致力于持续改进和完善产品。
- **Langflow 项目的开放性和模块化设计是其吸引力的关键，使其能够适应多种用户需求和创意实验。**
- MIT 许可证的使用体现了项目的开源精神，鼓励代码的复用和分享。
- 项目的流行度可以通过其在 GitHub 上的星标和叉子数量来体现，这表明它在开发者社区中具有一定的影响力和认可度。
- 通过提供多种接入和参与项目的方式，如通过 GitHub.dev、Codespace 以及移动设备通知，Langflow 项目展现了其对用户体验的重视。

### [Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm) 客户端 ![GitHub stars](https://img.shields.io/github/stars/Mintplex-Labs/anything-llm?style=social)


Mintplex-Labs/anything-llm 是一个集成了各种 AI 功能的桌面和 Docker 应用程序，支持全面的 RAG（Retrieve-Augmented-Generative）和 AI 代理功能。

**摘要**

Mintplex-Labs/anything-llm 是一个开源项目，旨在提供一个全能型的 AI 应用程序，支持桌面和 Docker 部署。该项目最新的提交是在 2024 年 5 月 24 日，实现了 Bing 搜索 API 的 Web 搜索提供者。项目拥有 14.9k stars 和 1.5k forks，并且有 118 名观察者。该应用程序支持语音转文本和文本转语音功能，并且可以通过 GitHub Codespaces 和 VSCode 的开发容器进行开发。最近的更新包括添加 Bing 搜索引擎、更新 README、实现 GitHub Codespaces 和 VSCode 开发容器的支持，以及对 Kubernetes 清单的更新。此外，还对项目的前端、服务端、图片和其他组件进行了更新和维护。项目遵循 MIT 许可证，并且提供了一个安全策略。用户可以通过 GitHub Sponsors 来资助该项目。

**特点**

- **集成 AI 功能**: 该项目提供了一个集成了多种 AI 功能的应用程序，包括 RAG 和 AI 代理功能，这使得用户能够利用 AI 进行增强型的生成和检索任务。
- **多平台支持**: Mintplex-Labs/anything-llm 可以作为桌面应用程序运行，也可以通过 Docker 容器化部署，提供了灵活的使用选择。
- **开源和社区驱动**: 作为一个开源项目，Mintplex-Labs/anything-llm 鼓励社区成员的参与和贡献，这体现在其高star和fork数量上。
- **持续更新和维护**: 项目团队持续对代码进行更新和维护，包括添加新功能、优化现有功能以及修复问题。
- **易于开发和部署**: 通过集成 GitHub Codespaces 和 VSCode 的开发容器，项目提供了一个简化的开发和部署流程。
- **透明的安全和许可策略**: 该项目遵循 MIT 许可证，并且提供了一个明确的安全策略，确保了用户对项目的信任和安全性。
- **资金支持机制**: 通过 GitHub Sponsors，用户和组织可以为该项目提供资金支持，以支持其持续发展。

### [dissorial/doc-chatbot](https://github.com/dissorial/doc-chatbot) ![GitHub stars](https://img.shields.io/github/stars/dissorial/doc-chatbot?style=social)

 是一个基于 GPT 的文档聊天机器人项目，支持多文件、多话题、多聊天窗口和聊天历史记录，可以在浏览器中上传文件并与 Pinecone 和 LangChain 集成。

**摘要**

dissorial/doc-chatbot 项目旨在通过 GPT、Pinecone 和 LangChain 的结合，提供一个功能强大的文档聊天机器人。该机器人允许用户创建多个话题进行聊天，支持存储任意数量的文件到每个话题，并为每个话题创建任意数量的聊天窗口。用户可以在浏览器中上传 .pdf、.docx 和 .txt 文件，将它们转换为嵌入向量，存储在 Pinecone 中，并且可以删除 Pinecone 命名空间。聊天机器人还支持本地存储，自动检索所有聊天的历史记录。

项目的特性包括：

支持多个话题的创建
每个话题可以存储任意数量的文件
支持创建多个聊天窗口
在浏览器中上传文件、转换为嵌入向量、存储在 Pinecone 中、删除 Pinecone 命名空间的功能
本地存储和自动检索聊天历史记录
支持 .pdf、.docx 和 .txt 文件格式
此外，项目提供了本地设置和开发的指南，包括克隆仓库、配置 Pinecone、安装依赖包、设置环境变量、部署和运行应用程序的步骤。项目还提供了故障排除指南，解决了一些常见的问题和错误。

**特点**
- 多功能性: 该项目强调了聊天机器人的多功能性，包括对多个话题和文件的支持，以及多聊天窗口的管理。
- 集成技术: 项目利用了最新的技术栈，如 GPT、Pinecone 和 LangChain，以及 Next.js、Tailwind CSS 等前端技术。
- 用户友好性: 通过在浏览器中提供文件上传和管理功能，项目提高了用户的操作便捷性。
- 本地存储和历史记录: 聊天机器人的能力在本地存储聊天历史，为用户提供了更加持久和可靠的聊天体验。
- 开发和部署指导: 项目提供了详细的本地开发和部署指南，使得开发者能够更容易地设置和运行自己的实例。
- 灵活性和可扩展性: 项目设计允许用户根据自己的需求调整和扩展功能，例如通过调整 QA_PROMPT 和 modelName 以适应不同的使用场景。
- 社区贡献和灵感: 该项目衍生自 mayooear 的 GPT-4 & LangChain 仓库，并在此基础上进行了大量的修改和增强，同时也得到了 ChatGPT 前端设计的灵感。

### [wandb/openui](https://github.com/wandb/openui) 代码生成 ![GitHub stars](https://img.shields.io/github/stars/wandb/openui?style=social)
 仓库提供了一个开源的 UI 描述工具，允许开发者使用想象力设计 UI，并实时查看渲染结果，同时支持将 HTML 转换为 React、Svelte 等多种框架。

**摘要**
wandb/openui 是一个开源项目，旨在简化 UI 组件的构建过程，使其变得有趣、快速和灵活。该工具支持实时渲染，并允许用户请求更改，以及将 HTML 代码转换为不同的前端框架，如 React、Svelte 和 Web Components。OpenUI 也是 W&B 公司在构建基于大型语言模型（LLMs）的强大应用程序时使用的测试和原型工具。该项目的代码和文档托管在 GitHub 上，用户可以通过克隆仓库、安装依赖项并设置相应的 API 密钥来在本地运行 OpenUI。此外，还提供了通过 Docker 和 Gitpod 的部署方式，以及如何在 Codespace 中进行开发的指南。项目使用 Apache-2.0 许可证，并且在 GitHub 上拥有 15k 个星标和 1.3k 个叉子。

**特点**
- OpenUI 旨在简化 UI 开发流程，使开发者能够更加自由地使用想象力来设计界面，并实时看到结果。
- 支持多种前端框架，包括但不限于 React、Svelte 和 Web Components，方便开发者根据需求进行代码转换。
- 项目是开源的，鼓励社区贡献，并且在 GitHub 上有较高的关注度和活跃度。
- 提供了详细的文档和指南，帮助开发者在本地和云环境中部署和开发 OpenUI。
- 与大型语言模型（LLMs）相结合，OpenUI 不仅是一个 UI 工具，也是 W&B 在探索和构建 LLMs 应用的平台。
- 项目的使用和部署方式多样，包括直接克隆仓库、使用 Docker、Gitpod 以及 Codespace，适应不同开发者的需求。
- 对于 GPU 加速和模型兼容性提供了支持，特别是对 Groq 模型的集成，为开发者提供了更快的处理速度选项。 


### ⭐️ [OpenDevin/OpenDevin](https://github.com/OpenDevin/OpenDevin) 代码生成 ![GitHub stars](https://img.shields.io/github/stars/OpenDevin/OpenDevin?style=social)
仓库是一个开源项目，旨在通过代码减少编程工作量，提高开发效率。

**摘要**

OpenDevin/OpenDevin 是一个 GitHub 上的公开仓库，其目标是“Code Less, Make More”（编码少，制作多）。该项目支持用户创建列表以组织他们星标的仓库，并提供了一个创建列表的界面，允许用户为列表添加名称和描述，并通过输入冒号 `:` 来添加表情符号。此外，该项目正在进行 Beta 测试，鼓励用户分享反馈和报告错误。

项目的通知功能允许用户在 iOS 或 Android 设备上接收推送通知。用户可以选择观察、取消关注或叉（Fork）该项目，以及查看和参与项目的活动。该项目使用 MIT 许可证，并遵循一定的行为准则。

截至最后一次提交，项目的主分支包含 45 个分支和 8 个标签，有 26.2k 个星标和 2.9k 个叉，以及 287 名观察者。项目的最新提交包括对不同组件的更新，例如支持实体推理竞赛（EDA）基准测试，更新错误模板以包含操作系统版本，以及整合多模态工具到 `agentskills`。

**特点**

- **简化编码**: OpenDevin 项目的核心目标是减少开发者需要编写的代码量，从而提高开发效率和产出。
- **组织和协作**: 通过创建列表和允许用户对星标仓库进行组织，项目促进了更好的代码管理和协作。
- **用户参与**: 项目正在进行 Beta 测试，鼓励用户提供反馈和报告错误，以持续改进项目。
- **跨平台通知**: 提供跨 iOS 和 Android 设备的推送通知功能，以便用户实时跟踪项目动态。
- **开源性和合规性**: 采用 MIT 许可证，遵循行为准则，体现了项目的开源精神和对社区贡献的重视。
- **持续更新**: 项目活跃地进行更新和维护，包括对多模态工具的集成，以及对项目依赖和文档的持续优化。



### [stitionai/devika](https://github.com/stitionai/devika) 代码生成 ![GitHub stars](https://img.shields.io/github/stars/stitionai/devika?style=social)

Devika 是一个开源的代理AI软件工程师，能够理解高级人类指令，将其分解成步骤，研究相关信息，并编写代码以达成目标。

**摘要**

Devika 是一个由 LeptonAI 创建的 AI 软件工程师，旨在通过理解高级人类指令、将任务分解成步骤、研究相关信息以及编写代码来实现给定的目标。它支持多种大型语言模型和本地语言模型，具备高级的 AI 规划和推理能力，能够进行上下文关键词提取，以及在多种编程语言中编写代码。Devika 还能够进行项目管理和自然语言交互，并且具备可扩展的架构以便添加新功能和集成。该项目目前处于早期开发阶段，欢迎社区贡献。用户可以通过配置 API 密钥和其他设置来安装和使用 Devika，并通过 Web 界面与之交互。

**特点**

1. **Devika 的目标是成为一个开源的 AI 软件工程师**, 与 Cognition AI 的 Devin 相竞争，并且在 SWE-bench Benchmarks 中达到或超越相同的评分。
2. **Devika 具备先进的功能**, 包括支持多种大型语言模型、高级 AI 规划和推理能力、上下文关键词提取、Web 浏览和信息搜集、多语言代码编写、项目管理和自然语言交互。
3. **项目正处于早期开发阶段**, 有许多未实现或不完整的功能，积极欢迎社区成员的贡献。
4. **Devika 提供了详细的安装和使用指南**, 包括系统要求、安装步骤、配置说明以及如何通过 Web 界面与之交互。
5. **用户需要配置 API 密钥和其他设置**, 以便 Devika 能够正常工作，包括搜索引擎 API 密钥、模型 API 密钥以及其他必要的配置。
6. **Devika 的开发是模块化和可扩展的**, 允许添加新的功能和集成，以进一步增强其能力。
7. **社区支持和贡献是项目成功的关键**, 项目提供了 CONTRIBUTING.md 文件来指导贡献者如何参与贡献。
8. **Devika 鼓励用户参与到社区中来**, 通过 Discord 服务器与其他用户和开发者交流和协作。



### [OpenBMB/ChatDev](https://github.com/OpenBMB/ChatDev)代码生成 ![GitHub stars](https://img.shields.io/github/stars/OpenBMB/ChatDev?style=social)
 是一个利用自然语言理念和基于大型语言模型（LLM）的多智能体协作，旨在创建定制化软件的项目。

**摘要**

OpenBMB/ChatDev 项目搭建了一个虚拟软件公司，通过不同角色的智能代理（如首席执行官、首席产品官、首席技术官、程序员、审稿人、测试人员、艺术设计师）协同工作，这些代理形成了一个多智能体组织结构。该项目的主要目标是提供一个易于使用、高度可定制和可扩展的框架，用于研究集体智能，并通过编程革新数字世界。项目支持多种语言，包括英语、中文、日语、韩语、菲律宾语、法语、斯洛伐克语、葡萄牙、西班牙语、荷兰语、土耳其语、印地语和印度尼西亚语。

ChatDev 已经推出了多项新功能，如迭代体验优化（IER）、经验共同学习模块、基于 Docker 的安全执行环境、Git 模式、人机交互模式、艺术模式等。项目提供了快速启动指南，包括通过 Web 界面和终端方式的部署，以及使用 Docker 的方式。高级技能包括命令行运行参数、本地 Web 可视化演示指南、ChatDev 框架概览以及如何定制 ChatChain、Phase 和 Role 设置。

项目鼓励社区贡献，包括代码、公司定制和软件分享。ChatDev 提供了一个平台，允许用户通过自然语言描述创建软件，并且提供了详细的使用和部署文档。项目的源代码采用 Apache 2.0 许可证，相关数据采用 CC BY-NC 4.0 许可证。项目的贡献者和使用者可以通过邮件与项目团队联系。

**特点**

- **多智能体协作**: ChatDev 通过各种角色的智能代理协作，形成了一个多智能体组织结构，旨在通过编程革新数字世界。
- **高度可定制和可扩展**: 项目提供了一个框架，用户可以根据自己的需求定制和扩展软件开发流程。
- **支持多语言**: ChatDev 支持多种语言，便于全球用户使用和贡献。
- **持续更新和创新**: ChatDev 定期推出新功能，如 IER、Experiential Co-Learning 等，以提高软件开发的效率和质量。
- **开源和社区驱动**: 项目鼓励社区成员参与开源项目，通过贡献代码和定制化公司来共同发展项目。
- **易于使用**: 提供了详细的快速启动指南和高级技能指导，使得用户能够轻松开始使用 ChatDev。
- **许可和合规性**: 项目的源代码和数据遵循 Apache 2.0 和 CC BY-NC 4.0 许可证，确保合规使用和分享。


### [khoj-ai/khoj](https://github.com/khoj-ai/khoj) AI助手 ![GitHub stars](https://img.shields.io/github/stars/khoj-ai/khoj?style=social)

khoj-ai/khoj 是一个开源项目，旨在为用户提供一个个人的 AI 助手，帮助扩展个人能力，通过整合个人笔记和文档，提供实时互联网信息访问，并支持多平台接入，包括桌面、Emacs、Obsidian、Web 和 WhatsApp。

**概述**

khoj-ai/khoj 项目是一个开源的个人人工智能助手，它允许用户将自己的笔记和文档整合到一个数字大脑中，从而扩展其认知能力。该 AI 助手能够访问互联网，让用户能够纳入最新信息。khoj 支持多种平台，包括桌面应用、Emacs、Obsidian、网页和 WhatsApp。用户可以分享 PDF、Markdown、Org-mode、Notion 文件以及 GitHub 仓库。khoj 提供快速准确的语义搜索功能，能够创建个性化图像，并理解语音。khoj 是一个开源项目，支持自托管，同时也提供云服务。项目的最新版本是 1.12.1，发布日期为 2024 年 5 月 25 日。此外，项目积极寻求贡献者参与新功能的开发、文档的改进或者 Bug 的修复，并提供了贡献指南和贡献者项目板。项目还获得了一些赞助商的支持。

**特点**

- **开源个人 AI 助手**: khoj-ai/khoj 是一个开源项目，旨在为用户提供一个个人化的 AI 助手，帮助用户管理和利用自己的数字资料。
- **多平台支持**: 用户可以通过多种方式访问 khoj，包括桌面应用、Emacs、Obsidian、网页和 WhatsApp，以适应不同用户的偏好。
- **文档整合与搜索**: khoj 允许用户整合各种格式的文档，并提供语义搜索功能，以便快速找到所需信息。
- **互联网访问与个性化服务**: AI 助手能够访问互联网，提供最新信息，并能够根据用户的需求创建个性化的图像和理解语音。
- **自托管与云服务**: 用户可以选择自己托管 khoj，或者使用提供的云服务实例。
- **社区贡献与发展**: khoj 项目鼓励社区成员的参与，提供了详细的贡献指南，并通过赞助机制支持项目的持续发展。
- **最新发布与活跃度**: 项目最近发布了 1.12.1 版本，并且维持着活跃的更新和部署记录，显示了项目的持续活跃和发展状态。

### [weaviate/Verba](https://github.com/weaviate/Verba) ![GitHub stars](https://img.shields.io/github/stars/weaviate/Verba?style=social)

Verba 是一个开源的 Retrieval Augmented Generation (RAG) 聊天机器人，由 Weaviate 提供支持，可以本地或通过云服务进行部署，支持多种数据和模型，并提供了详细的安装和使用指南。

**概述**

Verba 是一个基于 Weaviate 的 RAG 聊天机器人，它允许用户通过本地部署或云服务（如 Weaviate Cloud Service, WCS）来使用。该项目支持多种模型，包括 Ollama、HuggingFace、Cohere、Google 和 OpenAI，以及不同类型的数据导入，如 PDF 和 CSV/XLSX 文件。Verba 提供了多种特性，如混合搜索、语义缓存、自动补全建议、以及计划中的过滤器和高级查询功能。用户可以通过 pip、源代码构建或 Docker 来部署 Verba。项目鼓励开源贡献，并提供了详细的技术文档和前端文档。Verba 面临的已知问题包括在 Windows 上 Weaviate Embedded 不工作，并且提供了常见问题解答。

**特点**

- **灵活性**: Verba 提供了多种部署方式，包括本地安装、源代码构建和 Docker 部署，以满足不同用户的需求。
- **模型和数据支持**: Verba 支持多种 LLM 和数据类型，包括 PDF 和 CSV/XLSX 文件，以及通过 UnstructuredIO 的多模态数据导入。
- **RAG 特性**: Verba 具备多项 RAG 特性，如混合搜索、语义缓存和自动补全建议，同时正在开发更多高级功能，如过滤器和 RAG 评估界面。
- **开源和社区**: Verba 鼓励社区成员的参与和贡献，提供了详细的贡献指南，并通过 Weaviate Community Forum 提供支持。
- **文档和指南**: 项目提供了详细的安装指南、API 密钥配置说明以及关于如何解决已知问题的指导。
- **多语言和国际化**: Verba 的多语言支持取决于所选的嵌入和生成模型是否支持多语言数据。
- **集成和扩展**: Verba 允许用户通过环境变量配置不同的 API 密钥，以集成和使用不同的服务提供商，如 OpenAI、Google 和 HuggingFace。

### [stanford-oval/storm](https://github.com/stanford-oval/storm) 报告 ![GitHub stars](https://img.shields.io/github/stars/stanford-oval/storm?style=social)
 是一个由大型语言模型（LLM）驱动的知识策划系统，能够自动对话题进行研究并生成带有引用的完整报告。

**摘要**

**storm** 项目是一个位于 `https://github.com/stanford-oval/storm` 的开源仓库，它提供了一个基于大型语言模型的知识策划系统。该系统能够自动进行网络研究，收集参考资料，并生成一个类似维基百科文章的完整报告，包括引用。目前，该项目已经有超过4.5k的星标和438个叉子。

项目最近更新了支持Bing搜索的功能，并且可以配置使用 `GPT-4o` 模型来生成文章。**storm** 的工作流程分为两个阶段：预写作阶段和写作阶段。在预写作阶段，系统会进行基于互联网的研究并生成大纲；在写作阶段，系统使用该大纲和参考资料生成带有引用的完整文章。**storm** 采用了两种策略来提高问题的深度和广度：基于不同视角的问题提问和模拟对话。

**storm** 的代码库已经重构，提供了模块化的接口，允许用户自定义知识策划流程中的各个环节，包括搜索引擎和语言模型。项目鼓励社区贡献，包括集成更多的搜索引擎和语言模型客户端。此外，项目还提供了自动评估系统的质量，包括大纲质量和完整文章质量的评估指标。

项目的默认语言模型配置在 `src/modules/utils.py` 中设置，用户可以根据需要进行修改。**storm** 的开发团队鼓励开发者通过问题或拉取请求来提供反馈和建议，以改进系统和代码库。

**特点**

- **storm** 系统旨在通过自动化的研究和写作流程，帮助用户生成高质量的知识报告。
- 系统的核心在于自动提出有效的问题来指导研究过程，这是通过考虑不同视角和模拟与专家的对话来实现的。
- **storm** 的设计非常模块化，允许用户根据自己的需求自定义各个组件，包括知识策划、大纲生成、文章生成和文章润色模块。
- 项目团队重视社区贡献，鼓励集成更多的搜索引擎和语言模型，以及对系统性能的改进。
- 为了评估系统生成的文章质量，**storm** 提供了一套自动化的评估工具，包括基于ROUGE和实体回忆的指标，以及基于rubric评分的指标。
- 项目的文档目前仍在进行中，但已经提供了详细的使用说明和示例脚本，以便用户可以快速上手和定制系统。
- **storm** 项目的成果已经在 NAACL 2024 会议上发表，并提供了复现实验结果的指导和代码备份。

## 服务项目

### [ollama](https://github.com/ollama/ollama) ![GitHub stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social)

提供了一个框架可以本地化使用 Llama 3、Mistral、Gemma 等大型语言模型。

**摘要**

ollama 项目是一个开源框架，旨在帮助用户快速开始使用 Llama 3、Mistral、Gemma 等大型语言模型。

**特点**

- 开源性: ollama 项目是完全开源的，鼓励社区成员的参与和贡献。
- 支持多种大型语言模型: 项目支持 Llama 3、Mistral、Gemma 等流行的大型语言模型。
- 良好的文档支持: 提供了详尽的开发者指南和 API 文档，方便开发者快速上手和使用。
= 跨平台: 支持在多个操作系统上运行，包括 macOS、Linux 和 Windows。
- 活跃的开发维护: 项目仓库经常更新，有多位贡献者参与，表明项目得到了良好的维护。
- 用户互动: 用户可以通过 GitHub 的机制（如 Star、Fork、Issue 和 Pull Request）与项目互动。
- 自动化工具: 包括 Dockerfile、脚本和配置文件，以简化构建、部署和测试流程。
- MIT 许可证: 采用宽松的 MIT 许可证，有利于技术的广泛传播和商业应用。



### [janhq/jan](https://github.com/janhq/jan)![GitHub stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social)

 是一个开源项目，提供了一个与 ChatGPT 功能相似的本地运行 AI 语言模型，支持多种引擎（如 llama.cpp、TensorRT-LLM）。

**摘要**

 janhq/jan 项目是一个开放源代码的 AI 语言模型，它能够在不联网的情况下在个人电脑上运行。该项目模仿了 ChatGPT 的功能，并支持多种不同的引擎。该项目的最新提交包括更新 Aya 模型、修复代码中的拼写错误、优化代码签名的重试机制等。此外，项目还在不断地更新和改进其他方面，如文档、UI 组件库、服务器和客户端等。

**特点**

- 开源本地 AI 语言模型: janhq/jan 项目提供了一个可以在本地运行的 AI 语言模型，无需依赖网络连接。
- 多引擎支持: 项目支持多种引擎，如 llama.cpp 和 TensorRT-LLM，这使得用户可以根据自己的需求选择合适的引擎。
- 社区活跃: 项目拥有大量的 star 和 fork，反映了社区对该项目的高度关注和活跃参与。
- 持续更新: 项目的最新提交显示了持续的更新和维护，包括模型更新、代码优化、文档改进等。
- 许可证: 项目遵循 AGPL-3.0 许可证，这是一个对用户友好的开源许可证，允许用户自由地使用、修改和分发软件，只要他们遵守 AGPL 的条款。
- 跨平台支持: 项目的电子（Electron）部分表明它支持跨平台的桌面应用程序，这意味着它可以在不同的操作系统上运行。

### [modelscope/swift](https://github.com/modelscope/swift.git)  训练模型 ![GitHub stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social)
 仓库提供了一个名为 ms-swift 的框架，用于使用 PEFT（Parameter-Efficient Fine-Tuning）或全参数微调来对超过 200 个大型语言模型（LLMs）或多模态大型语言模型（MLLMs）进行微调，支持训练、推理、评估和部署。

**摘要**

modelscope/swift 仓库是一个开源项目，它提供了一个名为 ms-swift 的框架，旨在简化对大型语言模型（LLMs）和多模态大型语言模型（MLLMs）的微调过程。该框架支持对近 200 个 LLMs 和 15 个 MLLMs 进行训练、推理、评估和部署。ms-swift 支持 PEFT 和全参数微调方法，并提供了一个包含最新训练技术（如 NEFTune、LoRA+、LLaMA-PRO 等）的适配器库。用户可以直接在自己的研究和生产环境中使用这个框架，实现从模型训练和评估到应用的完整工作流程。

为了便于不熟悉深度学习的用户使用，ms-swift 提供了基于 Gradio 的 Web UI，用于控制训练和推理，并附带了相关的深度学习课程和最佳实践指南。此外，ms-swift 还在扩展其对其他模态的支持，目前已支持 AnimateDiff 的全参数训练和 LoRA 训练。

ms-swift 具有丰富的用户文档，用户可以通过仓库中的文档来了解如何使用。该框架的 Web UI 可以在 Huggingface space 和 ModelScope studio 上使用。

安装 ms-swift 需要 Python 环境，推荐使用 pip 安装，也可以通过源代码或 Docker 镜像进行安装。框架支持多种训练方法，包括单 GPU、多 GPU、数据并行、模型并行、DeepSpeed 训练以及多节点多 GPU 训练。此外，ms-swift 还支持多种推理、评估、导出和部署方法。

**特点**
- 易用性: ms-swift 提供了一个基于 Gradio 的 Web UI，使得没有深度学习背景的用户也能轻松进行模型的训练和部署。
- 灵活性: 该框架支持多种训练方法，包括单 GPU、多 GPU、数据并行、模型并行、DeepSpeed 训练，以及多节点多 GPU 训练，适应不同的硬件环境和需求。
- 高效性: ms-swift 支持 PEFT 技术，使得微调大型模型时只需调整少量参数，大大减少了资源消耗。
- 广泛的模型支持: 框架支持超过 200 个 LLMs 和 15 个 MLLMs，包括但不限于 Qwen、ChatGLM、Baichuan、Yuan、XVerse、LLaMA、Mistral、Yi、InternLM、DeepSeek、MAMBA、Gemma、MiniCPM、OpenBuddy、Orion、BlueLM、Ziya、Skywork、Zephyr、PolyLM、SeqGPT、SUS、Tongyi-Finance、CodeFuse、phi2/phi3、Grok、TeleChat、dbrx、mengzi3、c4ai-command-r 和 WizardLM2。
- 文档完善: ms-swift 提供了详细的文档和示例脚本，帮助用户快速上手和使用。
- 社区支持: 该项目鼓励社区贡献，提供了贡献指南，并有一个 WeChat 群组用于交流和支持。
- 跨平台部署: ms-swift 支持在不同的平台上部署模型，包括 Huggingface space 和 ModelScope studio。


### [modelscope/DashInfer](https://github.com/modelscope/DashInfer) 推理 ![GitHub stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social)
 是一个用于推理预训练大语言模型的高性能推理引擎，支持 C++ 和 Python 接口，适用于多种 CPU 架构，并提供了连续批处理、多 NUMA 推理、PTQ 量化等特性。

**摘要**
DashInfer 是一个轻量级的推理引擎，用于推理预训练大语言模型（LLM），采用 C++ Runtime 编写，提供 C++ 和 Python 语言接口。它具有生产级别的高性能表现，适用于多种 CPU 架构，包括 x86 和 ARMv9，并支持连续批处理（Continuous Batching）和多 NUMA 推理（NUMA-Aware）。DashInfer 能够充分利用服务器级 CPU 的算力，支持部分主流 LLM 开源模型，如 Qwen、LLaMA、ChatGLM 等，并支持 Huggingface 格式的模型读取。DashInfer 的 PTQ 量化（InstantQuant, IQ）技术允许无需训练微调即可实现 weight-only 量化加速。该引擎结合 OneDNN 和自研汇编 kernel，能够在 ARM 和 x86 上发挥硬件的最大性能。DashInfer 支持多 NUMA 的 tensor 并行推理，通过 numactl 和多进程架构精准控制计算线程的 NUMA 亲和性。目前版本支持 11k 的 Context Length，并计划未来支持更长的 Context Length。DashInfer 提供了多语言 API 接口，支持的操作系统包括 Centos7、Ubuntu22.04 等主流 Linux 服务器操作系统。此外，DashInfer 还提供了性能和精度测试结果，以及未来的规划方向，包括首包加速、扩展 Context Length、低位量化支持、QAT 量化支持和 MoE 模型支持。DashInfer 的软件框架包括模型加载与序列化、模型推理等流程，并且使用 conan 管理第三方依赖库。

**特点**
- DashInfer 提供了高精度的 LLM 推理技术，能够与 PyTorch、GPU 引擎（vLLM）提供一致的推理精度。
- DashInfer 采用了行业标准的 LLM 推理技术，如连续批处理和基于请求的异步接口，这些技术允许对每个请求的生成参数、请求状态等进行单独控制。
- DashInfer 在硬件支持方面，对 x86 和 ARMv9 CPU 提供了特定的指令集支持，如 AVX2、SVE 和 AMX，以及对 FP32、BF16 数据类型的支持。
- DashInfer 的 InstantQuant 量化技术能够在不影响模型精度的情况下，实现 weight-only 量化加速，特别是在 ARM CPU 上的 weight-only 8-bit 量化。
- DashInfer 在多 NUMA 架构下采用了多进程的 client-server 架构，以实现 tensor parallel 的模型推理，并通过 OpenMPI 进行协同。
- DashInfer 的性能和精度测试结果表明，它在不同的 LLM 模型和数据类型上都能提供与 transformers 接口相当的精度表现。
- DashInfer 的未来规划包括首包加速、扩展 Context Length、支持更多的量化技术和模型架构，如 MoE。
- DashInfer 的软件框架设计考虑了易于集成和使用，同时通过 conan 管理第三方依赖库，简化了编译和部署过程。


### [unslothai/unsloth](https://github.com/unslothai/unsloth) 微调 ![GitHub stars](https://img.shields.io/github/stars/unslothai/unsloth?style=social)

`unslothai/unsloth` 仓库提供了一个工具，用于加速 Llama 3、Mistral 和 Gemma LLMs 的微调过程，可以实现 2-5 倍的加速，同时减少 80% 的内存使用。

**概述**

`unslothai/unsloth` 仓库是一个公开的项目，用于优化大型语言模型（LLMs）的微调过程。该项目支持 Llama 3、Mistral 和 Gemma LLMs 的微调，通过使用该工具，用户可以在不牺牲性能的情况下，以更快的速度（2-5 倍加速）并且大幅减少内存使用（80% 减少）来进行模型的微调。此外，该项目还提供了一个列表功能，用于组织和管理用户星标的仓库，用户可以通过创建列表并添加描述来组织自己的仓库。该项目目前处于 Beta 阶段，鼓励用户提供反馈和报告 Bugs。项目的资金支持可以通过 ko-fi.com/unsloth 进行，该项目遵循 Apache-2.0 许可证。截至目前，该项目拥有超过 10.4k 的星标和 652 个叉子，以及 73 名观察者。

**特点**

- `unslothai/unsloth` 项目旨在提高大型语言模型微调的效率和速度，同时降低对计算资源的需求。
- 该工具支持特定的 LLMs，包括 Llama 3、Mistral 和 Gemma，并且可以显著提升微调的性能。
- 项目提供了一个用户友好的界面，允许用户创建和管理自己的仓库列表，以便更好地组织和跟踪他们感兴趣的项目。
- 项目正在积极开发中，欢迎用户反馈和参与改进过程。
- 项目的资金支持可以通过外部链接进行，这表明项目团队致力于社区支持和项目的持续发展。
- 该项目遵循 Apache-2.0 许可证，这是一个开源许可证，允许用户自由地使用、修改和分发软件。
- 项目的受欢迎程度可以通过其在 GitHub 上的星标和叉子数量来体现，这表明它在社区中有一定的知名度和影响力。

## 多模态

### [alibaba-damo-academy/FunClip](https://github.com/alibaba-damo-academy/FunClip)视频剪辑 ![GitHub stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social)
 是一个开源的视频语音识别与剪辑工具，集成了基于大型语言模型（LLM）的智能剪辑功能。

**摘要**
FunClip 是由阿里巴巴 DAMO 学院开发的一个全开源的视频剪辑工具，它利用 FunASR 系列模型进行视频语音识别，并允许用户从识别结果中选择文本段落或说话者进行剪辑。FunClip 支持多种功能，包括使用 Paraformer-Large 模型进行高效的语音识别，支持热词定制以提高识别准确性，集成了 CAM++ 模型进行说话者识别，以及通过 Gradio 交互实现简单安装和易用性。此外，FunClip 还支持智能剪辑，可以结合大型语言模型（如 GPT 系列）进行高级剪辑操作。最新版本的 FunClip 支持使用大型语言模型进行智能段落选择和剪辑，并且修复了一些已知的 bug。用户可以通过本地 Gradio 服务、Modelscope 空间或命令行使用 FunClip，并可以通过社区群组进行交流。

**特点**
- 开源性: FunClip 是一个完全开源的工具，鼓励社区贡献和分享。
- 易用性: 通过 Gradio 交互界面，FunClip 提供了简单的安装和使用体验。
- 高级功能: FunClip 集成了行业级别的语音识别和说话者识别模型，支持智能剪辑。
- 多样性: 支持多种使用方式，包括本地服务、在线平台和命令行工具。
- 持续更新: FunClip 不断更新，增加新功能并修复已知问题，以提供更好的用户体验。
- 社区支持: 提供了社区群组的加入方式，以便用户之间的交流和支持。
- 跨语言支持: FunClip 计划支持 Whisper 模型，以便英语用户的使用，并且在大型语言模型（LLM）的剪辑能力上也有所探索。

### [MoneyPrinterTurbo](https://github.com/MoneyPrinterTurbo/MoneyPrinterTurbo) 视频合成![GitHub stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social)

MoneyPrinterTurbo 是一个基于 AI 大模型的项目，能够通过一键操作，根据用户提供的主题或关键词，自动生成高清短视频，包括视频文案、素材、字幕和背景音乐。

**摘要**
MoneyPrinterTurbo 项目旨在利用 AI 技术自动化生成短视频的过程。用户只需提供视频主题或关键词，项目将自动创建视频文案、素材、字幕和背景音乐，并合成成完整的高清短视频。该项目支持 Web 界面和 API 界面操作，适用于 Windows 和 MacOS 系统。项目提供了一键启动包，并且支持 Docker 和手动部署方式。此外，项目还提供了字幕生成、语音合成和背景音乐选择等功能，并且支持多种语音合成服务商。项目还面临一些常见问题，如网络问题、文件数限制、模型下载失败等，并提供了相应的解决方案。该项目基于开源项目 MoneyPrinter 重构而来，增加了许多新功能，并且得到了多个赞助商的支持。

**特点**
- 自动化视频生成: 项目的核心观点是通过 AI 大模型实现视频内容的自动化生成，降低了视频制作的门槛。
- 用户友好性: 提供了多种部署和使用方式，包括一键启动包、Docker 部署和详细的 API 文档，以适应不同用户的需求。
- 多功能性: 支持多种语音合成服务商，提供了字幕生成和背景音乐选择等功能，增强了视频的多样性和丰富性。
- 开源与社区支持: 项目基于开源项目重构，鼓励社区参与和贡献，并且得到了赞助商的支持。
- 解决方案与反馈: 项目提供了对常见问题的解决方案，并且鼓励用户提交 issue 或 pull request 进行反馈和建议。

## 智能体

### [microsoft/autogen](https://github.com/microsoft/autogen) ![GitHub stars](https://img.shields.io/github/stars/microsoft/autogen?style=social)



**介绍**

microsoft/autogen 是一个由微软开发的开源项目，它是一个用于构建代理式人工智能（AI）的编程框架。该项目的目标是为 AI 提供一种方式，使其能够以更加自主和代理式的方式运作。项目提供了一个 Discord 社区，用于讨论和协作，以及一个公开的发展路线图，以便社区成员可以跟踪和参与未来的功能和改进。

**项目特点**
- 代理式 AI 框架: autogen 专为构建能够自主决策的 AI 系统设计，这种 AI 被称为代理式 AI。
- 开源性: 项目是开源的，鼓励社区成员参与贡献，共同推动项目的发展。
- 社区支持: 提供了 Discord 社区，方便开发者和用户之间的交流和协作。
- 透明的发展路线图: 项目提供了一个公开的路线图，让社区成员可以了解即将到来的特性和改进。
- 多种许可证: 项目包含了两种许可证，CC-BY-4.0 和 MIT 许可证，这允许在不同的条款下使用和分发项目。
- 行为准则: 项目强调社区行为准则，以维护一个积极健康的社区环境。
- 安全政策: 项目还有明确的安全政策，以确保代码的安全性和稳定性。
- 广泛的关注和参与: 截至目前，项目拥有超过 26.3k 的星标和 3.8k 的叉子，表明了社区的广泛关注和参与。
- 活跃的更新: 项目的更新非常活跃，最新的提交记录显示项目正在不断地进行改进和维护。
- 跨平台支持: 项目提供了跨平台的支持，包括对.devcontainer 和.github 的支持，这使得开发者可以在多种环境下工作和贡献。
- 详细的提交历史: 项目的 GitHub 仓库包含了详细的提交历史，这有助于开发者跟踪项目的变更和进展。
- 多语言支持: 项目的代码库支持多种编程语言，包括但不限于.NET 框架。
- 文档和教程: 项目提供了文档和教程，帮助开发者和用户更好地理解和使用autogen框架。
- 版本控制: 项目使用 Git 和 GitHub 进行版本控制，确保了代码的可追溯性和协作性。
 -持续集成 / 持续部署 (CI/CD): 项目配置了 CI/CD 工作流，确保每次提交都能通过自动化测试，保证代码质量。


### [lobehub/lobe-chat-agents](https://github.com/lobehub/lobe-chat-agents) ![GitHub stars](https://img.shields.io/github/stars/lobehub/lobe-chat-agents?style=social)
 仓库是 LobeChat 聊天机器人的代理列表索引，用于展示可用的代理列表，并允许用户通过提交 PR 将自己的代理添加到市场中。

**摘要**
lobehub/lobe-chat-agents 仓库是 LobeChat 聊天机器人的代理列表索引，用于展示可用的代理列表。该仓库的主页提供了如何提交代理的步骤，包括使用 agent-template.json 或 agent-template-full.json 模板在 src 目录下创建代理条目，并提交拉取请求。仓库中包含了多个代理的描述，这些代理覆盖了不同的领域和功能，如 IT 系统架构、哲学分析、中文文本修正、Minecraft 命令教学、禅宗思想、数据分析、地基工程助手、道教哲学、学习规划、语言学习、情感支持、学术论文编辑、高中科学辅导、占星术、生物学教授、营养餐食推荐、天气助手、微控制器工程、脏话学习、商业发展、建筑设计哲学、YouTube 脚本摘要、Shell 脚本开发、Shopify 主题开发、研究论文标题生成、游戏文本翻译、电子学教学、传统中医咨询、数学辅导、逻辑思维团队合作、用户研究管理、亚马逊产品描述撰写、英语词汇教学、Linux 系统问题解决、提示词架构优化、编程辅导、药物指南、亚马逊卖家支持、TikTok 脚本撰写、Gen Z 用户互动、日程管理、商务英语邮件撰写、Discord 风格文案、软件开发入门指南、创业演示文稿制作、F1 赛车数据分析、AI 图像生成提示词设计、英语作文辅导、灵魂导师、厨师食谱建议、科技探索、Markdown 转换专家和面试辅导。此外，仓库还包含了一系列的文件和目录，如 .github、locales、schema、scripts、src、.gitignore、.i18nrc.js、.npmrc、package.json、tsconfig.json 等，这些文件和目录包含了项目的配置文件、脚本、源代码和国际化资源。

**特点**
- 代理提交与审核: 用户可以通过创建代理条目并提交拉取请求来添加自己的代理到 LobeChat 的代理市场。所有提交的代理都将经过审核，以确保质量和相关性。
- 代理多样性: 该仓库 aggregates a wide variety of agents, each with its own specialization, catering to different user needs and interests.
- 项目组织: 仓库的文件和目录结构有助于维护和管理代理的列表，确保项目的可扩展性和国际化。
- 社区贡献: 通过 GitHub 的拉取请求机制，鼓励社区成员参与到代理的开发和维护中来，促进了开源社区的活跃。
- 代理功能展示: 仓库中的代理描述展示了每个代理的功能和特点，帮助用户根据自己的需求选择合适的代理。
- 技术栈: 项目使用了如 TypeScript、Tailwind CSS 等现代化的技术栈，体现了项目的技术前瞻性。
- 国际化支持: 项目支持多语言，包括中文和英文，便于不同语言背景的用户访问和理解。
- 用户指南: 仓库提供了详细的使用说明，帮助用户了解如何提交代理，以及如何在本地环境中进行开发和测试。

### [cpacker/MemGPT](https://github.com/cpacker/MemGPT) ![GitHub stars](https://img.shields.io/github/stars/cpacker/MemGPT?style=social)
MemGPT 是一个允许开发者构建具有长期记忆和自定义工具集成的大型语言模型（LLM）智能代理的开源框架。

**摘要**
MemGPT 项目的 GitHub 仓库介绍了如何使用该框架创建具有长期记忆管理、外部数据源连接（如 PDF 文件）以及定义和调用自定义工具（如 Google 搜索）的 LLM 智能代理。该项目支持将 LLM 代理部署为服务，允许多用户和多代理应用在支持的 LLM 提供商之上运行。MemGPT 提供了安装和设置指南，包括使用 pip 安装 pymemgpt 库，并设置 OpenAI API 密钥以使用 OpenAI 服务。项目的 GitHub 页面还展示了最新的提交记录和文件更新，包括代码修复、功能更新、文档更新等，以及如何通过创建列表来组织和管理仓库的星标功能。此外，页面还提供了关于如何卸载仓库、获取推送通知以及如何处理与仓库相关的问题的信息。

**特点**
- 易用性: MemGPT 旨在简化构建和部署 LLM 智能代理的过程，提供了易于理解和遵循的文档和安装指南。
- 功能丰富: 框架支持长期记忆 / 状态管理、外部数据源集成以及自定义工具的定义和调用，这使得 LLM 代理能够更加灵活和强大。
- 多用户多代理支持: MemGPT 允许将 LLM 代理作为服务部署，支持多用户和多代理的应用场景，适用于各种支持的 LLM 提供商。
- 社区贡献: 项目的更新和维护依赖于社区的贡献，如提交代码修复、功能增强和文档更新等。
- 开源透明: 作为一个开源项目，MemGPT 的所有代码和文档对外公开，鼓励开发者参与和贡献。
- 持续更新: 项目团队定期更新代码库，确保框架的安全性和功能的最新性。


### [AgentScope/modelscope](https://github.com/AgentScope/modelscope)  ![GitHub stars](https://img.shields.io/github/stars/AgentScope/modelscope?style=social)
是一个多智能体平台，旨在简化使用大型语言模型构建多智能体应用的过程。

**摘要**
AgentScope 是一个专为开发者设计的多智能体平台，它提供了丰富的组件、全面的文档和广泛的兼容性，使得构建基于大型语言模型的应用变得简单。平台支持自定义故障容错和重试机制，以提高应用的稳定性。同时，AgentScope 支持分布式多智能体应用的中心化编程方式，以便于开发。该平台提供了多种模型库的 ModelWrapper，包括 OpenAI API、DashScope API、Gemini API 等，支持本地模型服务和第三方模型 API。此外，AgentScope 还支持 Web 搜索、数据查询、检索、代码执行、文件操作和文本处理等服务。项目目前处于积极开发中，建议从源代码安装 AgentScope。安装后，可以通过配置文件快速启动和使用模型，并通过内置的用户和助手智能体创建对话，甚至可以通过 AgentScope Studio 提供的运行时用户界面查看多模态输出。

**特点**
- 易用性: AgentScope 被设计为易于使用，提供了拖放式编程平台和 AgentScope Workstation，帮助初学者更容易上手。
- 稳定性: 平台支持自定义故障容错和重试机制，以增强应用的健壮性。
- 分布式架构: AgentScope 采用基于 Actor 的分布式架构，使得开发分布式多智能体应用变得简单。
- 模型支持: AgentScope 提供了多种模型库的 ModelWrapper，支持多种模型和 API，包括但不限于 OpenAI、DashScope、Gemini 等。
- 服务丰富: 平台支持多种服务，如 Web 搜索、数据查询、检索、代码执行、文件操作和文本处理等。
- 示例应用: AgentScope 提供了多种示例应用，如基于 Llama3 的模型使用、多种对话类型、游戏（如井字棋和狼人杀）以- 及分布式应用等。
- 安装与配置: 建议从源代码安装 AgentScope，并通过配置文件来设置和使用模型。
- 用户界面: AgentScope Studio 提供了一个运行时用户界面，可以展示多模态输出，如文本、图片、音频和视频。


### [joaomdmoura/crewAI](https://github.com/joaomdmoura/crewAI) ![GitHub stars](https://img.shields.io/github/stars/joaomdmoura/crewAI?style=social)

crewAI 是一个先进的框架，旨在协调角色扮演的自治 AI 代理人，通过促进协作智能，使代理人能够无缝协作，共同解决复杂任务。

**概述**

crewAI 是一个开源的 AI 代理人框架，它允许开发者创建和管理一个由多个 AI 代理人组成的团队，这些代理人可以分配角色、共享目标，并且能够自主地相互委托任务，以提高问题解决的效率。框架支持使用不同的大型语言模型（LLMs），包括 OpenAI 的 API 和本地模型，如通过 Ollama 工具连接的模型。CrewAI 提供了两种流程管理方式：顺序流程和层次流程，后者允许自动分配管理员来协调任务的规划和执行。此外，CrewAI 支持将任务输出保存为文件，并且可以将输出解析为 Pydantic 模型或 Json 格式。CrewAI 的设计注重生产环境的适用性，它结合了 Autogen 的灵活性和 ChatDev 的流程概念，同时避免了它们的局限性。CrewAI 还集成了匿名的遥测功能，用于收集使用数据，以帮助改进库的功能和集成。CrewAI 遵循 MIT 许可证，并鼓励社区贡献。

**特点**

- **协作智能**: CrewAI 的核心理念是通过角色分配和目标共享，促进 AI 代理人之间的协作，以此来解决复杂的任务。
- **灵活性和适应性**: CrewAI 提供了灵活的任务管理和流程控制，支持顺序和层次流程，并且正在开发更复杂的流程，如共识和自主流程。
- **多样化的模型连接**: 框架支持多种大型语言模型，包括云服务和本地模型，提供了连接模型的多种方式。
- **生产环境就绪**: CrewAI 专为生产环境设计，具有可扩展性和灵活性，适用于实际应用场景。
- **社区和贡献**: CrewAI 鼓励开源贡献，并提供了详细的指南和工具来帮助贡献者参与进来。
- **遥测和改进**: 通过匿名的遥测数据，CrewAI 团队能够专注于改进最常用的特性和工具，同时保护用户隐私。


### [jgravelle/AutoGroq](https://github.com/jgravelle/AutoGroq) ![GitHub stars](https://img.shields.io/github/stars/jgravelle/AutoGroq?style=social)


AutoGroq 是一个 AI 助手，旨在通过自动生成专家代理和工作流程，简化用户与 AI 工具的互动。

**概述**

AutoGroq 是一个开源的 AI 助手，它能够快速、简单地自动生成专家代理和工作流程，以帮助用户解决各种问题和项目。它支持与 Groq、ChatGPT 和 Ollama 等语言模型的集成，并且允许用户添加自定义技能。AutoGroq 提供了一个在线演示版本，用户可以通过它来体验其功能，并且可以本地安装。项目的代码和文档都可以在 GitHub 仓库中找到。AutoGroq 的关键特性包括动态生成专家代理、自动化工作流程、自然的对话流程、代码片段提取、灵活的代理管理以及高级的提示重新编写。用户可以通过输入他们的请求来启动 AutoGroq，系统会自动生成代理并创建工作流程文件，这些文件可以作为 ZIP 文件下载。AutoGroq 的架构包括 Streamlit 应用程序、实用程序模块和代理管理模块。

**特点**

- **用户友好性**: AutoGroq 旨在提供一个无需配置的用户友好体验，使用户能够快速获得专业的 AI 辅助。
- **自动化和效率**: 通过一键式上传和自动代理生成，AutoGroq 大大提高了用户处理项目的效率。
- **灵活性和定制性**: 用户可以自定义代理，添加新的技能，并根据项目需求管理代理。
- **集成和支持**: AutoGroq 支持多种语言模型，并且正在扩展支持更多的模型。
- **开源和社区贡献**: AutoGroq 是开源的，鼓励社区成员提供反馈和贡献以进一步发展平台。
- **教育和易用性**: 提供了视频教程和在线演示，帮助用户快速上手 AutoGroq。
- **技术创新**: AutoGroq 利用 Streamlit 库和各种 API 集成，展示了最新的 AI 和自然语言处理技术。

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

## 算法

### [naklecha/llama3-from-scratch](https://github.com/naklecha/llama3-from-scratch) ![GitHub stars](https://img.shields.io/github/stars/naklecha/llama3-from-scratch?style=social)

该网页是一个开源项目 `naklecha/llama3-from-scratch`，详细介绍了如何从头开始实现 LLaMA3 模型，包括了解模型结构、加载权重、编写代码以及最终预测结果的过程。

**摘要**

`naklecha/llama3-from-scratch` 项目是一个关于实现 LLaMA3 模型的教程，它逐步指导如何使用 Python 和 PyTorch 库，从加载预训练权重开始，到如何处理输入文本、实现自注意力机制、位置编码、多头注意力、前馈神经网络以及最终的输出层。作者 Naklecha 通过详细的代码示例和解释，展示了如何一步一步构建 LLaMA3 模型，并通过一个示例输入文本 "the answer to the ultimate question of life, the universe, and everything is " 来验证模型的预测能力。最终，模型成功预测出了数字 "42"，这是文化作品《银河系漫游指南》中提到的宇宙终极问题的答案，从而验证了实现的正确性。此外，作者还提供了项目的背景信息、如何支持作者的工作，以及他的研究动机。

**特点**

1. **LLaMA3 模型的实现需要对模型架构有深入的理解**，包括自注意力机制、位置编码、多头注意力和前馈神经网络等。
2. **权重的加载和处理是实现过程中的关键步骤**，需要正确地从预训练模型文件中提取并加载权重参数。
3. **代码的详细注释和解释对于理解模型的工作原理至关重要**，作者通过详细的代码注释和解释，使读者能够跟随步骤并理解每个部分的作用。
4. **实现过程中使用了 RoPE（Rotary Position Embedding）来处理位置信息**，这对于模型理解和处理序列中的位置关系至关重要。
5. **最终的预测验证了模型的有效性**，通过预测出文化常识中的著名答案 "42"，展示了模型的预测能力和实现的正确性。
6. **开源项目和社区支持对于推动研究和实践的进步至关重要**，作者鼓励读者通过社交媒体和捐赠来支持他的工作，以及参与到 A10 研究实验室的活动中来。

## 研究论文

- **论文标题**：论文贡献和发现的简要总结。
- **论文标题**：论文贡献和发现的简要总结。


## 教程和课程

- **课程名称**：课程内容的简短描述。
- **课程名称**：课程内容的简短描述。

## 社区和会议

- **社区/会议名称**：社区或会议的简短描述和链接。
- **社区/会议名称**：社区或会议的简短描述和链接。
