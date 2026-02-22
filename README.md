-Sinüzoidal İşaret Analizi ve DTMF Sentezi-
Bu proje, temel sinyal işleme prensiplerini Python üzerinden uygulamalı olarak ele almaktadır.

Proje Özeti
Çalışma kapsamında iki temel görev gerçekleştirilmiştir:
1-Sinyal Örnekleme: Sinüzoidal işaretlerin Nyquist Kriteri'ne (f_s > 2f_{max}) uygun olarak örneklenmesi ve zaman düzleminde görselleştirilmesi.
  Bu bölümde, temel frekansı f_0 = 128 Hz olan üç farklı sinyal (f_1, f_2, f_3) sentezlenmiştir.
  Nyquist Analizi: En yüksek frekans olan 1280 Hz'in 10 katı hızda örnekleme yapıldığı için aliasing (örtüşme) engellenmiştir.
  Sonuç: İşaretler zaman düzleminde bozulma olmadan görselleştirilmiştir.
  
2-DTMF Sentezi: Telefon sistemlerinde kullanılan Çift Tonlu Çoklu Frekans sinyallerinin matematiksel olarak üretilmesi.
  Bu bölümde, telefon tuş takımında kullanılan standart frekans çiftleri (DTMF) simüle edilmiştir.
  Sinyal Yapısı: Her tuş, bir düşük ve bir yüksek frekanslı sinüs dalgasının toplamıyla (f_L + f_H) oluşturulmuştur.
  Standart ses iletimine uygun olarak f_s = 8000 Hz kullanılmıştır.
  Seçilen tuşlara ait işaretler zaman düzleminde çizdirilmiş ve genlikleri (-1, 1) aralığına normalize edilmiştir.

Kullanılan Araçlar
-Dil: Python
-Kütüphaneler: NumPy (Hesaplama), Matplotlib (Görselleştirme)

Dosya Yapısı
Görev_1.py: Sinüzoidal sinyal üretimi ve örnekleme analizi.
Görev_2.py: DTMF tuş takımı frekans sentezi.

