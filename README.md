# Kur_Algoritmik_islem_modeli_-TL

Yahoofinance verileri kullanılarak ilgili tarih Aselsan hisse değeri ve ilgili tarih $/tl kuru verileri çekilmiştir Bu veriler üzerinden ilk olarak Durağanlık kavramı incelenmiş olup veriye finans piyasalarında yaygın olarak kullanılan analizler eklenmiştir...

Çoklu doğrusal Bağlantı VIF testi ve ACPR plot testi veriye neden uygulandığı ve gözlemleri açıklanmıştır.

Zaman serileri için Çapraz doğrulama nasıl yapılacağını ve Yanlılık sorunu anlatılmıştır...

Bir modelin hatasının iki temel bileşeni vardır Yanlılık ve Varyans bunlar modelin optimizasyonu ile düşürülebilir bir de düşürülemen hata vardır (irreducible error ) vardır. 

MSE = Varyans + Yanlılık karesi + Düşürülemeyen hata

Modeli eğitim ve test seti üzerinden değerlendirmek için Learning Curve grafiği üzerinde yorumlar yapılmıştır..

![açıklama]learning_curve.jpg

Grafiği VARYANS açısından incelersek doğrulama skoru ile öğrenme scoru arasındaki fark azaldıkça varyans azalır demektir. iki öğrenme eğrisi arasındaki fark azalarak stabil hale geldiği için modelin varyans sorunu yoktur yani model train ile öğrenme setinde iyi performans göstermisse test seti doğrulama seti için de iyi performans göstericektir.

t zamanda df["close"] değerinden yola çıkara fiyat değişiminin ya da hisse senedi getirisinin t + 1 zamanda olan değerine t zamanında olan kapanış fiyatını eklersek t + 1 zamanının tahmini kapanış fiyatını buluruz.

Bu çalışma bir zaman serisi tahmini oluşturmadan bir zaman serisi modelinin temel testlerini yanlılık varyans ve düşürülemeyen hata başta olmak üzere back-test yöntemi ile ileri bir tarihe tahmin etmeye yönelik aynı zamanda zaman serisi ile alakalı bir notebook olmak üzere amaçlıdır...








