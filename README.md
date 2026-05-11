Telecom Customer Churn Analysis (Orange Data Mining Project)
Bu proje, bir telekomünikasyon şirketindeki müşteri terk etme (churn) oranlarını tahmin etmek ve
müşteri davranışlarını analiz etmek amacıyla Orange Data Mining platformu kullanılarak geliştirilmiştir.

Projenin Amacı
Veri seti üzerinden müşterilerin demografik bilgilerini, kullandıkları hizmetleri ve sözleşme detaylarını analiz ederek; 
hangi müşterilerin ayrılma riskinin 
(Churn) yüksek olduğunu makine öğrenmesi modelleri ile tespit etmektir.

İş Akışı ve Kullanılan Yöntemler
Proje, verinin içe aktarılmasından model değerlendirmesine kadar tam bir veri bilimi boru hattını (pipeline) kapsamaktadır:

Veri Ön İşleme (Preprocessing):
Impute: Eksik verilerin tamamlanması.  
Select Columns: Tahmin için anlamlı olan özelliklerin (feature) seçilmesi.  
Data Sampler: Verinin eğitim ve test olarak bölümlenmesi.

Distributions: Değişkenlerin dağılım analizi.  
Scatter Plot: Değişkenler arası ilişkilerin incelenmesi. 
Tree Viewer: Karar ağacı yapısının görsel olarak hiyerarşik incelenmesi.  

Makine Öğrenmesi Modelleri:
Logistic Regression: Doğrusal sınıflandırma analizi.  
Random Forest: Topluluk öğrenmesi (Ensemble learning) ile yüksek doğruluklu tahmin.  
Decision Tree: Karar mekanizmalarının ağaç yapısıyla modellenmesi.

Performans Değerlendirme:
Test and Score: Modellerin başarı oranlarının (AUC, CA, F1) karşılaştırılması.  
Confusion Matrix: Sınıflandırma hatalarının ve başarılarının detaylı dökümü.


Decision Tree: Karar mekanizmalarının ağaç yapısıyla modellenmesi.
