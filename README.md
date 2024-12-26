
**Türkçe Tweetlerde Cinsiyetçilik Tespiti**
Bu proje, metin sınıflandırma görevleri için BERT modelini kullanarak bir makine öğrenmesi modeli eğitmeyi amaçlamaktadır. Veri seti, model eğitimi öncesinde temizlenir ve etiketler one-hot encoding yöntemiyle dönüştürülür. Hugging Face kütüphanesi kullanılarak BERT modeli ve tokenizer yüklenir. Amaç, giriş metnine dayalı etiketleri doğru tahmin edebilen bir model oluşturmak ve yüksek doğruluk sağlamaktır.

Özellikler
Veri Hazırlığı: Veri, temizlenir ve etiketler one-hot encoding ile dönüştürülür.
BERT Entegrasyonu: Hugging Face transformers kütüphanesi kullanılarak önceden eğitilmiş BERT modeli ve tokenizer yüklenir.
CUDA Desteği: Eğitim, CUDA destekli GPU üzerinde hızlandırılmış olarak çalışır.
Model Eğitimi: BERT modeli, sağlanan veri seti ile ince ayar yapılır.
Değerlendirme: Modelin doğruluğu ve kaybı gibi performans metrikleri değerlendirilir.
