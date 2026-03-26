# Build a Large Language Model From Scratch

![Python](https://img.shields.io/badge/Python-3.12-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-2.2%2B-red)
![License](https://img.shields.io/badge/License-MIT-green)

I wanted to really understand how LLMs work under the hood, so I read Sebastian Raschka's [Build a Large Language Model From Scratch](https://github.com/rasbt/LLMs-from-scratch) and worked through the whole thing.

<img src="https://sebastianraschka.com/images/LLMs-from-scratch-images/mental-model.jpg">


## Topics from the Book

Each notebook builds on top of the last and it goes from raw text all the way to a finetuned instruction following model. 

| Notebook | Chapter | What I built |
|----------|---------|-------------|
| `c02-text-preprocessing.ipynb` | Ch 2: Working with Text Data | BPE tokenizer, data loading pipeline, token embeddings + positional encoding |
| `c03-attention-mechanism.ipynb` | Ch 3: Coding Attention Mechanisms | Self attention mechanism, QKV, causal masking, multi-head attention |
| `c04-implementing-gpt.ipynb` | Ch 4: Implementing a GPT Model From Scratch to Generate Text | Full GPT-2 architecture: LayerNorm, GELU, feed forward, shortcut connection, transformer blocks |
| `c05-pretraining-on-unlabeled-data.ipynb` | Ch 5: Pretraining on Unlabeled Data | Training loop, cross-entropy, perplexity, temperature scaling, top-k sampling |
| `c06-fine-tuning-for-classification.ipynb` | Ch 6: Fine-tuning for Classification | Spam classifier finetuned on GPT-2, dataset prep, evaluation |
| `c07-fine-tuning-to-follow-instruction.ipynb` | Ch 7: Fine-tuning to Follow Instructions | Instruction dataset creation, SFT on GPT-2 355M, OpenAI API evaluation |


## TODO

List of interesting resources from book repo for later:

- [ ] [DPO (Direct Preference Optimization) from scratch](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch07/04_preference-tuning-with-dpo/dpo-from-scratch.ipynb)
- [ ] [LLM as Judge evaluation](https://github.com/rasbt/reasoning-from-scratch/tree/main/chF/04_llm-judge)
- [ ] [Training a reasoning model with GRPO (Reasoning from Scratch, Ch 6)](https://github.com/rasbt/reasoning-from-scratch/blob/main/ch06/01_main-chapter-code/ch06_main.ipynb)
- [ ] [Parameter efficient finetuning with LoRA (Appendix E)](https://github.com/rasbt/LLMs-from-scratch/blob/main/appendix-E/01_main-chapter-code/appendix-E.ipynb)
