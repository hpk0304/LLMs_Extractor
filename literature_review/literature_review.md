# Literature Review
## Overview
### Literature 1: 
@article{tang2023struc,
  title={Struc-Bench: Are Large Language Models Really Good at Generating Complex Structured Data?},
  author={Xiangru Tang and Yiming Zong and Jason Phang and Yilun Zhao and Wangchunshu Zhou and Arman Cohan and Mark B. Gerstein},
  journal={arXiv preprint arXiv:2309.08963},
  year={2023}
}

- Use case: Generate complex structured data and evaluate it
- Challenge: need to achieve 2 requirements: generate accurate and coherence content, maintain a strict and specific data structure format
- Approach: structure-aware fine-tuning approach
- Models used: 
@ LLMs: GPT-NeoX-20X, GPT-3.5, GPT-4, Vicuna-13B
@ format structure: Gorilla 
@ fine-tuning: LLaMa-7B
- Training 4 dataset: Rotowire (Wiseman et al., 2017), E2E (Novikova et al., 2017), WikiTableText (Bao et al., 2018) and WikiBio (Lebret et al., 2016)
@ format: LaTex, HTML
@ number of training data:average 5k
- Evaluation: FORMATCOT (Chain-of-thought)

### Literature 2: