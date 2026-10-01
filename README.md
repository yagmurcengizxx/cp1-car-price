# CP1 — Araba Fiyatı Tahmini (Sıfırdan Linear Regression)

İkinci el araba fiyatlarını tahmin eden bir **multiple linear regression** modeli. Model hazır kütüphane kullanılmadan, sadece **NumPy** ile sıfırdan yazılıyor.

Bu proje, Andrew Ng'nin *Machine Learning Specialization* kursunun 1. kurs 2. haftasından sonraki checkpoint projesi.

## Durum

- [x] Veriyi yükleme, temizleme ve feature engineering (`age`, `engine_cc`, `owner_num`, `power_bhp`)
- [x] Her feature'ın fiyatla ilişkisini scatter plot ile inceleme
- [x] `compute_cost` fonksiyonu
- [ ] `compute_gradient` ve `gradient_descent`
- [ ] Feature scaling deneyi (z-score normalization)
- [ ] Farklı learning rate'lerin karşılaştırılması
- [ ] scikit-learn ile karşılaştırma

## Veri seti

[Vehicle dataset from CarDekho (Kaggle)](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho) içindeki `Car details v3.csv` dosyası. İndirip `data/` klasörüne koy.

## Çalıştırma

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

Sonra `cp1.ipynb` dosyasını VS Code veya Jupyter ile aç.
