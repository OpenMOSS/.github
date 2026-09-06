<div align="center">

<img src="https://raw.githubusercontent.com/OpenMOSS/.github/main/profile/assets/moss-logo.svg" width="360" alt="OpenMOSS" />

**Open models for speech, video, language, and embodied intelligence.**

Models, datasets, benchmarks, and tools you can run, study, and build on.

[Website](https://openmoss.ai/) · [Model downloads](https://huggingface.co/OpenMOSS-Team) · [All repositories](https://github.com/orgs/OpenMOSS/repositories) · [Follow on X](https://x.com/Open_MOSS)

English · [简体中文](https://github.com/OpenMOSS/.github/blob/main/profile/README_zh.md)

</div>

## Explore our projects

Browse models, training frameworks, benchmarks, and research resources by area. Project names link to code; the last column leads to models, demos, papers, or documentation.

[Language models](#language) · [Vision & generation](#vision) · [Speech generation](#speech) · [Audio understanding](#audio) · [Embodied AI](#embodied) · [Interpretability & training](#methods) · [Benchmarks](#benchmarks) · [Resources & tools](#resources)

<a id="language"></a>

### Language models & post-training

| Project | What it does | Explore |
| --- | --- | --- |
| **[MOSS](https://github.com/OpenMOSS/MOSS)** | Chinese and English dialogue with tool use | [Models](https://github.com/OpenMOSS/MOSS/blob/main/README_en.md#models) · [Get started](https://github.com/OpenMOSS/MOSS/blob/main/README_en.md#installation) |
| **[DiRL](https://github.com/OpenMOSS/DiRL)** | Supervised fine-tuning and reinforcement learning for diffusion language models | [Model](https://huggingface.co/OpenMOSS-Team/DiRL-8B-Instruct) · [Paper](https://arxiv.org/abs/2512.22234) |
| **[BandPO](https://github.com/OpenMOSS/BandPO)** | Probability-aware policy optimization for LLM reinforcement learning | [Paper](https://arxiv.org/abs/2603.04918) |

**Also explore:** [Ultra-Innerthought](https://github.com/OpenMOSS/Ultra-Innerthought) (bilingual reasoning data)

<a id="vision"></a>

### Vision & multimodal generation

| Project | What it does | Explore |
| --- | --- | --- |
| **[MOSS-VL](https://github.com/OpenMOSS/MOSS-VL)** | 11B models for long-form and real-time video understanding | [Demo](https://huggingface.co/spaces/OpenMOSS-Team/MOSS-VL) · [Models](https://huggingface.co/collections/OpenMOSS-Team/moss-vl) |
| **[MOVA](https://github.com/OpenMOSS/MOVA)** | Generate video and synchronized audio, with training and LoRA workflows | [Samples](https://github.com/OpenMOSS/MOVA#demo) · [Models](https://huggingface.co/collections/OpenMOSS-Team/mova) |
| **[OmniVAE](https://github.com/OpenMOSS/OmniVAE)** | Aligned audio-video representations for reconstruction and joint generation | [Project](https://openmoss.ai/OmniVAE.github.io/) · [Model](https://huggingface.co/OpenMOSS-Team/OmniVAE) |
| **[AnyGPT](https://github.com/OpenMOSS/AnyGPT)** | A multimodal language model for text, speech, images, and music | [Demos](https://junzhan2000.github.io/AnyGPT.github.io/) · [Dataset](https://huggingface.co/datasets/fnlp/AnyInstruct) |

**Also explore:** [MOSS-Video-Preview](https://github.com/OpenMOSS/MOSS-Video-Preview) (earlier streaming video model)

<a id="speech"></a>

### Speech & audio generation

| Project | What it does | Explore |
| --- | --- | --- |
| **[MOSS-TTS](https://github.com/OpenMOSS/MOSS-TTS)** | Model family for narration, dialogue, voice design, and sound effects | [Model guide](https://github.com/OpenMOSS/MOSS-TTS#choose-a-model-for-your-task) · [Models](https://huggingface.co/collections/OpenMOSS-Team/moss-tts) |
| **[MOSS-TTS-Nano](https://github.com/OpenMOSS/MOSS-TTS-Nano)** | 100M-parameter multilingual voice cloning with CPU and ONNX inference | [Demo](https://huggingface.co/spaces/OpenMOSS-Team/MOSS-TTS-Nano) · [Run locally](https://github.com/OpenMOSS/MOSS-TTS-Nano#quickstart) |
| **[MOSS-TTSD](https://github.com/OpenMOSS/MOSS-TTSD)** | Long-form, multi-speaker dialogue and podcast synthesis | [Demo](https://huggingface.co/spaces/OpenMOSS-Team/MOSS-TTSD-v1.0) · [Model](https://huggingface.co/OpenMOSS-Team/MOSS-TTSD-v1.0) |
| **[MOSS-Speech](https://github.com/OpenMOSS/MOSS-Speech)** | End-to-end speech-to-speech dialogue without text guidance | [Project](http://moss-speech.open-moss.com/) · [Paper](https://arxiv.org/abs/2510.00499) |
| **[MOSS-Audio-Tokenizer](https://github.com/OpenMOSS/MOSS-Audio-Tokenizer)** | Streaming audio tokenization across speech, sound, and music | [Model](https://huggingface.co/OpenMOSS-Team/MOSS-Audio-Tokenizer) · [Paper](https://arxiv.org/abs/2602.10934) |

**Also explore:** [MOSS-TTS-Nano-Reader](https://github.com/OpenMOSS/MOSS-TTS-Nano-Reader) (in-browser reading) · [SpeechGPT-2.0-preview](https://github.com/OpenMOSS/SpeechGPT-2.0-preview) (real-time spoken dialogue)

<a id="audio"></a>

### Speech, audio & music understanding

| Project | What it does | Explore |
| --- | --- | --- |
| **[MOSS-Transcribe-Diarize](https://github.com/OpenMOSS/MOSS-Transcribe-Diarize)** | 0.9B transcription in 50+ languages, with speaker labels and timestamps | [Subtitle app](https://github.com/OpenMOSS/MOSS-Transcribe-Diarize#subtitle-web-app) · [Model](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize) |
| **[MOSS-Audio](https://github.com/OpenMOSS/MOSS-Audio)** | Captioning, question answering, and reasoning over real-world audio | [Project](https://openmoss.ai/MOSS-Audio/) · [Models](https://huggingface.co/collections/OpenMOSS-Team/moss-audio) |
| **[MOSS-Music](https://github.com/OpenMOSS/MOSS-Music)** | Music captioning, lyrics transcription, structural analysis, and QA | [Model](https://huggingface.co/OpenMOSS-Team/MOSS-Music-8B-Instruct) |

**Also explore:** [MOSS-Audio-Tokenizer-Eval](https://github.com/OpenMOSS/MOSS-Audio-Tokenizer-Eval) (codec reconstruction evaluation) · [TTSD-eval](https://github.com/OpenMOSS/TTSD-eval) (multi-speaker speech evaluation)

<a id="embodied"></a>

### Embodied intelligence & robotics

| Project | What it does | Explore |
| --- | --- | --- |
| **[EasyWAM](https://github.com/OpenMOSS/EasyWAM)** | Train, fine-tune, and evaluate World Action Models in a shared framework | [Project](https://openmoss.ai/EasyWAM/) · [Models](https://huggingface.co/collections/OpenMOSS-Team/easywam) |
| **[OpenETA](https://github.com/OpenMOSS/OpenETA)** | An embodied agent linking perception, action, verification, and learning | [Project](https://openmoss.ai/OpenETA/) |
| **[RoboOmni](https://github.com/OpenMOSS/RoboOmni)** | Proactive robot manipulation in multimodal physical environments | [Project](https://openmoss.github.io/RoboOmni/) · [Model](https://huggingface.co/fnlp/RoboOmni) |
| **[FRoM-W1](https://github.com/OpenMOSS/FRoM-W1)** | Language-guided whole-body control for humanoid robots | [Project](https://openmoss.github.io/FRoM-W1) |

**Also explore:** [Embodied-Planner-R1](https://github.com/OpenMOSS/Embodied-Planner-R1) (reinforcement learning for embodied planning)

<a id="methods"></a>

### Interpretability, training & long context

| Project | What it does | Explore |
| --- | --- | --- |
| **[Llamascopium](https://github.com/OpenMOSS/Llamascopium)** | Train and analyze sparse autoencoders, trace circuits, and visualize features | [Docs](https://openmoss.ai/Llamascopium/) |
| **[CoLLiE](https://github.com/OpenMOSS/CoLLiE)** | Efficient collaborative training of large language models | [Docs](https://openlmlab-collie.readthedocs.io) |
| **[LongLLaDA](https://github.com/OpenMOSS/LongLLaDA)** | Extend the context length of diffusion language models | [Paper](https://arxiv.org/abs/2506.14429) |
| **[Sparse-dLLM](https://github.com/OpenMOSS/Sparse-dLLM)** | Accelerate diffusion LLMs with cache eviction and sparse attention | [Paper](https://arxiv.org/abs/2508.02558) |

**Also explore:** [Lorsa](https://github.com/OpenMOSS/Lorsa) (low-rank sparse attention decomposition) · [rope_pp](https://github.com/OpenMOSS/rope_pp) (rotary position embeddings for long context) · [ReAttention](https://github.com/OpenMOSS/ReAttention) (training-free context extension)

<a id="benchmarks"></a>

### Benchmarks & agent evaluation

| Project | What it does | Explore |
| --- | --- | --- |
| **[SWE-bench-Science](https://github.com/OpenMOSS/SWE-bench-Science)** | Coding-agent evaluation on engineering tasks in scientific software | [Leaderboard](https://swescience.github.io/) · [Dataset](https://huggingface.co/datasets/OpenMOSS-Team/SWE-bench-Science) |
| **[ContextWeave](https://github.com/OpenMOSS/ContextWeave)** | Evaluate coding-agent memory through long-horizon worklog tasks | [Paper](http://arxiv.org/abs/2608.04830) |
| **[AgentHPOBench](https://github.com/OpenMOSS/AgentHPOBench)** | Evaluate LLM agents as sequential hyperparameter optimizers | [Paper](https://arxiv.org/abs/2607.29626) |
| **[ABC-Bench](https://github.com/OpenMOSS/ABC-Bench)** | Test whether coding agents can build, deploy, and verify backend services | [Project](https://dawning-road.github.io/blog/abc-bench) |
| **[FutureOmni](https://github.com/OpenMOSS/FutureOmni)** | Forecast future events from audio and video context | [Project](https://openmoss.ai/FutureOmni/) · [Dataset](https://huggingface.co/datasets/OpenMOSS-Team/FutureOmni) |
| **[VLABench](https://github.com/OpenMOSS/VLABench)** | Evaluate vision-language-action models and embodied agents | [Project](https://vlabench.github.io/) |

**Also explore:** [LongSafety](https://github.com/OpenMOSS/LongSafety) (long-context safety) · [VehicleWorld](https://github.com/OpenMOSS/VehicleWorld) (connected cockpit interaction) · [HalluQA](https://github.com/OpenMOSS/HalluQA) (Chinese hallucination evaluation) · [GAOKAO-MM](https://github.com/OpenMOSS/GAOKAO-MM) (Chinese multimodal evaluation) · [Say-I-Dont-Know](https://github.com/OpenMOSS/Say-I-Dont-Know) (knowing when to abstain)

<a id="resources"></a>

### Surveys, datasets & developer tools

| Project | What it does | Explore |
| --- | --- | --- |
| **[Awesome-WAM](https://github.com/OpenMOSS/Awesome-WAM)** | World Action Model survey, paper collection, and benchmark comparisons | [Browse](https://openmoss.ai/Awesome-WAM/) · [Benchmarks](https://openmoss.ai/Awesome-WAM/leaderboard/) |
| **[Thus-Spake-Long-Context-LLM](https://github.com/OpenMOSS/Thus-Spake-Long-Context-LLM)** | A survey of long-context architectures, infrastructure, training, and evaluation | [Paper](https://arxiv.org/abs/2502.17129) |
| **[UnifiedToolHub](https://github.com/OpenMOSS/UnifiedToolHub)** | Prepare tool-use datasets and train and evaluate tool-using language models | [Quickstart](https://github.com/OpenMOSS/UnifiedToolHub#快速上手) |

**Also explore:** [claude-codex-handoff](https://github.com/OpenMOSS/claude-codex-handoff) (agent collaboration protocol) · [OurClaw](https://github.com/OpenMOSS/OurClaw) (multi-user OpenClaw deployment) · [imclaw-skill](https://github.com/OpenMOSS/imclaw-skill) (agent messaging)

## Build with us

Start with a project's README, then use its Issues or pull requests to report a reproducible bug, improve documentation, or contribute an integration. If you use a model or dataset in research, please cite the corresponding work linked in that repository.

Follow [OpenMOSS on Hugging Face](https://huggingface.co/OpenMOSS-Team) for models and datasets, and [@Open_MOSS on X](https://x.com/Open_MOSS) for release announcements.

OpenMOSS is led by **Prof. Xipeng Qiu** at the **Shanghai Innovation Institute (SII)**, in collaboration with **Fudan University** and **MOSI.AI**. For research collaborations, PhD and internship inquiries, contact **[openmoss@sii.edu.cn](mailto:openmoss@sii.edu.cn)**.
