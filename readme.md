#FINETUNED LANGUAGE MODELS ARE ZERO-SHOT LEARNERS

https://arxiv.org/pdf/2109.01652.pdf

*Jason Wei∗, Maarten Bosma∗, Vincent Y. Zhao∗, Kelvin Guu∗, Adams Wei Yu, Brian Lester, Nan Du, Andrew M. Dai, and Quoc V. Le*
*Google Research*

**ABSTRACT**
This paper explores a simple method for improving the zero-shot learning abilities of language models. We show that instruction tuning—finetuning language models on a collection of datasets described via instructions—substantially improves zero- shot performance on unseen tasks.
We take a 137B parameter pretrained language model and instruction tune it on over 60 NLP datasets verbalized via natural language instruction templates. We evaluate this instruction-tuned model, which we call FLAN, on unseen task types. FLAN substantially improves the performance of its unmodified counterpart and surpasses zero-shot 175B GPT-3 on 20 of 25 datasets that we evaluate. FLAN even outperforms few-shot GPT-3 by a large margin on ANLI, RTE, BoolQ, AI2-ARC, OpenbookQA, and StoryCloze. Ablation studies reveal that number of finetuning datasets, model scale, and natural language instructions are key to the success of instruction tuning.
