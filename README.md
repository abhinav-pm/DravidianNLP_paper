# Dravidian NLP Suite – Dravida Dataset

This repository contains the dataset released as part of the paper:

**Family helps one another: Dravidian NLP suite for Natural Language Understanding**  
Proceedings of IJCNLP 2025 (Findings)

---

## 📌 About

This repository provides the **Dravida dataset**, a multilingual dataset for core Natural Language Understanding (NLU) tasks in four major Dravidian languages:

- Kannada  
- Malayalam  
- Tamil  
- Telugu  

The dataset supports the following tasks:

- Morphological Analysis (MA)  
- POS Tagging (POS)  
- Named Entity Recognition (NER)  
- Dependency Parsing (DEP)  
- Coreference Resolution (CR)  

For full details about dataset creation, annotation guidelines, models, and experiments, please refer to the paper.

---

## 📖 Citation

If you use this dataset in your research, please cite:

```bibtex
@inproceedings{p-m-etal-2025-family,
    title = "Family helps one another: {D}ravidian {NLP} suite for Natural Language Understanding",
    author = "P M, Abhinav  and
      Dasari, Priyanka  and
      Vuppala, Nagaraju  and
      Krishnamurthy, Parameswari",
    editor = "Inui, Kentaro  and
      Sakti, Sakriani  and
      Wang, Haofen  and
      Wong, Derek F.  and
      Bhattacharyya, Pushpak  and
      Banerjee, Biplab  and
      Ekbal, Asif  and
      Chakraborty, Tanmoy  and
      Singh, Dhirendra Pratap",
    booktitle = "Proceedings of the 14th International Joint Conference on Natural Language Processing and the 4th Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics",
    month = dec,
    year = "2025",
    address = "Mumbai, India",
    publisher = "The Asian Federation of Natural Language Processing and The Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.findings-ijcnlp.120/",
    pages = "1926--1941",
    ISBN = "979-8-89176-303-6",
    abstract = "Developing robust Natural Language Understanding (NLU) for morphologically rich Dravidian languages like Kannada, Malayalam, Tamil, and Telugu presents significant challenges due to their agglutinative nature and syntactic complexity. In this work, we present the Dravidian NLP Suite tackling five core tasks: Morphological Analysis (MA), POS Tagging (POS), Named Entity Recognition (NER), Dependency Parsing (DEP), and Coreference Resolution (CR), trained for monolingual models and multilingual models. To facilitate this, we present the Dravida dataset, meticulously annotated multilingual corpus for these tasks across all four languages. Our experiments demonstrate that a multilingual model, which utilizes shared linguistic features and cross-lingual patterns inherent to the Dravidian family, consistently outperforms its monolingual counterparts across all tasks. These findings suggest that multilingual learning is an effective approach for enhancing Natural Language Understanding (NLU) capabilities, particularly for languages belonging to the same family. To the best of our knowledge, this is the first work to jointly address all these core tasks on the Dravidian languages."
}