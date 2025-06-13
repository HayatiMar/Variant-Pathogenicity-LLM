
# Variant Pathogenicity Prediction using DNABERT and Epigenomic Features

This project explores the use of pre-trained large language models (LLMs) for classifying variant pathogenicity, 
combining DNA sequence embeddings from DNABERT with epigenomic annotations from ENCODE.

##  Highlights

- Uses **ClinVar** variant data with pathogenicity labels
- Integrates **DNase** and **H3K27ac** epigenomic tracks from ENCODE
- Generates **DNA sequence embeddings** with **DNABERT**
- Trains a supervised classifier to predict variant pathogenicity

##  Data Sources

- [ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/)
- [ENCODE Epigenomic Tracks](https://www.encodeproject.org)
- DNABERT model: [`zhihan1996/DNA_bert_6`](https://huggingface.co/zhihan1996/DNA_bert_6)

##  Folder Structure

- `data/` — ClinVar and ENCODE .bed files
- `src/` — Scripts for feature extraction, embedding, training
- `notebooks/` — Colab or Jupyter notebooks
- `models/` — Saved embeddings or classifiers

##  Requirements

See `requirements.txt`

