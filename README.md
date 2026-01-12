# FromWords2Code: Do NLP Prompting Strategies Generalize to Code Generation?

This repository contains the prompt templates and documentation for the FASE 2026 paper: "From Words to Code: Do NLP Prompting Strategies Generalize to Code Generation?"

The goal of this work is to systematically evaluate whether prompting strategies developed for natural language processing (NLP) generalize to code generation tasks with large language models (LLMs).

This project was inspired by [ATLAS](https://github.com/VILA-Lab/ATLAS), which provides a framework and benchmark for adaptive language strategies. Our work extends this perspective specifically to the code generation domain.

## Prompt Categories (Overview)

While the files are numbered, the prompt strategies can be broadly categorized as:

- Basic Prompt
    - `basic_prompt.txt`
- Instruction-based Prompts
    - Located under the `/instruction_based` directory
- Reasoning-based Prompts
    - Located under the `/reasoning_based` directory
- Tailored Prompt
    - `tailored_prompt.txt` 

## Citation

Please cite our work if you use these prompts:
```bibtex
@inproceedings{woo2026fromwordstocode,
  title = {From Words to Code: Do NLP Prompting Strategies Generalize to Code Generation?},
  author = {Woo, Erin and Yeo, Sangyeop and Jun, Hyungkook and Kim, Sangcheol and Hwang, Seung-won and Ma, Yu-Seung},
  booktitle = {FASE},
  year = {2026},
}
```

## Acknowledgements

This work was supported by the Institute of Information and Communications Technology Planning and Evaluation (IITP) grant funded by the Korea government (MSIT)
(No. 2022-0-00995, Automated reliable source code generation from natural language descriptions).
