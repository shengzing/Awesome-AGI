# Awesome-AGI

欢迎来到 **Awesome-AGI**，这是一个精心整理的人工通用智能（AGI）项目和资源列表。

觉得有用请点个 Star 吧！

## 目录

- [Awesome-AGI](#awesome-agi)
	- [目录](#目录)
	- [简介](#简介)
	- [应用项目](#应用项目)
		- [QAnything ](#qanything-)
		- [open-webui/open-webui ](#open-webuiopen-webui-)
		- [rashadphz/farfalle ](#rashadphzfarfalle-)
		- [weaviate/Verba ](#weaviateverba-)
		- [vercel/ai-chatbot ](#vercelai-chatbot-)
	- [服务项目](#服务项目)
		- [ollama ](#ollama-)
		- [janhq/jan](#janhqjan)
	- [智能体](#智能体)
		- [microsoft/autogen ](#microsoftautogen-)
	- [工具](#工具)
		- [run-llama/create-llama ](#run-llamacreate-llama-)
		- [AutomaApp/automa ](#automaappautoma-)
		- [CopilotKit/CopilotKit ](#copilotkitcopilotkit-)
	- [研究论文](#研究论文)
	- [教程和课程](#教程和课程)
	- [社区和会议](#社区和会议)

## 简介



人工通用智能（AGI）旨在创建能够执行任何人类可以进行的智力任务的智能代理。该仓库致力于收集和展示最有前景的 AGI 项目、研究、工具和资源。

## 应用项目



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


 ## 工具



### [run-llama/create-llama](https://github.com/run-llama/create-llama) ![GitHub stars](https://img.shields.io/github/stars/run-llama/create-llama?style=social)

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

 ###  [AutomaApp/automa](https://github.com/AutomaApp/automa) ![GitHub stars](https://img.shields.io/github/stars/AutomaApp/automa?style=social)

 

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

### [CopilotKit/CopilotKit](https://github.com/CopilotKit/CopilotKit) ![GitHub stars](https://img.shields.io/github/stars/CopilotKit/CopilotKit?style=social)

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

## 研究论文

- **论文标题**：论文贡献和发现的简要总结。
- **论文标题**：论文贡献和发现的简要总结。


## 教程和课程

- **课程名称**：课程内容的简短描述。
- **课程名称**：课程内容的简短描述。

## 社区和会议

- **社区/会议名称**：社区或会议的简短描述和链接。
- **社区/会议名称**：社区或会议的简短描述和链接。
