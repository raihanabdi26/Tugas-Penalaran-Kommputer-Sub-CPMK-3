# Tugas-Penalaran-Kommputer-Sub-CPMK-3

# Case-Based Reasoning for Court Decision Analysis

## Deskripsi
Project ini membangun sistem Case-Based Reasoning (CBR) untuk analisis putusan pengadilan menggunakan data Direktori Putusan Mahkamah Agung.

Metode yang digunakan:
- Text preprocessing
- Metadata extraction
- TF-IDF Retrieval
- Weighted Similarity Reuse
- Evaluation (Accuracy, Precision, Recall, F1)

---

## Dataset
Sumber:
Direktori Putusan Mahkamah Agung RI

Jumlah:
≥30 dokumen putusan

Domain:
Pidana Umum

---

## Struktur Folder

```plaintext
data/
notebooks/
README.md
requirements.txt
```

---

## Instalasi

Clone repository:

```bash
git clone LINK_REPOSITORY
cd CBR-Putusan-Pengadilan
```

Install dependency:

```bash
pip install -r requirements.txt
```

---

## Cara Menjalankan

Tahap 1:
```bash
notebooks/01_case_base.ipynb
```

Tahap 2:
```bash
notebooks/02_case_representation.ipynb
```

Tahap 3:
```bash
notebooks/03_case_retrieval.ipynb
```

Tahap 4:
```bash
notebooks/04_case_reuse.ipynb
```

Tahap 5:
```bash
notebooks/05_evaluation.ipynb
```

---

## Output

- cases.csv
- predictions.csv
- retrieval_metrics.csv
- prediction_metrics.csv
  
## Petunjuk Instalasi (Installation)

1. _Clone_ repository ini ke komputer lokal Anda dengan menjalankan perintah berikut di Terminal/Command Prompt:
   ```bash
   git clone [https://github.com/raihanabdi26/Tugas-Penalaran-Kommputer-Sub-CPMK-3.git](https://github.com/raihanabdi26/Tugas-Penalaran-Kommputer-Sub-CPMK-3.git)
   cd Tugas-Penalaran-Kommputer-Sub-CPMK-3
   ```
