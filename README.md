# LEA_CLARIN_MALT_EN#

This repository contains resources and documentation for a small-scale research project exploring the impact of BPE vocabulary size on neural machine translation (NMT) performance in low-resource settings, using the Maltese–English parallel corpus from ELRC-SHARE.

## 🧪 Project Overview

- **Language Pair**: Maltese → English  
- **Corpus**: ~24,000 sentence pairs from ELRC-SHARE  
- **BPE Vocabulary Sizes**: 5k / 10k / 20k (trained with SentencePiece)  
- **NMT Model**: Marian (transformer base, CPU mode, trained for 5 epochs)  
- **Evaluation Metrics**: sacreBLEU and chrF on test set  
- **Annotation Tool**: UDPipe (POS tagging, dependency parsing, segmentation)  
- **Corpus Publication**: Searchable in [CLARIN AutoSearch](https://autosearch.ivdnt.org/autocorp/)

## 📦 Access to Models and Data

Trained models, vocabulary files, tokenized data, and evaluation results are publicly available via B2SHARE:

👉 [Access on B2SHARE (DOI link)](https://doi.org/10.23728/b2share.f37920cd5a634986b261dbdc4cc55476)  
← *Replace this link with your actual DOI before final submission.*

## 📊 Evaluation Highlights

This project compares translation quality across BPE vocabulary sizes. It includes:
- BLEU/chrF plots comparing model performance
- Sentence-level translation error analysis and examples

## 📁 Repository Contents

| File/Folder         | Description                                              |
|---------------------|----------------------------------------------------------|
| `models.zip`        | Marian NMT models trained with 5k, 10k, and 20k vocab    |
| `vocabs.zip`        | SentencePiece vocabularies and model files               |
| `tokenized_data.zip`| Pre-tokenized training/dev/test sets                     |
| `eval_reports.zip`  | Evaluation scores, example sentences, analysis reports   |
| `README.md`         | Project documentation (this file)                        |

## 📖 Citation

If you use these resources, please cite the DOI provided above and credit this GitHub repository.

## 🔗 Useful Tools and References

- [ELRC-SHARE](https://elrc-share.eu) – Source of parallel data  
- [UDPipe](https://ufal.mff.cuni.cz/udpipe) – Linguistic annotation  
- [AutoSearch](https://autosearch.ivdnt.org/autocorp/) – Concordance search  
- [Marian NMT](https://marian-nmt.github.io/) – Neural MT framework  
# LEA_CLARIN_MALT_EN

This repository contains resources and documentation for a small-scale research project exploring the impact of BPE vocabulary size on neural machine translation (NMT) performance in low-resource settings, using the Maltese–English parallel corpus from ELRC-SHARE.

## 🧪 Project Overview

- **Language Pair**: Maltese → English  
- **Corpus**: ~24,000 sentence pairs from ELRC-SHARE  
- **BPE Vocabulary Sizes**: 5k / 10k / 20k (trained with SentencePiece)  
- **NMT Model**: Marian (transformer base, CPU mode, trained for 5 epochs)  
- **Evaluation Metrics**: sacreBLEU and chrF on test set  
- **Annotation Tool**: UDPipe (POS tagging, dependency parsing, segmentation)  
- **Corpus Publication**: Searchable in [CLARIN AutoSearch](https://autosearch.ivdnt.org/autocorp/)

## 📦 Access to Models and Data

Trained models, vocabulary files, tokenized data, and evaluation results are publicly available via B2SHARE:

👉 [Access on B2SHARE (DOI link)](https://doi.org/10.23728/b2share.f37920cd5a634986b261dbdc4cc55476)  
← *Replace this link with your actual DOI before final submission.*

## 📊 Evaluation Highlights

This project compares translation quality across BPE vocabulary sizes. It includes:
- BLEU/chrF plots comparing model performance
- Sentence-level translation error analysis and examples

## 📁 Repository Contents

| File/Folder         | Description                                              |
|---------------------|----------------------------------------------------------|
| `models.zip`        | Marian NMT models trained with 5k, 10k, and 20k vocab    |
| `vocabs.zip`        | SentencePiece vocabularies and model files               |
| `tokenized_data.zip`| Pre-tokenized training/dev/test sets                     |
| `eval_reports.zip`  | Evaluation scores, example sentences, analysis reports   |
| `README.md`         | Project documentation (this file)                        |

## 📖 Citation

If you use these resources, please cite the DOI provided above and credit this GitHub repository.

## 🔗 Useful Tools and References

- [ELRC-SHARE](https://elrc-share.eu) – Source of parallel data  
- [UDPipe](https://ufal.mff.cuni.cz/udpipe) – Linguistic annotation  
- [AutoSearch](https://autosearch.ivdnt.org/autocorp/) – Concordance search  
- [Marian NMT](https://marian-nmt.github.io/) – Neural MT framework  
