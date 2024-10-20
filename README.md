# NTU-2023Fall-ADL
This repository is implementation of Homework for CSIE5431 Applied Deep Learning course in 2023 Fall semester at National Taiwan University.

## HW1: Question Answering
[report](https://github.com/jwliao1209/BERT-Question-Answering/blob/227bcf859307f56396a6d0c43609abc2d733a4e5/report.pdf)

| Method                        | Validation EM | Public EM  | Private EM |
| ----------------------------- | ------------- | ---------- | ---------- |
| Not pretrained                | 0.0499        | -          | -          |
| bert-base-chinese             | 0.7983        | -          | -          |
| chinese-roberta-wwm-ext-large | **0.8408**    | **0.8074** | **0.8121** |


## HW2: Chinese-News-Summarization
[report](https://github.com/jwliao1209/T5-Chinese-News-Summarization/blob/fb48a3303e5481fe46880ef233e50ac8c51ebd46/report.pdf)

| Method                 | rouge-1 | rouge-2 | rouge-L |
| ---------------------- | ------- | ------- | ------- |
| Baseline               | 22.0    | 8.5     | 20.5    |
| Supervised Learning    | **26.8510** | **10.7876** | **23.9712** |
| Reinforcement Learning | 26.5740 | 10.5980 | 23.7600 |


## HW3: Instruction-Tuning
[report](https://github.com/jwliao1209/Taiwan-LLaMa-Instruction-Tuning/blob/9508ce2a9b29a3facf7a7c33dd19d0609278a852/report.pdf)

| Method                 | ppl (mean / std)     |
| ---------------------- | -------------------- |
| Zero-shot              | 5.2045 / 4.1271      |
| Few-shot               | 4.8653 / 3.8037      |
| Fine-tuning with LoRA  | **3.6476 / 2.7748**  |


## Citation
```bibtex
@misc{liao_adl_hw_2023,
    title  = {Applied Deep Learning Homework},
    author = {Jia-Wei Liao},
    url    = {https://github.com/jwliao1209/NTU-ADL-2023},
    year   = {2023}
}
```
