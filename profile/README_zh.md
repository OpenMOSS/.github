<div align="center">

<img src="https://raw.githubusercontent.com/OpenMOSS/.github/main/profile/assets/moss-logo.svg" width="360" alt="OpenMOSS" />

**面向语音、视频、语言与具身智能的开放模型。**

提供可运行、可研究、可扩展的模型、数据集、评测基准与工具。

[团队网站](https://openmoss.ai/) · [模型下载](https://huggingface.co/OpenMOSS-Team) · [全部仓库](https://github.com/orgs/OpenMOSS/repositories) · [关注动态](https://x.com/Open_MOSS)

[English](https://github.com/OpenMOSS/.github/blob/main/profile/README.md) · 简体中文

</div>

## 按用途找到项目

| 你想完成的任务 | 项目 | 从这里开始 |
| --- | --- | --- |
| 在 CPU 上合成语音、克隆音色 | **[MOSS-TTS-Nano](https://github.com/OpenMOSS/MOSS-TTS-Nano)**：1 亿参数、多语言、支持 ONNX 推理 | [在线体验](https://huggingface.co/spaces/OpenMOSS-Team/MOSS-TTS-Nano) · [本地运行](https://github.com/OpenMOSS/MOSS-TTS-Nano/blob/main/README_zh.md#快速开始) |
| 生成长篇朗读、多人对话、音色或音效 | **[MOSS-TTS](https://github.com/OpenMOSS/MOSS-TTS)**：语音与声音生成模型家族 | [选择模型](https://github.com/OpenMOSS/MOSS-TTS/blob/main/README_zh.md#选择适合任务的模型) · [模型下载](https://huggingface.co/collections/OpenMOSS-Team/moss-tts) |
| 转写会议、播客与访谈 | **[MOSS-Transcribe-Diarize](https://github.com/OpenMOSS/MOSS-Transcribe-Diarize)**：0.9B 参数、50 多种语言、说话人标记与时间戳 | [字幕应用](https://github.com/OpenMOSS/MOSS-Transcribe-Diarize/blob/main/README_zh.md#字幕-web-应用) · [模型下载](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize) |
| 理解语音、环境音与音乐 | **[MOSS-Audio](https://github.com/OpenMOSS/MOSS-Audio)**：音频描述、问答与推理 | [本地运行](https://github.com/OpenMOSS/MOSS-Audio/blob/main/README_zh.md#快速开始) · [模型下载](https://huggingface.co/collections/OpenMOSS-Team/moss-audio) |
| 理解长视频或与实时视频流交互 | **[MOSS-VL](https://github.com/OpenMOSS/MOSS-VL)**：11B 参数，支持离线与实时视频理解 | [在线体验](https://huggingface.co/spaces/OpenMOSS-Team/MOSS-VL) · [项目主页](https://openmoss.ai/MOSS-VL/) |
| 生成声画同步的视频 | **[MOVA](https://github.com/OpenMOSS/MOVA)**：联合音视频生成，提供训练与 LoRA 微调流程 | [观看样例](https://github.com/OpenMOSS/MOVA#demo) · [模型下载](https://huggingface.co/collections/OpenMOSS-Team/mova) |
| 训练和评测世界动作模型 | **[EasyWAM](https://github.com/OpenMOSS/EasyWAM)**：统一训练、微调与评测流程 | [项目主页](https://openmoss.ai/EasyWAM/) · [模型下载](https://huggingface.co/collections/OpenMOSS-Team/easywam) |

## 研究工具与评测基准

- **[OmniVAE](https://github.com/OpenMOSS/OmniVAE)**：在对齐的潜在空间中编码和重建音视频，并提供联合生成流程。[项目主页](https://openmoss.ai/OmniVAE.github.io/)。
- **[Llamascopium](https://github.com/OpenMOSS/Llamascopium)**：训练稀疏自编码器、追踪电路、可视化学习到的特征。[使用文档](https://openmoss.ai/Llamascopium/)。
- **[SWE-bench-Science](https://github.com/OpenMOSS/SWE-bench-Science)**：用科学软件中的工程任务评测编程智能体。[排行榜](https://swescience.github.io/)。智能体记忆与超参数优化研究另见 [ContextWeave](https://github.com/OpenMOSS/ContextWeave) 和 [AgentHPOBench](https://github.com/OpenMOSS/AgentHPOBench)。
- **[Awesome-WAM](https://github.com/OpenMOSS/Awesome-WAM)**：通过综述、论文目录与[基准对比](https://openmoss.ai/Awesome-WAM/leaderboard/)了解世界动作模型。具身智能体研究另见 [OpenETA](https://github.com/OpenMOSS/OpenETA)、[RoboOmni](https://github.com/OpenMOSS/RoboOmni) 和 [FRoM-W1](https://github.com/OpenMOSS/FRoM-W1)。

<details>
<summary><b>展开全部研究方向</b></summary>

| 方向 | 项目 |
| --- | --- |
| 语言模型与后训练 | [MOSS](https://github.com/OpenMOSS/MOSS) · [DiRL](https://github.com/OpenMOSS/DiRL) · [BandPO](https://github.com/OpenMOSS/BandPO) |
| 视觉理解 | [MOSS-VL](https://github.com/OpenMOSS/MOSS-VL) · [MOSS-Video-Preview](https://github.com/OpenMOSS/MOSS-Video-Preview) |
| 多模态生成与建模 | [MOVA](https://github.com/OpenMOSS/MOVA) · [OmniVAE](https://github.com/OpenMOSS/OmniVAE) · [AnyGPT](https://github.com/OpenMOSS/AnyGPT) |
| 语音与声音生成 | [MOSS-TTS](https://github.com/OpenMOSS/MOSS-TTS) · [MOSS-TTS-Nano](https://github.com/OpenMOSS/MOSS-TTS-Nano) · [MOSS-TTSD](https://github.com/OpenMOSS/MOSS-TTSD) · [MOSS-Speech](https://github.com/OpenMOSS/MOSS-Speech) · [MOSS-Audio-Tokenizer](https://github.com/OpenMOSS/MOSS-Audio-Tokenizer) |
| 语音、音频与音乐理解 | [MOSS-Transcribe-Diarize](https://github.com/OpenMOSS/MOSS-Transcribe-Diarize) · [MOSS-Audio](https://github.com/OpenMOSS/MOSS-Audio) · [MOSS-Music](https://github.com/OpenMOSS/MOSS-Music) |
| 具身智能与机器人 | [EasyWAM](https://github.com/OpenMOSS/EasyWAM) · [OpenETA](https://github.com/OpenMOSS/OpenETA) · [RoboOmni](https://github.com/OpenMOSS/RoboOmni) · [FRoM-W1](https://github.com/OpenMOSS/FRoM-W1) |
| 可解释性 | [Llamascopium](https://github.com/OpenMOSS/Llamascopium)（原 Language-Model-SAEs）· [Lorsa](https://github.com/OpenMOSS/Lorsa) |
| 评测基准 | [SWE-bench-Science](https://github.com/OpenMOSS/SWE-bench-Science) · [ContextWeave](https://github.com/OpenMOSS/ContextWeave) · [AgentHPOBench](https://github.com/OpenMOSS/AgentHPOBench) · [FutureOmni](https://github.com/OpenMOSS/FutureOmni) · [VLABench](https://github.com/OpenMOSS/VLABench) |
| 高效训练与长上下文 | [CoLLiE](https://github.com/OpenMOSS/CoLLiE) · [LongLLaDA](https://github.com/OpenMOSS/LongLLaDA) · [Sparse-dLLM](https://github.com/OpenMOSS/Sparse-dLLM) · [rope_pp](https://github.com/OpenMOSS/rope_pp) · [LongSafety](https://github.com/OpenMOSS/LongSafety) |
| 综述与资源 | [Awesome-WAM](https://github.com/OpenMOSS/Awesome-WAM) · [Thus-Spake-Long-Context-LLM](https://github.com/OpenMOSS/Thus-Spake-Long-Context-LLM) |

</details>

## 一起参与

从项目 README 中的使用说明开始。遇到可复现的问题、希望改进文档或贡献应用集成，可以在对应仓库提交 Issue 或 Pull Request。研究中使用模型或数据集时，请引用该仓库列出的相应工作。

在 [Hugging Face](https://huggingface.co/OpenMOSS-Team) 关注模型与数据集，在 [X / @Open_MOSS](https://x.com/Open_MOSS) 关注发布动态。

OpenMOSS 由**邱锡鹏教授**领衔，依托**上海创智学院（SII）**，与**复旦大学**和 **MOSI.AI** 合作开展研究。科研合作、博士及实习机会咨询，请联系 **[openmoss@sii.edu.cn](mailto:openmoss@sii.edu.cn)**。
