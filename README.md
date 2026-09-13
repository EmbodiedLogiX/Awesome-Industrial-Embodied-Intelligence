# Awesome-Industrial-Embodied-Intelligence [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A practical, source-traceable map of **industrial embodied intelligence**: how machines perceive the shop floor, remember across long horizons, decide and act, cooperate safely, and earn trust through credible evaluation.

<p align="center"><b>🏭 Sense</b> &nbsp;→&nbsp; <b>🧠 Remember</b> &nbsp;→&nbsp; <b>🕹️ Decide</b> &nbsp;→&nbsp; <b>🤝 Coordinate</b> &nbsp;→&nbsp; <b>📏 Validate</b></p>

## 🧭 Find your lane

| I want to explore… | Start here |
| :-- | :-- |
| Industrial requirements, safety, cost, and trust | [Cognitive Framework](#framework) |
| Multimodal perception, spatial grounding, and world models | [Perception and World Models](#perception) |
| Memory, video streams, compression, and experience retrieval | [Memory and Continual Adaptation](#memory) |
| VLA policies, reasoning, affordances, and fast execution | [Decision-Making and Action Models](#decision-making) |
| Teams of robots or people and robots | [Multi-Agent and Human–Robot Collaboration](#collaboration) |
| Simulators, task toolkits, benchmarks, or physical validation | [Simulation to Real World](#sim2real) · [Benchmarks and Evaluation](#evaluation) |

## 🚀 Industrial task areas

| Task lane | Useful starting points |
| :-- | :-- |
| 🧰 Assembly and manipulation | [Decision-making](#decision-making) &nbsp;&#124;&nbsp; [Benchmarks](#evaluation) |
| 📦 Logistics, picking, and packing | [Decision-making](#decision-making) &nbsp;&#124;&nbsp; [Collaboration](#collaboration) |
| 🧭 Navigation and mobile operations | [Perception](#perception) &nbsp;&#124;&nbsp; [Sim-to-real](#sim2real) |
| 🦺 Human-in-the-loop operation | [Collaboration](#collaboration) &nbsp;&#124;&nbsp; [Reliability](#evaluation) |

## ✨ What is curated here?

This is a capability-first Awesome List, not a table of contents for the companion review. It consolidates the supplied literature into **169 de-duplicated works** (from 172 BibTeX records; three duplicate records are merged). Every work has one primary discovery path, so readers can browse the field rather than retrace manuscript sections.

### 🔗 Link bar legend

Each row keeps links compact: `[Paper] | [GitHub]`. `Paper` means the supplied bibliography contains a publisher, DOI, arXiv, or official source record; `GitHub` appears only when that record explicitly supplies a repository. `—` means no verified link of that kind was supplied — never a placeholder.

## 📢 News

- **[2026-09]** Rebuilt the list as a single, capability-oriented README and merged duplicate bibliography records.

## 🧩 Curated Resources

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Awesome Bin Packing with Robotic Arms** | Robotics packing, planning, stability, and execution | 2026 | [GitHub](https://github.com/3DBP-Lab/awesome-bin-packing-with-robotic-arms) | Community list |

<a id="framework"></a>
## 🧠 Cognitive Framework

### Industrial Requirements and Trustworthy Operation

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Distributed Agent System: Fault-Tolerant Collaboration Among Embodied Agents** | Distributed Agent System<br/><sub>bib: <code>26-DAC-Industry</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2607.10811) | arXiv |
| **Energy and Carbon Footprint of Vision-Language-Action Model Inference for Edge Robotic Systems** | Industrial embodied intelligence<br/><sub>bib: <code>26-ACMGSCC-Energy</code></sub> | 2026 | — | 16th ACM International Green and Sustainable Computing Conference |
| **IEI-TIA: Industrial Embodied Intelligence Trustworthy Interpretable Agent for Robotic Long-Horizon and Repetitive Tasks** | IEI-TIA<br/><sub>bib: <code>26-TASE-IEI-TIA</code></sub> | 2026 | — | IEEE Transactions on Automation Science and Engineering |
| **Embodied Intelligence for Flexible Manufacturing: A Survey** | Industrial embodied intelligence<br/><sub>bib: <code>25-FlexibleManusfacturing</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2602.06966) | arXiv |
| **Embodied intelligence: A synergy of morphology, action, perception and learning** | Embodied intelligence<br/><sub>bib: <code>25-CSUR-Embodied-Intelligence</code></sub> | 2025 | — | ACM Computing Surveys |
| **LAECIPS: Large vision model assisted adaptive edge-cloud collaboration for IoT-based embodied intelligence system** | LAECIPS<br/><sub>bib: <code>25-JIII-LAECIPS</code></sub> | 2025 | — | Journal of Industrial Information Integration |
| **Safe human--robot collaboration for industrial settings: a survey** | Industrial embodied intelligence<br/><sub>bib: <code>24-JIM-SafeHRC</code></sub> | 2024 | — | Journal of Intelligent Manufacturing |

### Cognitive Frameworks and Spatial Grounding

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Bio-inspired cognitive navigation for robots** | Cognitive framework<br/><sub>bib: <code>26-NREE-CogNav</code></sub> | 2026 | [Paper](https://doi.org/10.1038/s44287-026-00294-7) | Nature Reviews Electrical Engineering |
| **Two by two: Learning multi-task pairwise objects assembly for generalizable robot manipulation** | Two by two<br/><sub>bib: <code>25-CVPR-2BY2</code></sub> | 2025 | — | CVPR |

<a id="perception"></a>
## 👁️ Perception, Spatial Intelligence, and World Models

### Multimodal Sensing and Interaction

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Event-Driven Visual-Tactile Sensing and Learning for Robots** | Multimodal perception<br/><sub>bib: <code>taunyazov20event</code></sub> | 2020 | — | RSS |
| **Making Sense of Vision and Touch: Self-Supervised Learning of Multimodal Representations for Contact-Rich Tasks** | Making Sense of Vision and Touch<br/><sub>bib: <code>lee2019makings</code></sub> | 2019 | [Paper](https://doi.org/10.1109/ICRA.2019.8793485) | ICRA |

### Industrial Semantics, Scene Graphs, and World Models

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **AssemMate: Graph-Based LLM for Robotic Assembly Assistance** | AssemMate<br/><sub>bib: <code>zheng2026assemmategraphbasedllmrobotic</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2509.11617) | — |
| **A large language model-enabled machining process knowledge graph construction method for intelligent process planning** | World model<br/><sub>bib: <code>XU2025103244</code></sub> | 2025 | [Paper](https://www.sciencedirect.com/science/article/pii/S1474034625001375) | Advanced Engineering Informatics |
| **Generation of Asset Administration Shell With Large Language Model Agents: Toward Semantic Interoperability in Digital Twins in the Context of Industry 4.0** | World model<br/><sub>bib: <code>10559483</code></sub> | 2024 | [Paper](https://doi.org/10.1109/ACCESS.2024.3415470) | IEEE Access |

<a id="memory"></a>
## 💾 Memory and Continual Adaptation

### Memory Construction and Continual Experience

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Embodied agents meet personalization: Investigating challenges and solutions through the lens of memory utilization** | Memory architecture<br/><sub>bib: <code>26-ICLR-Personalization</code></sub> | 2026 | — | ICLR |
| **Mem: Multi-scale embodied memory for vision language action models** | Mem<br/><sub>bib: <code>26-Mem</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2603.03596) | arXiv |
| **Memoryvla: Perceptual-cognitive memory in vision-language-action models for robotic manipulation** | Memoryvla<br/><sub>bib: <code>26-ICLR-MemoryVLA</code></sub> | 2026 | — | ICLR |
| **Response-G1: Explicit Scene Graph Modeling for Proactive Streaming Video Understanding** | Response-G1<br/><sub>bib: <code>26-ACL-ResponseG1</code></sub> | 2026 | — | ACL |
| **Embodied videoagent: Persistent memory from egocentric videos and embodied sensors enables dynamic scene understanding** | Embodied videoagent<br/><sub>bib: <code>25-ICCV-EmbodiedVideoAgent</code></sub> | 2025 | — | ICCV |
| **Enter the mind palace: Reasoning and planning for long-term active embodied question answering** | Enter the mind palace<br/><sub>bib: <code>25-SceneMemory</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2507.12846) | arXiv |
| **From human memory to ai memory: A survey on memory mechanisms in the era of llms** | From human memory to ai memory<br/><sub>bib: <code>25-AI-memory</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2504.15965) | arXiv |
| **Robomemory: A brain-inspired multi-memory agentic framework for lifelong learning in physical embodied systems** | Robomemory<br/><sub>bib: <code>25-NeurIPS-Robomemory</code></sub> | 2025 | — | NeurIPS 2025 Workshop on Space in Vision, Language, and Embodied AI |
| **SAM2Act: Integrating Visual Foundation Model with A Memory Architecture for Robotic Manipulation** | SAM2Act<br/><sub>bib: <code>25-ICML-SAM2ACT</code></sub> | 2025 | — | ICML |
| **Collaborative Conversation in Safe Multimodal Human-Robot Collaboration** | Memory architecture<br/><sub>bib: <code>Ferrari2024colla</code></sub> | 2024 | — | IROS |
| **Robustifying Long-term Human-Robot Collaboration through a Hierarchical and Multimodal Framework** | Memory architecture<br/><sub>bib: <code>yu2024robustify</code></sub> | 2024 | [Paper](https://arxiv.org/abs/2411.15711) | arXiv |
| **Detecting Worker Attention Lapses in Human-Robot Interaction: An Eye Tracking and Multimodal Sensing Study** | Memory architecture<br/><sub>bib: <code>Dai2023detectingwork</code></sub> | 2023 | [Paper](https://doi.org/10.1109/ICAC57885.2023.10275177) | 2023 28th International Conference on Automation and Computing (ICAC) |
| **Play it by Ear: Learning Skills amidst Occlusion through Audio-Visual Imitation Learning** | Play it by Ear<br/><sub>bib: <code>du2022playitbyear</code></sub> | 2022 | [Paper](https://doi.org/10.15607/RSS.2022.XVIII.009) | RSS |
| **Human memory: A proposed system and its control processes** | Human memory<br/><sub>bib: <code>1968-Human-Memory</code></sub> | 1968 | — | Psychology of learning and motivation |

### Long-Horizon Video, Compression, and Keyframes

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Attend Before Attention: Efficient and Scalable Video Understanding via Autoregressive Gazing** | Attend Before Attention<br/><sub>bib: <code>26-CVPR-AutoGaze</code></sub> | 2026 | — | CVPR |
| **FlashVID: Efficient Video Large Language Models via Training-free Tree-based Spatiotemporal Token Merging** | FlashVID<br/><sub>bib: <code>26-ICLR-FlashVID</code></sub> | 2026 | [Paper](https://openreview.net/forum?id=H6rDX4w6Al) | ICLR |
| **KEMO: Event-Driven Keyframe Memory for Long-Horizon Robot Manipulation with VLA Policies** | KEMO<br/><sub>bib: <code>26-KEMO</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2606.23589) | — |
| **Non-markovian long-horizon robot manipulation via keyframe chaining** | Memory-efficient video model<br/><sub>bib: <code>26-KeyFrameVLA</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2603.01465) | arXiv |
| **Token Reduction via Local and Global Contexts Optimization for Efficient Video Large Language Models** | Memory-efficient video model<br/><sub>bib: <code>26-CVPR-AOT</code></sub> | 2026 | — | CVPR |
| **VisionPulse: Dynamic Visual Sparsity for Efficient Multimodal Reasoning** | VisionPulse<br/><sub>bib: <code>26-ICML-VisionPulse</code></sub> | 2026 | — | ICML |
| **Longvu: Spatiotemporal adaptive compression for long video-language understanding** | Longvu<br/><sub>bib: <code>25-ICML-LongVU</code></sub> | 2025 | — | ICML |
| **Memo: Training memory-efficient embodied agents with reinforcement learning** | Memo<br/><sub>bib: <code>25-NeurIPS-Memo</code></sub> | 2025 | — | NeurIPS |
| **Efficient Streaming Language Models with Attention Sinks** | Memory-efficient video model<br/><sub>bib: <code>24-ICLR-KVcache</code></sub> | 2024 | — | ICLR |
| **An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale** | An Image is Worth 16x16 Words<br/><sub>bib: <code>21-ICLR-ViT</code></sub> | 2021 | — | ICLR |

### Experience Retrieval and Generative Reconstruction

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **MemER: Scaling Up Memory for Robot Control via Experience Retrieval** | MemER<br/><sub>bib: <code>26-ICLR-MEBER</code></sub> | 2026 | — | ICLR |
| **Memgen: Weaving generative latent memory for self-evolving agents** | Memgen<br/><sub>bib: <code>26-ICLR-Memgen</code></sub> | 2026 | — | ICLR |
| **Scaling the Long Video Understanding of Multimodal Large Language Models via Visual Memory Mechanism** | Experience retrieval<br/><sub>bib: <code>26-CVPR-FlexMem</code></sub> | 2026 | — | CVPR |
| **Jarvis-1: Open-world multi-task agents with memory-augmented multimodal language models** | Jarvis-1<br/><sub>bib: <code>24-TPAMI-Jarvis1</code></sub> | 2024 | — | IEEE Transactions on Pattern Analysis and Machine Intelligence |
| **Remembering: A study in experimental and social psychology** | Remembering<br/><sub>bib: <code>1995-Remembering-Reconstruct</code></sub> | 1995 | — | Cambridge university press |

### Multimodal Memory and Memory Benchmarks

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Mem-gallery: Benchmarking multimodal long-term conversational memory for mllm agents** | Mem-gallery<br/><sub>bib: <code>26-ACL-MemGallery</code></sub> | 2026 | — | ACL |
| **A generative model of memory construction and consolidation** | Multimodal memory<br/><sub>bib: <code>24-MHB-Generative · 24-NHB-Generative</code></sub> | 2024 | — | Nature Human Behaviour |
| **Constructive memory: past and future** | Constructive memory<br/><sub>bib: <code>12-Constructive-Memory</code></sub> | 2012 | — | Dialogues in clinical neuroscience |

<a id="decision-making"></a>
## 🕹️ Decision-Making and Action Models

### Generalist Vision–Language–Action Policies

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **OpenVLA: An Open-Source Vision-Language-Action Model** | OpenVLA<br/><sub>bib: <code>kim2025openvla</code></sub> | 2025 | [Paper](https://proceedings.mlr.press/v270/kim25c.html) | CoRL |
| **π₀: A Vision-Language-Action Flow Model for General Robot Control** | π₀<br/><sub>bib: <code>black2025pi0</code></sub> | 2025 | [Paper](https://www.roboticsproceedings.org/rss21/p010.html) | RSS |
| **Octo: An Open-Source Generalist Robot Policy** | Octo<br/><sub>bib: <code>ghosh2024octo</code></sub> | 2024 | [Paper](https://www.roboticsproceedings.org/rss20/p090.html) | RSS |
| **Learning fine-grained bimanual manipulation with low-cost hardware** | VLA policy<br/><sub>bib: <code>23-ACT</code></sub> | 2023 | [Paper](https://arxiv.org/abs/2304.13705) | arXiv |
| **RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control** | RT-2<br/><sub>bib: <code>23-Rt2 · zitkovich2023rt2</code></sub> | 2023 | [Paper](https://proceedings.mlr.press/v229/zitkovich23a.html) | CoRL |

### Reasoning, Affordances, and Self-Assessment

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **ACoT-VLA: Action Chain-of-Thought for Vision-Language-Action Models** | ACoT-VLA<br/><sub>bib: <code>zhong2026acotvla</code></sub> | 2026 | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Zhong_ACoT-VLA_Action_Chain-of-Thought_for_Vision-Language-Action_Models_CVPR_2026_paper.html) | CVPR |
| **Think Before Action: Learning Suction Health for Reliable Grasp Evaluation in Logistics** | Think Before Action<br/><sub>bib: <code>26-KDD-GraspGuard</code></sub> | 2026 | — | 32nd ACM SIGKDD Conference on Knowledge Discovery and Data Mining V. 2 |
| **villa-X: Enhancing Latent Action Modeling in Vision-Language-Action Models** | villa-X<br/><sub>bib: <code>26-ICLR-villaX</code></sub> | 2026 | — | ICLR |
| **CoA-VLA: Improving Vision-Language-Action Models via Visual-Text Chain-of-Affordance** | CoA-VLA<br/><sub>bib: <code>li2025coavla</code></sub> | 2025 | [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Li_CoA-VLA_Improving_Vision-Language-Action_Models_via_Visual-Text_Chain-of-Affordance_ICCV_2025_paper.html) | ICCV |
| **CoT-VLA: Visual Chain-of-Thought Reasoning for Vision-Language-Action Models** | CoT-VLA<br/><sub>bib: <code>zhao2025cotvla</code></sub> | 2025 | [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Zhao_CoT-VLA_Visual_Chain-of-Thought_Reasoning_for_Vision-Language-Action_Models_CVPR_2025_paper.html) | CVPR |
| **Dense Policy: Bidirectional Autoregressive Learning of Actions** | Dense Policy<br/><sub>bib: <code>25-ICCV-DensePolicy</code></sub> | 2025 | — | ICCV |

### Fast and On-Device Action Generation

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Real-time execution of action chunking flow policies** | Efficient action policy<br/><sub>bib: <code>black2026real</code></sub> | 2026 | — | NeurIPS |
| **On-device diffusion transformer policy for efficient robot manipulation** | Efficient action policy<br/><sub>bib: <code>wu2025device</code></sub> | 2025 | — | ICCV |
| **One-Step Diffusion Policy: Fast Visuomotor Policies via Diffusion Distillation** | One-Step Diffusion Policy<br/><sub>bib: <code>pmlr-v267-wang25ba</code></sub> | 2025 | — | ICML |

<a id="collaboration"></a>
## 🤝 Multi-Agent and Human–Robot Collaboration

### Multi-Robot and Collective Intelligence

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Dynamic reconfiguration in multi-robot agent systems using embedded language models** | Multi-robot collaboration<br/><sub>bib: <code>MURDIVIEN2026103308</code></sub> | 2026 | [Paper](https://www.sciencedirect.com/science/article/pii/S0736584526000876) | Robotics and Computer-Integrated Manufacturing |
| **When Multi-Robot Systems Meet Agentic AI: Towards Embodied Collective Intelligence** | Multi-robot collaboration<br/><sub>bib: <code>yan2026multi</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2606.27929) | arXiv |
| **Capability-aware shared hypernetworks for flexible heterogeneous multi-robot coordination** | Multi-robot collaboration<br/><sub>bib: <code>fu2025capability</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2501.06058) | arXiv |
| **Collaborative tree search for enhancing embodied multi-agent collaboration** | Multi-robot collaboration<br/><sub>bib: <code>zu2025collaborative</code></sub> | 2025 | — | CVPR |
| **Emos: Embodiment-aware heterogeneous multi-robot operating system with llm agents** | Emos<br/><sub>bib: <code>chen2025emos</code></sub> | 2025 | — | ICLR |
| **Robofactory: Exploring embodied agent collaboration with compositional constraints** | Robofactory<br/><sub>bib: <code>qin2025robofactory</code></sub> | 2025 | — | ICCV |
| **Roboos-next: A unified memory-based framework for lifelong, scalable, and robust multi-robot collaboration** | Roboos-next<br/><sub>bib: <code>25-Roboos-next</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2510.26536) | arXiv |
| **Roco: Dialectic multi-robot collaboration with large language models** | Roco<br/><sub>bib: <code>mandi2024roco</code></sub> | 2024 | — | ICRA |

### Human–Robot Collaboration

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Recognizing actions from robotic view for natural human-robot interaction** | Human–robot collaboration<br/><sub>bib: <code>wang2025recognizing</code></sub> | 2025 | — | ICCV |
| **Robridge: A hierarchical architecture bridging cognition and execution for general robotic manipulation** | Robridge<br/><sub>bib: <code>zhang2025robridge</code></sub> | 2025 | — | ICCV |
| **When embodied AI meets Industry 5.0: Human-centered smart manufacturing** | Human–robot collaboration<br/><sub>bib: <code>25-JAS-Industry5</code></sub> | 2025 | — | IEEE/CAA Journal of Automatica Sinica |
| **An LLM-based approach for enabling seamless Human-Robot collaboration in assembly** | Human–robot collaboration<br/><sub>bib: <code>GKOURNELOS20249</code></sub> | 2024 | [Paper](https://www.sciencedirect.com/science/article/pii/S000785062400012X) | CIRP Annals |
| **Yell at your robot: Improving on-the-fly from language corrections** | Yell at your robot<br/><sub>bib: <code>shi2024yell</code></sub> | 2024 | [Paper](https://arxiv.org/abs/2403.12910) | arXiv |

<a id="sim2real"></a>
## 🌉 From Simulation to Real World

### Physics Engines and Computational Backends

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Newton: GPU-accelerated physics simulation for robotics, and simulation research** | Newton<br/><sub>bib: <code>contributors2025newton</code></sub> | 2025 | [GitHub](https://github.com/newton-physics/newton) | Newton a Series of LF Projects, LLC |
| **Factory: Fast contact for robotic assembly** | Factory<br/><sub>bib: <code>narang2022factory</code></sub> | 2022 | [Paper](https://arxiv.org/abs/2205.03532) | arXiv |
| **Warp: A high-performance python framework for gpu simulation and graphics** | Warp<br/><sub>bib: <code>macklin2022warp</code></sub> | 2022 | [GitHub](https://github.com/NVIDIA/warp) | NVIDIA GPU Technology Conference (GTC) |
| **Brax--a differentiable physics engine for large scale rigid body simulation** | Physics engine<br/><sub>bib: <code>freeman2021brax</code></sub> | 2021 | [Paper](https://arxiv.org/abs/2106.13281) | arXiv |
| **Fast and feature-complete differentiable physics for articulated rigid bodies with contact** | Physics engine<br/><sub>bib: <code>werling2021fast</code></sub> | 2021 | [Paper](https://arxiv.org/abs/2103.16021) | arXiv |
| **Compiling machine learning programs via high-level tracing** | Physics engine<br/><sub>bib: <code>frostig2019compiling</code></sub> | 2019 | — | SysML conference 2018 |
| **Drake: Model-based design and verification for robotics** | Drake<br/><sub>bib: <code>tedrake2019drake</code></sub> | 2019 | [Paper](https://drake.mit.edu/) | — |
| **Dart: Dynamic animation and robotics toolkit** | Dart<br/><sub>bib: <code>lee2018dart</code></sub> | 2018 | — | The Journal of Open Source Software |
| **Per-contact iteration method for solving contact dynamics** | Physics engine<br/><sub>bib: <code>hwangbo2018per</code></sub> | 2018 | — | IEEE Robotics and Automation Letters |
| **PyBullet: A Python Module for Physics Simulation for Games, Robotics, and Machine Learning** | PyBullet<br/><sub>bib: <code>coumans2016pybullet</code></sub> | 2016 | [Paper](https://pybullet.org) | — |
| **Chrono: An open source multi-physics dynamics engine** | Chrono<br/><sub>bib: <code>tasora2015chrono</code></sub> | 2015 | — | international conference on high performance computing in science and engineering |
| **Mujoco: A physics engine for model-based control** | Mujoco<br/><sub>bib: <code>todorov2012mujoco</code></sub> | 2012 | — | IROS |
| **Sofa: A multi-model framework for interactive physical simulation** | Sofa<br/><sub>bib: <code>faure2012sofa</code></sub> | 2012 | — | Soft tissue biomechanical modeling for computer assisted surgery |
| **Open dynamics engine** | Physics engine<br/><sub>bib: <code>smith2005open</code></sub> | 2005 | — | — |
| **Bullet Physics SDK** | Physics engine<br/><sub>bib: <code>bullet3</code></sub> | — | [GitHub](https://github.com/bulletphysics/bullet3) | — |
| **MJX-Warp** | Physics engine<br/><sub>bib: <code>googledeepmind_mjx_warp</code></sub> | — | [Paper](https://mujoco.readthedocs.io/en/stable/mjwarp/index.html) | — |
| **MuJoCo Warp (MJWarp)** | Physics engine<br/><sub>bib: <code>googledeepmind_mujoco_warp</code></sub> | — | [GitHub](https://github.com/google-deepmind/mujoco_warp) | — |
| **MuJoCo XLA (MJX)** | Physics engine<br/><sub>bib: <code>googledeepmind_mjx</code></sub> | — | [Paper](https://mujoco.readthedocs.io/en/stable/mjx.html) | — |
| **NVIDIA PhysX** | Physics engine<br/><sub>bib: <code>nvidia_physx</code></sub> | — | [Paper](https://developer.nvidia.com/physx-sdk) | — |

### Simulation Platforms and Environments

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Nyx for Genesis** | Simulation platform<br/><sub>bib: <code>genesis2026nyx</code></sub> | 2026 | [GitHub](https://github.com/Genesis-Embodied-AI/genesis-nyx) | — |
| **Quadrants: High-Performance Multi-Platform Compiler for Physics Simulation** | Quadrants<br/><sub>bib: <code>genesis2026quadrants</code></sub> | 2026 | [GitHub](https://github.com/Genesis-Embodied-AI/quadrants) | — |
| **The Role of Simulation in Scalable Robotics, Genesis World 1.0, and the Path Forward** | Simulation platform<br/><sub>bib: <code>genesis2026genesisworld</code></sub> | 2026 | [Paper](https://www.genesis.ai/blog/the-role-of-simulation-in-scalable-robotics-genesis-world-10-and-the-path-forward) | Genesis AI Blog |
| **Discoverse: Efficient robot simulation in complex high-fidelity environments** | Discoverse<br/><sub>bib: <code>jia2025discoverse</code></sub> | 2025 | — | IROS |
| **Unity** | Simulation platform<br/><sub>bib: <code>unity_physics</code></sub> | 2025 | [Paper](https://docs.unity3d.com/6000.0/Documentation/Manual/PhysicsSection.html) | — |
| **A review of platforms for simulating embodied agents in 3D virtual environments** | Simulation platform<br/><sub>bib: <code>kaur2023review</code></sub> | 2023 | — | Artificial Intelligence Review |
| **Behavior-1k: A benchmark for embodied ai with 1,000 everyday activities and realistic simulation** | Behavior-1k<br/><sub>bib: <code>li2023behavior</code></sub> | 2023 | — | CoRL |
| **igibson 2.0: Object-centric simulation for robot learning of everyday household tasks** | igibson 2.0<br/><sub>bib: <code>li2021igibson</code></sub> | 2021 | [Paper](https://arxiv.org/abs/2108.03272) | arXiv |
| **Robothor: An open simulation-to-real embodied ai platform** | Robothor<br/><sub>bib: <code>deitke2020robothor</code></sub> | 2020 | — | CVPR |
| **Sapien: A simulated part-based interactive environment** | Sapien<br/><sub>bib: <code>xiang2020sapien</code></sub> | 2020 | — | CVPR |
| **Threedworld: A platform for interactive multi-modal physical simulation** | Threedworld<br/><sub>bib: <code>gan2020threedworld</code></sub> | 2020 | [Paper](https://arxiv.org/abs/2007.04954) | arXiv |
| **Habitat: A Platform for Embodied AI Research** | Habitat<br/><sub>bib: <code>habitat19iccv · savva2019habitat</code></sub> | 2019 | — | ICCV |
| **Ai2-thor: An interactive 3d environment for visual ai** | Ai2-thor<br/><sub>bib: <code>kolve2017ai2</code></sub> | 2017 | [Paper](https://arxiv.org/abs/1712.05474) | arXiv |
| **The material point method** | Simulation platform<br/><sub>bib: <code>zhang2017material</code></sub> | 2017 | — | Elsevier |
| **V-REP: A versatile and scalable robot simulation framework** | V-REP<br/><sub>bib: <code>rohmer2013v</code></sub> | 2013 | — | IROS |
| **Smoothed particle hydrodynamics (SPH): an overview and recent developments** | Simulation platform<br/><sub>bib: <code>liu2010smoothed</code></sub> | 2010 | — | Archives of computational methods in engineering |
| **Position based dynamics** | Simulation platform<br/><sub>bib: <code>muller2007position</code></sub> | 2007 | — | Journal of Visual Communication and Image Representation |
| **Cyberbotics ltd. webots™: professional mobile robot simulation** | Cyberbotics ltd. webots™<br/><sub>bib: <code>michel2004cyberbotics</code></sub> | 2004 | — | International Journal of Advanced Robotic Systems |
| **Design and use paradigms for gazebo, an open-source multi-robot simulator** | Simulation platform<br/><sub>bib: <code>koenig2004design</code></sub> | 2004 | — | IROS |
| **The finite element method** | Simulation platform<br/><sub>bib: <code>zienkiewicz2000finite</code></sub> | 2000 | — | Elsevier |
| **Isaac Sim** | Simulation platform<br/><sub>bib: <code>NVIDIA_Isaac_Sim</code></sub> | — | [GitHub](https://github.com/isaac-sim/IsaacSim) | — |

### Learning Frameworks and Task Toolkits

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **mjlab: A lightweight framework for gpu-accelerated robot learning** | mjlab<br/><sub>bib: <code>zakka2026mjlab</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2601.22074) | arXiv |
| **Deep reinforcement learning for robotic bipedal locomotion: a brief survey** | Robot-learning framework<br/><sub>bib: <code>bao2025deep</code></sub> | 2025 | — | Artificial Intelligence Review |
| **Isaac lab: A gpu-accelerated simulation framework for multi-modal robot learning** | Isaac lab<br/><sub>bib: <code>mittal2025isaac</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2511.04831) | arXiv |
| **ManiSkill3: GPU Parallelized Robotics Simulation and Rendering for Generalizable Embodied AI** | ManiSkill3<br/><sub>bib: <code>taomaniskill3</code></sub> | 2025 | — | RSS |
| **Mujoco playground** | Robot-learning framework<br/><sub>bib: <code>zakka2025mujoco</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2502.08844) | arXiv |
| **Habitat 3.0: A co-habitat for humans, avatars, and robots** | Habitat 3.0<br/><sub>bib: <code>puig2023habitat3</code></sub> | 2024 | — | ICLR |
| **Habitat 2.0: Training home assistants to rearrange their habitat** | Habitat 2.0<br/><sub>bib: <code>szot2021habitat</code></sub> | 2021 | — | NeurIPS |
| **Deepbots: A webots-based deep reinforcement learning framework for robotics** | Deepbots<br/><sub>bib: <code>kirtas2020deepbots</code></sub> | 2020 | — | IFIP international conference on artificial intelligence applications and innovations |
| **dm_control: Software and tasks for continuous control** | dm_control<br/><sub>bib: <code>tunyasuvunakool2020dm_control</code></sub> | 2020 | — | Software Impacts |
| **robosuite: A modular simulation framework and benchmark for robot learning** | robosuite<br/><sub>bib: <code>zhu2020robosuite</code></sub> | 2020 | [Paper](https://arxiv.org/abs/2009.12293) | arXiv |
| **Pyrep: Bringing v-rep to deep robot learning** | Pyrep<br/><sub>bib: <code>james2019pyrep</code></sub> | 2019 | [Paper](https://arxiv.org/abs/1906.11176) | arXiv |

### Evaluation Infrastructures and Sim-to-Real Workflows

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Genie sim 3.0: A high-fidelity comprehensive simulation platform for humanoid robot** | Genie sim 3.0<br/><sub>bib: <code>yin2026genie</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2601.02078) | arXiv |
| **Robolab: A high-fidelity simulation benchmark for analysis of task generalist policies** | Robolab<br/><sub>bib: <code>yang2026robolab</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2604.09860) | arXiv |
| **WM-DAgger: Enabling Efficient Data Aggregation for Imitation Learning with World Models** | WM-DAgger<br/><sub>bib: <code>yu2026wm</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2604.11351) | arXiv |
| **Digital twins to embodied artificial intelligence: Review and perspective** | Evaluation infrastructure<br/><sub>bib: <code>li2025digital</code></sub> | 2025 | — | Intelligence & Robotics |
| **Isaac Lab-Arena: Composable Environment Creation and Policy Evaluation for Robotics** | Isaac Lab-Arena<br/><sub>bib: <code>isaaclab-arena2025</code></sub> | 2025 | [GitHub](https://github.com/isaac-sim/IsaacLab-Arena) | — |
| **Lightwheel RoboFinals** | Evaluation infrastructure<br/><sub>bib: <code>lightwheel2025robofinals</code></sub> | 2025 | [Paper](https://lightwheel.ai/robofinals) | — |
| **Evaluating real-world robot manipulation policies in simulation** | Evaluation infrastructure<br/><sub>bib: <code>li2024evaluating</code></sub> | 2024 | [Paper](https://arxiv.org/abs/2405.05941) | arXiv |
| **Gensim: Generating robotic simulation tasks via large language models** | Gensim<br/><sub>bib: <code>wang2024gensim</code></sub> | 2024 | — | ICLR |
| **Robocasa: Large-scale simulation of everyday tasks for generalist robots** | Robocasa<br/><sub>bib: <code>nasiriany2024robocasa</code></sub> | 2024 | [Paper](https://arxiv.org/abs/2406.02523) | arXiv |
| **LW-BenchHub: Lightwheel's End-to-End Embodied AI Simulation Platform** | LW-BenchHub<br/><sub>bib: <code>Lightwheel_Team_LW-BenchHub_Lightwheel_s_End-to-End</code></sub> | — | [GitHub](https://github.com/lightwheel-ai/lw_benchhub) | — |

### Differentiable Mechanics and Simulation Research

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Fildeep: Learning large deformations of elastic-plastic solids with multi-fidelity data** | Fildeep<br/><sub>bib: <code>tang2026fildeep</code></sub> | 2026 | — | 32nd ACM SIGKDD Conference on Knowledge Discovery and Data Mining V. 1 |
| **Maven: A mesh-aware volumetric encoding network for simulating 3d flexible deformation** | Maven<br/><sub>bib: <code>feng2026maven</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2604.04474) | arXiv |
| **Neural Latent Arbitrary Lagrangian-Eulerian Grids for Fluid-Solid Interaction** | Simulation research<br/><sub>bib: <code>tao2026neural</code></sub> | 2026 | — | ICLR |
| **A survey: Learning embodied intelligence from physical simulators and world models** | A survey<br/><sub>bib: <code>long2025survey</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2507.00917) | arXiv |
| **Ladeep: A deep learning-based surrogate model for large deformation of elastic-plastic solids** | Ladeep<br/><sub>bib: <code>tao2025ladeep</code></sub> | 2025 | — | 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining V. 2 |
| **Unisoma: A Unified Transformer-based Solver for Multi-Solid Systems** | Unisoma<br/><sub>bib: <code>pmlr-v267-tao25b</code></sub> | 2025 | — | ICML |
| **A survey of embodied ai: From simulators to research tasks** | A survey of embodied ai<br/><sub>bib: <code>duan2022survey</code></sub> | 2022 | — | IEEE Transactions on Emerging Topics in Computational Intelligence |

<a id="evaluation"></a>
## 📏 Benchmarks, Reliability, and Evaluation

> For industrial deployment, report task outcome **and** recovery, safety, latency, throughput, reproducibility, and amortized operating cost.

### Industrial Task Suites and Capability Benchmarks

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **How Much Progress Has There Been in NVIDIA Datacenter GPUs?** | Benchmark<br/><sub>bib: <code>26-Nvidia-GPUs</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2601.20115) | arXiv |
| **Industryeqa: Pushing the frontiers of embodied question answering in industrial scenarios** | Industryeqa<br/><sub>bib: <code>26-NeurIPS-Industryeqa</code></sub> | 2026 | — | NeurIPS |
| **Intelligent Automation for Embodied Benchmark Construction: Pipelines, Embodiments, Simulators, and Trends** | Benchmark<br/><sub>bib: <code>lai2026intelligent</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2606.12207) | arXiv |
| **Pac bench: Do foundation models understand prerequisites for executing manipulation policies?** | Pac bench<br/><sub>bib: <code>gundawar2026pac</code></sub> | 2026 | — | NeurIPS |
| **Phyblock: A progressive benchmark for physical understanding and planning via 3d block assembly** | Phyblock<br/><sub>bib: <code>ma2026phyblock</code></sub> | 2026 | — | NeurIPS |
| **RoboMME: Benchmarking and Understanding Memory for Robotic Generalist Policies** | RoboMME<br/><sub>bib: <code>26-ICML-RoboMME</code></sub> | 2026 | — | ICML |
| **RobotArena infty : Scalable Robot Benchmarking via Real-to-Sim Translation** | RobotArena infty<br/><sub>bib: <code>jangir2026robotarena</code></sub> | 2026 | — | ICLR |
| **WorkBenchMark: A LEGO-Based Assembly Benchmark with an Assembly-by-Disassembly Baseline for the Smart Manufacturing League** | WorkBenchMark<br/><sub>bib: <code>ma2026workbenchmark</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2606.19358) | arXiv |
| **BOP Challenge 2025: BOP-Industrial** | BOP Challenge 2025<br/><sub>bib: <code>bopindustrial2025</code></sub> | 2025 | [Paper](https://bop.felk.cvut.cz/challenges/bop-challenge-2025/) | — |
| **From production logistics to smart manufacturing: The vision for a new RoboCup industrial league** | Benchmark<br/><sub>bib: <code>dissanayaka2025production</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2507.11402) | arXiv |
| **IndustryNav: Exploring Spatial Reasoning of Embodied Agents in Dynamic Industrial Navigation** | IndustryNav<br/><sub>bib: <code>25-IndustryNav</code></sub> | 2025 | — | arXiv |
| **Maniskill-hab: A benchmark for low-level manipulation in home rearrangement tasks** | Maniskill-hab<br/><sub>bib: <code>shukla2025maniskill</code></sub> | 2025 | — | ICLR |
| **RoboBPP: Benchmarking robotic online bin packing with physics-based simulation** | RoboBPP<br/><sub>bib: <code>25-RoboBpp</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2512.04415) | arXiv |
| **World Robot Summit 2025: Manufacturing Robotics Challenge** | World Robot Summit 2025<br/><sub>bib: <code>wrs2025manufacturing</code></sub> | 2025 | [Paper](https://worldrobotsummit.org/en/wrs2025/mrc/) | — |
| **A retrospective on the Robot Air Hockey Challenge: benchmarking robust, reliable, and safe learning techniques for real-world robotics** | Benchmark<br/><sub>bib: <code>liu2024retrospective</code></sub> | 2024 | — | NeurIPS |
| **AutoMate: Specialist and Generalist Assembly Policies over Diverse Geometries.** | AutoMate<br/><sub>bib: <code>tang2024automate</code></sub> | 2024 | — | RSS |
| **Point cloud matters: Rethinking the impact of different observation spaces on robot learning** | Point cloud matters<br/><sub>bib: <code>zhu2024point</code></sub> | 2024 | — | NeurIPS |
| **Industreal: Transferring contact-rich assembly tasks from simulation to reality** | Industreal<br/><sub>bib: <code>tang2023industreal</code></sub> | 2023 | [Paper](https://arxiv.org/abs/2305.17110) | arXiv |
| **Maniskill2: A unified benchmark for generalizable manipulation skills** | Maniskill2<br/><sub>bib: <code>gu2023maniskill2</code></sub> | 2023 | [Paper](https://arxiv.org/abs/2302.04659) | arXiv |
| **Assessing industrial robot agility through international competitions** | Benchmark<br/><sub>bib: <code>21-ARIAC</code></sub> | 2021 | — | Robotics and computer-integrated manufacturing |
| **Robotic grasping and manipulation competition: Future tasks to support the development of assembly robotics** | Benchmark<br/><sub>bib: <code>van2016robotic</code></sub> | 2016 | — | Robotic Grasping and Manipulation Challenge |

### Physical, Offline, and Distributed Evaluation

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **RoboArena: Distributed Real-World Evaluation of Generalist Robot Policies** | RoboArena<br/><sub>bib: <code>atreya2025roboarena</code></sub> | 2025 | [Paper](https://proceedings.mlr.press/v305/atreya25a.html) | CoRL |
| **RoboChallenge: Large-scale Real-robot Evaluation of Embodied Policies** | RoboChallenge<br/><sub>bib: <code>yakefu2025robochallenge</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2510.17950) | CoRR |
| **Towards Using Multiple Iterated, Reproduced, and Replicated Experiments with Robots (MIRRER) for Evaluation and Benchmarking** | Real-world benchmark<br/><sub>bib: <code>norton2024mirrer</code></sub> | 2024 | [Paper](https://arxiv.org/abs/2408.04736) | — |
| **ARMBench: An Object-centric Benchmark Dataset for Robotic Manipulation** | ARMBench<br/><sub>bib: <code>mitash2023armbench</code></sub> | 2023 | [Paper](https://doi.org/10.1109/ICRA48891.2023.10160846) | ICRA |
| **Performance measures to benchmark the grasping, manipulation, and assembly of deformable objects typical to manufacturing applications** | Real-world benchmark<br/><sub>bib: <code>kimble2022performance</code></sub> | 2022 | — | Frontiers in Robotics and AI |
| **RB2: Robotic Manipulation Benchmarking with a Twist** | RB2<br/><sub>bib: <code>dasari2021rb2</code></sub> | 2021 | [Paper](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/hash/3988c7f88ebcb58c6ce932b957b6f332-Abstract-round2.html) | NeurIPS |

<a id="future-directions"></a>
## ⚡ Emerging Directions

> The frontier is not a separate silo: multimodal grounding, long-horizon memory, metacognitive control, and collective intelligence are linked back to their operational homes above.

### Research Roadmap

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Towards a unified understanding of robot manipulation: A comprehensive survey** | Research agenda<br/><sub>bib: <code>25-Manipulation-Review</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2510.10903) | arXiv |

## 📐 Curation Rules

- Keep the list **capability-first**: add a work under the problem it principally solves, not under the manuscript section where it happened to be cited.
- Use the row format **Title | Focus / Model | Year | Links | Venue**. Keep publisher, DOI, arXiv, or official project links in the `Paper` slot; only use the `GitHub` slot for an explicit repository link.
- Prefer one primary placement. For genuinely cross-cutting work, add a short text cross-reference rather than duplicating a full row.
- The small `bib:` label keeps the supplied source bibliography auditable. It does not claim independent replication, code availability, or scientific validation.

### Maintainer

[@derongdeng](https://github.com/derongdeng) — catalogue curation and maintenance

### 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=EmbodiedLogiX/Awesome-Industrial-Embodied-Intelligence&type=Date)](https://star-history.com/#EmbodiedLogiX/Awesome-Industrial-Embodied-Intelligence&Date)
