# SmolVLM-R1-Zero

> [!NOTE]
> This is an open research initiative exploring the capabilities of small VLMs trained exclusively through ​GRPO, inspired by DeepSeek's R1-Zero methodology.
> 

## 🚀 Key Features

- **​Pure GRPO**: First systematic exploration of RL-only training for small VLMs, bypassing traditional supervised fine-tuning (SFT) dependencies.
- **​Multi-Scale Evaluation**: Benchmarked across datasets spanning math/code problem solving, counting, grounding, ​and ego video reasoning to quantify cross-domain robustness.
- **​Architecture Zoo**: Unified RL pipelines for Qwen-VL, InternVL, LLaVA, and others, enabling direct comparison of open-source models.

## 🚨 News 

- [2025-03-15] Initial release of SmolVLM-R1-Zero with Qwen2.5-VL models.

install with emoji
## 🛠️ Installation
- Create your virtual environment
    ```bash
    conda create --name smolvlmr1 python=3.10 -y
    conda activate smolvlmr1
    ```
- Install dependencies:
    ```bash
    pip install wandb==0.18.3
    pip install tensorboardx
    pip install flash-attn --no-build-isolation
    # additional vlm dependencies
    # pip install qwen_vl_utils torchvision
    ```

## 🌐 Community & Contribution
We welcome contributions to:

- Add new VLM models.
- Propose novel RL reward functions.
- Share training logs (successes ​and failures) to enrich our failure mode analysis.