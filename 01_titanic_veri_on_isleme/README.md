# 01 - Titanic Veri Ön İşleme

Titanic veri seti üzerinde temel veri ön işleme adımları uygulandı.

Veri seti incelendi, sayısal ve kategorik değişkenler ayrıldı. Eksik sayısal değerler median, kategorik değerler ise mode kullanılarak dolduruldu.

`age` değişkenine Z-score standardizasyonu, `fare` değişkenine Min-Max normalizasyonu uygulandı. Kategorik veriler için `sex` üzerinde Label Encoding, `embarked` üzerinde One-Hot Encoding kullanıldı.

Son olarak yaş dağılımı histogram ile, yolcu sınıfına göre ücret dağılımı ise boxplot ile görselleştirildi.

## Dosya

`01_titanic_veri_on_isleme.ipynb`

## Kullanılan Kütüphaneler

- NumPy
- Pandas
- Seaborn
- Matplotlib
