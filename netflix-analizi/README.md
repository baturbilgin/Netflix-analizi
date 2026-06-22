# Netflix İçerik Kataloğu Analizi

**Yazar:** Batur Bilgin  
**Öğrenci No:** 24 LITT 036  
**Ders:** Veri Analizinde Bilgisayar Programlama 2

🔗 **Canlı Rapor:** https://baturbilgin.github.io/netflix-analizi/

## Hakkında

Netflix'in 2021 yılına kadar olan 7787 film ve dizilik kataloğunun analizi. İçerik türü, üretim ülkesi, çıkış yılı, eklenme tarihi, rating ve süre gibi değişkenler kullanılarak Netflix'in büyüme stratejisi ve içerik kompozisyonu incelenmiştir.

## İçerik

- Tanımsal istatistikler (`describe`, `value_counts`, `groupby`)
- 8 farklı grafik:
  - Bar, histogram, scatter (matplotlib/seaborn)
  - 2 etkileşimli Plotly grafiği (yıllık tip trendi + tür dağılımı)
- Veri hazırlığı: tarih ayrıştırma, süre temizliği, ülke/tür ayrıştırma
- Bulgular ve sınırlılıklar bölümü

## Veri Kaynağı

Kaggle / TidyTuesday — Netflix Movies and TV Shows  
https://www.kaggle.com/datasets/shivamb/netflix-shows

## Yerel Çalıştırma

```bash
pip install -r requirements.txt
jupyter notebook notebook/rapor.ipynb
```

## Klasör Yapısı

```
netflix-analizi/
├── data/
│   └── netflix_titles.csv
├── notebook/
│   └── rapor.ipynb
├── docs/
│   └── index.html        # GitHub Pages bunu yayınlar
├── requirements.txt
├── .gitignore
└── README.md
```
