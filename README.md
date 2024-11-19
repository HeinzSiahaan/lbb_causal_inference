# LBB - Causal Inference for Business Decisions
Author: Heinz Metrosan Donradt Siahaan

## Description
Proyek ini bertujuan untuk menganalisis hubungan sebab-akibat dalam pengambilan keputusan bisnis, khususnya dampak hukum parental involvement law terhadap indikator kesehatan masyarakat. Proyek ini memanfaatkan pendekatan causal inference untuk menggambarkan hubungan antara variabel dengan teknik observasional dan statistik.

## Notebook ini menyertakan langkah-langkah:

### Definisi tujuan dan hipotesis kausal.
Eksplorasi data dan diagram kausal menggunakan causal graphical models.
Analisis efek kausal menggunakan regresi OLS dengan kontrol variabel confounder.
Pembahasan hasil dan implikasi kebijakan.
Features
Membuat dan menganalisis model kausal.
Menggunakan causal graphical models untuk memetakan hubungan variabel.
Menyediakan analisis berbasis data observasi.
Installation
Requirements
Pastikan Anda telah menginstal Python versi 3.8 atau lebih baru.

Instal dependencies yang tercantum di file requirements.txt:
```python
pip install -r requirements.txt
``` 
Isi requirements.txt
Berikut adalah daftar pustaka yang digunakan:
- numpy
- pandas
- seaborn
- statsmodels
- matplotlib
- causaldata
- causalgraphicalmodels

Anda dapat menyesuaikan atau menambahkan pustaka lain sesuai kebutuhan proyek Anda.

### Usage
1. Clone repository:

```python
git clone <repository-url>
cd <repository-directory>
```

2. Instal dependencies dengan requirements.txt.

3. Jalankan Jupyter Notebook lbb_causal_inference.ipynb untuk memulai analisis.

### Notebook Highlights
- Causal Diagram: Membantu memahami relasi antara variabel treatment, outcome, dan confounders.
- OLS Regression: Digunakan untuk memodelkan efek variabel treatment.
- Insights: Menyoroti implikasi kebijakan dari hasil analisis.

### Results
Efek dari parental involvement law terhadap angka kematian AIDS menunjukkan hasil yang tidak terduga, dengan peningkatan angka kematian sebesar 27.56%. Diskusi lebih lanjut disertakan dalam notebook untuk mengeksplorasi alasan di balik fenomena ini.
