# Gammafest IPB Football Match Prediction

Project machine learning untuk memprediksi skor pertandingan sepak bola internasional pada kompetisi Gammafest IPB.

## Objective

Tujuan dari kompetisi ini adalah memprediksi hasil skor pertandingan sepak bola internasional menggunakan berbagai fitur historis dan statistik pertandingan.

Target prediksi:
- `team_goals` : jumlah gol tim utama
- `opp_goals` : jumlah gol tim lawan

Dataset mencakup pertandingan dari tahun 1872 hingga proyeksi pertandingan tahun 2026.

## Dataset Overview

Dataset menggabungkan berbagai informasi seperti:
- statistik performa tim
- Elo rating
- FIFA ranking
- statistik pertandingan terakhir
- data geografis
- kondisi cuaca
- GDP dan populasi negara

### Files
- `train.csv` : data historis pertandingan beserta target
- `test.csv` : data pengujian tanpa beberapa fitur historis
- `sample_submission.csv` : contoh format submission
- `metadata.txt` : deskripsi fitur dataset

Dataset diberikan oleh panitia kompetisi dan tidak disertakan dalam repository ini.

## Project Structure

```text
project/
├── main.ipynb
├── README.md
└── requirements.txt
```

## Libraries Used

- pandas
- numpy
- matplotlib
- xgboost

## Installation

```bash
pip install -r requirements.txt
```

## Run Notebook

```bash
jupyter notebook
```

Lalu buka:
```text
main.ipynb
```

## Notes

Notebook mencakup:
- preprocessing data
- feature engineering
- model training
- evaluasi model
- prediksi submission
