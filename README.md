# 📚Awesome-Compositionality
Paper list for Compositionality (compositional reasoning, compositional generalization, compositional generation, etc.)




## 📑Survey
- Explain Before You Answer: A Survey on Compositional Visual Reasoning [[Preprint 2025]](https://arxiv.org/abs/2508.17298)
- A Survey on Compositional Learning of AI Models: Theoretical and Experimental Practices [[TMLR 2024]](https://arxiv.org/abs/2406.08787)
- A Survey on Compositional Generalization in Applications [[Preprint 2023]](https://arxiv.org/abs/2302.01067)




## 🧠Compositional Reasoning
### 📬Benchmark
1. LLMs
- Benchmarking and Understanding Compositional Relational Reasoning of LLMs [[AAAI 2025]](https://ojs.aaai.org/index.php/AAAI/article/view/34170)

  *It uses associative recall, knowledge recall and indirect object identification to generate generalized associative recall (GAR) tasks to evaluate compositional reasoning. Then it performs attribution patching method to discover the core circuits and vital attention heads.*

- CryptoX : Compositional Reasoning Evaluation of Large Language Models [[Preprint 2025]](https://arxiv.org/abs/2502.07813)

  *It performs instruction encryption and instruction transformation on the common benchmark X to generate Crypto-X benchmark. Encoding rules include base morse, emoji shuffle and emoji morse.*

- Reasoning about Affordances: Causal and Compositional Reasoning in LLMs [[Preprint 2025]](https://arxiv.org/abs/2502.16606)

  *It artificially desighs 20 questions to request LLMs to select unconventional objects to replace a typical tool for a particular purpose. Unconventional tool selection task requires LLMs to decompose the objects into their constituent abstract properties and determine which are superfluous and which are causally necessary.*

- StructTest: Benchmarking LLMs’ Reasoning through Compositional Structured Outputs [[Preprint 2025]](https://arxiv.org/abs/2412.18011)

  *It evaluates composiotional reasoning through adding addtional rules on summarization, coding, HTML generation and mathematical reasoning, like <Domain Task, Format Rules>.*

- Exploring the Compositional Deficiency of Large Language Models in Mathematical Reasoning Through Trap Problems [[EMNLP 2024]](https://aclanthology.org/2024.emnlp-main.915/)

  *It manually creates trap problems in math problems, such as undefined concept and missing condition and investigates the influence of prompt (trap ↑ origin -), few-shot demonstration (trap ↑ origin ↑) and fine-tuning (trap ↑ origin ↓).*

- Large Language Model is not a (Multilingual) Compositional Relation Reasoner [[COLM 2024]](https://openreview.net/forum?id=wLQ3I0F1oj)

  *It proposes a multilingual benchmark to assess compositional relations including identity, math, position and person.*

2. VLMs
- ConMe: Rethinking Evaluation of Compositional Reasoning for Modern VLMs [[NeurIPS 2024]](https://proceedings.neurips.cc/paper_files/paper/2024/hash/28aad3b3b315d86910d7f4ee2867dfa4-Abstract-Datasets_and_Benchmarks_Track.html)
- COLA: A Benchmark for Compositional Text-to-image Retrieval [[NeurIPS 2023]](https://proceedings.neurips.cc/paper_files/paper/2023/hash/917cd410aa55b61594fa2a6f6e5a9e94-Abstract-Datasets_and_Benchmarks.html)
- SugarCrepe: Fixing Hackable Benchmarks for Vision-Language Compositionality [[NeurIPS 2023]](https://proceedings.neurips.cc/paper_files/paper/2023/hash/63461de0b4cb760fc498e85b18a7fe81-Abstract-Datasets_and_Benchmarks.html)
- CREPE: Can Vision-Language Foundation Models Reason Compositionally? [[CVPR 2023]](https://openaccess.thecvf.com/content/CVPR2023/html/Ma_CREPE_Can_Vision-Language_Foundation_Models_Reason_Compositionally_CVPR_2023_paper.html)
- VLC-BERT: Visual Question Answering with Contextualized Commonsense Knowledge [[WACV 2023]](https://openaccess.thecvf.com/content/WACV2023/html/Ravi_VLC-BERT_Visual_Question_Answering_With_Contextualized_Commonsense_Knowledge_WACV_2023_paper.html)
- Winoground: Probing Vision and Language Models for Visio-Linguistic Compositionality [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/html/Thrush_Winoground_Probing_Vision_and_Language_Models_for_Visio-Linguistic_Compositionality_CVPR_2022_paper)

3. Agents
- WorkArena++: Towards Compositional Planning and Reasoning-based Common Knowledge Work Tasks [[NeurIPS 2024]](https://proceedings.neurips.cc/paper_files/paper/2024/hash/0b82662b6c32e887bb252a74d8cb2d5e-Abstract-Datasets_and_Benchmarks_Track.html)




### 📈Analysis
1. LLM
- ***Not All LLM Reasoners Are Created Equal** [[NeurIPS 2024 Workshop]](https://arxiv.org/abs/2410.01748)

  *It investigates the reasoning gap in 2-question-composition math problems, where the answer to the second problem depends on correctly answering the first problem. It thoroughly analyses the effect of cost-efficient and math-specialized models, instruction-following tuning, fine-tuning, generating code solution, finding that the reasoning gap is due to distraction from additional context and poor second-hop reasoning.*




### 🛠️Methodology

1. LLMs
- MAC-Tuning: LLM Multi-Compositional Problem Reasoning with Enhanced Knowledge Boundary Awareness [[EMNLP 2025]](https://arxiv.org/abs/2504.21773)

  *It mainly focuses on hallucination in multi-problem setting and proposes a two-step supervised fine-tuning process to train the model of ground-truth answers and confidence.*

- ***Understanding and Patching Compositional Reasoning in LLMs** [[ACL 2024 Findings]](https://aclanthology.org/2024.findings-acl.576/)

  *It finds that most compositional reasoning failures stem from the improperly generated or leveraged implicit reasoning results. Then it employs logit lens and an intervention experiment to locate multi-head self-attention modules within middle layers, which emerge as the linchpins in accurate generation and leveraing of implicit reasoning results. Finally, it develops a lightweight method to patch errors in compositional reasoning via editing the located MHSA modules.*




## 🤖Compositional Generalization
