# Su-Stresi-Modeli
-------------------------------------------------------------------------------------
Su stresi modeli, “Kişi başına orman alanı (metre kare)”, “Kişi başına düşen yenilenebilir tatlı su kaynakları (metreküp)”, “Yılda ortalama yağış (mm)” ve “Temel Su Stresi” değişkenlerini baz alarak oluşturulmuştur. Söz konusu değişkenler “Temel Su Stresini” tahminlemek için kullanılmaktadır.
--------------------------------------------------------------------------------------
Elle oluşturulan veri setinde 31 farklı ülke bulunmaktadır. Ülkeler K.Amerika, G.Amerika, Avrupa, Asya, Afrika ve Avustralya kıtalarında bulunmaktadır.
--------------------------------------------------------------------------------------
• Kişi başına düşen orman alanı (metre kare) değişkeni; ülkelerde kişi başına düşen orman alanlarının metrekare cinsinden değerlerini göstermektedir.

• Kişi başına düşen yenilenebilir tatlı su kaynakları(metreküp) değişkeni; ülkelerde kişi başına düşen yenilenebilir tatlı su kaynaklarının metreküp cinsinden değerlerini göstermektedir.

• Yılda ortalama yağış (mm) değişkeni; ülkelerde yılda ortalama yağışının mm cinsinden değerlerini göstermektedir.

• Temel Su Stresi değişkeni değerleri; ülkelerin, WRI (World Resources Institute) tarafından belirlenmiş olan temel su stresi seviyesini göstermektedir.

---------------------------------------------------------------------------------------
Bu çalışmada, su stresinin artmasına neden olan değişkenlerin belirlenmesi amacıyla bir regresyon modeli kullanılarak makine öğrenmesi yapıldı. Modelin OLS Regresyon tablosunda yer alan Düzeltilmiş R-kare değeri 0.316’dır. Modelin kalitesini iyileştirmek için eklenen bağımsız değişkenleri göz önünde bulundurarak daha güvenilir bir sonuçtur. Düzeltilmiş R-kare değerine göre bağımsız değişkenin bağımlı değişkeni açıklama yüzdesi %31’dir. Makine öğrenmesi ile birlikte elde edilen sonuçlara göre, yılda ortalama yağmur yağış miktarının su stres seviyesini tahmin etmede kullanılabileceği öngörülmüştür. Model, giriş olarak “500” olarak verilen Yılda Ortalama Yağış değerine karşılık Su Stres seviyesini “57.139” olarak tahmin etmiştir. Oluşturulan veri setindeki Yılda Ortalama Yağış verileriyle karşılaştırıldığında, modelin yakın sonuç verdiği söylenebilmektedir. Modelin doğruya yakın sonuçlar verme yeteneği, veriler arasındaki ilişkiyi anlama kabiliyetiyle ölçülebilmektedir.
