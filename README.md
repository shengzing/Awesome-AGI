# Awesome-AGI

欢迎来到 **Awesome-AGI**，这是一个精心整理的人工通用智能（AGI）项目和资源列表。

觉得有用请点个 Star 吧！

## 目录

- [Awesome-AGI](#awesome-agi)
	- [目录](#目录)
	- [简介](#简介)
	- [多模态](#多模态)
		- [alibaba-damo-academy/FunClip视频剪辑 ](#alibaba-damo-academyfunclip视频剪辑-)
		- [MoneyPrinterTurbo 视频合成](#moneyprinterturbo-视频合成)
		- [rany2/edge-tts ](#rany2edge-tts-)
		- [ictnlp/StreamSpeech 声音 ](#ictnlpstreamspeech-声音-)
	- [算法](#算法)
		- [naklecha/llama3-from-scratch ](#naklechallama3-from-scratch-)
		- [lencx/Noi ](#lencxnoi-)
		- [multimodal-art-projection/MAP-NEO ](#multimodal-art-projectionmap-neo-)
		- [XuezheMax/megalodon](#xuezhemaxmegalodon)
		- [danielmiessler/fabric 提示词 ](#danielmiesslerfabric-提示词-)
	- [benchmark](#benchmark)
		- [FudanVI/benchmarking-chinese-text-recognition ](#fudanvibenchmarking-chinese-text-recognition-)
	- [研究论文](#研究论文)
	- [教程和课程](#教程和课程)
		- [microsoft/llmops-workshop ](#microsoftllmops-workshop-)
	- [社区和会议](#社区和会议)

## 简介



人工通用智能（AGI）旨在创建能够执行任何人类可以进行的智力任务的智能代理。该仓库致力于收集和展示最有前景的 AGI 项目、研究、工具和资源。


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

### [rany2/edge-tts](https://github.com/rany2/edge-tts) ![GitHub stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social)



`edge-tts` 是一个允许在 Python 代码中使用微软 Edge 浏览器的在线文本到语音服务的模块，无需安装 Edge 浏览器、Windows 操作系统或 API 密钥。

**摘要**

`edge-tts` 是一个开源的 Python 模块，它允许开发者通过 Python 代码或命令行工具 `edge-tts` 和 `edge-playback` 使用微软 Edge 的在线文本到语音（TTS）服务。该模块支持将文本转换为语音文件，并可以生成字幕文件。用户可以通过 `pip` 或 `pipx` 安装该模块。`edge-tts` 提供了多种语言和声音选项，允许用户自定义语音的速率、音量和音调。此外，`edge-tts` 支持直接播放生成的语音，但需要安装 `mpv` 命令行播放器。自 5.0.0 版本起，`edge-tts` 不再支持自定义 SSML（语音合成标记语言），因为微软阻止了这一功能。该项目在 GitHub 上有 4k 个星标、41 个关注者和 426 个叉子，使用 Python 语言编写了 97.7% 的代码，另有 2.3% 的 Shell 脚本。

**特点**

- **无需依赖微软 Edge 浏览器或 Windows 系统**: `edge-tts` 模块使得在任何支持 Python 的平台上都能够利用微软 Edge 的 TTS 服务，无需安装 Edge 浏览器或在 Windows 系统上运行。
- **易于安装和使用**: 用户可以通过 `pip` 或 `pipx` 轻松安装 `edge-tts`，并通过命令行或 Python 代码直接使用 TTS 功能。
- **丰富的语言和声音选项**: 用户可以通过 `--list-voices` 选项查看所有可用的语言和声音，并选择合适的声音进行文本转语音。
- **自定义语音特性**: 用户可以调整语音的速率、音量和音调，以适应特定的使用场景。
- **生成字幕和语音文件**: `edge-tts` 支持输出语音文件和对应的字幕文件，方便用户进行后续处理或播放。
- **不支持自定义 SSML**: 由于微软的限制，`edge-tts` 从 5.0.0 版本开始不再支持自定义 SSML，用户必须使用微软提供的标准 SSML。
- **社区活跃和开源**: 该项目在 GitHub 上拥有大量的星标和叉子，反映了其在社区中的流行度和活跃度，同时遵循 GPL-3.0 许可证，鼓励社区贡献和共享。


**特点**

### [ictnlp/StreamSpeech](https://github.com/ictnlp/StreamSpeech) 声音 ![GitHub Repo Stars](https://img.shields.io/github/stars/ictnlp/StreamSpeech?style=social)



StreamSpeech 是一个集成了离线和同声传译功能的综合模型，支持多种语音识别、翻译和合成任务。

**摘要**

StreamSpeech 是一个开源的“全能型”语音模型，它能够在离线和同声模式下进行语音识别（ASR）、语音到文本的翻译（S2TT）、语音到语音的翻译（S2ST）以及语音合成（TTS）。该模型在 ACL 2024 会议上发布了相关论文，并提供了代码、模型、演示和文档。StreamSpeech 支持 8 种任务，包括离线和同声模式下的各种组合，并且可以通过 GUI 演示进行体验。模型可以从 Huggingface 和 Baidu 网盘下载，并且提供了详细的安装、配置和运行指南。此外，StreamSpeech 还支持自定义数据和模型训练，并且提供了多种评估方法和指标。作者鼓励用户提出问题和建议，并提供了联系方式。最后，作者还提供了引用方式，以便其他研究人员能够正确引用这项工作。

**特点**

- **创新性**: StreamSpeech 模型在同声传译领域取得了最先进的性能，它能够同时处理流式 ASR、同声语音到文本翻译和同声语音到语音翻译。
- **多功能性**: 该模型能够在任何延迟下进行实时 TTS，并且支持单个模型同时处理多种任务。
- **用户体验**: StreamSpeech 提供了一个 GUI 演示，用户可以在本地浏览器中体验同声传译的效果。
- **数据和配置**: 模型的使用需要准备测试数据和配置文件，并且提供了详细的指导来确保模型能够正确运行。
- **开源和可扩展性**: StreamSpeech 的代码和模型都是开源的，研究人员和开发者可以在此基础上进行二次开发和扩展。
- **评估和指标**: 提供了多种评估脚本和指标，以便用户能够评估模型在不同任务上的性能。
- **引用和贡献**: 作者强调了引用 StreamSpeech 的重要性，并鼓励用户对项目做出贡献。
- 



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

### [lencx/Noi](https://github.com/lencx/Noi) ![GitHub stars](https://img.shields.io/github/stars/lencx/Noi?style=social)

**Noi** 是一个基于 AI 的定制化浏览器，旨在通过探索、扩展和赋能，提升用户的数字体验。

**摘要**

**Noi** 是一个由 AI 增强的、高度可定制的浏览器，它旨在通过提供个性化的浏览体验、强大的提示管理、批量消息发送、多种主题选择、独特的缓存模式以及账户数据隔离等功能，来简化和优化用户的数字生活。用户可以通过添加自定义链接来同步自己的数据，并且可以选择不同的模式来使用 Noi。此外，Noi 支持多平台下载，包括 macOS、Windows 和 Linux。项目提供了详细的文档和常见问题解答，以帮助用户更好地理解和使用 Noi。目前，Noi 还没有实现自动更新功能，用户需要自行关注新版本的发布。Noi 的开发者鼓励用户参与到 Noi 的社区中来，分享经验和反馈，同时也提供了打赏的方式来支持项目。

**观点**

- **定制化体验**: Noi 允许用户创建自定义的浏览模式，添加任意 URL，并提供丰富的主题选择，以满足不同用户的需求。
- **提升生产力**: 通过 Noi Ask 功能，用户可以同时向多个 AI 聊天发送批量消息，提高了与 AI 服务交互的效率。
- **便捷的数据同步**: Noi 提供了同步数据的功能，允许用户通过自定义链接来同步自己的数据，并且支持多账户数据隔离。
- **跨平台支持**: Noi 支持 macOS、Windows 和 Linux 系统，确保了广泛的用户基础可以使用。
- **社区支持与参与**: Noi 鼓励用户参与到社区中来，提供反馈，并通过公众号进行交流和讨论。
- **持续更新**: Noi 项目持续更新，包括新功能的添加和现有功能的改进，以提供更好的用户体验。
- **技术细节**: Noi 的开发依赖于 JavaScript、TypeScript 和 CSS，这些技术的使用使得 Noi 能够提供流畅和现代化的用户界面。 


### [multimodal-art-projection/MAP-NEO](https://github.com/multimodal-art-projection/MAP-NEO) ![GitHub stars](https://img.shields.io/github/stars/multimodal-art-projection/MAP-NEO?style=social)


**MAP-NEO** 是一个完全开源的大型语言模型，包括预训练数据、数据处理流程、预训练脚本和对齐代码。该模型从头开始训练了4.5万亿英文和中文token，性能与LLaMA2 7B相当，在推理、数学和编程等挑战性任务中表现出与专有模型相当的性能。MAP-Neo 旨在实现LLM训练过程的完全透明度，为研究目的而进行了全面的发布，包括最终和中间检查点、自训练的分词器、预训练语料库和高效、稳定的优化过的预训练代码库。

**观点**

MAP-NEO 是一个开源的大型语言模型，它包括了预训练数据、数据处理管道（Matrix）、预训练脚本和对齐代码。该模型在4.5万亿英文和中文token上进行了从头开始的训练，并在各种基准测试中展示了与LLaMA2 7B相当的性能。MAP-Neo 在推理、数学和编程等任务中表现出色，超过了同类规模的其他模型。为了支持学术和商业界的更广泛和多样化的研究，MAP-NEO 公开发布了7B基础模型和一系列中间检查点。该项目遵循 MIT 许可证，并提供了 WeChat 和 Discord 的联系方式供进一步沟通。此外，还提供了数据和模型的下载链接，以及项目的一些技术细节，如编程语言的使用比例。

**优点**

- **开源性**: MAP-NEO 强调其完全开源的特性，包括预训练数据、数据处理流程、预训练脚本和对齐代码，旨在推动大型语言模型研究的透明度和可重复性。
- **性能**: MAP-NEO 7B 在各种基准测试中表现出与 LLaMA2 7B 相当的性能，尤其在推理、数学和编程等挑战性任务中。
- **研究支持**: 通过发布最终和中间检查点、自训练的分词器、预训练语料库和优化过的预训练代码库，MAP-NEO 支持更广泛的研究。
- **许可和使用**: 项目遵循 MIT 许可证，允许商业使用，并提供了 WeChat 和 Discord 的联系方式供进一步沟通。
- **数据和模型下载**: MAP-NEO 提供了 Huggingface 上的模型和数据下载链接，方便研究人员和开发者获取和使用。
- **社区和沟通**: 项目鼓励社区参与和反馈，通过 WeChat 和 Discord 提供了沟通渠道。
- **技术细节**: 项目主要使用 Python 语言（98.7%），并且没有发布任何版本或包。


### [XuezheMax/megalodon](https://github.com/XuezheMax/megalodon)![GitHub stars](https://img.shields.io/github/stars/XuezheMax/megalodon?style=social)



`https://github.com/XuezheMax/megalodon` 是 Megalodon 7B 模型的参考实现，提供了大型语言模型（LLM）的高效预训练和推理方法，支持无限制的上下文长度。

**观点**

该网页是 Megalodon 7B 模型的 GitHub 仓库，由 Xuezhe Ma 等人维护。Megalodon 是一个专注于提高大型语言模型（LLM）预训练和推理效率的项目，同时支持无限制的上下文长度。该项目于 2024 年 4 月 15 日向公众发布。仓库包含了必要的安装指南，包括 PyTorch、Apex 和 Fairscale 的安装步骤，以及如何安装 Megalodon 本身。此外，还提供了评估预训练 LLM 的方法，包括使用 `torchrun` 或 `slurm` 启动评估作业的示例脚本，以及如何准备评估数据。对于 LLM 预训练，网页提供了一个伪代码示例，展示了如何初始化模型、构建优化器和调度器，以及如何进行训练循环。该项目的参考文献包括了 Megalodon 和 Mega（Moving Average Equipped Gated Attention）的相关研究论文。该仓库目前没有发布任何版本，也没有发布任何包。项目的主要编程语言是 Cuda、Python 和 C++。

**优点**

- **Megalodon 项目旨在提供高效的大型语言模型（LLM）预训练和推理解决方案**，特别是在处理长文本上下文时。
- **项目提供了详细的安装和使用指南**，包括如何安装必要的依赖项和如何设置评估和预训练作业。
- **Megalodon 模型支持无限制的上下文长度**，这在处理大型文本数据时非常重要。
- **该项目的研究成果已经在学术论文中得到了展示**，这表明了其在科学研究和工程实践中的应用潜力。
- **GitHub 仓库包含了所有必要的代码和配置文件**，以便开发者和研究人员可以轻松地复现结果和进行二次开发。
- **该项目还没有发布正式版本**，这意味着它可能仍在积极开发中，或者正在进行测试和完善。
- **仓库的活动指标显示了项目的受欢迎程度**，例如星标数量、关注者数量和叉库数量。


### [danielmiessler/fabric](https://github.com/danielmiessler/fabric) 提示词 ![GitHub stars](https://img.shields.io/github/stars/danielmiessler/fabric?style=social)

`fabric`是一个开源框架，旨在利用AI增强人类能力，提供模块化解决方案，通过众包的AI提示集合，可以在任何地方应用这些解决方案。

**观点**

`fabric`框架旨在通过AI技术帮助人们解决具体问题题，它提供了一个基于Markdown的模板系统，用于创建和分享AI提示，即“Patterns”。这些Patterns可以用于各种生活和工作场景，如提取视频或播客中的精华内容、撰写文章、总结学术论文、创建AI艺术提示、评估内容质量等。`fabric`框架包括三个主要组件：Mill（服务器）、Patterns（AI使用案例）和Stitches（链式的Patterns），以及Loom（客户端应用）。用户可以通过命令行直接使用Patterns，也可以搭建自己的Fabric Mill服务器，或者使用Fabric提供的帮助工具，如`yt`命令从YouTube视频中提取字幕，`ts`命令使用OpenAI Whisper API对音频文件进行转录。此外，`fabric`还支持自定义Patterns，并且已经集成了PraisonAI，允许创建AI代理来执行任务。`fabric`项目由Daniel Miessler于2024年1月创立，并得到了多位贡献者的支持和贡献。

**优点**

1. **AI整合问题**: `fabric`框架的创建是为了解决AI技术在实际应用中的整合问题，即AI技术虽然强大，但难以融入日常生活中。
2. **人类创造力的放大器**: `fabric`认为AI不是一个独立的实体，而是人类创造力的放大器，它的目的是帮助人类繁荣。
3. **问题分解方法**: `fabric`的方法是将问题分解成小块，然后分别应用AI技术。
4. **Patterns的重要性**: `fabric`强调Patterns的重要性，它们是预先设计的AI提示，可以帮助用户更好地利用AI技术。
5. **开源和社区驱动**: `fabric`鼓励社区成员分享和贡献Patterns，以便不断完善和扩展框架的功能。
6. **命令行优先**: `fabric`是命令行优先的，它允许用户直接在命令行中使用Patterns，同时也提供了搭建个人AI服务器的代码。
7. **技术栈**: `fabric`使用Python作为主要编程语言，同时也包含了JavaScript、HTML和CSS等技术栈。
8. **未来趋势**: `fabric`计划将框架从Python迁移到Go语言，以简化安装过程并提高性能。
9. **社区贡献**: `fabric`项目得到了多位贡献者的支持，他们在项目结构、客户端开发、服务器基础设施和依赖管理等方面做出了贡献。



## benchmark

### [FudanVI/benchmarking-chinese-text-recognition](https://github.com/FudanVI/benchmarking-chinese-text-recognition) ![GitHub stars](https://img.shields.io/github/stars/FudanVI/benchmarking-chinese-text-recognition?style=social)


该网页是一个开源项目，旨在为中文文本识别提供基准测试的数据集和基线模型。

**摘要**

FudanVI 的 `benchmarking-chinese-text-recognition` 项目是一个专门针对中文文本识别的基准测试仓库。该仓库包含了多个用于训练和测试的数据集，如场景文本、网页文本、文档文本和手写文本数据集，并且这些数据集已经转换为 lmdb 格式以便使用。项目还提供了六种代表性的基线模型，包括 CRNN、ASTER、MORAN、SAR、SEED 和 TransOCR，这些模型的实验结果和代码都已公开。此外，项目还提供了详细的实验设置和结果分析，以及相关的论文引用和如何引用该项目的指南。该项目的目的是为了推动中文文本识别领域的研究和实践。

**优点**

- **数据集**: 项目提供了多个数据集，包括场景、网页、文档和手写等类型的中文文本图像，以支持基准测试。
- **基线模型**: 选择了六种不同的基线方法，用于评估和比较中文文本识别的性能。
- **实验结果**: 提供了基线模型在各个数据集上的详细实验结果，包括准确率和召回率等指标。
- **代码和权重**: 所有基线模型的代码和训练后的权重都可以直接下载和使用。
- **更新和维护**: 项目定期更新，包括上传新的数据集和修改实验设置。
- **引用指南**: 提供了项目的引用方式，鼓励使用该项目的研究者进行正确引用。
- **贡献和感谢**: 项目团队表达了对贡献者和反馈者的感谢，强调了团队合作的重要性。
- **版权声明**: 项目受到版权保护，版权归 Fudan-FudanVI 所有。
## 研究论文

- **论文标题**：论文贡献和发现的简要总结。
- **论文标题**：论文贡献和发现的简要总结。


## 教程和课程

### [microsoft/llmops-workshop](https://github.com/microsoft/llmops-workshop) ![GitHub stars](https://img.shields.io/github/stars/microsoft/llmops-workshop?style=social)


**Microsoft/llmops-workshop** 是一个在 GitHub 上的公开仓库，旨在教授如何使用 Azure AI、Azure Machine Learning Prompt Flow、Content Safety 和 Azure OpenAI 高效地构建、评估、监控和部署基于大型语言模型的解决方案。

**概述**

Microsoft/llmops-workshop 仓库是一个专注于大型语言模型操作（LLMOps）的工作坊，提供了一系列的课程内容，指导用户如何利用 Azure 的各项服务来构建和管理基于大型语言模型的解决方案。该工作坊包括工作坊内容、交付指南和更改日志。仓库鼓励社区贡献，并要求贡献者同意贡献者许可协议（CLA）。此外，该项目采用了 Microsoft Open Source 行为准则，并提供了关于如何报告安全问题的指南。该仓库包含了 Microsoft 的商标和徽标，使用受 Microsoft 商标和品牌指南的约束。目前，该仓库有 77 颗星（收藏）、7 名观察者和 31 个分支（fork），但尚未发布任何正式版本。主要使用的编程语言是 Jupyter Notebook（98.4%）和 Shell（1.6%）。

**观点**

- **教育目的**: 该仓库的主要目的是教育和指导用户如何使用 Azure 平台的工具和服务来操作和部ploy 大型语言模型。
- **社区参与**: 项目鼓励并欢迎来自社区的贡献，同时提供了详细的贡献指南和许可协议流程。
- **合规性和行为准则**: 该项目强调对 Microsoft 的商标和品牌使用规范，并采用了 Microsoft Open Source 行为准则，确保项目环境的积极性和包容性。
- **安全性**: 提供了如何报告安全问题的指南，强调对项目安全性的重视。
- **开源协作**: 通过 GitHub 的星标、观察者和分支功能，展示了项目的开源精神和社区的活跃参与。
- **技术栈**: 仓库的内容主要以 Jupyter Notebook 形式提供，显示了该项目的技术偏好和应用场景。 

## 社区和会议

- **社区/会议名称**：社区或会议的简短描述和链接。
- **社区/会议名称**：社区或会议的简短描述和链接。
