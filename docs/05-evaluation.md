# Chapter 5 — Evaluation of Industrial Embodied Intelligence

[← Back to the catalogue](../README.md)

> A layered evaluation map spanning industrial task suites, simulators, real-world protocols, and deployment-facing metrics.

All rows preserve the repository convention: **Title | Method/Model | Date | Code | Venue**. A linked title comes directly from the supplied bibliography (URL, DOI, or arXiv record); `—` means that record did not provide a verified source-code repository.

## Evaluation Framing and Compute Foundations

| Title | Method/Model | Date | Code | Venue |
| :-- | :-- | :--: | :--: | :--: |
| [**How Much Progress Has There Been in NVIDIA Datacenter GPUs?**](https://arxiv.org/abs/2601.20115) | Evaluation framing<br/><sub><code>26-Nvidia-GPUs</code></sub> | 2026 | — | arXiv |

## Industrial Task Suites and Benchmarks

| Title | Method/Model | Date | Code | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Industryeqa: Pushing the frontiers of embodied question answering in industrial scenarios** | Industryeqa<br/><sub><code>26-NeurIPS-Industryeqa</code></sub> | 2026 | — | NeurIPS |
| **Pac bench: Do foundation models understand prerequisites for executing manipulation policies?** | Pac bench<br/><sub><code>gundawar2026pac</code></sub> | 2026 | — | NeurIPS |
| **Phyblock: A progressive benchmark for physical understanding and planning via 3d block assembly** | Phyblock<br/><sub><code>ma2026phyblock</code></sub> | 2026 | — | NeurIPS |
| **RoboMME: Benchmarking and Understanding Memory for Robotic Generalist Policies** | RoboMME<br/><sub><code>26-ICML-RoboMME</code></sub> | 2026 | — | ICML |
| **RobotArena infty : Scalable Robot Benchmarking via Real-to-Sim Translation** | RobotArena infty<br/><sub><code>jangir2026robotarena</code></sub> | 2026 | — | ICLR |
| [**WorkBenchMark: A LEGO-Based Assembly Benchmark with an Assembly-by-Disassembly Baseline for the Smart Manufacturing League**](https://arxiv.org/abs/2606.19358) | WorkBenchMark<br/><sub><code>ma2026workbenchmark</code></sub> | 2026 | — | arXiv |
| [**BOP Challenge 2025: BOP-Industrial**](https://bop.felk.cvut.cz/challenges/bop-challenge-2025/) | BOP Challenge 2025<br/><sub><code>bopindustrial2025</code></sub> | 2025 | — | — |
| [**From production logistics to smart manufacturing: The vision for a new RoboCup industrial league**](https://arxiv.org/abs/2507.11402) | Benchmark<br/><sub><code>dissanayaka2025production</code></sub> | 2025 | — | arXiv |
| **IndustryNav: Exploring Spatial Reasoning of Embodied Agents in Dynamic Industrial Navigation** | IndustryNav<br/><sub><code>25-IndustryNav</code></sub> | 2025 | — | arXiv |
| [**RoboBPP: Benchmarking robotic online bin packing with physics-based simulation**](https://arxiv.org/abs/2512.04415) | RoboBPP<br/><sub><code>25-RoboBpp</code></sub> | 2025 | — | arXiv |
| [**World Robot Summit 2025: Manufacturing Robotics Challenge**](https://worldrobotsummit.org/en/wrs2025/mrc/) | World Robot Summit 2025<br/><sub><code>wrs2025manufacturing</code></sub> | 2025 | — | — |
| **A retrospective on the Robot Air Hockey Challenge: benchmarking robust, reliable, and safe learning techniques for real-world robotics** | Benchmark<br/><sub><code>liu2024retrospective</code></sub> | 2024 | — | NeurIPS |
| **AutoMate: Specialist and Generalist Assembly Policies over Diverse Geometries.** | AutoMate<br/><sub><code>tang2024automate</code></sub> | 2024 | — | RSS |
| **Point cloud matters: Rethinking the impact of different observation spaces on robot learning** | Point cloud matters<br/><sub><code>zhu2024point</code></sub> | 2024 | — | NeurIPS |
| [**Industreal: Transferring contact-rich assembly tasks from simulation to reality**](https://arxiv.org/abs/2305.17110) | Industreal<br/><sub><code>tang2023industreal</code></sub> | 2023 | — | arXiv |
| [**Maniskill2: A unified benchmark for generalizable manipulation skills**](https://arxiv.org/abs/2302.04659) | Maniskill2<br/><sub><code>gu2023maniskill2</code></sub> | 2023 | — | arXiv |
| **Performance measures to benchmark the grasping, manipulation, and assembly of deformable objects typical to manufacturing applications** | Benchmark<br/><sub><code>kimble2022performance</code></sub> | 2022 | — | Frontiers in Robotics and AI |
| **Assessing industrial robot agility through international competitions** | Benchmark<br/><sub><code>21-ARIAC</code></sub> | 2021 | — | Robotics and computer-integrated manufacturing |
| **Robotic grasping and manipulation competition: Future tasks to support the development of assembly robotics** | Benchmark<br/><sub><code>van2016robotic</code></sub> | 2016 | — | Robotic Grasping and Manipulation Challenge |

## Evaluation Environment Design

| Title | Method/Model | Date | Code | Venue |
| :-- | :-- | :--: | :--: | :--: |
| [**Intelligent Automation for Embodied Benchmark Construction: Pipelines, Embodiments, Simulators, and Trends**](https://arxiv.org/abs/2606.12207) | Evaluation design<br/><sub><code>lai2026intelligent</code></sub> | 2026 | — | arXiv |
| **Maniskill-hab: A benchmark for low-level manipulation in home rearrangement tasks** | Maniskill-hab<br/><sub><code>shukla2025maniskill</code></sub> | 2025 | — | ICLR |

## Physics Engines and Numerical Foundations

| Title | Method/Model | Date | Code | Venue |
| :-- | :-- | :--: | :--: | :--: |
| [**Newton: GPU-accelerated physics simulation for robotics, and simulation research**](https://github.com/newton-physics/newton) | Newton<br/><sub><code>contributors2025newton</code></sub> | 2025 | [repo](https://github.com/newton-physics/newton) | Newton a Series of LF Projects, LLC |
| [**Factory: Fast contact for robotic assembly**](https://arxiv.org/abs/2205.03532) | Factory<br/><sub><code>narang2022factory</code></sub> | 2022 | — | arXiv |
| [**Warp: A high-performance python framework for gpu simulation and graphics**](https://github.com/NVIDIA/warp) | Warp<br/><sub><code>macklin2022warp</code></sub> | 2022 | [repo](https://github.com/NVIDIA/warp) | NVIDIA GPU Technology Conference (GTC) |
| [**Brax--a differentiable physics engine for large scale rigid body simulation**](https://arxiv.org/abs/2106.13281) | Physics engine<br/><sub><code>freeman2021brax</code></sub> | 2021 | — | arXiv |
| [**Fast and feature-complete differentiable physics for articulated rigid bodies with contact**](https://arxiv.org/abs/2103.16021) | Physics engine<br/><sub><code>werling2021fast</code></sub> | 2021 | — | arXiv |
| **Compiling machine learning programs via high-level tracing** | Physics engine<br/><sub><code>frostig2019compiling</code></sub> | 2019 | — | SysML conference 2018 |
| [**Drake: Model-based design and verification for robotics**](https://drake.mit.edu/) | Drake<br/><sub><code>tedrake2019drake</code></sub> | 2019 | — | — |
| **Dart: Dynamic animation and robotics toolkit** | Dart<br/><sub><code>lee2018dart</code></sub> | 2018 | — | The Journal of Open Source Software |
| **Per-contact iteration method for solving contact dynamics** | Physics engine<br/><sub><code>hwangbo2018per</code></sub> | 2018 | — | IEEE Robotics and Automation Letters |
| [**PyBullet: A Python Module for Physics Simulation for Games, Robotics, and Machine Learning**](https://pybullet.org) | PyBullet<br/><sub><code>coumans2016pybullet</code></sub> | 2016 | — | — |
| **Chrono: An open source multi-physics dynamics engine** | Chrono<br/><sub><code>tasora2015chrono</code></sub> | 2015 | — | international conference on high performance computing in science and engineering |
| **Mujoco: A physics engine for model-based control** | Mujoco<br/><sub><code>todorov2012mujoco</code></sub> | 2012 | — | IROS |
| **Sofa: A multi-model framework for interactive physical simulation** | Sofa<br/><sub><code>faure2012sofa</code></sub> | 2012 | — | Soft tissue biomechanical modeling for computer assisted surgery |
| **Open dynamics engine** | Physics engine<br/><sub><code>smith2005open</code></sub> | 2005 | — | — |
| [**Bullet Physics SDK**](https://github.com/bulletphysics/bullet3) | Physics engine<br/><sub><code>bullet3</code></sub> | — | [repo](https://github.com/bulletphysics/bullet3) | — |
| [**MJX-Warp**](https://mujoco.readthedocs.io/en/stable/mjwarp/index.html) | Physics engine<br/><sub><code>googledeepmind_mjx_warp</code></sub> | — | — | — |
| [**MuJoCo Warp (MJWarp)**](https://github.com/google-deepmind/mujoco_warp) | Physics engine<br/><sub><code>googledeepmind_mujoco_warp</code></sub> | — | [repo](https://github.com/google-deepmind/mujoco_warp) | — |
| [**MuJoCo XLA (MJX)**](https://mujoco.readthedocs.io/en/stable/mjx.html) | Physics engine<br/><sub><code>googledeepmind_mjx</code></sub> | — | — | — |
| [**NVIDIA PhysX**](https://developer.nvidia.com/physx-sdk) | Physics engine<br/><sub><code>nvidia_physx</code></sub> | — | — | — |

## Simulation Platforms and Environments

| Title | Method/Model | Date | Code | Venue |
| :-- | :-- | :--: | :--: | :--: |
| [**Nyx for Genesis**](https://github.com/Genesis-Embodied-AI/genesis-nyx) | Simulation platform<br/><sub><code>genesis2026nyx</code></sub> | 2026 | [repo](https://github.com/Genesis-Embodied-AI/genesis-nyx) | — |
| [**Quadrants: High-Performance Multi-Platform Compiler for Physics Simulation**](https://github.com/Genesis-Embodied-AI/quadrants) | Quadrants<br/><sub><code>genesis2026quadrants</code></sub> | 2026 | [repo](https://github.com/Genesis-Embodied-AI/quadrants) | — |
| [**The Role of Simulation in Scalable Robotics, Genesis World 1.0, and the Path Forward**](https://www.genesis.ai/blog/the-role-of-simulation-in-scalable-robotics-genesis-world-10-and-the-path-forward) | Simulation platform<br/><sub><code>genesis2026genesisworld</code></sub> | 2026 | — | Genesis AI Blog |
| **Discoverse: Efficient robot simulation in complex high-fidelity environments** | Discoverse<br/><sub><code>jia2025discoverse</code></sub> | 2025 | — | IROS |
| [**Unity**](https://docs.unity3d.com/6000.0/Documentation/Manual/PhysicsSection.html) | Simulation platform<br/><sub><code>unity_physics</code></sub> | 2025 | — | — |
| **A review of platforms for simulating embodied agents in 3D virtual environments** | Simulation platform<br/><sub><code>kaur2023review</code></sub> | 2023 | — | Artificial Intelligence Review |
| **Behavior-1k: A benchmark for embodied ai with 1,000 everyday activities and realistic simulation** | Behavior-1k<br/><sub><code>li2023behavior</code></sub> | 2023 | — | CoRL |
| [**igibson 2.0: Object-centric simulation for robot learning of everyday household tasks**](https://arxiv.org/abs/2108.03272) | igibson 2.0<br/><sub><code>li2021igibson</code></sub> | 2021 | — | arXiv |
| **Robothor: An open simulation-to-real embodied ai platform** | Robothor<br/><sub><code>deitke2020robothor</code></sub> | 2020 | — | CVPR |
| **Sapien: A simulated part-based interactive environment** | Sapien<br/><sub><code>xiang2020sapien</code></sub> | 2020 | — | CVPR |
| [**Threedworld: A platform for interactive multi-modal physical simulation**](https://arxiv.org/abs/2007.04954) | Threedworld<br/><sub><code>gan2020threedworld</code></sub> | 2020 | — | arXiv |
| **Habitat: A platform for embodied ai research** | Habitat<br/><sub><code>savva2019habitat</code></sub> | 2019 | — | ICCV |
| [**Ai2-thor: An interactive 3d environment for visual ai**](https://arxiv.org/abs/1712.05474) | Ai2-thor<br/><sub><code>kolve2017ai2</code></sub> | 2017 | — | arXiv |
| **The material point method** | Simulation platform<br/><sub><code>zhang2017material</code></sub> | 2017 | — | Elsevier |
| **V-REP: A versatile and scalable robot simulation framework** | V-REP<br/><sub><code>rohmer2013v</code></sub> | 2013 | — | IROS |
| **Smoothed particle hydrodynamics (SPH): an overview and recent developments** | Simulation platform<br/><sub><code>liu2010smoothed</code></sub> | 2010 | — | Archives of computational methods in engineering |
| **Position based dynamics** | Simulation platform<br/><sub><code>muller2007position</code></sub> | 2007 | — | Journal of Visual Communication and Image Representation |
| **Cyberbotics ltd. webots™: professional mobile robot simulation** | Cyberbotics ltd. webots™<br/><sub><code>michel2004cyberbotics</code></sub> | 2004 | — | International Journal of Advanced Robotic Systems |
| **Design and use paradigms for gazebo, an open-source multi-robot simulator** | Simulation platform<br/><sub><code>koenig2004design</code></sub> | 2004 | — | IROS |
| **The finite element method** | Simulation platform<br/><sub><code>zienkiewicz2000finite</code></sub> | 2000 | — | Elsevier |
| [**Isaac Sim**](https://github.com/isaac-sim/IsaacSim) | Simulation platform<br/><sub><code>NVIDIA_Isaac_Sim</code></sub> | — | [repo](https://github.com/isaac-sim/IsaacSim) | — |

## Robot-Learning Frameworks

| Title | Method/Model | Date | Code | Venue |
| :-- | :-- | :--: | :--: | :--: |
| [**mjlab: A lightweight framework for gpu-accelerated robot learning**](https://arxiv.org/abs/2601.22074) | mjlab<br/><sub><code>zakka2026mjlab</code></sub> | 2026 | — | arXiv |
| **Deep reinforcement learning for robotic bipedal locomotion: a brief survey** | Learning framework<br/><sub><code>bao2025deep</code></sub> | 2025 | — | Artificial Intelligence Review |
| [**Isaac lab: A gpu-accelerated simulation framework for multi-modal robot learning**](https://arxiv.org/abs/2511.04831) | Isaac lab<br/><sub><code>mittal2025isaac</code></sub> | 2025 | — | arXiv |
| **ManiSkill3: GPU Parallelized Robotics Simulation and Rendering for Generalizable Embodied AI** | ManiSkill3<br/><sub><code>taomaniskill3</code></sub> | 2025 | — | RSS |
| [**Mujoco playground**](https://arxiv.org/abs/2502.08844) | Learning framework<br/><sub><code>zakka2025mujoco</code></sub> | 2025 | — | arXiv |
| **Habitat 3.0: A co-habitat for humans, avatars, and robots** | Habitat 3.0<br/><sub><code>puig2023habitat3</code></sub> | 2024 | — | ICLR |
| **Habitat 2.0: Training home assistants to rearrange their habitat** | Habitat 2.0<br/><sub><code>szot2021habitat</code></sub> | 2021 | — | NeurIPS |
| **Deepbots: A webots-based deep reinforcement learning framework for robotics** | Deepbots<br/><sub><code>kirtas2020deepbots</code></sub> | 2020 | — | IFIP international conference on artificial intelligence applications and innovations |
| **dm_control: Software and tasks for continuous control** | dm_control<br/><sub><code>tunyasuvunakool2020dm_control</code></sub> | 2020 | — | Software Impacts |
| [**robosuite: A modular simulation framework and benchmark for robot learning**](https://arxiv.org/abs/2009.12293) | robosuite<br/><sub><code>zhu2020robosuite</code></sub> | 2020 | — | arXiv |
| **Habitat: A Platform for Embodied AI Research** | Habitat<br/><sub><code>habitat19iccv</code></sub> | 2019 | — | ICCV |
| [**Pyrep: Bringing v-rep to deep robot learning**](https://arxiv.org/abs/1906.11176) | Pyrep<br/><sub><code>james2019pyrep</code></sub> | 2019 | — | arXiv |

## Evaluation Infrastructures and Sim-to-Real Workflows

| Title | Method/Model | Date | Code | Venue |
| :-- | :-- | :--: | :--: | :--: |
| [**Genie sim 3.0: A high-fidelity comprehensive simulation platform for humanoid robot**](https://arxiv.org/abs/2601.02078) | Genie sim 3.0<br/><sub><code>yin2026genie</code></sub> | 2026 | — | arXiv |
| [**Robolab: A high-fidelity simulation benchmark for analysis of task generalist policies**](https://arxiv.org/abs/2604.09860) | Robolab<br/><sub><code>yang2026robolab</code></sub> | 2026 | — | arXiv |
| [**WM-DAgger: Enabling Efficient Data Aggregation for Imitation Learning with World Models**](https://arxiv.org/abs/2604.11351) | WM-DAgger<br/><sub><code>yu2026wm</code></sub> | 2026 | — | arXiv |
| **Digital twins to embodied artificial intelligence: Review and perspective** | Evaluation infrastructure<br/><sub><code>li2025digital</code></sub> | 2025 | — | Intelligence & Robotics |
| [**Isaac Lab-Arena: Composable Environment Creation and Policy Evaluation for Robotics**](https://github.com/isaac-sim/IsaacLab-Arena) | Isaac Lab-Arena<br/><sub><code>isaaclab-arena2025</code></sub> | 2025 | [repo](https://github.com/isaac-sim/IsaacLab-Arena) | — |
| [**Lightwheel RoboFinals**](https://lightwheel.ai/robofinals) | Evaluation infrastructure<br/><sub><code>lightwheel2025robofinals</code></sub> | 2025 | — | — |
| [**Evaluating real-world robot manipulation policies in simulation**](https://arxiv.org/abs/2405.05941) | Evaluation infrastructure<br/><sub><code>li2024evaluating</code></sub> | 2024 | — | arXiv |
| **Gensim: Generating robotic simulation tasks via large language models** | Gensim<br/><sub><code>wang2024gensim</code></sub> | 2024 | — | ICLR |
| [**Robocasa: Large-scale simulation of everyday tasks for generalist robots**](https://arxiv.org/abs/2406.02523) | Robocasa<br/><sub><code>nasiriany2024robocasa</code></sub> | 2024 | — | arXiv |
| [**LW-BenchHub: Lightwheel's End-to-End Embodied AI Simulation Platform**](https://github.com/lightwheel-ai/lw_benchhub) | LW-BenchHub<br/><sub><code>Lightwheel_Team_LW-BenchHub_Lightwheel_s_End-to-End</code></sub> | — | [repo](https://github.com/lightwheel-ai/lw_benchhub) | — |

## Simulation Surveys and Physical Surrogates

| Title | Method/Model | Date | Code | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Fildeep: Learning large deformations of elastic-plastic solids with multi-fidelity data** | Fildeep<br/><sub><code>tang2026fildeep</code></sub> | 2026 | — | 32nd ACM SIGKDD Conference on Knowledge Discovery and Data Mining V. 1 |
| [**Maven: A mesh-aware volumetric encoding network for simulating 3d flexible deformation**](https://arxiv.org/abs/2604.04474) | Maven<br/><sub><code>feng2026maven</code></sub> | 2026 | — | arXiv |
| **Neural Latent Arbitrary Lagrangian-Eulerian Grids for Fluid-Solid Interaction** | Simulation research<br/><sub><code>tao2026neural</code></sub> | 2026 | — | ICLR |
| [**A survey: Learning embodied intelligence from physical simulators and world models**](https://arxiv.org/abs/2507.00917) | A survey<br/><sub><code>long2025survey</code></sub> | 2025 | — | arXiv |
| **Ladeep: A deep learning-based surrogate model for large deformation of elastic-plastic solids** | Ladeep<br/><sub><code>tao2025ladeep</code></sub> | 2025 | — | 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining V. 2 |
| **Unisoma: A Unified Transformer-based Solver for Multi-Solid Systems** | Unisoma<br/><sub><code>pmlr-v267-tao25b</code></sub> | 2025 | — | ICML |
| **A survey of embodied ai: From simulators to research tasks** | A survey of embodied ai<br/><sub><code>duan2022survey</code></sub> | 2022 | — | IEEE Transactions on Emerging Topics in Computational Intelligence |

## Physical, Offline, and Distributed Evaluation

| Title | Method/Model | Date | Code | Venue |
| :-- | :-- | :--: | :--: | :--: |
| [**RoboArena: Distributed Real-World Evaluation of Generalist Robot Policies**](https://proceedings.mlr.press/v305/atreya25a.html) | RoboArena<br/><sub><code>atreya2025roboarena</code></sub> | 2025 | — | CoRL |
| [**RoboChallenge: Large-scale Real-robot Evaluation of Embodied Policies**](https://arxiv.org/abs/2510.17950) | RoboChallenge<br/><sub><code>yakefu2025robochallenge</code></sub> | 2025 | — | CoRR |
| [**Towards Using Multiple Iterated, Reproduced, and Replicated Experiments with Robots (MIRRER) for Evaluation and Benchmarking**](https://arxiv.org/abs/2408.04736) | Real-world benchmark<br/><sub><code>norton2024mirrer</code></sub> | 2024 | — | — |
| [**ARMBench: An Object-centric Benchmark Dataset for Robotic Manipulation**](https://doi.org/10.1109/ICRA48891.2023.10160846) | ARMBench<br/><sub><code>mitash2023armbench</code></sub> | 2023 | — | ICRA |
| **Performance measures to benchmark the grasping, manipulation, and assembly of deformable objects typical to manufacturing applications** | Real-world benchmark<br/><sub><code>kimble2022performance</code></sub> | 2022 | — | Frontiers in Robotics and AI |
| [**RB2: Robotic Manipulation Benchmarking with a Twist**](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/hash/3988c7f88ebcb58c6ce932b957b6f332-Abstract-round2.html) | RB2<br/><sub><code>dasari2021rb2</code></sub> | 2021 | — | NeurIPS |

## Metrics, Safety, Generalization, and Deployment Cost

| Title | Method/Model | Date | Code | Venue |
| :-- | :-- | :--: | :--: | :--: |
| **Industryeqa: Pushing the frontiers of embodied question answering in industrial scenarios** | Industryeqa<br/><sub><code>26-NeurIPS-Industryeqa</code></sub> | 2026 | — | NeurIPS |
| **Pac bench: Do foundation models understand prerequisites for executing manipulation policies?** | Pac bench<br/><sub><code>gundawar2026pac</code></sub> | 2026 | — | NeurIPS |
| **Phyblock: A progressive benchmark for physical understanding and planning via 3d block assembly** | Phyblock<br/><sub><code>ma2026phyblock</code></sub> | 2026 | — | NeurIPS |
| **RoboMME: Benchmarking and Understanding Memory for Robotic Generalist Policies** | RoboMME<br/><sub><code>26-ICML-RoboMME</code></sub> | 2026 | — | ICML |
| **RobotArena infty : Scalable Robot Benchmarking via Real-to-Sim Translation** | RobotArena infty<br/><sub><code>jangir2026robotarena</code></sub> | 2026 | — | ICLR |
| [**WorkBenchMark: A LEGO-Based Assembly Benchmark with an Assembly-by-Disassembly Baseline for the Smart Manufacturing League**](https://arxiv.org/abs/2606.19358) | WorkBenchMark<br/><sub><code>ma2026workbenchmark</code></sub> | 2026 | — | arXiv |
| [**BOP Challenge 2025: BOP-Industrial**](https://bop.felk.cvut.cz/challenges/bop-challenge-2025/) | BOP Challenge 2025<br/><sub><code>bopindustrial2025</code></sub> | 2025 | — | — |
| [**From production logistics to smart manufacturing: The vision for a new RoboCup industrial league**](https://arxiv.org/abs/2507.11402) | Evaluation protocol<br/><sub><code>dissanayaka2025production</code></sub> | 2025 | — | arXiv |
| **IndustryNav: Exploring Spatial Reasoning of Embodied Agents in Dynamic Industrial Navigation** | IndustryNav<br/><sub><code>25-IndustryNav</code></sub> | 2025 | — | arXiv |
| [**RoboArena: Distributed Real-World Evaluation of Generalist Robot Policies**](https://proceedings.mlr.press/v305/atreya25a.html) | RoboArena<br/><sub><code>atreya2025roboarena</code></sub> | 2025 | — | CoRL |
| [**RoboBPP: Benchmarking robotic online bin packing with physics-based simulation**](https://arxiv.org/abs/2512.04415) | RoboBPP<br/><sub><code>25-RoboBpp</code></sub> | 2025 | — | arXiv |
| [**World Robot Summit 2025: Manufacturing Robotics Challenge**](https://worldrobotsummit.org/en/wrs2025/mrc/) | World Robot Summit 2025<br/><sub><code>wrs2025manufacturing</code></sub> | 2025 | — | — |
| **A retrospective on the Robot Air Hockey Challenge: benchmarking robust, reliable, and safe learning techniques for real-world robotics** | Evaluation protocol<br/><sub><code>liu2024retrospective</code></sub> | 2024 | — | NeurIPS |
| **AutoMate: Specialist and Generalist Assembly Policies over Diverse Geometries.** | AutoMate<br/><sub><code>tang2024automate</code></sub> | 2024 | — | RSS |
| **Point cloud matters: Rethinking the impact of different observation spaces on robot learning** | Point cloud matters<br/><sub><code>zhu2024point</code></sub> | 2024 | — | NeurIPS |
| [**Towards Using Multiple Iterated, Reproduced, and Replicated Experiments with Robots (MIRRER) for Evaluation and Benchmarking**](https://arxiv.org/abs/2408.04736) | Evaluation protocol<br/><sub><code>norton2024mirrer</code></sub> | 2024 | — | — |
| [**Industreal: Transferring contact-rich assembly tasks from simulation to reality**](https://arxiv.org/abs/2305.17110) | Industreal<br/><sub><code>tang2023industreal</code></sub> | 2023 | — | arXiv |
| [**Maniskill2: A unified benchmark for generalizable manipulation skills**](https://arxiv.org/abs/2302.04659) | Maniskill2<br/><sub><code>gu2023maniskill2</code></sub> | 2023 | — | arXiv |
| **Performance measures to benchmark the grasping, manipulation, and assembly of deformable objects typical to manufacturing applications** | Evaluation protocol<br/><sub><code>kimble2022performance</code></sub> | 2022 | — | Frontiers in Robotics and AI |
| **Assessing industrial robot agility through international competitions** | Evaluation protocol<br/><sub><code>21-ARIAC</code></sub> | 2021 | — | Robotics and computer-integrated manufacturing |
| [**RB2: Robotic Manipulation Benchmarking with a Twist**](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/hash/3988c7f88ebcb58c6ce932b957b6f332-Abstract-round2.html) | RB2<br/><sub><code>dasari2021rb2</code></sub> | 2021 | — | NeurIPS |
| **Robotic grasping and manipulation competition: Future tasks to support the development of assembly robotics** | Evaluation protocol<br/><sub><code>van2016robotic</code></sub> | 2016 | — | Robotic Grasping and Manipulation Challenge |

## Provenance

The compact `bib:` identifiers in the Method/Model column trace each row to the companion review's supplied BibTeX record. They are included for auditability and are not a claim of independent replication or code availability.
