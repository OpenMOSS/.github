<div align="center">

<img src="https://raw.githubusercontent.com/OpenMOSS/.github/main/profile/assets/moss-logo.svg" width="360" alt="OpenMOSS" />

**面向语音、视频、语言与具身智能的开放模型。**

提供可运行、可研究、可扩展的模型、数据集、评测基准与工具。

[团队网站](https://openmoss.ai/) · [模型下载](https://huggingface.co/OpenMOSS-Team) · [全部仓库](https://github.com/orgs/OpenMOSS/repositories) · [关注动态](https://x.com/Open_MOSS)

[English](https://github.com/OpenMOSS/.github/blob/main/profile/README.md) · 简体中文

</div>

## 项目导航

按研究方向探索模型、训练框架、评测基准与开源工具。

[语言模型](#user-content-language) · [视觉生成](#user-content-vision) · [语音生成](#user-content-speech) · [音频理解](#user-content-audio) · [具身智能](#user-content-embodied) · [模型训练](#user-content-training) · [可解释性与长上下文](#user-content-methods) · [评测基准](#user-content-benchmarks) · [工具与资源](#user-content-resources)

<a id="language"></a>

## 语言模型

<p>
<a href="https://github.com/OpenMOSS/MOSS"><img align="right" hspace="16" src="https://raw.githubusercontent.com/OpenMOSS/.github/main/profile/assets/projects/moss.png" width="112" height="53" alt="MOSS logo"></a>
<strong><a href="https://github.com/OpenMOSS/MOSS">MOSS</a></strong><br>
支持中英双语对话与工具调用<br>
<a href="https://github.com/OpenMOSS/MOSS#模型">模型</a> · <a href="https://github.com/OpenMOSS/MOSS#下载安装">使用说明</a>
</p>

> **相关项目：** [Ultra-Innerthought](https://github.com/OpenMOSS/Ultra-Innerthought)（双语推理数据）

<a id="vision"></a>

## 视觉理解与多模态生成

<p>
<a href="https://github.com/OpenMOSS/MOSS-VL"><img align="right" hspace="16" src="https://raw.githubusercontent.com/OpenMOSS/MOSS-VL/main/assets/logo.png" width="82" height="56" alt="MOSS-VL logo"></a>
<strong><a href="https://github.com/OpenMOSS/MOSS-VL">MOSS-VL</a></strong><br>
11B 参数，支持长视频理解与实时视频交互<br>
<a href="https://huggingface.co/spaces/OpenMOSS-Team/MOSS-VL">体验</a> · <a href="https://huggingface.co/collections/OpenMOSS-Team/moss-vl">模型</a>
</p>

<p>
<a href="https://github.com/OpenMOSS/MOVA"><img align="right" hspace="16" src="https://raw.githubusercontent.com/OpenMOSS/MOVA/main/assets/logo.png" width="112" height="53" alt="MOVA logo"></a>
<strong><a href="https://github.com/OpenMOSS/MOVA">MOVA</a></strong><br>
声画同步生成，提供训练与 LoRA 微调流程<br>
<a href="https://github.com/OpenMOSS/MOVA#demo">样例</a> · <a href="https://huggingface.co/collections/OpenMOSS-Team/mova">模型</a>
</p>

<p>
<strong><a href="https://github.com/OpenMOSS/OmniVAE">OmniVAE</a></strong><br>
面向重建与联合生成的音视频对齐表征<br>
<a href="https://openmoss.ai/OmniVAE.github.io/">主页</a> · <a href="https://huggingface.co/OpenMOSS-Team/OmniVAE">模型</a>
</p>

<p>
<a href="https://github.com/OpenMOSS/AnyGPT"><img align="right" hspace="16" src="https://raw.githubusercontent.com/OpenMOSS/AnyGPT/main/static/images/logo.png" width="56" height="56" alt="AnyGPT logo"></a>
<strong><a href="https://github.com/OpenMOSS/AnyGPT">AnyGPT</a></strong><br>
统一建模文本、语音、图像与音乐的多模态语言模型<br>
<a href="https://junzhan2000.github.io/AnyGPT.github.io/">演示</a> · <a href="https://huggingface.co/datasets/fnlp/AnyInstruct">数据集</a>
</p>

> **相关项目：** [MOSS-Video-Preview](https://github.com/OpenMOSS/MOSS-Video-Preview)（早期流式视频模型）

<a id="speech"></a>

## 语音与声音生成

<p>
<strong><a href="https://github.com/OpenMOSS/MOSS-TTS">MOSS-TTS</a></strong><br>
覆盖朗读、对话、音色设计与音效的模型家族<br>
<a href="https://github.com/OpenMOSS/MOSS-TTS/blob/main/README_zh.md#选择适合任务的模型">模型选型</a> · <a href="https://huggingface.co/collections/OpenMOSS-Team/moss-tts">模型</a>
</p>

<p>
<strong><a href="https://github.com/OpenMOSS/MOSS-TTS-Nano">MOSS-TTS-Nano</a></strong><br>
1 亿参数多语言音色克隆，支持 CPU 与 ONNX 推理<br>
<a href="https://huggingface.co/spaces/OpenMOSS-Team/MOSS-TTS-Nano">体验</a> · <a href="https://github.com/OpenMOSS/MOSS-TTS-Nano/blob/main/README_zh.md#快速开始">本地运行</a>
</p>

<p>
<a href="https://github.com/OpenMOSS/MOSS-TTSD"><img align="right" hspace="16" src="https://raw.githubusercontent.com/OpenMOSS/MOSS-TTSD/main/asset/ttsd.png" width="84" height="56" alt="MOSS-TTSD logo"></a>
<strong><a href="https://github.com/OpenMOSS/MOSS-TTSD">MOSS-TTSD</a></strong><br>
长时、多说话人对话与播客语音合成<br>
<a href="https://huggingface.co/spaces/OpenMOSS-Team/MOSS-TTSD-v1.0">体验</a> · <a href="https://huggingface.co/OpenMOSS-Team/MOSS-TTSD-v1.0">模型</a>
</p>

<p>
<a href="https://github.com/OpenMOSS/MOSS-Speech"><img align="right" hspace="16" src="https://raw.githubusercontent.com/OpenMOSS/MOSS-Speech/main/assets/logo-large.png" width="112" height="30" alt="MOSS-Speech logo"></a>
<strong><a href="https://github.com/OpenMOSS/MOSS-Speech">MOSS-Speech</a></strong><br>
无需文本引导的端到端语音对话<br>
<a href="http://moss-speech.open-moss.com/">主页</a> · <a href="https://arxiv.org/abs/2510.00499">论文</a>
</p>

<p>
<strong><a href="https://github.com/OpenMOSS/MOSS-Audio-Tokenizer">MOSS-Audio-Tokenizer</a></strong><br>
统一语音、环境音与音乐的流式音频编码<br>
<a href="https://huggingface.co/OpenMOSS-Team/MOSS-Audio-Tokenizer">模型</a> · <a href="https://arxiv.org/abs/2602.10934">论文</a>
</p>

> **相关项目：** [MOSS-TTS-Nano-Reader](https://github.com/OpenMOSS/MOSS-TTS-Nano-Reader)（浏览器朗读应用） · [SpeechGPT-2.0-preview](https://github.com/OpenMOSS/SpeechGPT-2.0-preview)（实时语音对话）

<a id="audio"></a>

## 语音、音频与音乐理解

<p>
<a href="https://github.com/OpenMOSS/MOSS-Transcribe-Diarize"><img align="right" hspace="16" src="https://raw.githubusercontent.com/OpenMOSS/MOSS-Transcribe-Diarize/main/moss_transcribe_diarize/app/static/favicon.svg" width="56" height="56" alt="MOSS-Transcribe-Diarize logo"></a>
<strong><a href="https://github.com/OpenMOSS/MOSS-Transcribe-Diarize">MOSS-Transcribe-Diarize</a></strong><br>
0.9B 参数、50 多种语言转写，输出说话人标记与时间戳<br>
<a href="https://github.com/OpenMOSS/MOSS-Transcribe-Diarize/blob/main/README_zh.md#字幕-web-应用">字幕应用</a> · <a href="https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize">模型</a>
</p>

<p>
<a href="https://github.com/OpenMOSS/MOSS-Audio"><img align="right" hspace="16" src="https://raw.githubusercontent.com/OpenMOSS/MOSS-Audio/main/assets/moss-audio-logo.png" width="84" height="56" alt="MOSS-Audio logo"></a>
<strong><a href="https://github.com/OpenMOSS/MOSS-Audio">MOSS-Audio</a></strong><br>
面向真实场景音频的描述、问答与推理<br>
<a href="https://openmoss.ai/MOSS-Audio/">主页</a> · <a href="https://huggingface.co/collections/OpenMOSS-Team/moss-audio">模型</a>
</p>

<p>
<a href="https://github.com/OpenMOSS/MOSS-Music"><img align="right" hspace="16" src="https://raw.githubusercontent.com/OpenMOSS/MOSS-Music/main/assets/MOSS-Music.png" width="84" height="56" alt="MOSS-Music logo"></a>
<strong><a href="https://github.com/OpenMOSS/MOSS-Music">MOSS-Music</a></strong><br>
音乐描述、歌词转写、结构分析与问答<br>
<a href="https://huggingface.co/OpenMOSS-Team/MOSS-Music-8B-Instruct">模型</a>
</p>

> **相关项目：** [MOSS-Audio-Tokenizer-Eval](https://github.com/OpenMOSS/MOSS-Audio-Tokenizer-Eval)（音频编码器重建评测） · [TTSD-eval](https://github.com/OpenMOSS/TTSD-eval)（多说话人语音评测）

<a id="embodied"></a>

## 具身智能与机器人

<p>
<a href="https://github.com/OpenMOSS/EasyWAM"><img align="right" hspace="16" src="https://raw.githubusercontent.com/OpenMOSS/EasyWAM/main/assets/icon.png" width="56" height="56" alt="EasyWAM logo"></a>
<strong><a href="https://github.com/OpenMOSS/EasyWAM">EasyWAM</a></strong><br>
世界动作模型的统一训练、微调与评测框架<br>
<a href="https://openmoss.ai/EasyWAM/">主页</a> · <a href="https://huggingface.co/collections/OpenMOSS-Team/easywam">模型</a>
</p>

<p>
<a href="https://github.com/OpenMOSS/OpenETA"><img align="right" hspace="16" src="https://raw.githubusercontent.com/OpenMOSS/OpenETA/main/docs/assets/openeta-header-eta-clear.png" width="112" height="39" alt="OpenETA logo"></a>
<strong><a href="https://github.com/OpenMOSS/OpenETA">OpenETA</a></strong><br>
连接感知、行动、验证与学习的具身智能体<br>
<a href="https://openmoss.ai/OpenETA/">主页</a>
</p>

<p>
<a href="https://github.com/OpenMOSS/RoboOmni"><img align="right" hspace="16" src="https://raw.githubusercontent.com/OpenMOSS/RoboOmni/main/assets/logo.png" width="112" height="28" alt="RoboOmni logo"></a>
<strong><a href="https://github.com/OpenMOSS/RoboOmni">RoboOmni</a></strong><br>
面向多模态物理环境的主动式机器人操作<br>
<a href="https://openmoss.github.io/RoboOmni/">主页</a> · <a href="https://huggingface.co/fnlp/RoboOmni">模型</a>
</p>

<p>
<strong><a href="https://github.com/OpenMOSS/FRoM-W1">FRoM-W1</a></strong><br>
语言引导的人形机器人全身控制<br>
<a href="https://openmoss.github.io/FRoM-W1">主页</a>
</p>

> **相关项目：** [Embodied-Planner-R1](https://github.com/OpenMOSS/Embodied-Planner-R1)（面向具身规划的强化学习）

<a id="training"></a>

## 训练与后训练

<p>
<a href="https://github.com/OpenMOSS/CoLLiE"><img align="right" hspace="16" src="https://raw.githubusercontent.com/OpenMOSS/CoLLiE/main/docs/assets/images/banner.png" width="112" height="28" alt="CoLLiE logo"></a>
<strong><a href="https://github.com/OpenMOSS/CoLLiE">CoLLiE</a></strong><br>
面向大语言模型的高效协同训练框架<br>
<a href="https://openlmlab-collie.readthedocs.io">文档</a>
</p>

<p>
<a href="https://github.com/OpenMOSS/DiRL"><img align="right" hspace="16" src="https://raw.githubusercontent.com/OpenMOSS/DiRL/main/static/images/DiRL.jpg" width="112" height="47" alt="DiRL logo"></a>
<strong><a href="https://github.com/OpenMOSS/DiRL">DiRL</a></strong><br>
扩散语言模型的监督微调与强化学习<br>
<a href="https://huggingface.co/OpenMOSS-Team/DiRL-8B-Instruct">模型</a> · <a href="https://arxiv.org/abs/2512.22234">论文</a>
</p>

<a id="methods"></a>

## 可解释性与长上下文

<p>
<strong><a href="https://github.com/OpenMOSS/Llamascopium">Llamascopium</a></strong><br>
训练分析稀疏自编码器、追踪电路并可视化特征<br>
<a href="https://openmoss.ai/Llamascopium/">文档</a>
</p>

<p>
<strong><a href="https://github.com/OpenMOSS/LongLLaDA">LongLLaDA</a></strong><br>
扩展扩散语言模型的上下文长度<br>
<a href="https://arxiv.org/abs/2506.14429">论文</a>
</p>

<p>
<strong><a href="https://github.com/OpenMOSS/Sparse-dLLM">Sparse-dLLM</a></strong><br>
通过缓存淘汰与稀疏注意力加速扩散语言模型<br>
<a href="https://arxiv.org/abs/2508.02558">论文</a>
</p>

> **相关项目：** [Lorsa](https://github.com/OpenMOSS/Lorsa)（低秩稀疏注意力分解） · [rope_pp](https://github.com/OpenMOSS/rope_pp)（长上下文旋转位置编码） · [ReAttention](https://github.com/OpenMOSS/ReAttention)（无需训练的上下文扩展）

<a id="benchmarks"></a>

## 评测基准与智能体评测

<p>
<strong><a href="https://github.com/OpenMOSS/SWE-bench-Science">SWE-bench-Science</a></strong><br>
基于科学软件工程任务的编程智能体评测<br>
<a href="https://swescience.github.io/">排行榜</a> · <a href="https://huggingface.co/datasets/OpenMOSS-Team/SWE-bench-Science">数据集</a>
</p>

<p>
<strong><a href="https://github.com/OpenMOSS/ContextWeave">ContextWeave</a></strong><br>
通过长程工作日志任务评测编程智能体记忆<br>
<a href="http://arxiv.org/abs/2608.04830">论文</a>
</p>

<p>
<a href="https://github.com/OpenMOSS/AgentHPOBench"><img align="right" hspace="16" src="https://raw.githubusercontent.com/OpenMOSS/AgentHPOBench/main/assets/agenthpobench-logo.png" width="112" height="37" alt="AgentHPOBench logo"></a>
<strong><a href="https://github.com/OpenMOSS/AgentHPOBench">AgentHPOBench</a></strong><br>
评测大模型智能体的序贯超参数优化能力<br>
<a href="https://arxiv.org/abs/2607.29626">论文</a>
</p>

<p>
<strong><a href="https://github.com/OpenMOSS/ABC-Bench">ABC-Bench</a></strong><br>
评测编程智能体构建、部署与验证后端服务的能力<br>
<a href="https://dawning-road.github.io/blog/abc-bench">主页</a>
</p>

<p>
<a href="https://github.com/OpenMOSS/FutureOmni"><img align="right" hspace="16" src="https://raw.githubusercontent.com/OpenMOSS/FutureOmni/main/asset/logo0.png" width="58" height="56" alt="FutureOmni logo"></a>
<strong><a href="https://github.com/OpenMOSS/FutureOmni">FutureOmni</a></strong><br>
根据音视频上下文预测未来事件<br>
<a href="https://openmoss.ai/FutureOmni/">主页</a> · <a href="https://huggingface.co/datasets/OpenMOSS-Team/FutureOmni">数据集</a>
</p>

<p>
<strong><a href="https://github.com/OpenMOSS/VLABench">VLABench</a></strong><br>
评测视觉语言动作模型与具身智能体<br>
<a href="https://vlabench.github.io/">主页</a>
</p>

> **相关项目：** [LongSafety](https://github.com/OpenMOSS/LongSafety)（长上下文安全） · [VehicleWorld](https://github.com/OpenMOSS/VehicleWorld)（智能座舱交互） · [HalluQA](https://github.com/OpenMOSS/HalluQA)（中文幻觉评测） · [GAOKAO-MM](https://github.com/OpenMOSS/GAOKAO-MM)（中文多模态评测） · [Say-I-Dont-Know](https://github.com/OpenMOSS/Say-I-Dont-Know)（评测模型是否知道何时应承认不知道）

<a id="resources"></a>

## 综述、数据与开发工具

<p>
<strong><a href="https://github.com/OpenMOSS/Awesome-WAM">Awesome-WAM</a></strong><br>
世界动作模型综述、论文目录与基准对比<br>
<a href="https://openmoss.ai/Awesome-WAM/">浏览</a> · <a href="https://openmoss.ai/Awesome-WAM/leaderboard/">基准对比</a>
</p>

<p>
<strong><a href="https://github.com/OpenMOSS/Thus-Spake-Long-Context-LLM">Thus-Spake-Long-Context-LLM</a></strong><br>
覆盖架构、基础设施、训练与评测的长上下文综述<br>
<a href="https://arxiv.org/abs/2502.17129">论文</a>
</p>

> **相关项目：** [claude-codex-handoff](https://github.com/OpenMOSS/claude-codex-handoff)（智能体协作协议） · [OurClaw](https://github.com/OpenMOSS/OurClaw)（多用户 OpenClaw 部署） · [imclaw-skill](https://github.com/OpenMOSS/imclaw-skill)（智能体即时通讯）

## 一起参与

从项目 README 中的使用说明开始。遇到可复现的问题、希望改进文档或贡献应用集成，可以在对应仓库提交 Issue 或 Pull Request。研究中使用模型或数据集时，请引用该仓库列出的相应工作。

在 [Hugging Face](https://huggingface.co/OpenMOSS-Team) 关注模型与数据集，在 [X / @Open_MOSS](https://x.com/Open_MOSS) 关注发布动态。

OpenMOSS 由**邱锡鹏教授**领衔，依托**上海创智学院（SII）**，与**复旦大学**和 **MOSI.AI** 合作开展研究。科研合作、博士及实习机会咨询，请联系 **[openmoss@sii.edu.cn](mailto:openmoss@sii.edu.cn)**。
