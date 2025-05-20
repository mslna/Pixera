# Pixera - Görüntü İşleme Uygulaması

Pixera, Python ve Windows Forms (C#) teknolojileriyle geliştirilen bir görüntü işleme projesidir. Histogram germe, eşitleme, renk dönüşümleri, filtre uygulamaları ve uzamsal işlemler gibi temel işlemleri kullanıcı dostu bir arayüzle sunar.

Özellikler

- Görüntüyü griye çevirme
- Histogram germe ve eşitleme
- Ortalama ve medyan filtre uygulamaları
- Salt & Pepper gürültü ekleme
- Konvolüsyon işlemleri
- Çoklu form yapısı ile modüler kontrol

Teknolojiler

- Python (OpenCV, PIL)
- C# Windows Forms arayüzü
- Görüntü işleme algoritmaları elle kodlandı (hazır kütüphaneler sınırlı kullanıldı)

Bu proje kapsamında geliştirilen masaüstü uygulama, temel görüntü işleme algoritmalarının Python diliyle sıfırdan kodlanması ve bu algoritmaların C# Windows Forms Application ortamına entegre edilmesi prensibine dayanmaktadır. Uygulama, kullanıcıya görsel bir arayüz üzerinden farklı görüntü işleme işlemleri gerçekleştirme olanağı sunmaktadır. Her bir işlem, arka planda ilgili Python modülünün çağrılmasıyla gerçekleştirilir.
