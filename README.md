# Enhancing Sentence Relatedness Assessment using Siamese Networks
ACL2024
[Paper](https://aclanthology.org/2024.semeval-1.138)

Authors: Yasamin Aali, Sardar Hamidian, Parsa Farinneya

## Abstract
The proposed system integrates a Siamese Network architecture with pre-trained language models, including BERT, RoBERTa, and the Universal Sentence Encoder. Through rigorous experimentation and analysis, we evaluate the performance of these models across multiple languages. Our findings reveal that the Universal Sentence Encoder excels in capturing semantic similarities, outperforming BERT and RoBERTa in most scenarios. Particularly notable is the USE’s exceptional performance in English and Marathi. These results emphasize the importance of selecting appropriate pre-trained models based on linguistic considerations and task requirements.

### Embeddings
- "Universal Sentence Encoder(USE)" for [USE](https://arxiv.org/abs/1803.11175)
- "BERT" for [BERT](https://arxiv.org/abs/1810.04805)
- "RoBERTa for [RoBERTa](https://arxiv.org/abs/1907.11692)

## Cite This Paper
```
@inproceedings{aali-etal-2024-ysp,
    title = "{YSP} at {S}em{E}val-2024 Task 1: Enhancing Sentence Relatedness Assessment using {S}iamese Networks",
    author = "Aali, Yasamin  and
      Hamidian, Sardar  and
      Farinneya, Parsa",
    editor = {Ojha, Atul Kr.  and
      Do{\u{g}}ru{\"o}z, A. Seza  and
      Tayyar Madabushi, Harish  and
      Da San Martino, Giovanni  and
      Rosenthal, Sara  and
      Ros{\'a}, Aiala},
    booktitle = "Proceedings of the 18th International Workshop on Semantic Evaluation (SemEval-2024)",
    month = jun,
    year = "2024",
    address = "Mexico City, Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.semeval-1.138",
    pages = "959--963",
    abstract = "In this paper we present the system for Track A in the SemEval-2024 Task 1: Semantic Textual Relatedness for African and Asian Languages (STR). The proposed system integrates a Siamese Network architecture with pre-trained language models, including BERT, RoBERTa, and the Universal Sentence Encoder (USE). Through rigorous experimentation and analysis, we evaluate the performance of these models across multiple languages. Our findings reveal that the Universal Sentence Encoder excels in capturing semantic similarities, outperforming BERT and RoBERTa in most scenarios. Particularly notable is the USE{'}s exceptional performance in English and Marathi. These results emphasize the importance of selecting appropriate pre-trained models based on linguistic considerations and task requirements.",
}

```
