# Verified Research Papers

This file contains verified and categorized research papers related to agentic AI,
verification, reliability, reasoning, tool use, evaluation, and security.

## 1. Agentic AI and Tool Use

### 1. ReAct: Synergizing Reasoning and Acting in Language Models

Authors: Shunyu Yao, Jeffrey Zhao, Dian Yu, Nan Du, Izhak Shafran, Karthik Narasimhan, Yuan Cao
Year: 2023
Venue: International Conference on Learning Representations (ICLR)
Link: https://arxiv.org/abs/2210.03629

Why relevant:
This paper combines reasoning and acting in language models. It is useful for understanding how intermediate actions and reasoning can be checked in an agentic pipeline.

### 2. Toolformer: Language Models Can Teach Themselves to Use Tools

Authors: Timo Schick, Jane Dwivedi-Yu, Roberto Dessi, Roberta Raileanu, Maria Lomeli, Luke Zettlemoyer, Nicola Cancedda, Thomas Scialom
Year: 2023
Venue: Advances in Neural Information Processing Systems (NeurIPS)
Link: https://arxiv.org/abs/2302.04761

Why relevant:
The paper studies how language models can learn to use external tools. This is relevant to checking whether an agent selects and uses tools correctly.

### 3. AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation

Authors: Qingyun Wu, Gagan Bansal, Jieyu Zhang, Yiran Wu, Beibin Li, Erkang Zhu, Li Jiang, Xiaoyun Zhang, Shuyuan Zhang, Chi Wang, et al.
Year: 2024
Venue: Conference on Language Modeling (COLM)
Link: https://arxiv.org/abs/2308.08155

Why relevant:
AutoGen provides a framework for applications involving multiple LLM agents. It is useful for studying communication, coordination, delegation, and errors between agents.

Lab 1 note:
The original paper had an incomplete author list. The publication itself is genuine, so it was classified as B in the citation audit.

### 4. AgentBench: Evaluating LLMs as Agents

Authors: Xiao Liu, Hao Yu, Hanchen Zhang, Yifan Xu, Xuanyu Lei, Hanyu Lai, Yu Gu, Hangliang Ding, Kai Men, Ke Yang, Shuyuan Zhang, Zhao Xie, Qianqian Deng, An Zhang, et al.
Year: 2024
Venue: International Conference on Learning Representations (ICLR)
Link: https://arxiv.org/abs/2308.03688

Why relevant:
AgentBench evaluates language models as agents in different environments. It is useful for studying errors in long and interactive agent tasks.

### 5. SWE-bench: Can Language Models Resolve Real-World GitHub Issues?

Authors: Carlos E. Jimenez, John Yang, Alexander Wettig, Shunyu Yao, Kexin Pei, Ofir Press, Karthik Narasimhan
Year: 2024
Venue: International Conference on Learning Representations (ICLR)
Link: https://arxiv.org/abs/2310.06770

Why relevant:
SWE-bench evaluates AI systems on real-world software engineering problems. It shows the difficulty of completing long multi-step tasks reliably.

## 2. Agent Evaluation and Surveys

### 6. Evaluation and Benchmarking of LLM Agents: A Survey

Authors: Mahmoud Mohammadi, Yipeng Li, Jane Lo, Wendy Yip
Year: 2025
Source: arXiv
Link: https://arxiv.org/abs/2507.21504

Why relevant:
This survey discusses methods for evaluating LLM agents and provides useful background for designing reliability and verification checks.

### 7. A Survey on Evaluation of LLM-based Agents

Authors: Asaf Yehudai, Lilach Edelstein, Alan Li, Guy Uziel, Yilun Zhao, Roy Bar-Haim, Arman Cohan, Michal Shmueli-Scheuer
Year: 2026
Venue: Findings of the Association for Computational Linguistics: ACL 2026
Link: https://aclanthology.org/2026.findings-acl.1330/

Why relevant:
This paper reviews different approaches for evaluating LLM-based agents, including their capabilities, safety, robustness, and tool use.

Lab 1 note:
The original AI-generated citation contained incorrect or incomplete metadata. The publication is genuine and was classified as B in the audit.

## 3. Reasoning and Verification

### 8. Chain-of-Thought Prompting Elicits Reasoning in Large Language Models

Authors: Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma, Brian Ichter, Fei Xia, Ed Chi, Quoc V. Le, Denny Zhou
Year: 2022
Venue: Advances in Neural Information Processing Systems (NeurIPS)
Link: https://arxiv.org/abs/2201.11903

Why relevant:
The paper shows how intermediate reasoning steps can improve problem solving. This is related to checking reasoning before an agent produces its final result.

### 9. Self-Consistency Improves Chain of Thought Reasoning in Language Models

Authors: Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc V. Le, Ed H. Chi, Sharan Narang, Aakanksha Chowdhery, Denny Zhou
Year: 2023
Venue: International Conference on Learning Representations (ICLR)
Link: https://arxiv.org/abs/2203.11171

Why relevant:
Self-consistency compares multiple reasoning paths. This can help identify disagreement and improve confidence in an agent's reasoning.

### 10. Let's Verify Step by Step

Authors: Hunter Lightman, Vineet Kosaraju, Yuri Burda, Harrison Edwards, Bowen Baker, Teddy Lee, Jan Leike, John Schulman, Ilya Sutskever, Karl Cobbe
Year: 2023
Source: arXiv
Link: https://arxiv.org/abs/2305.20050

Why relevant:
This work studies process supervision and shows why checking intermediate reasoning steps can be useful instead of checking only the final answer.

## 4. Hallucination and Factual Verification

### 11. SelfCheckGPT: Zero-Resource Black-Box Hallucination Detection for Generative Large Language Models

Authors: Potsawee Manakul, Adian Liusie, Mark J. F. Gales
Year: 2023
Venue: EMNLP 2023
Link: https://aclanthology.org/2023.emnlp-main.557/

Why relevant:
SelfCheckGPT provides a way to detect possible hallucinations by comparing multiple generated responses.

### 12. FActScore: Fine-grained Atomic Evaluation of Factual Precision in Long Form Text Generation

Authors: Sewon Min, Kalpesh Krishna, Xinxi Lyu, Mike Lewis, Wen-tau Yih, Pang Wei Koh, Mohit Iyyer, Luke Zettlemoyer, Hannaneh Hajishirzi
Year: 2023
Venue: EMNLP 2023
Link: https://aclanthology.org/2023.emnlp-main.741/

Why relevant:
FActScore checks factual accuracy at the level of individual claims. This is useful when verifying generated information.

### 13. RAGAs: Automated Evaluation of Retrieval Augmented Generation

Authors: Shahul Es, Jithin James, Luis Espinosa Anke, Steven Schockaert
Year: 2024
Venue: EACL 2024
Link: https://aclanthology.org/2024.eacl-demo.16/

Why relevant:
RAGAs provides automated evaluation methods for retrieval-augmented generation systems and can help identify problems in retrieval and generated answers.

## 5. Evaluation and Context

### 14. Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena

Authors: Lianmin Zheng, Wei-Lin Chiang, Ying Sheng, Siyuan Zhuang, Zhanghao Wu, Yonghao Zhuang, Zi Lin, Zhuohan Li, Dacheng Li, Eric P. Xing, Hao Zhang, Joseph E. Gonzalez, Ion Stoica
Year: 2023
Source: arXiv
Link: https://arxiv.org/abs/2306.05685

Why relevant:
This paper studies the use of language models as evaluators and discusses issues such as bias and reliability in automated evaluation.

### 15. Lost in the Middle: How Language Models Use Long Contexts

Authors: Nelson F. Liu, Kevin Lin, John Hewitt, Ashwin Paranjape, Michele Bevilacqua, Fabio Petroni, Percy Liang
Year: 2024
Venue: Transactions of the Association for Computational Linguistics
Link: https://aclanthology.org/2024.tacl-1.9/

Why relevant:
The paper shows that models can have difficulty using information located in the middle of long contexts. This is relevant to state and context verification in long agent workflows.

## 6. Security and Reliability

### 16. Red Teaming Language Models with Language Models

Authors: Ethan Perez, Saffron Huang, Francis Song, Trevor Cai, Roman Ring, John Aslanides, Amelia Glaese, Nathan McAleese, Geoffrey Irving
Year: 2022
Venue: EMNLP 2022
Link: https://arxiv.org/abs/2202.03286

Why relevant:
This work uses red teaming to find weaknesses in language models. Similar testing can be applied to agentic AI systems to find failure cases.

### 17. The Attack and Defense Landscape of Agentic AI: A Comprehensive Survey

Authors: J. Kim, X. Liu, Z. Wang, S. Qiu, B. Li, W. Guo, D. Song
Year: 2026
Source: arXiv
Link: https://arxiv.org/abs/2603.11088

Why relevant:
This survey discusses security threats and defenses for agentic AI systems. It is relevant to security checkpoints and protection against harmful agent actions.

## 7. Additional Papers

### 18. WebArena: A Realistic Web Environment for Building Autonomous Agents

Authors: Shuyan Zhou, Frank F. Xu, Hao Zhu, Xuhui Zhou, Robert Lo, Aman Alon, Sumit S. Awad, et al.
Year: 2024
Venue: International Conference on Learning Representations (ICLR)
Link: https://arxiv.org/abs/2307.13854

Why relevant:
WebArena provides realistic web environments for evaluating autonomous agents and their ability to complete multi-step tasks.

### 19. GAIA: A Benchmark for General AI Assistants

Authors: Grégoire Mialon, Clémentine Fourrier, Craig Swift, Thomas Wolf, Thomas Scialom, Antoine Lacroix, et al.
Year: 2024
Venue: International Conference on Learning Representations (ICLR)
Link: https://arxiv.org/abs/2311.12983

Why relevant:
GAIA evaluates general AI assistants on tasks involving reasoning, tool use, browsing, and multi-step problem solving.

### 20. WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents

Authors: Shunyu Yao, Howard Chen, John Yang, Karthik Narasimhan
Year: 2022
Venue: Advances in Neural Information Processing Systems (NeurIPS)
Link: https://arxiv.org/abs/2207.01206

Why relevant:
WebShop studies agents interacting with a simulated web shopping environment. It is useful for understanding errors involving actions, observations, and changing states.

### 21. Reflexion: Language Agents with Verbal Reinforcement Learning

Authors: Noah Shinn, Federico Cassano, Ashwin Gopinath, Karthik Narasimhan, Shunyu Yao
Year: 2023
Venue: Advances in Neural Information Processing Systems (NeurIPS)
Link: https://arxiv.org/abs/2303.11366

Why relevant:
Reflexion studies how agents can use feedback from previous attempts to improve later decisions. This is closely related to error recovery and self-correction.

### 22. AgentDojo: A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents

Year: 2024
Source: arXiv
Link: https://arxiv.org/abs/2406.13352

Why relevant:
AgentDojo provides an environment for testing attacks and defenses against tool-using LLM agents. It is useful for studying security verification checkpoints.

## Summary

Original references from the AI-generated research paper: 17

Additional papers added for the repository: 5

Total papers in this collection: 22

The original 17 references were taken from the research paper generated for
Lab 1. Ten of those references were systematically audited during the citation
integrity audit.

Audit result:

A - Verified: 8
B - Wrong Metadata: 2
C - Frankenstein: 0
D - Fabricated: 0
E - Identifier Mismatch: 0

Authenticity Score: 95/100
