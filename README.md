# Bidirectional-Awngi-Amharic-Machine-Translation
Bidirectional Awngi (አዊኛ)–Amharic Machine Translation research
# Bidirectional Awngi–Amharic Machine Translation: A Deep Learning Approach

This repository accompanies the paper:
**"Bidirectional Awngi (አዊኛ)–Amharic Machine Translation: A Deep Learning Approach"**
by Melak Teshome, Zewdu Ayinie, and Habtamu Abate (Wollo University, Ethiopia).

---

## 📖 Overview
We present the first bidirectional neural machine translation (NMT) system for the low-resource Ethiopian languages **Awngi** and **Amharic**.  
We compiled a new parallel corpus (~15,000 sentence pairs) and trained Transformer-based models in both directions.

| Direction | Model | BLEU |
|------------|--------|------|
| Awngi → Amharic | Transformer | **33.12** |
| Amharic → Awngi | Transformer | **34.24** |

---

## 📂 Repository Structure

---

## ⚙️ Requirements
- Python ≥ 3.8  
- PyTorch ≥ 1.13  
- OpenNMT-py or Fairseq  
- sentencepiece (for BPE tokenization)
- sacrebleu (for evaluation)

Install dependencies:
```bash
pip install torch sentencepiece sacrebleu


🧰 Dataset

The Awngi–Amharic parallel corpus consists of approximately 15,000 sentence pairs collected from:

Amhara Media Corporation’s official Facebook page

Awngi and Amharic school textbooks

Awngi newspaper (ቺርቤዋ ጋዜጣ)

Community-verified translations

Data split:

Training: 90%

Testing: 10%

Note: The dataset is available upon reasonable request from the authors.

@article{teshome2025awngi_amharic_mt,
  title={Bidirectional Awngi--Amharic Machine Translation: A Deep Learning Approach},
  author={Teshome, Melak and Ayinie, Zewdu and Abate, Habtamu},
  year={2025},
  institution={Wollo University},
  note={Manuscript submitted to Natural Language Engineering}
}

📫 Contact

For questions or collaboration, please contact:
Melak Teshome
Department of Information Technology, Wollo University
📧 melak.teshome@wu.edu.et
or    melemelak@gmail.com
]
