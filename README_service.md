# Awesome-AGI

欢迎来到 **Awesome-AGI**，这是一个精心整理的人工通用智能（AGI）项目和资源列表。

觉得有用请点个 Star 吧！

## 目录

- [Awesome-AGI](#awesome-agi)
	- [目录](#目录)
	- [服务项目](#服务项目)
		- [ollama ](#ollama-)
		- [Hujiazeng/Vach 数字人 ](#hujiazengvach-数字人-)
		- [janhq/jan](#janhqjan)
		- [modelscope/swift  训练模型 ](#modelscopeswift--训练模型-)
		- [modelscope/DashInfer 推理 ](#modelscopedashinfer-推理-)
		- [unslothai/unsloth 微调 ](#unslothaiunsloth-微调-)


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


### [Hujiazeng/Vach](https://github.com/Hujiazeng/Vach) 数字人 ![GitHub stars](https://img.shields.io/github/stars/Hujiazeng/Vach?style=social)


**Hujiazeng/Vach** 是一个开源项目，提供了一个实时流式的数字人头部聊天系统，支持文本和语音交互，并且可以与SyncTalk项目协同工作，包括声音克隆和直播间业务，适用于展厅显示屏互动，已经可以达到商用效果。

**摘要**

**Hujiazeng/Vach** 项目是一个在GitHub上公开的仓库，专注于实现音视频同步的数字人头部聊天系统。该项目目前获得了294个星标和9个监视者，并有41个分叉。项目的最新提交是在2024年5月17日，主要进行了全身推理性能优化。项目结构包括模块如 `ai_module`、`core`、`links`、`talkers` 和 `web`，以及关键文件 `.gitignore`、`README.md`、`app.py` 和 `requirements.txt`。

项目支持的特性包括文本和语音交互、SyncTalk项目的支持、声音克隆、直播间业务和展厅显示屏互动。安装依赖需要Python 3.10环境，以及特定版本的Pytorch和CUDA。项目提供了预训练模型下载和测试，用户也可以替换成自己训练的模型。快速启动项目可以通过执行 `python app.py` 命令，并且可以通过 `--mike` 参数开启麦克风监听功能。如果无法访问huggingface，需要设置环境变量 `HF_ENDPOINT`。

项目的开发依赖于 `aiortc`、`ER-NeRF` 和 `SyncTalk`。语言使用情况主要是Python，其次是Cuda、HTML、C、C++和JavaScript。

**特点**

- **项目创新性**: Hujiazeng/Vach 项目实现了流式数字人头部聊天系统，具有商用潜力，体现了人工智能在虚拟助手领域的应用前景。
- **技术实现**: 项目依赖于先进的技术栈，如Pytorch、CUDA和Python，同时整合了其他开源项目的优势，如 `aiortc`、`ER-NeRF` 和 `SyncTalk`，展现了开源生态的协作力量。
- **用户交互**: 支持多种交互方式，包括文本和语音，提供了丰富的用户体验，适应了不同的应用场景，如直播互动和展厅互动。
- **社区支持**: 项目鼓励用户参与，提供了详细的安装和使用指南，同时开设了交流群以促进社区成员之间的交流和协作。
- **性能优化**: 项目不断进行性能优化，如全身推理性能优化，确保了系统的实时性和流畅性。
- **模块化设计**: 项目采用模块化设计，方便用户理解和扩展，同时也便于项目的维护和更新。
- **多平台支持**: 提供了跨平台的安装方案，支持Ubuntu系统，并且可以通过Web界面进行交互，增加了项目的可访问性。

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
