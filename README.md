# SceMQA 

[**🌐 Homepage**](https://scemqa.github.io/) | [**🤗 Dataset**](https://github.com/SceMQA/SceMQA) | [**🤗 Paper**](https://huggingface.co/papers/2402.05138) | [**📖 arXiv**](https://arxiv.org/abs/2402.05138) | [**GitHub**](https://github.com/SceMQA/SceMQA)


This repo contains the evaluation code for the paper "[SceMQA: A Scientific College Entrance Level Multimodal Question Answering Benchmark]()"

## 🔔News

- **🚀[2024-02-05]: Our [GitHub Code Repo](https://github.com/SceMQA/SceMQA) is now available online!**

- **🔥[2024-01-25]: Our [website](https://scemqa.github.io/) is now available online! 😆**

## Introduction
We introduce  SceMQA, a novel benchmark for scientific multimodal question answering at the college entrance level. It addresses a critical educational phase often overlooked in existing benchmarks, spanning high school to pre-college levels. SceMQA focuses on core science subjects including Mathematics, Physics, Chemistry, and Biology. It features a blend of multiple-choice and freeresponse formats, ensuring a comprehensive evaluation of AI models’ abilities. Additionally, our benchmark provides specific knowledge
points for each problem and detailed explanations for each answer. SceMQA also uniquely presents problems with identical contexts but varied questions to facilitate a more thorough and accurate assessment of reasoning capabilities. In the experiment, we evaluate both open-source and close-source state-of-the-art Multimodal Large Language Models (MLLMs), across various experimental settings. The results show that further research and development are needed in developing more capable MLLM, as highlighted by only 50% to 60% accuracy achieved by the strongest models

<!-- ## Dataset Creation

SceMQA was created to challenge multimodal models with tasks that demand college-level subject knowledge and deliberate reasoning, pushing the boundaries of what these models can achieve in terms of expert-level perception and reasoning. Please refer to our huggingface [**🤗 Dataset**]() for more details. -->

## Evaluation
<!-- Please refer to our [eval](eval) folder for more details. -->

## 🏆 Mini-Leaderboard
| Model                      | Setting       | Val (MC) | Val (FR) |
|----------------------------|---------------|:--------:|:--------:|
| **Open-sourced models**    |               |          |          |
| InstructBLIP-7B            |               | 20.48    | 12.50    |
| InstructBLIP-13B           |               | 21.31    | 13.50    |
| MiniGPT4-7B                |               | 21.90    | 6.50     |
| MiniGPT4-13B               |               | 27.74    | 7.00     |
| LLaVA1.5-7B                |               | 27.50    | 10.50    |
| LLaVA1.5-13B               |               | 31.19    | 13.00    |
| Yi-VL-6B                   |               | 37.14    | 5.50     |
| Deepseek-VL-Chat-7B        |               | 26.79    | 14.00    |
| InternLM-XComposer2-7B     |               | 30.48    | 13.00    |
| Qwen-VL-chat               |               | 26.55    | 7.00     |
| **Closed-sourced models**  |               |          |          |
| Google Bard                | Text-only     | 41.31    | -        |
| Gemini Pro                 | Text-only     | 30.06    | 15.00    |
| Gemini Pro                 | Few-shot      | 38.34    | 19.50    |
| Gemini Pro                 | Zero-shot     | 41.18    | 21.50    |
| GPT4-V                     | Text-only     | 51.24    | 21.50    |
| GPT4-V                     | Few-shot      | 58.70    | 33.00    |
| GPT4-V                     | Zero-shot     | 60.83    | 36.00    |

*: results provided by the authors. -->

## Disclaimers
The guidelines for the annotators emphasized strict compliance with copyright and licensing rules from the initial data source, specifically avoiding materials from websites that forbid copying and redistribution. 
Should you encounter any data samples potentially breaching the copyright or licensing regulations of any site, we encourage you to [contact](#contact) us. Upon verification, such samples will be promptly removed.

## Contact
- Zhenwen Liang: zliang6@nd.edu
- Xiangliang Zhang: xzhang33@nd.edu

## Citation

**BibTeX:**
```bibtex
@article{
  title={SceMQA: A Scientific College Entrance Level Multimodal Question Answering Benchmark},
  author={Liang, Zhenwen and Guo, Kehan and Liu, Gang and Guo, Taicheng and Zhou, Yujun and Yang, Tianyu and Zhang, Jipeng and Pi, Renjie and Zhang, Xiangliang},
  journal={GitHub repository},
  year={2024},
}
```
