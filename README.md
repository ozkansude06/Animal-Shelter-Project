# Hayvan Barınaklarındaki Sahiplenme Oranlarının Analizi

## Problem

- Hayvan barınaklarının ve geçici yuvaların en büyük problemi  kapasite aşımı ve yetersiz finansal kaynak sebebiyle alınamayan gıda ve ilaç eksikliğidir. Finansal ve kapasite sorunlarının yönetilmesi çalışanların gözlem ve tahminlerine dayanır. Proje kapsamında geliştiriceğimiz makine öğrenmesi modeli  hayvanların özelliklerine bakılarak sahiplenilme olasılıklarını tahmin etmeyi amaçlamaktadır. Elde edilen sonuçlar sahiplenilme olasılığı düşük edilen hayvanlar için proaktif önlemler alınmasına ve sürecin kısaltılmasına olanak sağlicaktır

## Hedef Kullanıcı
- Hayvan barınağı çalışanları
- Hayvan koruma kuruluşları
- Hayvan sahiplendirme süreçleri üzerine araştırma yapan kişiler
- hayvanseverler

## Proje Amacı

- Hayvanların tür, cins, yaş, cinsiyet, ırk ve benzeri özelliklerinden yararlanarak sahiplendirilme durumlarını tahmin edebilen bir makine öğrenmesi modeli geliştirmek. Ayrıca bu özelliklerin sahiplendirme sonuçlarıyla ilişkisini incelemek.

## Kapsam

- Hayvan barınağı verilerinin incelenmesi.
- Veri temizleme ve ön işleme işlemlerinin yapılması.
- Hayvan özelliklerinin sahiplendirme sonuçlarıyla ilişkisinin analiz edilmesi.
- Veri görselleştirmelerinin hazırlanması.
- Logistic Regression ve Decision Tree algoritmalarının uygulanması.
- Modellerin performanslarının karşılaştırılması.
- Tahmin sonuçlarının değerlendirilmesi ve raporlanması.

## Kapsam Dışı

- Sahiplendirme kararının kesin olarak verilmesi veya garanti edilmesi.
- Veri setinde bulunmayan özellikler üzerinden tahmin yapılması.

## Literatür Taraması

### 1. Bradley ve Rajendran (2021)
- Bu çalışmada, hayvan barınaklarında kalan hayvanların barınakta kalma süreleri makine öğrenmesi yöntemleriyle tahmin edilmiştir. Logistic Regression, Artificial Neural Network, Gradient Boosting ve Random Forest algoritmaları karşılaştırılmış; genel olarak en başarılı sonuç Gradient Boosting algoritmasından elde edilmiştir. Hayvanların yaşı, boyutu ve rengi gibi özelliklerin tahminde önemli olduğu belirtilmiştir.
- https://doi.org/10.1186/s12917-020-02728-2

### 2. Sazara ve Gao (2022)
- Bu araştırmada, Austin Animal Center'ın hayvan kabul ve çıkış verileri kullanılarak hayvanların sahiplendirilme süreleri tahmin edilmiştir. Kabul ve çıkış verileri Animal ID üzerinden birleştirilmiş, CatBoost algoritmasıyla sahiplendirilme süresi 15 günden az veya fazla olacak şekilde sınıflandırılmıştır. Yaş ve ırk gibi özelliklerin sahiplendirilme süresi üzerinde etkili olduğu gösterilmiştir.
- https://doi.org/10.1109/IS57118.2022.10019608

### 3. Islamiyah, Ibrahim, M. R., Gunawan, S., Khairina, D. M., & Erniati. (2025)
- Bu çalışmada, hayvanların sahiplendirilme olasılığını tahmin etmek için Logistic Regression, Decision Tree, Random Forest, SVM ve Naive Bayes algoritmaları karşılaştırılmıştır. Modeller Accuracy, Precision, Recall ve F1-score gibi ölçütlerle değerlendirilmiştir. Decision Tree ve Random Forest modellerinin başarılı sonuçlar verdiği, hayvanın yaşı ve kilosu gibi özelliklerin tahminde önemli olduğu belirtilmiştir.
- https://doi.org/10.11591/ijres.v14.i3.pp638-648    

## Veri Seti

- https://www.kaggle.com/datasets/jackdaoud/animal-shelter-analytics/data
- https://data.austintexas.gov/Health-and-Community-Services/Austin-Animal-Center-Outcomes-10-01-2013-to-05-05-/9t4d-g238/about_data
- https://data.austintexas.gov/Health-and-Community-Services/Austin-Animal-Center-Intakes-10-01-2013-to-05-05-2/wter-evkm/about_data

## İlk Yöntem

- Logistic Regression
- Decision Tree

## Ekip ve Roller

- Sude Nur Özkan - Data Analyst & Developer
- Berra Suer - Developer & Tester
- Gizem Görgün - Tester & Documentation Officer
