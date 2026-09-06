<div align="center">

<img src="https://raw.githubusercontent.com/OpenMOSS/.github/main/profile/assets/moss-logo.svg" width="360" alt="OpenMOSS" />

**Open models for speech, video, language, and embodied intelligence.**

Models, datasets, benchmarks, and tools you can run, study, and build on.

[Website](https://openmoss.ai/) · [Model downloads](https://huggingface.co/OpenMOSS-Team) · [All repositories](https://github.com/orgs/OpenMOSS/repositories) · [Follow on X](https://x.com/Open_MOSS)

English · [简体中文](https://github.com/OpenMOSS/.github/blob/main/profile/README_zh.md)

</div>

## Find your starting point

| What you want to do | Project | Get started |
| --- | --- | --- |
| Generate speech and clone voices on a CPU | **[MOSS-TTS-Nano](https://github.com/OpenMOSS/MOSS-TTS-Nano)** — 100M parameters, multilingual, ONNX inference | [Try demo](https://huggingface.co/spaces/OpenMOSS-Team/MOSS-TTS-Nano) · [Run locally](https://github.com/OpenMOSS/MOSS-TTS-Nano#quickstart) |
| Create narration, dialogue, voices, or sound effects | **[MOSS-TTS](https://github.com/OpenMOSS/MOSS-TTS)** — speech and sound generation family | [Choose a model](https://github.com/OpenMOSS/MOSS-TTS#choose-a-model-for-your-task) · [Models](https://huggingface.co/collections/OpenMOSS-Team/moss-tts) |
| Transcribe meetings, podcasts, or interviews | **[MOSS-Transcribe-Diarize](https://github.com/OpenMOSS/MOSS-Transcribe-Diarize)** — 0.9B, 50+ languages, speaker labels and timestamps | [Subtitle app](https://github.com/OpenMOSS/MOSS-Transcribe-Diarize#subtitle-web-app) · [Model](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize) |
| Ask questions about speech, sounds, and music | **[MOSS-Audio](https://github.com/OpenMOSS/MOSS-Audio)** — audio captioning and reasoning | [Run locally](https://github.com/OpenMOSS/MOSS-Audio#quickstart) · [Models](https://huggingface.co/collections/OpenMOSS-Team/moss-audio) |
| Understand long videos or interact with live streams | **[MOSS-VL](https://github.com/OpenMOSS/MOSS-VL)** — 11B models for offline and real-time video understanding | [Try demo](https://huggingface.co/spaces/OpenMOSS-Team/MOSS-VL) · [Project page](https://openmoss.ai/MOSS-VL/) |
| Generate video with synchronized audio | **[MOVA](https://github.com/OpenMOSS/MOVA)** — joint video and audio generation, with training and LoRA workflows | [Watch samples](https://github.com/OpenMOSS/MOVA#demo) · [Models](https://huggingface.co/collections/OpenMOSS-Team/mova) |
| Train and evaluate World Action Models | **[EasyWAM](https://github.com/OpenMOSS/EasyWAM)** — shared training, fine-tuning, and evaluation workflows | [Project page](https://openmoss.ai/EasyWAM/) · [Checkpoints](https://huggingface.co/collections/OpenMOSS-Team/easywam) |

## Research tools and benchmarks

- **[OmniVAE](https://github.com/OpenMOSS/OmniVAE):** Encode and reconstruct audio and video in an aligned latent space, with joint generation workflows. [Project page](https://openmoss.ai/OmniVAE.github.io/).
- **[Llamascopium](https://github.com/OpenMOSS/Llamascopium):** Train sparse autoencoders, trace circuits, and visualize learned features. [Documentation](https://openmoss.ai/Llamascopium/).
- **[SWE-bench-Science](https://github.com/OpenMOSS/SWE-bench-Science):** Evaluate coding agents on engineering tasks in scientific software. [Leaderboard](https://swescience.github.io/). Explore agent memory with [ContextWeave](https://github.com/OpenMOSS/ContextWeave) and hyperparameter optimization with [AgentHPOBench](https://github.com/OpenMOSS/AgentHPOBench).
- **[Awesome-WAM](https://github.com/OpenMOSS/Awesome-WAM):** Explore World Action Models through a survey, paper collection, and [benchmark comparisons](https://openmoss.ai/Awesome-WAM/leaderboard/). For embodied agents, see [OpenETA](https://github.com/OpenMOSS/OpenETA), [RoboOmni](https://github.com/OpenMOSS/RoboOmni), and [FRoM-W1](https://github.com/OpenMOSS/FRoM-W1).

<details>
<summary><b>Explore all research directions</b></summary>

| Direction | Repositories |
| --- | --- |
| Language models and post-training | [MOSS](https://github.com/OpenMOSS/MOSS) · [DiRL](https://github.com/OpenMOSS/DiRL) · [BandPO](https://github.com/OpenMOSS/BandPO) |
| Visual understanding | [MOSS-VL](https://github.com/OpenMOSS/MOSS-VL) · [MOSS-Video-Preview](https://github.com/OpenMOSS/MOSS-Video-Preview) |
| Multimodal generation and modeling | [MOVA](https://github.com/OpenMOSS/MOVA) · [OmniVAE](https://github.com/OpenMOSS/OmniVAE) · [AnyGPT](https://github.com/OpenMOSS/AnyGPT) |
| Speech and audio generation | [MOSS-TTS](https://github.com/OpenMOSS/MOSS-TTS) · [MOSS-TTS-Nano](https://github.com/OpenMOSS/MOSS-TTS-Nano) · [MOSS-TTSD](https://github.com/OpenMOSS/MOSS-TTSD) · [MOSS-Speech](https://github.com/OpenMOSS/MOSS-Speech) · [MOSS-Audio-Tokenizer](https://github.com/OpenMOSS/MOSS-Audio-Tokenizer) |
| Speech, audio, and music understanding | [MOSS-Transcribe-Diarize](https://github.com/OpenMOSS/MOSS-Transcribe-Diarize) · [MOSS-Audio](https://github.com/OpenMOSS/MOSS-Audio) · [MOSS-Music](https://github.com/OpenMOSS/MOSS-Music) |
| Embodied AI and robotics | [EasyWAM](https://github.com/OpenMOSS/EasyWAM) · [OpenETA](https://github.com/OpenMOSS/OpenETA) · [RoboOmni](https://github.com/OpenMOSS/RoboOmni) · [FRoM-W1](https://github.com/OpenMOSS/FRoM-W1) |
| Interpretability | [Llamascopium](https://github.com/OpenMOSS/Llamascopium) (formerly Language-Model-SAEs) · [Lorsa](https://github.com/OpenMOSS/Lorsa) |
| Benchmarks and evaluation | [SWE-bench-Science](https://github.com/OpenMOSS/SWE-bench-Science) · [ContextWeave](https://github.com/OpenMOSS/ContextWeave) · [AgentHPOBench](https://github.com/OpenMOSS/AgentHPOBench) · [FutureOmni](https://github.com/OpenMOSS/FutureOmni) · [VLABench](https://github.com/OpenMOSS/VLABench) |
| Efficient training and long context | [CoLLiE](https://github.com/OpenMOSS/CoLLiE) · [LongLLaDA](https://github.com/OpenMOSS/LongLLaDA) · [Sparse-dLLM](https://github.com/OpenMOSS/Sparse-dLLM) · [rope_pp](https://github.com/OpenMOSS/rope_pp) · [LongSafety](https://github.com/OpenMOSS/LongSafety) |
| Surveys and resources | [Awesome-WAM](https://github.com/OpenMOSS/Awesome-WAM) · [Thus-Spake-Long-Context-LLM](https://github.com/OpenMOSS/Thus-Spake-Long-Context-LLM) |

</details>

## Build with us

Start with a project's README, then use its Issues or pull requests to report a reproducible bug, improve documentation, or contribute an integration. If you use a model or dataset in research, please cite the corresponding work linked in that repository.

Follow [OpenMOSS on Hugging Face](https://huggingface.co/OpenMOSS-Team) for models and datasets, and [@Open_MOSS on X](https://x.com/Open_MOSS) for release announcements.

OpenMOSS is led by **Prof. Xipeng Qiu** at the **Shanghai Innovation Institute (SII)**, in collaboration with **Fudan University** and **MOSI.AI**. For research collaborations, PhD and internship inquiries, contact **[openmoss@sii.edu.cn](mailto:openmoss@sii.edu.cn)**.
