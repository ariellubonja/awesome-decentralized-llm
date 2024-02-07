# awesome-llm-decentralized
Collection of papers, algorithms, and other resources to allow you to train, perform inference, and deploy LLMs in the cheapest way possible!



## Knowledge Distillation

| Title & Authors | Selling Point | Links |
|:----|  :----: | :---:|
|[![Star](https://img.shields.io/github/stars/yandex-research/swarm.svg?style=social&label=Star)](https://github.com/yandex-research/swarm)<br>[SWARM Parallelism: Training Large Models Can Be Surprisingly Communication-Efficient](https://arxiv.org/abs/2301.11913) <br> Max Ryabinin, Tim Dettmers, Michael Diskin, Alexander Borzunov | Train a large Transformer language model with 1B shared parameters (≈13B before sharing) on cheap, preemptible T4 GPUs with less than 200Mb/s network bandwidth. Resilient training using cheap “preemptible” instances or pooling existing resources from multiple regions. Paper finds configurations where training larger models becomes less communication-intensive and proposes SWARM parallelism, a model-parallel training algorithm designed for poorly connected, heterogeneous and unreliable devices. |[Github](https://github.com/yandex-research/swarm) <br> [Paper](https://arxiv.org/abs/2301.11913)|

<br/>

## Related Repos

[Awesome-Efficient-LLM](https://github.com/horseee/Awesome-Efficient-LLM)

<br/><br/><br/>

Thanks to [horseee](https://github.com/horseee/Awesome-Efficient-LLM/blob/main/README.md?plain=1) for the table!
