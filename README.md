# Awesome-Compositionality
Paper list for Compositionality (compositional reasoning, compositional generalization, compositional generation, etc.)

## Survey
- Explain Before You Answer: A Survey on Compositional Visual Reasoning [[Preprint 2025]](https://arxiv.org/abs/2508.17298)
- A Survey on Compositional Learning of AI Models: Theoretical and Experimental Practices [[TMLR 2024]](https://arxiv.org/abs/2406.08787)
- A Survey on Compositional Generalization in Applications [[Preprint 2023]](https://arxiv.org/abs/2302.01067)

## Compositional Reasoning
### Benchmarks and Datasets
1. LLMs
- Benchmarking and Understanding Compositional Relational Reasoning of LLMs [[AAAI 2025]](https://ojs.aaai.org/index.php/AAAI/article/view/34170)

  *It uses associative recall, knowledge recall and indirect object identification to generate generalized associative recall (GAR) tasks to evaluate compositional reasoning. Then it performs attribution patching method to discover the core circuits and vital attention heads.*

- CryptoX : Compositional Reasoning Evaluation of Large Language Models [[Preprint 2025]](https://arxiv.org/abs/2502.07813)

  *It performs instruction encryption and instruction transformation on the common benchmark X to generate Crypto-X benchmark. Encoding rules include base morse, emoji shuffle and emoji morse.*

- StructTest: Benchmarking LLMs’ Reasoning through Compositional Structured Outputs [[Preprint 2025]](https://arxiv.org/abs/2412.18011)

  *It evaluates composiotional reasoning through adding addtional rules on summarization, coding, HTML generation and mathematical reasoning, like <Domain Task, Format Rules>.*

2. VLMs
- ConMe: Rethinking Evaluation of Compositional Reasoning for Modern VLMs [[NeurIPS 2024]](https://proceedings.neurips.cc/paper_files/paper/2024/hash/28aad3b3b315d86910d7f4ee2867dfa4-Abstract-Datasets_and_Benchmarks_Track.html)
- COLA: A Benchmark for Compositional Text-to-image Retrieval [[NeurIPS 2023]](https://proceedings.neurips.cc/paper_files/paper/2023/hash/917cd410aa55b61594fa2a6f6e5a9e94-Abstract-Datasets_and_Benchmarks.html)
- SugarCrepe: Fixing Hackable Benchmarks for Vision-Language Compositionality [[NeurIPS 2023]](https://proceedings.neurips.cc/paper_files/paper/2023/hash/63461de0b4cb760fc498e85b18a7fe81-Abstract-Datasets_and_Benchmarks.html)
- CREPE: Can Vision-Language Foundation Models Reason Compositionally? [[CVPR 2023]](https://openaccess.thecvf.com/content/CVPR2023/html/Ma_CREPE_Can_Vision-Language_Foundation_Models_Reason_Compositionally_CVPR_2023_paper.html)
- VLC-BERT: Visual Question Answering with Contextualized Commonsense Knowledge [[WACV 2023]](https://openaccess.thecvf.com/content/WACV2023/html/Ravi_VLC-BERT_Visual_Question_Answering_With_Contextualized_Commonsense_Knowledge_WACV_2023_paper.html)
- Winoground: Probing Vision and Language Models for Visio-Linguistic Compositionality [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/html/Thrush_Winoground_Probing_Vision_and_Language_Models_for_Visio-Linguistic_Compositionality_CVPR_2022_paper)
3. Agents
- WorkArena++: Towards Compositional Planning and Reasoning-based Common Knowledge Work Tasks [[NeurIPS 2024]](https://proceedings.neurips.cc/paper_files/paper/2024/hash/0b82662b6c32e887bb252a74d8cb2d5e-Abstract-Datasets_and_Benchmarks_Track.html)
