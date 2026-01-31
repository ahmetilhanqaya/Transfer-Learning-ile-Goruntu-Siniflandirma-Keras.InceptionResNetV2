InceptionResNetV2 ile Nesne Tanıma (Image Classification)
Bu proje, TensorFlow ve Keras kütüphanelerini kullanarak, önceden eğitilmiş (pre-trained) derin öğrenme modelleriyle nasıl nesne sınıflandırması yapılacağını gösteren başlangıç seviyesinde bir uygulamadır.

Projede Google'ın geliştirdiği güçlü bir model olan InceptionResNetV2 kullanılmıştır.

Proje Hakkında
Bu kod parçası, transfer öğrenimi (transfer learning) konseptinin temel bir örneğidir. Sıfırdan bir model eğitmek yerine, milyonlarca resimle eğitilmiş "ImageNet" ağırlıklarını kullanan hazır bir model yüklenir ve verilen bir resmi (örneğin bir iPhone fotoğrafını) analiz ederek ne olduğunu tahmin eder.

Temel Adımlar:
Görüntü İşleme: Resim yüklenir ve modelin istediği 299x299 boyutuna getirilir.

Ön İşleme (Preprocessing): Piksel değerleri modelin anlayacağı matematiksel aralığa (-1 ile 1 arasına) çekilir.

Tahmin (Prediction): Resim InceptionResNetV2 modeline verilir.

Sonuç (Decoding): Modelin ürettiği olasılıklar, okunabilir etiketlere (örn: "modem", "cep telefonu") dönüştürülür.


Kullanılan Model: InceptionResNetV2

Eğitim Seti: ImageNet (1000 farklı sınıf)

Giriş Boyutu: 299x299 piksel

Kullanım Alanı: Yüksek doğruluklu nesne tanıma ve sınıflandırma.

