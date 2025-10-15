# Citation

If you use this work in your research or project, please cite:

## BibTeX

```bibtex
@software{txt2sql_slm_2025,
  author = {Your Name},
  title = {Text-to-SQL with Small Language Models},
  year = {2025},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/SaniyaGapchup/TXT2SQL}},
  version = {0.1.0}
}
```

## APA

```
Your Name. (2025). Text-to-SQL with Small Language Models (Version 0.1.0) [Computer software]. GitHub. https://github.com/SaniyaGapchup/TXT2SQL
```

## MLA

```
Your Name. "Text-to-SQL with Small Language Models." GitHub, 2025, github.com/SaniyaGapchup/TXT2SQL.
```

## Acknowledgments

This project builds upon several foundational works:

### Datasets

**Spider**
```bibtex
@inproceedings{yu2018spider,
  title={Spider: A Large-Scale Human-Labeled Dataset for Complex and Cross-Domain Semantic Parsing and Text-to-SQL Task},
  author={Yu, Tao and Zhang, Rui and Yang, Kai and Yasunaga, Michihiro and Wang, Dongxu and Li, Zifan and Ma, James and Li, Irene and Yao, Qingning and Roman, Shanelle and others},
  booktitle={Proceedings of EMNLP},
  year={2018}
}
```

**WikiSQL**
```bibtex
@article{zhong2017seq2sql,
  title={Seq2SQL: Generating Structured Queries from Natural Language using Reinforcement Learning},
  author={Zhong, Victor and Xiong, Caiming and Socher, Richard},
  journal={arXiv preprint arXiv:1709.00103},
  year={2017}
}
```

### Methods

**LoRA**
```bibtex
@inproceedings{hu2022lora,
  title={LoRA: Low-Rank Adaptation of Large Language Models},
  author={Hu, Edward J and Shen, Yelong and Wallis, Phillip and Allen-Zhu, Zeyuan and Li, Yuanzhi and Wang, Shean and Wang, Lu and Chen, Weizhu},
  booktitle={International Conference on Learning Representations},
  year={2022}
}
```

**DoRA**
```bibtex
@article{liu2024dora,
  title={DoRA: Weight-Decomposed Low-Rank Adaptation},
  author={Liu, Shih-Yang and Wang, Chien-Yi and Yin, Hongxu and Molchanov, Pavlo and Wang, Yu-Chiang Frank and Chao, Wei-Lun and Kautz, Jan},
  journal={arXiv preprint arXiv:2402.09353},
  year={2024}
}
```

### Libraries

This project uses:
- [PyTorch](https://pytorch.org/)
- [HuggingFace Transformers](https://huggingface.co/docs/transformers)
- [PEFT (Parameter-Efficient Fine-Tuning)](https://github.com/huggingface/peft)
- [TRL (Transformer Reinforcement Learning)](https://github.com/huggingface/trl)

## Related Work

If you're interested in Text-to-SQL research, you may also find these papers useful:

- "RESDSQL: Decoupling Schema Linking and Skeleton Parsing for Text-to-SQL" (AAAI 2023)
- "DIN-SQL: Decomposed In-Context Learning of Text-to-SQL with Self-Correction" (NeurIPS 2023)
- "C3: Zero-shot Text-to-SQL with ChatGPT" (arXiv 2023)
- "SQL-PaLM: Improved Large Language Model Adaptation for Text-to-SQL" (arXiv 2023)

## Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## License

This project is licensed under the MIT License - see [LICENSE](LICENSE) for details.
