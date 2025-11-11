# Lojistik Regresyon ile Sınıflandırma Analizi

Bu projede, **Lojistik Regresyon** modeli kullanılarak sınıflandırma yapılmıştır.  
Model kurulmadan önce veri **train/test** olarak ayrılmış, ardından değişkenler `StandardScaler` ile ölçeklenmiştir.  
Ek olarak, değişkenler arasındaki korelasyon ilişkileri **seaborn heatmap** ile görselleştirilmiştir.

## Kullanılan Adımlar
- Veri ön işleme (Eksik değer, seçme/ayırma)
- Train/Test Split
- StandardScaler ile ölçekleme
- LogisticRegression model eğitimi
- Model doğruluk değerlendirmesi
- Korelasyon heatmap görselleştirmesi

## Kullanılan Kütüphaneler
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Örnek Çıktılar
- Train Accuracy
- Test Accuracy
- Heatmap Korelasyon Grafiği

## Amaç
Veri setindeki bağımsız değişkenlerin hedef değişkeni ne kadar etkilediğini analiz etmek ve sınıflandırma performansını değerlendirmek.

