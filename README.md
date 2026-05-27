# Zaman Serisi Analizi

Zaman Serisi ve İstatistiksel Tahminleme, bu depo derin matematiksel teori ile güçlü Python uygulamaları arasındaki köprüyü kuran 10 derslik kapsamlı bir müfredatı içerir. 

---

## 📚 İçerik

| Notebook | Ders | Konular |
|----------|-------|---------|
| [`Ders_01_Giris.ipynb`](Ders_01_Giris.ipynb) | Ders 1 | Zaman serisi örnekleri, basit modeller (WN/MA/AR), durağanlık, ACF, trend ve mevsimsellik tahmini, Ljung-Box testi |
| [`Ders_02_Duragan_Surecler.ipynb`](Ders_02_Duragan_Surecler.ipynb) | Ders 2 | ACVF/ACF teorisi, doğrusal süreçler, Durbin-Levinson algoritması, Wold ayrışımı |
| [`Ders_03_ARMA_Modelleri.ipynb`](Ders_03_ARMA_Modelleri.ipynb) | Ders 3 | ARMA(p,q), nedensellik ve tersinirlik (karakteristik kökler), Yule-Walker ACF, model tanıma (ACF/PACF), h-adım öngörü |
| [`Ders_04_Spektral_Analiz.ipynb`](Ders_04_Spektral_Analiz.ipynb) | Ders 4 | Teorik spektral yoğunluk, periyodogram, Welch yöntemi, Butterworth filtreler |
| [`Ders_05_ARMA_Modelleme.ipynb`](Ders_05_ARMA_Modelleme.ipynb) | Ders 5 | Yule-Walker ve Burg tahmini, MLE, bootstrap, artık teşhis (ACF/QQ/LB), AICC model seçimi |
| [`Ders_06_ARIMA_SARIMA.ipynb`](Ders_06_ARIMA_SARIMA.ipynb) | Ders 6 | Entegre süreçler, farklama, ADF/KPSS birim kök testleri, SARIMA, AirPassengers örneği |
| [`Ders_07_Finansal_Zaman_Serileri.ipynb`](Ders_07_Finansal_Zaman_Serileri.ipynb) | Ders 7 | Finansal getiri özellikleri, ARCH/GARCH(1,1)/EGARCH, volatilite kümelenmesi, Geometrik Brownian Motion, Black-Scholes |
| [`Ders_08_Cok_Degiskenli.ipynb`](Ders_08_Cok_Degiskenli.ipynb) | Ders 8 | Çapraz kovaryans (CCF), VAR(p) modeli, gecikme seçimi, Granger nedensellik, Engle-Granger eşbütünleşme |
| [`Ders_09_Durum_Uzayi_Kalman.ipynb`](Ders_09_Durum_Uzayi_Kalman.ipynb) | Ders 9 | Durum-uzayı gösterimi, Kalman filtresi (elle uygulama), yerel doğrusal trend modeli, eksik gözlem işleme |
| [`Ders_10_Ongoruler.ipynb`](Ders_10_Ongoruler.ipynb) | Ders 10 | ARAR algoritması, SES/Holt/Holt-Winters (additive & multiplicative), 5 yöntem benchmark karşılaştırması |

---

## 🚀 Kurulum

### 1. Repoyu klonlayın
```bash
git clone https://github.com/HAYDARKILIC/zaman_serisi_analizi.git
cd zaman_serisi_analizi
```

### 2. Bağımlılıkları yükleyin
```bash
pip install -r requirements.txt
```

### 3. Jupyter'ı başlatın
```bash
jupyter notebook
```
---

## 🔧 Gereksinimler

| Kütüphane | Sürüm | Kullanım |
|-----------|-------|---------|
| `numpy` | ≥ 2.0 | Temel sayısal işlemler |
| `pandas` | ≥ 2.0 | Zaman serisi veri yönetimi |
| `matplotlib` | ≥ 3.7 | Görselleştirme |
| `scipy` | ≥ 1.11 | İstatistiksel testler, sinyal işleme |
| `statsmodels` | ≥ 0.14 | ARIMA/SARIMA/VAR/ETS modelleri |
| `arch` | ≥ 6.0 | ARCH/GARCH/EGARCH modelleri |
| `filterpy` | ≥ 1.4 | Kalman filtresi (Ders 9, opsiyonel) |
| `scikit-learn` | ≥ 1.3 | Hata metrikleri (MSE/MAE) |

Detaylı sürüm listesi için [`requirements.txt`](requirements.txt) dosyasına bakın.

## 📖 Kaynak Kitap

Brockwell, P. J., & Davis, R. A. (2009). Time series: theory and methods. Springer science & business media.

---
