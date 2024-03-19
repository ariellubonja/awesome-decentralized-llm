# awesome-llm-decentralized
Collection of papers, algorithms, and other resources to allow you to train, perform inference, and deploy LLMs in the cheapest way possible!

## Tools 🛠️

| Name | Summary | Links |
|:----|  :----: | :---:|
|[![Star](https://img.shields.io/github/stars/skypilot-org/skypilot.svg?style=social&label=Star)](https://github.com/skypilot-org/skypilot)<br>[SkyPilot: Run LLMs and AI on Any Cloud](https://github.com/skypilot-org/skypilot) | Run LLMs, AI, and Batch jobs on any cloud. Get maximum savings, highest GPU availability, and managed execution—all with a simple interface: Managed Spot: 3-6x cost savings using spot VMs, with auto-recovery from preemptions, Optimizer: 2x cost savings by auto-picking the cheapest VM/zone/region/cloud, Autostop: hands-free cleanup of idle clusters |[Github](https://github.com/skypilot-org/skypilot) <br/> [Whitepaper](https://arxiv.org/pdf/2205.07147.pdf)|


# Papers


## Distributed Computation

| Name | Summary | Links |
|:----|  :----: | :---:|
|[Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism](https://arxiv.org/pdf/1909.08053.pdf) | We present our techniques for training very large transformer models and implement a simple, efficient intra-layer model parallel approach that enables training transformer models with billions of parameters. We sustain 15.1 PetaFLOPs across the entire application with 76% scaling efficiency when compared to a strong single GPU baseline that sustains 39 TeraFLOPs, which is 30% of peak FLOPs. Using the GPT-2 model we achieve SOTA results on the WikiText103  | [Paper](https://arxiv.org/pdf/1909.08053.pdf)|
|[![Star](https://img.shields.io/github/stars/yandex-research/swarm.svg?style=social&label=Star)](https://github.com/yandex-research/swarm)<br>[SWARM Parallelism: Training Large Models Can Be Surprisingly Communication-Efficient](https://arxiv.org/abs/2301.11913) | Train a large Transformer language model with 1B shared parameters (≈13B before sharing) on cheap, preemptible T4 GPUs with less than 200Mb/s network bandwidth. Resilient training using cheap “preemptible” instances or pooling existing resources from multiple regions. Paper finds configurations where training larger models becomes less communication-intensive and proposes SWARM parallelism, a model-parallel training algorithm designed for poorly connected, heterogeneous and unreliable devices. |[Github](https://github.com/yandex-research/swarm) <br> [Paper](https://arxiv.org/abs/2301.11913)|
|[TENPLEX: Changing Resources of Deep Learning Jobs using Parallelizable Tensor Collections](https://arxiv.org/abs/2301.11913) | Describes TENPLEX, a state management library for Deep Learning frameworks that enables jobs to change the GPU allocation and job parallelism at runtime | [Paper](https://arxiv.org/abs/2301.11913)|
|[Sia: Heterogeneity-aware, goodput-optimized ML-cluster scheduling](https://dl.acm.org/doi/pdf/10.1145/3600006.3613175) | Sia introduces a new scheduling formulation that can scale to the search-space sizes and intentionally match jobs and their configurations to GPU types and counts, while adapting to changes in cluster load and job mix over time. Sia also introduces a lowprofiling-overhead approach to bootstrapping  | [Paper](https://dl.acm.org/doi/pdf/10.1145/3600006.3613175)|
<br/>


## Speculative Decoding

**Speculative decoding processes future tokens based on the likelihood that they're needed**

| Title & Link | Summary | Date |
|:----|  :----: | :---:|
|[![Star](https://img.shields.io/github/stars/Infini-AI-Lab/Sequoia.svg?style=social&label=Star)](https://github.com/Infini-AI-Lab/Sequoia)<br>[Scalable, Robust, and Hardware-aware Speculative Decoding](https://arxiv.org/pdf/2402.12374.pdf) | Introduces better Dynamic-Programming based speculative decoding algorithm.  | Mar-2024 |


## Related Repos

[Awesome-Efficient-LLM](https://github.com/horseee/Awesome-Efficient-LLM)

<br/><br/><br/>

Thanks to [horseee](https://github.com/horseee/Awesome-Efficient-LLM/blob/main/README.md?plain=1) for the table!
