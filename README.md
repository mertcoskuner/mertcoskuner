<h2 align="left">Mert Coskuner</h2>

<p align="left">
<strong>ML researcher working on trustworthy machine learning</strong> — Byzantine-robust federated learning, adversarial robustness, and efficient multilingual LLMs.<br>
MSc @ Sabancı University · Researcher @ TÜBİTAK.
</p>

## About

I study *when and why machine learning systems fail* — under poisoned clients, adversarial inputs, distribution shift, and aggressive compression — and I build the benchmarks and defenses to measure and fix it. As a full-time researcher at TÜBİTAK and an MSc student at Sabancı University, my work centers on robustness and reliability in distributed and resource-constrained settings, spanning Byzantine-resilient federated learning, corruption/adversarial robustness of compressed models, and quantization of LLMs for low-resource languages. My MSc thesis direction extends this line into secure and privacy-preserving federated learning.

## Research Interests

- **Byzantine-resilient federated learning** — robust aggregation and poisoning/backdoor attacks, including sparsity-aware attack families guided by pruning-at-initialization saliency.
- **Adversarial and corruption robustness of compressed models** — PGD/AugMix, and how robustness transfers from teacher to distilled student networks.
- **Efficient multilingual LLMs** — post-training quantization (GPTQ/AWQ) and how calibration language shapes degradation for low-resource languages.
- **Privacy in federated graph learning** — structure-aware personalized aggregation with degree-calibrated differential privacy.
- **Reproducible, HPC-scale empirical ML** — controlled ablations and honest negative results on multi-GPU/SLURM clusters.

## Selected Projects

- **[byzantine-fl-bench](https://github.com/mertcoskuner/byzantine-fl-bench)** — PyTorch benchmark for Byzantine-robust federated learning: **40+ robust aggregators vs 17 poisoning attacks**, including a novel sparsity-aware attack family (SNIP/GraSP/SynFlow-guided).
- **[tr-quantbench](https://github.com/mertcoskuner/tr-quantbench)** — how calibration language shapes 4-bit quantization of multilingual LLMs: **Turkish perplexity degradation cut from +49.7% to +19.1%** with native-language calibration.
- **[structure-aware-fedala](https://github.com/mertcoskuner/structure-aware-fedala)** — structure-aware personalized federated graph learning (topology-weighted aggregation + degree-calibrated DP), benchmarked across **7 graph datasets** on OpenFGL.
- **[robust-distillation](https://github.com/mertcoskuner/robust-distillation)** — corruption/adversarial robustness of transfer-learned and distilled CNNs: AugMix+JSD, from-scratch PGD (L∞/L2), and a **teacher-to-student adversarial transferability** finding.

## More Projects

- **[gnn-backdoor-attacks](https://github.com/mertcoskuner/gnn-backdoor-attacks)** — PyTorch Geometric framework for GNN training across graph/node/link tasks with **GTA backdoor attacks** (GCN/SAGE/GAT on TU + Planetoid datasets).
- **[neural-feedback-codes](https://github.com/mertcoskuner/neural-feedback-codes)** — end-to-end learned channel codes for AWGN with noiseless feedback: transformer TX/RX trained through the channel, with rounds/noise/capacity ablations.
- **[aspect-based-recommender](https://github.com/mertcoskuner/aspect-based-recommender)** — content-based product recommendation from Amazon reviews via instruction-tuned ABSA, LDA/BERTopic topic modeling, and hierarchical meta-aspect clustering.
- **[mlp-ablation-suite](https://github.com/mertcoskuner/mlp-ablation-suite)** — configurable PyTorch MLP with a SLURM-orchestrated **22-run ablation** over depth, width, activation, dropout, BatchNorm, and L1/L2 regularization.

## Skills

- **ML:** PyTorch, PyTorch Geometric (PyG), Hugging Face Transformers
- **Experimentation:** SLURM, multi-GPU training, reproducible pipelines
- **Infra:** Docker, Kubernetes, AWS/GCP

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mertcoskuner/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:mertcoskuner@gmail.com)
