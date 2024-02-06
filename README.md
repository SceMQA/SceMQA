# SceMQA 

[**🌐 Homepage**](https://scemqa.github.io/) | [**🤗 Dataset**]() | [**🤗 Paper**]() | [**📖 arXiv**]() | [**GitHub**](https://github.com/SceMQA/SceMQA)


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
| Model                      | Val |
|----------------------------|:---------:|
<!-- | Expert (Best)              |   88.6    |      -       |
| Expert (Medium)            |   82.6    |      -       |
| Expert (Worst)             |   76.2    |      -       |
| Gemini Ultra*              | **59.4**  |      -       |
| GPT-4V(ision) (Playground) |   56.8    |   **55.7**   |
| Qwen-VL-MAX*               |   51.4    |     46.8     |
| LLaVA-1.6-34B*             |   51.1    |     44.7     |
| Adept Fuyu-Heavy*          |   48.3    |      -       |
| Gemini Pro*                |   47.9    |      -       |
| Yi-VL-34B*                 |   45.9    |     41.6     |
| Qwen-VL-PLUS*              |   45.2    |     40.8     |
| Marco-VL*                  |   41.2    |     40.4     |
| InternLM-XComposer2-VL*    |   43.0    |     38.2     |
| Yi-VL-6B*                  |   39.1    |     37.8     |
| InfiMM-Zephyr-7B*          |   39.4    |     35.5     |
| InternVL-Chat-V1.1*        |   39.1    |     35.3     |
| SVIT*                      |   38.0    |     34.1     |
| Emu2-Chat*                 |   36.3    |     34.1     |
| BLIP-2 FLAN-T5-XXL         |   35.4    |     34.0     |
| InstructBLIP-T5-XXL        |   35.7    |     33.8     |
| LLaVA-1.5-13B              |   36.4    |     33.6     |
| Qwen-VL-7B-Chat            |   35.9    |     32.9     |
| SPHINX*                    |   32.9    |     32.9     |
| mPLUG-OWL2*                |   32.7    |     32.1     |
| BLIP-2 FLAN-T5-XL          |   34.4    |     31.0     |
| InstructBLIP-T5-XL         |   32.9    |     30.6     |
| Gemini Nano2*              |   32.6    |      -       |
| CogVLM                     |   32.1    |     30.1     |
| Otter                      |   32.2    |     29.1     |
| LLaMA-Adapter2-7B          |   29.8    |     27.7     |
| MiniGPT4-Vicuna-13B        |   26.8    |     27.6     |
| Adept Fuyu-8B              |   27.9    |     27.4     |
| Kosmos2                    |   24.4    |     26.6     |
| OpenFlamingo2-9B           |   28.7    |     26.3     |
| Frequent Choice            |   22.1    |     23.9     |
| Random Choice              |   26.8    |     25.8     |

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
