# AdamAsmacaOyunu

#  Java Swing Adam Asmaca Oyunu

Bu proje, Java Swing kullanılarak geliştirilmiş gelişmiş bir **Adam Asmaca** oyunudur.
Oyuncu rastgele seçilen kelimeyi tahmin etmeye çalışırken hata yaptıkça görseller güncellenir ve oyun durumu takip edilir.

##  Özellikler

*  Java Swing arayüzü
*  Rastgele kelime seçimi
*  Harf tahmin sistemi
*  Kelime tahmin sistemi
*  Süre sayacı
*  Skor kayıt sistemi
*  Log kayıt sistemi
*  Şifre korumalı giriş
*  Oyun sıfırlama özelliği
*  Menü sistemi
*  Dosya işlemleri (TXT okuma/yazma)
*  Adam asmaca görselleri


## Kullanılan Teknolojiler

* Java
* Java Swing
* File I/O
* Timer
* JTable
* JOptionPane
* NetBeans GUI Builder


##  Oyun Mantığı

1. Oyuncu oyunu başlatır.
2. Sistem rastgele bir kelime seçer.
3. Her doğru tahminde ilgili harf açılır.
4. Yanlış tahminlerde adam asmaca görseli ilerler.
5. 11 yanlış tahminde oyun kaybedilir.
6. Oyuncu tüm kelimeyi tahmin ederse oyunu kazanır.
7. Süre ve sonuç skor tablosuna kaydedilir.


##  Şifre Sistemi

Program ilk açıldığında kullanıcıdan bir şifre oluşturması istenir.

Sonraki girişlerde:

* Kullanıcı şifreyi doğru girerse giriş yapılır.
* 3 kez yanlış girilirse program kapanır.


##  Log Sistemi

Program aşağıdaki işlemleri kayıt altına alır:

* Giriş işlemleri
* Hatalı şifre girişleri
* Yeni şifre oluşturulması

Loglar JTable üzerinde görüntülenebilir.


##  Skor Sistemi

Her oyun sonunda:

* Süre
* Tarih
* Kazandı/Kaybetti bilgisi

`oyunlar.txt` dosyasına kaydedilir.





---

## 📜 Lisans

Bu proje eğitim amaçlı geliştirilmiştir.
