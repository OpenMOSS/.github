<div align="center">

<img src="https://raw.githubusercontent.com/OpenMOSS/.github/main/profile/assets/moss-logo.svg" width="360" alt="OpenMOSS" />

**面向语音、视频、语言与具身智能的开放模型。**

提供可运行、可研究、可扩展的模型、数据集、评测基准与工具。

[团队网站](https://openmoss.ai/) · [模型下载](https://huggingface.co/OpenMOSS-Team) · [全部仓库](https://github.com/orgs/OpenMOSS/repositories) · [关注动态](https://x.com/Open_MOSS)

[English](https://github.com/OpenMOSS/.github/blob/main/profile/README.md) · 简体中文

</div>

## 项目导航

按方向浏览模型、训练框架、评测基准与研究资源。点击项目名进入代码仓库，右侧可直达模型、演示、论文或文档。

[语言模型](#user-content-language) · [视觉与生成](#user-content-vision) · [语音生成](#user-content-speech) · [音频理解](#user-content-audio) · [具身智能](#user-content-embodied) · [可解释性与训练](#user-content-methods) · [评测基准](#user-content-benchmarks) · [资源与工具](#user-content-resources)

<a id="language"></a>

### 语言模型与后训练

| 项目 | 主要能力与用途 | 直达入口 |
| --- | --- | --- |
| <a href="https://github.com/OpenMOSS/MOSS"><img src="https://raw.githubusercontent.com/OpenMOSS/.github/main/profile/assets/projects/moss.png" width="112" height="53" alt="MOSS logo"></a><br>**[MOSS](https://github.com/OpenMOSS/MOSS)** | 支持中英双语对话与工具调用 | [模型](https://github.com/OpenMOSS/MOSS#模型) · [使用说明](https://github.com/OpenMOSS/MOSS#下载安装) |
| <a href="https://github.com/OpenMOSS/DiRL"><img src="https://raw.githubusercontent.com/OpenMOSS/DiRL/main/static/images/DiRL.jpg" width="112" height="47" alt="DiRL logo"></a><br>**[DiRL](https://github.com/OpenMOSS/DiRL)** | 扩散语言模型的监督微调与强化学习 | [模型](https://huggingface.co/OpenMOSS-Team/DiRL-8B-Instruct) · [论文](https://arxiv.org/abs/2512.22234) |
| **[BandPO](https://github.com/OpenMOSS/BandPO)** | 面向大模型强化学习的概率感知策略优化 | [论文](https://arxiv.org/abs/2603.04918) |

**相关项目：** [Ultra-Innerthought](https://github.com/OpenMOSS/Ultra-Innerthought)（双语推理数据）

<a id="vision"></a>

### 视觉理解与多模态生成

| 项目 | 主要能力与用途 | 直达入口 |
| --- | --- | --- |
| <a href="https://github.com/OpenMOSS/MOSS-VL"><img src="https://raw.githubusercontent.com/OpenMOSS/MOSS-VL/main/assets/logo.png" width="82" height="56" alt="MOSS-VL logo"></a><br>**[MOSS-VL](https://github.com/OpenMOSS/MOSS-VL)** | 11B 参数，支持长视频理解与实时视频交互 | [体验](https://huggingface.co/spaces/OpenMOSS-Team/MOSS-VL) · [模型](https://huggingface.co/collections/OpenMOSS-Team/moss-vl) |
| <a href="https://github.com/OpenMOSS/MOVA"><img src="https://raw.githubusercontent.com/OpenMOSS/MOVA/main/assets/logo.png" width="112" height="53" alt="MOVA logo"></a><br>**[MOVA](https://github.com/OpenMOSS/MOVA)** | 声画同步生成，提供训练与 LoRA 微调流程 | [样例](https://github.com/OpenMOSS/MOVA#demo) · [模型](https://huggingface.co/collections/OpenMOSS-Team/mova) |
| **[OmniVAE](https://github.com/OpenMOSS/OmniVAE)** | 面向重建与联合生成的音视频对齐表征 | [主页](https://openmoss.ai/OmniVAE.github.io/) · [模型](https://huggingface.co/OpenMOSS-Team/OmniVAE) |
| <a href="https://github.com/OpenMOSS/AnyGPT"><img src="https://raw.githubusercontent.com/OpenMOSS/AnyGPT/main/static/images/logo.png" width="56" height="56" alt="AnyGPT logo"></a><br>**[AnyGPT](https://github.com/OpenMOSS/AnyGPT)** | 统一建模文本、语音、图像与音乐的多模态语言模型 | [演示](https://junzhan2000.github.io/AnyGPT.github.io/) · [数据集](https://huggingface.co/datasets/fnlp/AnyInstruct) |

**相关项目：** [MOSS-Video-Preview](https://github.com/OpenMOSS/MOSS-Video-Preview)（早期流式视频模型）

<a id="speech"></a>

### 语音与声音生成

| 项目 | 主要能力与用途 | 直达入口 |
| --- | --- | --- |
| **[MOSS-TTS](https://github.com/OpenMOSS/MOSS-TTS)** | 覆盖朗读、对话、音色设计与音效的模型家族 | [模型选型](https://github.com/OpenMOSS/MOSS-TTS/blob/main/README_zh.md#选择适合任务的模型) · [模型](https://huggingface.co/collections/OpenMOSS-Team/moss-tts) |
| **[MOSS-TTS-Nano](https://github.com/OpenMOSS/MOSS-TTS-Nano)** | 1 亿参数多语言音色克隆，支持 CPU 与 ONNX 推理 | [体验](https://huggingface.co/spaces/OpenMOSS-Team/MOSS-TTS-Nano) · [本地运行](https://github.com/OpenMOSS/MOSS-TTS-Nano/blob/main/README_zh.md#快速开始) |
| <a href="https://github.com/OpenMOSS/MOSS-TTSD"><img src="https://raw.githubusercontent.com/OpenMOSS/MOSS-TTSD/main/asset/ttsd.png" width="84" height="56" alt="MOSS-TTSD logo"></a><br>**[MOSS-TTSD](https://github.com/OpenMOSS/MOSS-TTSD)** | 长时、多说话人对话与播客语音合成 | [体验](https://huggingface.co/spaces/OpenMOSS-Team/MOSS-TTSD-v1.0) · [模型](https://huggingface.co/OpenMOSS-Team/MOSS-TTSD-v1.0) |
| <a href="https://github.com/OpenMOSS/MOSS-Speech"><img src="https://raw.githubusercontent.com/OpenMOSS/MOSS-Speech/main/assets/logo-large.png" width="112" height="30" alt="MOSS-Speech logo"></a><br>**[MOSS-Speech](https://github.com/OpenMOSS/MOSS-Speech)** | 无需文本引导的端到端语音对话 | [主页](http://moss-speech.open-moss.com/) · [论文](https://arxiv.org/abs/2510.00499) |
| **[MOSS-Audio-Tokenizer](https://github.com/OpenMOSS/MOSS-Audio-Tokenizer)** | 统一语音、环境音与音乐的流式音频编码 | [模型](https://huggingface.co/OpenMOSS-Team/MOSS-Audio-Tokenizer) · [论文](https://arxiv.org/abs/2602.10934) |

**相关项目：** [MOSS-TTS-Nano-Reader](https://github.com/OpenMOSS/MOSS-TTS-Nano-Reader)（浏览器朗读应用） · [SpeechGPT-2.0-preview](https://github.com/OpenMOSS/SpeechGPT-2.0-preview)（实时语音对话）

<a id="audio"></a>

### 语音、音频与音乐理解

| 项目 | 主要能力与用途 | 直达入口 |
| --- | --- | --- |
| <a href="https://github.com/OpenMOSS/MOSS-Transcribe-Diarize"><img src="https://raw.githubusercontent.com/OpenMOSS/MOSS-Transcribe-Diarize/main/moss_transcribe_diarize/app/static/favicon.svg" width="56" height="56" alt="MOSS-Transcribe-Diarize logo"></a><br>**[MOSS-Transcribe-Diarize](https://github.com/OpenMOSS/MOSS-Transcribe-Diarize)** | 0.9B 参数、50 多种语言转写，输出说话人标记与时间戳 | [字幕应用](https://github.com/OpenMOSS/MOSS-Transcribe-Diarize/blob/main/README_zh.md#字幕-web-应用) · [模型](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize) |
| <a href="https://github.com/OpenMOSS/MOSS-Audio"><img src="https://raw.githubusercontent.com/OpenMOSS/MOSS-Audio/main/assets/moss-audio-logo.png" width="84" height="56" alt="MOSS-Audio logo"></a><br>**[MOSS-Audio](https://github.com/OpenMOSS/MOSS-Audio)** | 面向真实场景音频的描述、问答与推理 | [主页](https://openmoss.ai/MOSS-Audio/) · [模型](https://huggingface.co/collections/OpenMOSS-Team/moss-audio) |
| <a href="https://github.com/OpenMOSS/MOSS-Music"><img src="https://raw.githubusercontent.com/OpenMOSS/MOSS-Music/main/assets/MOSS-Music.png" width="84" height="56" alt="MOSS-Music logo"></a><br>**[MOSS-Music](https://github.com/OpenMOSS/MOSS-Music)** | 音乐描述、歌词转写、结构分析与问答 | [模型](https://huggingface.co/OpenMOSS-Team/MOSS-Music-8B-Instruct) |

**相关项目：** [MOSS-Audio-Tokenizer-Eval](https://github.com/OpenMOSS/MOSS-Audio-Tokenizer-Eval)（音频编码器重建评测） · [TTSD-eval](https://github.com/OpenMOSS/TTSD-eval)（多说话人语音评测）

<a id="embodied"></a>

### 具身智能与机器人

| 项目 | 主要能力与用途 | 直达入口 |
| --- | --- | --- |
| <a href="https://github.com/OpenMOSS/EasyWAM"><img src="https://raw.githubusercontent.com/OpenMOSS/EasyWAM/main/assets/icon.png" width="56" height="56" alt="EasyWAM logo"></a><br>**[EasyWAM](https://github.com/OpenMOSS/EasyWAM)** | 世界动作模型的统一训练、微调与评测框架 | [主页](https://openmoss.ai/EasyWAM/) · [模型](https://huggingface.co/collections/OpenMOSS-Team/easywam) |
| <a href="https://github.com/OpenMOSS/OpenETA"><img src="https://raw.githubusercontent.com/OpenMOSS/OpenETA/main/docs/assets/openeta-header-eta-clear.png" width="112" height="39" alt="OpenETA logo"></a><br>**[OpenETA](https://github.com/OpenMOSS/OpenETA)** | 连接感知、行动、验证与学习的具身智能体 | [主页](https://openmoss.ai/OpenETA/) |
| <a href="https://github.com/OpenMOSS/RoboOmni"><img src="https://raw.githubusercontent.com/OpenMOSS/RoboOmni/main/assets/logo.png" width="112" height="28" alt="RoboOmni logo"></a><br>**[RoboOmni](https://github.com/OpenMOSS/RoboOmni)** | 面向多模态物理环境的主动式机器人操作 | [主页](https://openmoss.github.io/RoboOmni/) · [模型](https://huggingface.co/fnlp/RoboOmni) |
| **[FRoM-W1](https://github.com/OpenMOSS/FRoM-W1)** | 语言引导的人形机器人全身控制 | [主页](https://openmoss.github.io/FRoM-W1) |

**相关项目：** [Embodied-Planner-R1](https://github.com/OpenMOSS/Embodied-Planner-R1)（面向具身规划的强化学习）

<a id="methods"></a>

### 可解释性、高效训练与长上下文

| 项目 | 主要能力与用途 | 直达入口 |
| --- | --- | --- |
| **[Llamascopium](https://github.com/OpenMOSS/Llamascopium)** | 训练分析稀疏自编码器、追踪电路并可视化特征 | [文档](https://openmoss.ai/Llamascopium/) |
| <a href="https://github.com/OpenMOSS/CoLLiE"><img src="https://raw.githubusercontent.com/OpenMOSS/CoLLiE/main/docs/assets/images/banner.png" width="112" height="28" alt="CoLLiE logo"></a><br>**[CoLLiE](https://github.com/OpenMOSS/CoLLiE)** | 面向大语言模型的高效协同训练框架 | [文档](https://openlmlab-collie.readthedocs.io) |
| **[LongLLaDA](https://github.com/OpenMOSS/LongLLaDA)** | 扩展扩散语言模型的上下文长度 | [论文](https://arxiv.org/abs/2506.14429) |
| **[Sparse-dLLM](https://github.com/OpenMOSS/Sparse-dLLM)** | 通过缓存淘汰与稀疏注意力加速扩散语言模型 | [论文](https://arxiv.org/abs/2508.02558) |

**相关项目：** [Lorsa](https://github.com/OpenMOSS/Lorsa)（低秩稀疏注意力分解） · [rope_pp](https://github.com/OpenMOSS/rope_pp)（长上下文旋转位置编码） · [ReAttention](https://github.com/OpenMOSS/ReAttention)（无需训练的上下文扩展）

<a id="benchmarks"></a>

### 评测基准与智能体评测

| 项目 | 主要能力与用途 | 直达入口 |
| --- | --- | --- |
| **[SWE-bench-Science](https://github.com/OpenMOSS/SWE-bench-Science)** | 基于科学软件工程任务的编程智能体评测 | [排行榜](https://swescience.github.io/) · [数据集](https://huggingface.co/datasets/OpenMOSS-Team/SWE-bench-Science) |
| **[ContextWeave](https://github.com/OpenMOSS/ContextWeave)** | 通过长程工作日志任务评测编程智能体记忆 | [论文](http://arxiv.org/abs/2608.04830) |
| <a href="https://github.com/OpenMOSS/AgentHPOBench"><img src="https://raw.githubusercontent.com/OpenMOSS/AgentHPOBench/main/assets/agenthpobench-logo.png" width="112" height="37" alt="AgentHPOBench logo"></a><br>**[AgentHPOBench](https://github.com/OpenMOSS/AgentHPOBench)** | 评测大模型智能体的序贯超参数优化能力 | [论文](https://arxiv.org/abs/2607.29626) |
| **[ABC-Bench](https://github.com/OpenMOSS/ABC-Bench)** | 评测编程智能体构建、部署与验证后端服务的能力 | [主页](https://dawning-road.github.io/blog/abc-bench) |
| <a href="https://github.com/OpenMOSS/FutureOmni"><img src="https://raw.githubusercontent.com/OpenMOSS/FutureOmni/main/asset/logo0.png" width="58" height="56" alt="FutureOmni logo"></a><br>**[FutureOmni](https://github.com/OpenMOSS/FutureOmni)** | 根据音视频上下文预测未来事件 | [主页](https://openmoss.ai/FutureOmni/) · [数据集](https://huggingface.co/datasets/OpenMOSS-Team/FutureOmni) |
| **[VLABench](https://github.com/OpenMOSS/VLABench)** | 评测视觉语言动作模型与具身智能体 | [主页](https://vlabench.github.io/) |

**相关项目：** [LongSafety](https://github.com/OpenMOSS/LongSafety)（长上下文安全） · [VehicleWorld](https://github.com/OpenMOSS/VehicleWorld)（智能座舱交互） · [HalluQA](https://github.com/OpenMOSS/HalluQA)（中文幻觉评测） · [GAOKAO-MM](https://github.com/OpenMOSS/GAOKAO-MM)（中文多模态评测） · [Say-I-Dont-Know](https://github.com/OpenMOSS/Say-I-Dont-Know)（评测模型是否知道何时应承认不知道）

<a id="resources"></a>

### 综述、数据与开发工具

| 项目 | 主要能力与用途 | 直达入口 |
| --- | --- | --- |
| **[Awesome-WAM](https://github.com/OpenMOSS/Awesome-WAM)** | 世界动作模型综述、论文目录与基准对比 | [浏览](https://openmoss.ai/Awesome-WAM/) · [基准对比](https://openmoss.ai/Awesome-WAM/leaderboard/) |
| **[Thus-Spake-Long-Context-LLM](https://github.com/OpenMOSS/Thus-Spake-Long-Context-LLM)** | 覆盖架构、基础设施、训练与评测的长上下文综述 | [论文](https://arxiv.org/abs/2502.17129) |
| **[UnifiedToolHub](https://github.com/OpenMOSS/UnifiedToolHub)** | 工具调用数据处理，以及工具使用模型的训练与评测 | [快速上手](https://github.com/OpenMOSS/UnifiedToolHub#快速上手) |

**相关项目：** [claude-codex-handoff](https://github.com/OpenMOSS/claude-codex-handoff)（智能体协作协议） · [OurClaw](https://github.com/OpenMOSS/OurClaw)（多用户 OpenClaw 部署） · [imclaw-skill](https://github.com/OpenMOSS/imclaw-skill)（智能体即时通讯）

## 一起参与

从项目 README 中的使用说明开始。遇到可复现的问题、希望改进文档或贡献应用集成，可以在对应仓库提交 Issue 或 Pull Request。研究中使用模型或数据集时，请引用该仓库列出的相应工作。

在 [Hugging Face](https://huggingface.co/OpenMOSS-Team) 关注模型与数据集，在 [X / @Open_MOSS](https://x.com/Open_MOSS) 关注发布动态。

OpenMOSS 由**邱锡鹏教授**领衔，依托**上海创智学院（SII）**，与**复旦大学**和 **MOSI.AI** 合作开展研究。科研合作、博士及实习机会咨询，请联系 **[openmoss@sii.edu.cn](mailto:openmoss@sii.edu.cn)**。
