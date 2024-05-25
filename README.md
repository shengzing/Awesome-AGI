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
		- [toeverything/AFFiNE ](#toeverythingaffine-)
		- [rashadphz/farfalle ](#rashadphzfarfalle-)
		- [weaviate/Verba ](#weaviateverba-)
		- [vercel/ai-chatbot ](#vercelai-chatbot-)
		- [mckaywrigley/chatbot-ui ](#mckaywrigleychatbot-ui-)
		- [dissorial/doc-chatbot ](#dissorialdoc-chatbot-)
		- [wandb/openui 代码生成 ](#wandbopenui-代码生成-)
		- [⭐️ OpenDevin/OpenDevin 代码生成 ](#️-opendevinopendevin-代码生成-)
		- [stitionai/devika 代码生成 ](#stitionaidevika-代码生成-)
		- [OpenBMB/ChatDev代码生成 ](#openbmbchatdev代码生成-)
	- [服务项目](#服务项目)
		- [ollama ](#ollama-)
		- [janhq/jan](#janhqjan)
		- [\[modelscope/swift\] 训练模型 ](#modelscopeswift-训练模型-)
		- [modelscope/DashInfer 推理 ](#modelscopedashinfer-推理-)
	- [多模态](#多模态)
		- [alibaba-damo-academy/FunClip视频剪辑 ](#alibaba-damo-academyfunclip视频剪辑-)
		- [MoneyPrinterTurbo 视频合成](#moneyprinterturbo-视频合成)
	- [智能体](#智能体)
		- [microsoft/autogen ](#microsoftautogen-)
		- [lobehub/lobe-chat-agents ](#lobehublobe-chat-agents-)
		- [cpacker/MemGPT ](#cpackermemgpt-)
		- [\[AgentScope/modelscope\] (https://github.com/AgentScope/modelscope) ](#agentscopemodelscope-httpsgithubcomagentscopemodelscope-)
	- [工具](#工具)
		- [run-llama/create-llama 构建 ](#run-llamacreate-llama-构建-)
		- [AutomaApp/automa 工具 ](#automaappautoma-工具-)
		- [CopilotKit/CopilotKit 交互 ](#copilotkitcopilotkit-交互-)
		- [mendableai/firecrawl 抽取 ](#mendableaifirecrawl-抽取-)
		- [mendableai/firecrawl-py 抽取 ](#mendableaifirecrawl-py-抽取-)
		- [josStorer/chatGPTBox 浏览器插件 ](#josstorerchatgptbox-浏览器插件-)
		- [continuedev/continue IDE插件 ](#continuedevcontinue-ide插件-)
		- [langchain-ai/langchain-nextjs-template 构建工具 ](#langchain-ailangchain-nextjs-template-构建工具-)
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

### [modelscope/swift]![GitHub stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social) 训练模型 ![GitHub stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social)
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


### [AgentScope/modelscope] (https://github.com/AgentScope/modelscope) ![GitHub stars](https://img.shields.io/github/stars/AgentScope/modelscope?style=social)
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

### [continuedev/continue](https://github.com/continuedev/continue) IDE插件 ![GitHub stars](https://img.shields.io/github/stars/continuedev/continue?style=social)
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


- 
## 研究论文

- **论文标题**：论文贡献和发现的简要总结。
- **论文标题**：论文贡献和发现的简要总结。


## 教程和课程

- **课程名称**：课程内容的简短描述。
- **课程名称**：课程内容的简短描述。

## 社区和会议

- **社区/会议名称**：社区或会议的简短描述和链接。
- **社区/会议名称**：社区或会议的简短描述和链接。
