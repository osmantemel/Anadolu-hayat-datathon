* K-en Yakın Komşu (KNN):
 KNN, veri setindeki benzer örnekleri gruplandırır ve yeni örneklerin etiketlerini belirlemek için bu gruplardan en yakın olanları kullanır. Eksik verilerle başa çıkmak için bu model, eksik verilerin tahmin edilmesinde veya doldurulmasında kullanılabilir.

* Karar Ağaçları:
 Karar ağaçları, veri setindeki özelliklerin değerlerine göre kararlar alır ve sınıflandırma yapar. Eksik verileri doğrudan kullanabilir ve bu eksiklikleri modele göre otomatik olarak ele alabilir.

* Rastgele Orman:
 Rastgele ormanlar, birçok karar ağacını bir araya getirerek sınıflandırma yapar. Her bir ağaç farklı bir alt küme üzerinde eğitilir ve sınıflandırma sonuçları bir araya getirilir. Eksik verilerle başa çıkmak için karar ağaçlarında olduğu gibi, rastgele ormanlar da eksik verileri otomatik olarak ele alabilir.

* XGBoost, LightGBM, CatBoost:
 Bu üç model de artan popülerlik kazanmıştır ve eksik veri ile çalışmaya uygun hale getirilmiştir. XGBoost, LightGBM ve CatBoost, eksik verileri otomatik olarak işleyebilir ve sınıflandırma performansını artırmak için çeşitli teknikler kullanır.

* Missing Forest: 
Missing Forest, eksik veri ile başa çıkmak için geliştirilmiş bir modeldir. Bu model, eksik verileri tahmin etmek ve doldurmak için orman tabanlı bir yaklaşım kullanır.

* Amelia II: 
Amelia II, eksik veri analizi ve doldurma için kullanılan istatistiksel bir yöntemdir. Çeşitli makine öğrenimi modellerinden farklı olarak, Amelia II, eksik veri doldurma için istatistiksel yöntemler kullanır.