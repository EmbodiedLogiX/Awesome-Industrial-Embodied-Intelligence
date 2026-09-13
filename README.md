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

Each row keeps links compact: `[Paper] | [GitHub]`. `Paper` links point to a publisher, DOI, arXiv, or official project record; `GitHub` links are restricted to author- or organization-maintained repositories confirmed from paper, project, or repository metadata. `—` means no verified link of that kind is available — never a placeholder.

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
| **Energy and Carbon Footprint of Vision-Language-Action Model Inference for Edge Robotic Systems** | Industrial embodied intelligence<br/><sub>bib: <code>26-ACMGSCC-Energy</code></sub> | 2026 | [Paper](https://doi.org/10.1145/3797248.3815411) | 16th ACM International Green and Sustainable Computing Conference |
| **IEI-TIA: Industrial Embodied Intelligence Trustworthy Interpretable Agent for Robotic Long-Horizon and Repetitive Tasks** | IEI-TIA<br/><sub>bib: <code>26-TASE-IEI-TIA</code></sub> | 2026 | [Paper](https://doi.org/10.1109/TASE.2026.3687369) | IEEE Transactions on Automation Science and Engineering |
| **Embodied Intelligence for Flexible Manufacturing: A Survey** | Industrial embodied intelligence<br/><sub>bib: <code>25-FlexibleManusfacturing</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2602.06966) | arXiv |
| **Embodied intelligence: A synergy of morphology, action, perception and learning** | Embodied intelligence<br/><sub>bib: <code>25-CSUR-Embodied-Intelligence</code></sub> | 2025 | [Paper](https://doi.org/10.1145/3717059) | ACM Computing Surveys |
| **LAECIPS: Large vision model assisted adaptive edge-cloud collaboration for IoT-based embodied intelligence system** | LAECIPS<br/><sub>bib: <code>25-JIII-LAECIPS</code></sub> | 2025 | [Paper](https://doi.org/10.1016/j.jii.2025.100955) | Journal of Industrial Information Integration |
| **Safe human--robot collaboration for industrial settings: a survey** | Industrial embodied intelligence<br/><sub>bib: <code>24-JIM-SafeHRC</code></sub> | 2024 | [Paper](https://doi.org/10.1007/s10845-023-02159-4) | Journal of Intelligent Manufacturing |

### Cognitive Frameworks and Spatial Grounding

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Bio-inspired cognitive navigation for robots** | Cognitive framework<br/><sub>bib: <code>26-NREE-CogNav</code></sub> | 2026 | [Paper](https://doi.org/10.1038/s44287-026-00294-7) | Nature Reviews Electrical Engineering |
| **Two by two: Learning multi-task pairwise objects assembly for generalizable robot manipulation** | Two by two<br/><sub>bib: <code>25-CVPR-2BY2</code></sub> | 2025 | [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Qi_Two_by_Two_Learning_Multi-Task_Pairwise_Objects_Assembly_for_Generalizable_CVPR_2025_paper.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/TEA-Lab/TwoByTwo) | CVPR |

<a id="perception"></a>
## 👁️ Perception, Spatial Intelligence, and World Models

### Multimodal Sensing and Interaction

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Event-Driven Visual-Tactile Sensing and Learning for Robots** | Multimodal perception<br/><sub>bib: <code>taunyazov20event</code></sub> | 2020 | [Paper](https://arxiv.org/abs/2009.07083)&nbsp;&#124;&nbsp;[GitHub](https://github.com/clear-nus/VT_SNN) | RSS |
| **Making Sense of Vision and Touch: Self-Supervised Learning of Multimodal Representations for Contact-Rich Tasks** | Making Sense of Vision and Touch<br/><sub>bib: <code>lee2019makings</code></sub> | 2019 | [Paper](https://doi.org/10.1109/ICRA.2019.8793485) | ICRA |

### Industrial Semantics, Scene Graphs, and World Models

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **AssemMate: Graph-Based LLM for Robotic Assembly Assistance** | AssemMate<br/><sub>bib: <code>zheng2026assemmategraphbasedllmrobotic</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2509.11617)&nbsp;&#124;&nbsp;[GitHub](https://github.com/cristina304/AssemMate) | — |
| **A large language model-enabled machining process knowledge graph construction method for intelligent process planning** | World model<br/><sub>bib: <code>XU2025103244</code></sub> | 2025 | [Paper](https://www.sciencedirect.com/science/article/pii/S1474034625001375) | Advanced Engineering Informatics |
| **Generation of Asset Administration Shell With Large Language Model Agents: Toward Semantic Interoperability in Digital Twins in the Context of Industry 4.0** | World model<br/><sub>bib: <code>10559483</code></sub> | 2024 | [Paper](https://doi.org/10.1109/ACCESS.2024.3415470) | IEEE Access |

<a id="memory"></a>
## 💾 Memory and Continual Adaptation

### Memory Construction and Continual Experience

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Embodied agents meet personalization: Investigating challenges and solutions through the lens of memory utilization** | Memory architecture<br/><sub>bib: <code>26-ICLR-Personalization</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2505.16348)&nbsp;&#124;&nbsp;[GitHub](https://github.com/Connoriginal/MEMENTO) | ICLR |
| **Mem: Multi-scale embodied memory for vision language action models** | Mem<br/><sub>bib: <code>26-Mem</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2603.03596) | arXiv |
| **Memoryvla: Perceptual-cognitive memory in vision-language-action models for robotic manipulation** | Memoryvla<br/><sub>bib: <code>26-ICLR-MemoryVLA</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2508.19236)&nbsp;&#124;&nbsp;[GitHub](https://github.com/shihao1895/MemoryVLA) | ICLR |
| **Response-G1: Explicit Scene Graph Modeling for Proactive Streaming Video Understanding** | Response-G1<br/><sub>bib: <code>26-ACL-ResponseG1</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2605.07575)&nbsp;&#124;&nbsp;[GitHub](https://github.com/PolyX-Research/Response-G1) | ACL |
| **Embodied videoagent: Persistent memory from egocentric videos and embodied sensors enables dynamic scene understanding** | Embodied videoagent<br/><sub>bib: <code>25-ICCV-EmbodiedVideoAgent</code></sub> | 2025 | [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Fan_Embodied_VideoAgent_Persistent_Memory_from_Egocentric_Videos_and_Embodied_Sensors_ICCV_2025_paper.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/Embodied-VideoAgent/embodied-videoagent) | ICCV |
| **Enter the mind palace: Reasoning and planning for long-term active embodied question answering** | Enter the mind palace<br/><sub>bib: <code>25-SceneMemory</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2507.12846)&nbsp;&#124;&nbsp;[GitHub](https://github.com/mind-palace-laeqa/benchmark) | arXiv |
| **From human memory to ai memory: A survey on memory mechanisms in the era of llms** | From human memory to ai memory<br/><sub>bib: <code>25-AI-memory</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2504.15965) | arXiv |
| **Robomemory: A brain-inspired multi-memory agentic framework for lifelong learning in physical embodied systems** | Robomemory<br/><sub>bib: <code>25-NeurIPS-Robomemory</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2508.01415) | NeurIPS 2025 Workshop on Space in Vision, Language, and Embodied AI |
| **SAM2Act: Integrating Visual Foundation Model with A Memory Architecture for Robotic Manipulation** | SAM2Act<br/><sub>bib: <code>25-ICML-SAM2ACT</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2501.18564)&nbsp;&#124;&nbsp;[GitHub](https://github.com/sam2act/sam2act) | ICML |
| **Collaborative Conversation in Safe Multimodal Human-Robot Collaboration** | Memory architecture<br/><sub>bib: <code>Ferrari2024colla</code></sub> | 2024 | [Paper](https://arxiv.org/abs/2409.07158) | IROS |
| **Robustifying Long-term Human-Robot Collaboration through a Hierarchical and Multimodal Framework** | Memory architecture<br/><sub>bib: <code>yu2024robustify</code></sub> | 2024 | [Paper](https://arxiv.org/abs/2411.15711) | arXiv |
| **Detecting Worker Attention Lapses in Human-Robot Interaction: An Eye Tracking and Multimodal Sensing Study** | Memory architecture<br/><sub>bib: <code>Dai2023detectingwork</code></sub> | 2023 | [Paper](https://doi.org/10.1109/ICAC57885.2023.10275177) | 2023 28th International Conference on Automation and Computing (ICAC) |
| **Play it by Ear: Learning Skills amidst Occlusion through Audio-Visual Imitation Learning** | Play it by Ear<br/><sub>bib: <code>du2022playitbyear</code></sub> | 2022 | [Paper](https://doi.org/10.15607/RSS.2022.XVIII.009) | RSS |
| **Human memory: A proposed system and its control processes** | Human memory<br/><sub>bib: <code>1968-Human-Memory</code></sub> | 1968 | [Paper](https://doi.org/10.1016/S0079-7421(08)60422-3) | Psychology of learning and motivation |

### Long-Horizon Video, Compression, and Keyframes

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Attend Before Attention: Efficient and Scalable Video Understanding via Autoregressive Gazing** | Attend Before Attention<br/><sub>bib: <code>26-CVPR-AutoGaze</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2603.12254)&nbsp;&#124;&nbsp;[GitHub](https://github.com/NVlabs/AutoGaze) | CVPR |
| **FlashVID: Efficient Video Large Language Models via Training-free Tree-based Spatiotemporal Token Merging** | FlashVID<br/><sub>bib: <code>26-ICLR-FlashVID</code></sub> | 2026 | [Paper](https://openreview.net/forum?id=H6rDX4w6Al) | ICLR |
| **KEMO: Event-Driven Keyframe Memory for Long-Horizon Robot Manipulation with VLA Policies** | KEMO<br/><sub>bib: <code>26-KEMO</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2606.23589) | — |
| **Non-markovian long-horizon robot manipulation via keyframe chaining** | Memory-efficient video model<br/><sub>bib: <code>26-KeyFrameVLA</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2603.01465)&nbsp;&#124;&nbsp;[GitHub](https://github.com/cytoplastm/KC-VLA) | arXiv |
| **Token Reduction via Local and Global Contexts Optimization for Efficient Video Large Language Models** | Memory-efficient video model<br/><sub>bib: <code>26-CVPR-AOT</code></sub> | 2026 | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Li_Token_Reduction_via_Local_and_Global_Contexts_Optimization_for_Efficient_CVPR_2026_paper.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/TyroneLi/AOT) | CVPR |
| **VisionPulse: Dynamic Visual Sparsity for Efficient Multimodal Reasoning** | VisionPulse<br/><sub>bib: <code>26-ICML-VisionPulse</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2605.31457) | ICML |
| **Longvu: Spatiotemporal adaptive compression for long video-language understanding** | Longvu<br/><sub>bib: <code>25-ICML-LongVU</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2410.17434)&nbsp;&#124;&nbsp;[GitHub](https://github.com/Vision-CAIR/LongVU) | ICML |
| **Memo: Training memory-efficient embodied agents with reinforcement learning** | Memo<br/><sub>bib: <code>25-NeurIPS-Memo</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2510.19732)&nbsp;&#124;&nbsp;[GitHub](https://github.com/gunshi/memo) | NeurIPS |
| **Efficient Streaming Language Models with Attention Sinks** | Memory-efficient video model<br/><sub>bib: <code>24-ICLR-KVcache</code></sub> | 2024 | [Paper](https://arxiv.org/abs/2309.17453)&nbsp;&#124;&nbsp;[GitHub](https://github.com/mit-han-lab/streaming-llm) | ICLR |
| **An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale** | An Image is Worth 16x16 Words<br/><sub>bib: <code>21-ICLR-ViT</code></sub> | 2021 | [Paper](https://arxiv.org/abs/2010.11929)&nbsp;&#124;&nbsp;[GitHub](https://github.com/google-research/vision_transformer) | ICLR |

### Experience Retrieval and Generative Reconstruction

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **MemER: Scaling Up Memory for Robot Control via Experience Retrieval** | MemER<br/><sub>bib: <code>26-ICLR-MEBER</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2510.20328) | ICLR |
| **Memgen: Weaving generative latent memory for self-evolving agents** | Memgen<br/><sub>bib: <code>26-ICLR-Memgen</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2509.24704)&nbsp;&#124;&nbsp;[GitHub](https://github.com/KANABOON1/MemGen) | ICLR |
| **Scaling the Long Video Understanding of Multimodal Large Language Models via Visual Memory Mechanism** | Experience retrieval<br/><sub>bib: <code>26-CVPR-FlexMem</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2603.29252)&nbsp;&#124;&nbsp;[GitHub](https://github.com/city1517/FlexMem) | CVPR |
| **Jarvis-1: Open-world multi-task agents with memory-augmented multimodal language models** | Jarvis-1<br/><sub>bib: <code>24-TPAMI-Jarvis1</code></sub> | 2024 | [Paper](https://arxiv.org/abs/2311.05997)&nbsp;&#124;&nbsp;[GitHub](https://github.com/CraftJarvis/JARVIS-1) | IEEE Transactions on Pattern Analysis and Machine Intelligence |
| **Remembering: A study in experimental and social psychology** | Remembering<br/><sub>bib: <code>1995-Remembering-Reconstruct</code></sub> | 1995 | — | Cambridge university press |

### Multimodal Memory and Memory Benchmarks

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Mem-gallery: Benchmarking multimodal long-term conversational memory for mllm agents** | Mem-gallery<br/><sub>bib: <code>26-ACL-MemGallery</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2601.03515)&nbsp;&#124;&nbsp;[GitHub](https://github.com/YuanchenBei/Mem-Gallery) | ACL |
| **A generative model of memory construction and consolidation** | Multimodal memory<br/><sub>bib: <code>24-MHB-Generative · 24-NHB-Generative</code></sub> | 2024 | [Paper](https://doi.org/10.1038/s41562-023-01799-z)&nbsp;&#124;&nbsp;[GitHub](https://github.com/ellie-as/generative-memory) | Nature Human Behaviour |
| **Constructive memory: past and future** | Constructive memory<br/><sub>bib: <code>12-Constructive-Memory</code></sub> | 2012 | [Paper](https://doi.org/10.31887/DCNS.2012.14.1/dschacter) | Dialogues in clinical neuroscience |

<a id="decision-making"></a>
## 🕹️ Decision-Making and Action Models

### Generalist Vision–Language–Action Policies

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **OpenVLA: An Open-Source Vision-Language-Action Model** | OpenVLA<br/><sub>bib: <code>kim2025openvla</code></sub> | 2025 | [Paper](https://proceedings.mlr.press/v270/kim25c.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/openvla/openvla) | CoRL |
| **π₀: A Vision-Language-Action Flow Model for General Robot Control** | π₀<br/><sub>bib: <code>black2025pi0</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2410.24164)&nbsp;&#124;&nbsp;[GitHub](https://github.com/Physical-Intelligence/openpi) | RSS |
| **Octo: An Open-Source Generalist Robot Policy** | Octo<br/><sub>bib: <code>ghosh2024octo</code></sub> | 2024 | [Paper](https://www.roboticsproceedings.org/rss20/p090.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/octo-models/octo) | RSS |
| **Learning fine-grained bimanual manipulation with low-cost hardware** | VLA policy<br/><sub>bib: <code>23-ACT</code></sub> | 2023 | [Paper](https://arxiv.org/abs/2304.13705)&nbsp;&#124;&nbsp;[GitHub](https://github.com/tonyzhaozh/aloha) | arXiv |
| **RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control** | RT-2<br/><sub>bib: <code>23-Rt2 · zitkovich2023rt2</code></sub> | 2023 | [Paper](https://proceedings.mlr.press/v229/zitkovich23a.html) | CoRL |

### Reasoning, Affordances, and Self-Assessment

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **ACoT-VLA: Action Chain-of-Thought for Vision-Language-Action Models** | ACoT-VLA<br/><sub>bib: <code>zhong2026acotvla</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2601.11404)&nbsp;&#124;&nbsp;[GitHub](https://github.com/AgibotTech/ACoT-VLA) | CVPR |
| **Think Before Action: Learning Suction Health for Reliable Grasp Evaluation in Logistics** | Think Before Action<br/><sub>bib: <code>26-KDD-GraspGuard</code></sub> | 2026 | [Paper](https://doi.org/10.1145/3770855.3818492) | 32nd ACM SIGKDD Conference on Knowledge Discovery and Data Mining V. 2 |
| **villa-X: Enhancing Latent Action Modeling in Vision-Language-Action Models** | villa-X<br/><sub>bib: <code>26-ICLR-villaX</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2507.23682)&nbsp;&#124;&nbsp;[GitHub](https://github.com/microsoft/villa-x) | ICLR |
| **CoA-VLA: Improving Vision-Language-Action Models via Visual-Text Chain-of-Affordance** | CoA-VLA<br/><sub>bib: <code>li2025coavla</code></sub> | 2025 | [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Li_CoA-VLA_Improving_Vision-Language-Action_Models_via_Visual-Text_Chain-of-Affordance_ICCV_2025_paper.html) | ICCV |
| **CoT-VLA: Visual Chain-of-Thought Reasoning for Vision-Language-Action Models** | CoT-VLA<br/><sub>bib: <code>zhao2025cotvla</code></sub> | 2025 | [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Zhao_CoT-VLA_Visual_Chain-of-Thought_Reasoning_for_Vision-Language-Action_Models_CVPR_2025_paper.html) | CVPR |
| **Dense Policy: Bidirectional Autoregressive Learning of Actions** | Dense Policy<br/><sub>bib: <code>25-ICCV-DensePolicy</code></sub> | 2025 | [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Su_Dense_Policy_Bidirectional_Autoregressive_Learning_of_Actions_ICCV_2025_paper.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/Selen-Suyue/DensePolicy) | ICCV |

### Fast and On-Device Action Generation

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Real-time execution of action chunking flow policies** | Efficient action policy<br/><sub>bib: <code>black2026real</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2506.07339)&nbsp;&#124;&nbsp;[GitHub](https://github.com/Physical-Intelligence/real-time-chunking-kinetix) | NeurIPS |
| **On-device diffusion transformer policy for efficient robot manipulation** | Efficient action policy<br/><sub>bib: <code>wu2025device</code></sub> | 2025 | [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Wu_On-Device_Diffusion_Transformer_Policy_for_Efficient_Robot_Manipulation_ICCV_2025_paper.html) | ICCV |
| **One-Step Diffusion Policy: Fast Visuomotor Policies via Diffusion Distillation** | One-Step Diffusion Policy<br/><sub>bib: <code>pmlr-v267-wang25ba</code></sub> | 2025 | [Paper](https://proceedings.mlr.press/v267/wang25ba.html) | ICML |

<a id="collaboration"></a>
## 🤝 Multi-Agent and Human–Robot Collaboration

### Multi-Robot and Collective Intelligence

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Dynamic reconfiguration in multi-robot agent systems using embedded language models** | Multi-robot collaboration<br/><sub>bib: <code>MURDIVIEN2026103308</code></sub> | 2026 | [Paper](https://www.sciencedirect.com/science/article/pii/S0736584526000876) | Robotics and Computer-Integrated Manufacturing |
| **When Multi-Robot Systems Meet Agentic AI: Towards Embodied Collective Intelligence** | Multi-robot collaboration<br/><sub>bib: <code>yan2026multi</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2606.27929) | arXiv |
| **Capability-aware shared hypernetworks for flexible heterogeneous multi-robot coordination** | Multi-robot collaboration<br/><sub>bib: <code>fu2025capability</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2501.06058) | arXiv |
| **Collaborative tree search for enhancing embodied multi-agent collaboration** | Multi-robot collaboration<br/><sub>bib: <code>zu2025collaborative</code></sub> | 2025 | [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Zu_Collaborative_Tree_Search_for_Enhancing_Embodied_Multi-Agent_Collaboration_CVPR_2025_paper.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/zulihit/CoTS) | CVPR |
| **Emos: Embodiment-aware heterogeneous multi-robot operating system with llm agents** | Emos<br/><sub>bib: <code>chen2025emos</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2410.22662)&nbsp;&#124;&nbsp;[GitHub](https://github.com/SgtVincent/EMOS) | ICLR |
| **Robofactory: Exploring embodied agent collaboration with compositional constraints** | Robofactory<br/><sub>bib: <code>qin2025robofactory</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2503.16408)&nbsp;&#124;&nbsp;[GitHub](https://github.com/MARS-EAI/RoboFactory) | ICCV |
| **Roboos-next: A unified memory-based framework for lifelong, scalable, and robust multi-robot collaboration** | Roboos-next<br/><sub>bib: <code>25-Roboos-next</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2510.26536) | arXiv |
| **Roco: Dialectic multi-robot collaboration with large language models** | Roco<br/><sub>bib: <code>mandi2024roco</code></sub> | 2024 | [Paper](https://arxiv.org/abs/2307.04738)&nbsp;&#124;&nbsp;[GitHub](https://github.com/MandiZhao/robot-collab) | ICRA |

### Human–Robot Collaboration

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Recognizing actions from robotic view for natural human-robot interaction** | Human–robot collaboration<br/><sub>bib: <code>wang2025recognizing</code></sub> | 2025 | [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Wang_Recognizing_Actions_from_Robotic_View_for_Natural_Human-Robot_Interaction_ICCV_2025_paper.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/wangzy01/ACTIVE-Action-from-Robotic-View) | ICCV |
| **Robridge: A hierarchical architecture bridging cognition and execution for general robotic manipulation** | Robridge<br/><sub>bib: <code>zhang2025robridge</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2505.01709)&nbsp;&#124;&nbsp;[GitHub](https://github.com/abliao/RoBridge) | ICCV |
| **When embodied AI meets Industry 5.0: Human-centered smart manufacturing** | Human–robot collaboration<br/><sub>bib: <code>25-JAS-Industry5</code></sub> | 2025 | [Paper](https://doi.org/10.1109/JAS.2025.125327) | IEEE/CAA Journal of Automatica Sinica |
| **An LLM-based approach for enabling seamless Human-Robot collaboration in assembly** | Human–robot collaboration<br/><sub>bib: <code>GKOURNELOS20249</code></sub> | 2024 | [Paper](https://www.sciencedirect.com/science/article/pii/S000785062400012X) | CIRP Annals |
| **Yell at your robot: Improving on-the-fly from language corrections** | Yell at your robot<br/><sub>bib: <code>shi2024yell</code></sub> | 2024 | [Paper](https://arxiv.org/abs/2403.12910) | arXiv |

<a id="sim2real"></a>
## 🌉 From Simulation to Real World

### Physics Engines and Computational Backends

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Newton: GPU-accelerated physics simulation for robotics, and simulation research** | Newton<br/><sub>bib: <code>contributors2025newton</code></sub> | 2025 | [GitHub](https://github.com/newton-physics/newton) | Newton a Series of LF Projects, LLC |
| **Factory: Fast contact for robotic assembly** | Factory<br/><sub>bib: <code>narang2022factory</code></sub> | 2022 | [Paper](https://arxiv.org/abs/2205.03532)&nbsp;&#124;&nbsp;[GitHub](https://github.com/isaac-sim/IsaacGymEnvs) | arXiv |
| **Warp: A high-performance python framework for gpu simulation and graphics** | Warp<br/><sub>bib: <code>macklin2022warp</code></sub> | 2022 | [GitHub](https://github.com/NVIDIA/warp) | NVIDIA GPU Technology Conference (GTC) |
| **Brax--a differentiable physics engine for large scale rigid body simulation** | Physics engine<br/><sub>bib: <code>freeman2021brax</code></sub> | 2021 | [Paper](https://arxiv.org/abs/2106.13281)&nbsp;&#124;&nbsp;[GitHub](https://github.com/google/brax) | arXiv |
| **Fast and feature-complete differentiable physics for articulated rigid bodies with contact** | Physics engine<br/><sub>bib: <code>werling2021fast</code></sub> | 2021 | [Paper](https://arxiv.org/abs/2103.16021) | arXiv |
| **Compiling machine learning programs via high-level tracing** | Physics engine<br/><sub>bib: <code>frostig2019compiling</code></sub> | 2019 | [Paper](https://research.google/pubs/compiling-machine-learning-programs-via-high-level-tracing/)&nbsp;&#124;&nbsp;[GitHub](https://github.com/jax-ml/jax) | SysML conference 2018 |
| **Drake: Model-based design and verification for robotics** | Drake<br/><sub>bib: <code>tedrake2019drake</code></sub> | 2019 | [Paper](https://drake.mit.edu/)&nbsp;&#124;&nbsp;[GitHub](https://github.com/RobotLocomotion/drake) | — |
| **Dart: Dynamic animation and robotics toolkit** | Dart<br/><sub>bib: <code>lee2018dart</code></sub> | 2018 | [Paper](https://doi.org/10.21105/joss.00500)&nbsp;&#124;&nbsp;[GitHub](https://github.com/dartsim/dart) | The Journal of Open Source Software |
| **Per-contact iteration method for solving contact dynamics** | Physics engine<br/><sub>bib: <code>hwangbo2018per</code></sub> | 2018 | [Paper](https://doi.org/10.1109/LRA.2018.2792536) | IEEE Robotics and Automation Letters |
| **PyBullet: A Python Module for Physics Simulation for Games, Robotics, and Machine Learning** | PyBullet<br/><sub>bib: <code>coumans2016pybullet</code></sub> | 2016 | [Paper](https://pybullet.org) | — |
| **Chrono: An open source multi-physics dynamics engine** | Chrono<br/><sub>bib: <code>tasora2015chrono</code></sub> | 2015 | [Paper](https://doi.org/10.1007/978-3-319-40361-8_2)&nbsp;&#124;&nbsp;[GitHub](https://github.com/projectchrono/chrono) | international conference on high performance computing in science and engineering |
| **Mujoco: A physics engine for model-based control** | Mujoco<br/><sub>bib: <code>todorov2012mujoco</code></sub> | 2012 | [Paper](https://doi.org/10.1109/IROS.2012.6386109)&nbsp;&#124;&nbsp;[GitHub](https://github.com/google-deepmind/mujoco) | IROS |
| **Sofa: A multi-model framework for interactive physical simulation** | Sofa<br/><sub>bib: <code>faure2012sofa</code></sub> | 2012 | [Paper](https://www.lirmm.fr/~gilles/papers/faure_springer12.pdf)&nbsp;&#124;&nbsp;[GitHub](https://github.com/sofa-framework/sofa) | Soft tissue biomechanical modeling for computer assisted surgery |
| **Open dynamics engine** | Physics engine<br/><sub>bib: <code>smith2005open</code></sub> | 2005 | — | — |
| **Bullet Physics SDK** | Physics engine<br/><sub>bib: <code>bullet3</code></sub> | — | [GitHub](https://github.com/bulletphysics/bullet3) | — |
| **MJX-Warp** | Physics engine<br/><sub>bib: <code>googledeepmind_mjx_warp</code></sub> | — | [Paper](https://mujoco.readthedocs.io/en/stable/mjwarp/index.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/google-deepmind/mujoco_warp) | — |
| **MuJoCo Warp (MJWarp)** | Physics engine<br/><sub>bib: <code>googledeepmind_mujoco_warp</code></sub> | — | [GitHub](https://github.com/google-deepmind/mujoco_warp) | — |
| **MuJoCo XLA (MJX)** | Physics engine<br/><sub>bib: <code>googledeepmind_mjx</code></sub> | — | [Paper](https://mujoco.readthedocs.io/en/stable/mjx.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/google-deepmind/mujoco) | — |
| **NVIDIA PhysX** | Physics engine<br/><sub>bib: <code>nvidia_physx</code></sub> | — | [Paper](https://developer.nvidia.com/physx-sdk) | — |

### Simulation Platforms and Environments

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Nyx for Genesis** | Simulation platform<br/><sub>bib: <code>genesis2026nyx</code></sub> | 2026 | [GitHub](https://github.com/Genesis-Embodied-AI/genesis-nyx) | — |
| **Quadrants: High-Performance Multi-Platform Compiler for Physics Simulation** | Quadrants<br/><sub>bib: <code>genesis2026quadrants</code></sub> | 2026 | [GitHub](https://github.com/Genesis-Embodied-AI/quadrants) | — |
| **The Role of Simulation in Scalable Robotics, Genesis World 1.0, and the Path Forward** | Simulation platform<br/><sub>bib: <code>genesis2026genesisworld</code></sub> | 2026 | [Paper](https://www.genesis.ai/blog/the-role-of-simulation-in-scalable-robotics-genesis-world-10-and-the-path-forward)&nbsp;&#124;&nbsp;[GitHub](https://github.com/Genesis-Embodied-AI/genesis-world) | Genesis AI Blog |
| **Discoverse: Efficient robot simulation in complex high-fidelity environments** | Discoverse<br/><sub>bib: <code>jia2025discoverse</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2507.21981)&nbsp;&#124;&nbsp;[GitHub](https://github.com/discoverse-dev/DISCOVERSE) | IROS |
| **Unity** | Simulation platform<br/><sub>bib: <code>unity_physics</code></sub> | 2025 | [Paper](https://docs.unity3d.com/6000.0/Documentation/Manual/PhysicsSection.html) | — |
| **A review of platforms for simulating embodied agents in 3D virtual environments** | Simulation platform<br/><sub>bib: <code>kaur2023review</code></sub> | 2023 | [Paper](https://doi.org/10.1007/s10462-022-10253-x) | Artificial Intelligence Review |
| **Behavior-1k: A benchmark for embodied ai with 1,000 everyday activities and realistic simulation** | Behavior-1k<br/><sub>bib: <code>li2023behavior</code></sub> | 2023 | [Paper](https://proceedings.mlr.press/v205/li23a.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/StanfordVL/BEHAVIOR-1K) | CoRL |
| **igibson 2.0: Object-centric simulation for robot learning of everyday household tasks** | igibson 2.0<br/><sub>bib: <code>li2021igibson</code></sub> | 2021 | [Paper](https://proceedings.mlr.press/v164/li22b.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/StanfordVL/iGibson) | arXiv |
| **Robothor: An open simulation-to-real embodied ai platform** | Robothor<br/><sub>bib: <code>deitke2020robothor</code></sub> | 2020 | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Deitke_RoboTHOR_An_Open_Simulation-to-Real_Embodied_AI_Platform_CVPR_2020_paper.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/allenai/ai2thor) | CVPR |
| **Sapien: A simulated part-based interactive environment** | Sapien<br/><sub>bib: <code>xiang2020sapien</code></sub> | 2020 | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Xiang_SAPIEN_A_SimulAted_Part-Based_Interactive_ENvironment_CVPR_2020_paper.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/haosulab/SAPIEN) | CVPR |
| **Threedworld: A platform for interactive multi-modal physical simulation** | Threedworld<br/><sub>bib: <code>gan2020threedworld</code></sub> | 2020 | [Paper](https://arxiv.org/abs/2007.04954)&nbsp;&#124;&nbsp;[GitHub](https://github.com/threedworld-mit/tdw) | arXiv |
| **Habitat: A Platform for Embodied AI Research** | Habitat<br/><sub>bib: <code>habitat19iccv · savva2019habitat</code></sub> | 2019 | [Paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Savva_Habitat_A_Platform_for_Embodied_AI_Research_ICCV_2019_paper.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/facebookresearch/habitat-lab) | ICCV |
| **Ai2-thor: An interactive 3d environment for visual ai** | Ai2-thor<br/><sub>bib: <code>kolve2017ai2</code></sub> | 2017 | [Paper](https://arxiv.org/abs/1712.05474)&nbsp;&#124;&nbsp;[GitHub](https://github.com/allenai/ai2thor) | arXiv |
| **The material point method** | Simulation platform<br/><sub>bib: <code>zhang2017material</code></sub> | 2017 | [Paper](https://doi.org/10.1016/B978-0-12-407716-4.00003-X) | Elsevier |
| **V-REP: A versatile and scalable robot simulation framework** | V-REP<br/><sub>bib: <code>rohmer2013v</code></sub> | 2013 | [Paper](https://doi.org/10.1109/IROS.2013.6696520)&nbsp;&#124;&nbsp;[GitHub](https://github.com/CoppeliaRobotics/CoppeliaSimLib) | IROS |
| **Smoothed particle hydrodynamics (SPH): an overview and recent developments** | Simulation platform<br/><sub>bib: <code>liu2010smoothed</code></sub> | 2010 | [Paper](https://doi.org/10.1007/s11831-010-9040-7) | Archives of computational methods in engineering |
| **Position based dynamics** | Simulation platform<br/><sub>bib: <code>muller2007position</code></sub> | 2007 | [Paper](https://doi.org/10.1016/j.jvcir.2007.01.005) | Journal of Visual Communication and Image Representation |
| **Cyberbotics ltd. webots™: professional mobile robot simulation** | Cyberbotics ltd. webots™<br/><sub>bib: <code>michel2004cyberbotics</code></sub> | 2004 | [GitHub](https://github.com/cyberbotics/webots) | International Journal of Advanced Robotic Systems |
| **Design and use paradigms for gazebo, an open-source multi-robot simulator** | Simulation platform<br/><sub>bib: <code>koenig2004design</code></sub> | 2004 | [Paper](https://doi.org/10.1109/IROS.2004.1389727)&nbsp;&#124;&nbsp;[GitHub](https://github.com/gazebosim/gz-sim) | IROS |
| **The finite element method** | Simulation platform<br/><sub>bib: <code>zienkiewicz2000finite</code></sub> | 2000 | — | Elsevier |
| **Isaac Sim** | Simulation platform<br/><sub>bib: <code>NVIDIA_Isaac_Sim</code></sub> | — | [GitHub](https://github.com/isaac-sim/IsaacSim) | — |

### Learning Frameworks and Task Toolkits

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **mjlab: A lightweight framework for gpu-accelerated robot learning** | mjlab<br/><sub>bib: <code>zakka2026mjlab</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2601.22074)&nbsp;&#124;&nbsp;[GitHub](https://github.com/mujocolab/mjlab) | arXiv |
| **Deep reinforcement learning for robotic bipedal locomotion: a brief survey** | Robot-learning framework<br/><sub>bib: <code>bao2025deep</code></sub> | 2025 | [Paper](https://doi.org/10.1007/s10462-025-11451-z) | Artificial Intelligence Review |
| **Isaac lab: A gpu-accelerated simulation framework for multi-modal robot learning** | Isaac lab<br/><sub>bib: <code>mittal2025isaac</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2511.04831)&nbsp;&#124;&nbsp;[GitHub](https://github.com/isaac-sim/IsaacLab) | arXiv |
| **ManiSkill3: GPU Parallelized Robotics Simulation and Rendering for Generalizable Embodied AI** | ManiSkill3<br/><sub>bib: <code>taomaniskill3</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2410.00425)&nbsp;&#124;&nbsp;[GitHub](https://github.com/mani-skill/ManiSkill) | RSS |
| **Mujoco playground** | Robot-learning framework<br/><sub>bib: <code>zakka2025mujoco</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2502.08844)&nbsp;&#124;&nbsp;[GitHub](https://github.com/google-deepmind/mujoco_playground) | arXiv |
| **Habitat 3.0: A co-habitat for humans, avatars, and robots** | Habitat 3.0<br/><sub>bib: <code>puig2023habitat3</code></sub> | 2024 | [Paper](https://proceedings.iclr.cc/paper_files/paper/2024/hash/430894999584d0bd358611e2ecf00b15-Abstract-Conference.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/facebookresearch/habitat-lab) | ICLR |
| **Habitat 2.0: Training home assistants to rearrange their habitat** | Habitat 2.0<br/><sub>bib: <code>szot2021habitat</code></sub> | 2021 | [Paper](https://proceedings.neurips.cc/paper/2021/hash/021bbc7ee20b71134d53e20206bd6feb-Abstract.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/facebookresearch/habitat-lab) | NeurIPS |
| **Deepbots: A webots-based deep reinforcement learning framework for robotics** | Deepbots<br/><sub>bib: <code>kirtas2020deepbots</code></sub> | 2020 | [Paper](https://doi.org/10.1007/978-3-030-49186-4_6)&nbsp;&#124;&nbsp;[GitHub](https://github.com/aidudezzz/deepbots) | IFIP international conference on artificial intelligence applications and innovations |
| **dm_control: Software and tasks for continuous control** | dm_control<br/><sub>bib: <code>tunyasuvunakool2020dm_control</code></sub> | 2020 | [Paper](https://doi.org/10.1016/j.simpa.2020.100022)&nbsp;&#124;&nbsp;[GitHub](https://github.com/google-deepmind/dm_control) | Software Impacts |
| **robosuite: A modular simulation framework and benchmark for robot learning** | robosuite<br/><sub>bib: <code>zhu2020robosuite</code></sub> | 2020 | [Paper](https://arxiv.org/abs/2009.12293)&nbsp;&#124;&nbsp;[GitHub](https://github.com/ARISE-Initiative/robosuite) | arXiv |
| **Pyrep: Bringing v-rep to deep robot learning** | Pyrep<br/><sub>bib: <code>james2019pyrep</code></sub> | 2019 | [Paper](https://arxiv.org/abs/1906.11176)&nbsp;&#124;&nbsp;[GitHub](https://github.com/stepjam/PyRep) | arXiv |

### Evaluation Infrastructures and Sim-to-Real Workflows

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Genie sim 3.0: A high-fidelity comprehensive simulation platform for humanoid robot** | Genie sim 3.0<br/><sub>bib: <code>yin2026genie</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2601.02078) | arXiv |
| **Robolab: A high-fidelity simulation benchmark for analysis of task generalist policies** | Robolab<br/><sub>bib: <code>yang2026robolab</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2604.09860)&nbsp;&#124;&nbsp;[GitHub](https://github.com/NVLabs/RoboLab) | arXiv |
| **WM-DAgger: Enabling Efficient Data Aggregation for Imitation Learning with World Models** | WM-DAgger<br/><sub>bib: <code>yu2026wm</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2604.11351) | arXiv |
| **Digital twins to embodied artificial intelligence: Review and perspective** | Evaluation infrastructure<br/><sub>bib: <code>li2025digital</code></sub> | 2025 | [Paper](https://doi.org/10.20517/ir.2025.11) | Intelligence & Robotics |
| **Isaac Lab-Arena: Composable Environment Creation and Policy Evaluation for Robotics** | Isaac Lab-Arena<br/><sub>bib: <code>isaaclab-arena2025</code></sub> | 2025 | [GitHub](https://github.com/isaac-sim/IsaacLab-Arena) | — |
| **Lightwheel RoboFinals** | Evaluation infrastructure<br/><sub>bib: <code>lightwheel2025robofinals</code></sub> | 2025 | [Paper](https://lightwheel.ai/robofinals) | — |
| **Evaluating real-world robot manipulation policies in simulation** | Evaluation infrastructure<br/><sub>bib: <code>li2024evaluating</code></sub> | 2024 | [Paper](https://arxiv.org/abs/2405.05941) | arXiv |
| **Gensim: Generating robotic simulation tasks via large language models** | Gensim<br/><sub>bib: <code>wang2024gensim</code></sub> | 2024 | [Paper](https://arxiv.org/abs/2310.01361)&nbsp;&#124;&nbsp;[GitHub](https://github.com/liruiw/GenSim) | ICLR |
| **Robocasa: Large-scale simulation of everyday tasks for generalist robots** | Robocasa<br/><sub>bib: <code>nasiriany2024robocasa</code></sub> | 2024 | [Paper](https://arxiv.org/abs/2406.02523)&nbsp;&#124;&nbsp;[GitHub](https://github.com/robocasa/robocasa) | arXiv |
| **LW-BenchHub: Lightwheel's End-to-End Embodied AI Simulation Platform** | LW-BenchHub<br/><sub>bib: <code>Lightwheel_Team_LW-BenchHub_Lightwheel_s_End-to-End</code></sub> | — | [GitHub](https://github.com/lightwheel-ai/lw_benchhub) | — |

### Differentiable Mechanics and Simulation Research

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Fildeep: Learning large deformations of elastic-plastic solids with multi-fidelity data** | Fildeep<br/><sub>bib: <code>tang2026fildeep</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2601.10031)&nbsp;&#124;&nbsp;[GitHub](https://github.com/tangent-heng/FilDeep) | 32nd ACM SIGKDD Conference on Knowledge Discovery and Data Mining V. 1 |
| **Maven: A mesh-aware volumetric encoding network for simulating 3d flexible deformation** | Maven<br/><sub>bib: <code>feng2026maven</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2604.04474) | arXiv |
| **Neural Latent Arbitrary Lagrangian-Eulerian Grids for Fluid-Solid Interaction** | Simulation research<br/><sub>bib: <code>tao2026neural</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2603.00792)&nbsp;&#124;&nbsp;[GitHub](https://github.com/therontau0054/Fisale) | ICLR |
| **A survey: Learning embodied intelligence from physical simulators and world models** | A survey<br/><sub>bib: <code>long2025survey</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2507.00917) | arXiv |
| **Ladeep: A deep learning-based surrogate model for large deformation of elastic-plastic solids** | Ladeep<br/><sub>bib: <code>tao2025ladeep</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2506.06001)&nbsp;&#124;&nbsp;[GitHub](https://github.com/therontau0054/LaDEEP) | 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining V. 2 |
| **Unisoma: A Unified Transformer-based Solver for Multi-Solid Systems** | Unisoma<br/><sub>bib: <code>pmlr-v267-tao25b</code></sub> | 2025 | [Paper](https://proceedings.mlr.press/v267/tao25b.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/therontau0054/Unisoma) | ICML |
| **A survey of embodied ai: From simulators to research tasks** | A survey of embodied ai<br/><sub>bib: <code>duan2022survey</code></sub> | 2022 | [Paper](https://arxiv.org/abs/2103.04918) | IEEE Transactions on Emerging Topics in Computational Intelligence |

<a id="evaluation"></a>
## 📏 Benchmarks, Reliability, and Evaluation

> For industrial deployment, report task outcome **and** recovery, safety, latency, throughput, reproducibility, and amortized operating cost.

### Industrial Task Suites and Capability Benchmarks

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **How Much Progress Has There Been in NVIDIA Datacenter GPUs?** | Benchmark<br/><sub>bib: <code>26-Nvidia-GPUs</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2601.20115) | arXiv |
| **Industryeqa: Pushing the frontiers of embodied question answering in industrial scenarios** | Industryeqa<br/><sub>bib: <code>26-NeurIPS-Industryeqa</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2505.20640)&nbsp;&#124;&nbsp;[GitHub](https://github.com/JackYFL/IndustryEQA) | NeurIPS |
| **Intelligent Automation for Embodied Benchmark Construction: Pipelines, Embodiments, Simulators, and Trends** | Benchmark<br/><sub>bib: <code>lai2026intelligent</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2606.12207) | arXiv |
| **Pac bench: Do foundation models understand prerequisites for executing manipulation policies?** | Pac bench<br/><sub>bib: <code>gundawar2026pac</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2506.23725) | NeurIPS |
| **Phyblock: A progressive benchmark for physical understanding and planning via 3d block assembly** | Phyblock<br/><sub>bib: <code>ma2026phyblock</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2506.08708)&nbsp;&#124;&nbsp;[GitHub](https://github.com/PhyBlock/PhyBlock) | NeurIPS |
| **RoboMME: Benchmarking and Understanding Memory for Robotic Generalist Policies** | RoboMME<br/><sub>bib: <code>26-ICML-RoboMME</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2603.04639)&nbsp;&#124;&nbsp;[GitHub](https://github.com/RoboMME/robomme_benchmark) | ICML |
| **RobotArena infty : Scalable Robot Benchmarking via Real-to-Sim Translation** | RobotArena infty<br/><sub>bib: <code>jangir2026robotarena</code></sub> | 2026 | [Paper](https://proceedings.iclr.cc/paper_files/paper/2026/hash/2aa3da3c1463ee2cdaaee94be4f8ba3f-Abstract-Conference.html)&nbsp;&#124;&nbsp;[GitHub](https://github.com/offjangir/RobotArena) | ICLR |
| **WorkBenchMark: A LEGO-Based Assembly Benchmark with an Assembly-by-Disassembly Baseline for the Smart Manufacturing League** | WorkBenchMark<br/><sub>bib: <code>ma2026workbenchmark</code></sub> | 2026 | [Paper](https://arxiv.org/abs/2606.19358) | arXiv |
| **BOP Challenge 2025: BOP-Industrial** | BOP Challenge 2025<br/><sub>bib: <code>bopindustrial2025</code></sub> | 2025 | [Paper](https://bop.felk.cvut.cz/challenges/bop-challenge-2025/) | — |
| **From production logistics to smart manufacturing: The vision for a new RoboCup industrial league** | Benchmark<br/><sub>bib: <code>dissanayaka2025production</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2507.11402) | arXiv |
| **IndustryNav: Exploring Spatial Reasoning of Embodied Agents in Dynamic Industrial Navigation** | IndustryNav<br/><sub>bib: <code>25-IndustryNav</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2511.17384)&nbsp;&#124;&nbsp;[GitHub](https://github.com/JackYFL/IndustryNav) | arXiv |
| **Maniskill-hab: A benchmark for low-level manipulation in home rearrangement tasks** | Maniskill-hab<br/><sub>bib: <code>shukla2025maniskill</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2412.13211)&nbsp;&#124;&nbsp;[GitHub](https://github.com/mani-skill/ManiSkill) | ICLR |
| **RoboBPP: Benchmarking robotic online bin packing with physics-based simulation** | RoboBPP<br/><sub>bib: <code>25-RoboBpp</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2512.04415) | arXiv |
| **World Robot Summit 2025: Manufacturing Robotics Challenge** | World Robot Summit 2025<br/><sub>bib: <code>wrs2025manufacturing</code></sub> | 2025 | [Paper](https://worldrobotsummit.org/en/wrs2025/mrc/) | — |
| **A retrospective on the Robot Air Hockey Challenge: benchmarking robust, reliable, and safe learning techniques for real-world robotics** | Benchmark<br/><sub>bib: <code>liu2024retrospective</code></sub> | 2024 | [Paper](https://arxiv.org/abs/2411.05718) | NeurIPS |
| **AutoMate: Specialist and Generalist Assembly Policies over Diverse Geometries.** | AutoMate<br/><sub>bib: <code>tang2024automate</code></sub> | 2024 | [Paper](https://arxiv.org/abs/2407.08028)&nbsp;&#124;&nbsp;[GitHub](https://github.com/isaac-sim/IsaacGymEnvs/tree/automate) | RSS |
| **Point cloud matters: Rethinking the impact of different observation spaces on robot learning** | Point cloud matters<br/><sub>bib: <code>zhu2024point</code></sub> | 2024 | [Paper](https://arxiv.org/abs/2402.02500)&nbsp;&#124;&nbsp;[GitHub](https://github.com/HaoyiZhu/PointCloudMatters) | NeurIPS |
| **Industreal: Transferring contact-rich assembly tasks from simulation to reality** | Industreal<br/><sub>bib: <code>tang2023industreal</code></sub> | 2023 | [Paper](https://arxiv.org/abs/2305.17110)&nbsp;&#124;&nbsp;[GitHub](https://github.com/NVlabs/industreallib) | arXiv |
| **Maniskill2: A unified benchmark for generalizable manipulation skills** | Maniskill2<br/><sub>bib: <code>gu2023maniskill2</code></sub> | 2023 | [Paper](https://arxiv.org/abs/2302.04659)&nbsp;&#124;&nbsp;[GitHub](https://github.com/KolinGuo/ManiSkill2) | arXiv |
| **Assessing industrial robot agility through international competitions** | Benchmark<br/><sub>bib: <code>21-ARIAC</code></sub> | 2021 | [Paper](https://doi.org/10.1016/j.rcim.2020.102113) | Robotics and computer-integrated manufacturing |
| **Robotic grasping and manipulation competition: Future tasks to support the development of assembly robotics** | Benchmark<br/><sub>bib: <code>van2016robotic</code></sub> | 2016 | [Paper](https://doi.org/10.1007/978-3-319-94568-2_13) | Robotic Grasping and Manipulation Challenge |

### Physical, Offline, and Distributed Evaluation

| Title | Focus / Model | Year | Links | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **RoboArena: Distributed Real-World Evaluation of Generalist Robot Policies** | RoboArena<br/><sub>bib: <code>atreya2025roboarena</code></sub> | 2025 | [Paper](https://proceedings.mlr.press/v305/atreya25a.html) | CoRL |
| **RoboChallenge: Large-scale Real-robot Evaluation of Embodied Policies** | RoboChallenge<br/><sub>bib: <code>yakefu2025robochallenge</code></sub> | 2025 | [Paper](https://arxiv.org/abs/2510.17950) | CoRR |
| **Towards Using Multiple Iterated, Reproduced, and Replicated Experiments with Robots (MIRRER) for Evaluation and Benchmarking** | Real-world benchmark<br/><sub>bib: <code>norton2024mirrer</code></sub> | 2024 | [Paper](https://arxiv.org/abs/2408.04736) | — |
| **ARMBench: An Object-centric Benchmark Dataset for Robotic Manipulation** | ARMBench<br/><sub>bib: <code>mitash2023armbench</code></sub> | 2023 | [Paper](https://doi.org/10.1109/ICRA48891.2023.10160846)&nbsp;&#124;&nbsp;[GitHub](https://github.com/amzn/armbench) | ICRA |
| **Performance measures to benchmark the grasping, manipulation, and assembly of deformable objects typical to manufacturing applications** | Real-world benchmark<br/><sub>bib: <code>kimble2022performance</code></sub> | 2022 | [Paper](https://doi.org/10.3389/frobt.2022.999348) | Frontiers in Robotics and AI |
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

[@derongdeng](https://github.com/DerongDeng-dero) — catalogue curation and maintenance

### 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=EmbodiedLogiX/Awesome-Industrial-Embodied-Intelligence&type=Date)](https://star-history.com/#EmbodiedLogiX/Awesome-Industrial-Embodied-Intelligence&Date)
