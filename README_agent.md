# Awesome-AGI

欢迎来到 **Awesome-AGI**，这是一个精心整理的人工通用智能（AGI）项目和资源列表。

觉得有用请点个 Star 吧！

## 目录

- [Awesome-AGI](#awesome-agi)
	- [目录](#目录)
	- [简介](#简介)
	- [智能体](#智能体)
		- [microsoft/autogen ](#microsoftautogen-)
		- [lobehub/lobe-chat-agents ](#lobehublobe-chat-agents-)
		- [cpacker/MemGPT ](#cpackermemgpt-)
		- [AgentScope/modelscope  ](#agentscopemodelscope--)
		- [joaomdmoura/crewAI ](#joaomdmouracrewai-)
		- [jgravelle/AutoGroq ](#jgravelleautogroq-)
		- [phidatahq/phidata ](#phidatahqphidata-)
		- [andrewyng/translation-agent ](#andrewyngtranslation-agent-)

## 简介



人工通用智能（AGI）旨在创建能够执行任何人类可以进行的智力任务的智能代理。该仓库致力于收集和展示最有前景的 AGI 项目、研究、工具和资源。



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


### [phidatahq/phidata](https://github.com/phidatahq/phidata) ![GitHub stars](https://img.shields.io/github/stars/phidatahq/phidata?style=social)


phidatahq/phidata 是一个用于构建具有长期记忆、上下文知识和执行任务能力的自治助手（即代理）的框架。

**概述**

phidatahq/phidata 是一个开源框架，旨在通过添加记忆、知识和工具来克服大型语言模型（LLMs）的局限性，如有限的上下文和无法执行操作的问题。该框架允许开发者创建能够存储聊天历史、访问业务相关信息以及执行 API 调用、发送电子邮件或查询数据库等操作的助手。phidata 支持使用 Streamlit、FastApi 或 Django 部署助手应用程序。安装过程简单，可以通过 pip 安装，并且提供了多个示例代码，如使用 LLMs 作为操作系统的中心处理器、构建自治引用答案生成器（RAG）、本地 RAG、投资研究助手、新闻文章编写、YouTube 视频摘要、研究助手等。此外，还有 Python 助手、SQL 分析助手、PDF 助手等，它们可以执行特定的任务，如编写和运行 Python 代码、使用 SQL 进行数据分析、从 PDF 文件中回答问题等。phidata 还提供了一个烹饪书示例库，用于展示更深入的代码示例和实践。项目鼓励社区贡献，并提供了贡献指南，同时还有一个公开的路线图，展示了未来的发展方向。

**特点**

- **问题与解决方案**: phidata 框架解决了 LLMs 有限上下文和无法执行操作的问题，通过添加记忆、知识和工具来增强助手的能力。
- **组件与工作流程**: 助手的构建包括三个主要组件：工具（函数调用）、知识（向量数据库）和存储（数据库）。开发者可以通过创建助手、添加组件并使用所选的框架（如 Streamlit）来部署 AI 应用程序。
- **易用性**: 提供了详细的安装指南和快速入门示例，使得开发者能够快速上手并创建具有特定功能的助手。
- **实际应用**: 通过多种示例展示了 phidata 在不同场景下的应用，如构建 LLM 操作系统、本地 RAG、投资研究助手等，这些示例展示了框架的灵活性和强大功能。
- **社区与支持**: 鼓励社区参与贡献，提供了贡献指南，并且有一个公开的路线图，表明项目的透明度和对未来发展的规划。
- **商业应用**: 提供了构建 AI 产品的一般工作流程，包括构建定制的助手、连接产品到助手以及监控和改进 AI 产品，同时还提供了专门的支持和开发服务。



### [andrewyng/translation-agent](https://github.com/andrewyng/translation-agent) ![GitHub stars](https://img.shields.io/github/stars/andrewyng/translation-agent?style=social)


andrewyng/translation-agent 是一个开源的 Python 项目，旨在演示使用大型语言模型（LLM）进行机器翻译的代理工作流程，通过提示、反思和改进步骤来提高翻译质量。

**概述**

**andrewyng/translation-agent** 项目是一个探索性的机器翻译解决方案，它采用了一种代理工作流程，利用大型语言模型（LLM）进行翻译。该项目的主要步骤包括：向 LLM 提出翻译请求、让 LLM 反思其翻译并提出改进建议、以及使用这些建议来提升翻译结果。项目特点是高度可定制，可以通过调整提示来改变翻译风格、处理俚语和专业术语、以及针对特定地区或方言进行翻译。目前项目仍处于初级阶段，由 Andrew Ng 及其合作者开发，旨在促进进一步的讨论、实验、研究和开源贡献。根据 BLEU 分数评估，该工作流程在某些情况下与商业领先产品竞争，但也存在性能不稳定的情况。项目还提供了一种自动生成并行文本语料库的方法，这些语料库可用于进一步训练和改进传统的机器翻译算法。项目鼓励社区成员尝试不同的 LLM、构建专业术语词汇表、评估不同语言的性能、进行错误分析以及设计更好的评估指标。

**特点**

* **代理翻译工作流程**：通过 LLM 的提示、反思和改进步骤，可能会产生比传统端到端翻译模型更好的翻译结果。
* **可定制性**：项目的设计允许用户根据需求调整翻译风格、处理特殊术语和地区性语言。
* **自动生成训练数据**：该方法可以用来自动生成并行文本语料库，有助于改进传统的机器翻译系统。
* **社区贡献和扩展**：项目鼓励开源社区探索其他 LLM、构建和使用词汇表、评估不同语言的表现、进行错误分析，以及设计更好的评估指标。
* **评估和改进**：BLEU 分数等当前评估指标可能不足以捕捉到文档级别的翻译质量，需要开发新的评估方法以更好地反映人类偏好。
* **研究方向**：代理翻译是一个有前景的研究领域，有望进一步提高翻译质量，特别是对于低资源语言和特定领域的翻译。



