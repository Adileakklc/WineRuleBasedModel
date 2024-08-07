# WineRuleBasedModel
Bu proje, UCI Machine Learning Repository'den alınan Wine veri seti üzerinde kural tabanlı yöntemler kullanarak şarap türlerinin sınıflandırılmasını amaçlamaktadır. Proje kapsamında, veri ön işleme, model eğitimi, değerlendirme ve sonuçların karşılaştırılması gibi adımlar gerçekleştirilmiştir.

## İçindekiler
- [Giriş](#giriş)
- [Veri Seti ve Ön İşleme](#veri-seti-ve-ön-işleme)
- [Sınıflandırma Yöntemi](#sınıflandırma-yöntemi)
- [Modelin Eğitimi ve Değerlendirilmesi](#modelin-eğitimi-ve-değerlendirilmesi)
- [Sonuçlar ve Karşılaştırma](#sonuçlar-ve-karşılaştırma)
- [Sonuç ve Tartışma](#sonuç-ve-tartışma)
- [Kullanım](#kullanım)
- [Kaynaklar](#kaynaklar)

## Giriş
Bu proje, BLM0463 Veri Madenciliğine Giriş dersi kapsamında gerçekleştirilmiştir. Amaç, Wine veri seti üzerinde kural tabanlı yöntemler kullanarak şarap türlerini sınıflandırmaktır.

## Veri Seti ve Ön İşleme
Veri seti, UCI Machine Learning Repository'den alınmıştır. Wine veri seti, 13 kimyasal özellik ve 3 farklı şarap türünü (class_0, class_1, class_2) içermektedir. Eksik veriler temizlenmiş, gerekli dönüşümler yapılmış ve veriler normalizasyon işlemine tabi tutulmuştur.

## Sınıflandırma Yöntemi
Bu projede Kurala Dayalı Yöntemler (Rule-based Methods) kullanılmıştır. Bu yöntemler, belirli "if-then" kuralları ile verileri sınıflandırır. Kolay anlaşılır ve yorumlanabilir olmaları nedeniyle tercih edilmiştir.

## Modelin Eğitimi ve Değerlendirilmesi
- **Model Eğitimi:** Kurala dayalı model, eğitim veri seti kullanılarak eğitilmiştir. Modelin hiperparametreleri optimize edilmiştir.
- **Model Değerlendirme:** Model, test veri seti üzerinde değerlendirilmiştir. Değerlendirme ölçütleri olarak doğruluk (Accuracy), duyarlılık (Recall), hassasiyet (Precision) ve F1-Measure kullanılmıştır.

## Sonuçlar ve Karşılaştırma
Bu projede elde edilen sonuçlar aşağıdaki gibidir:
- **Doğruluk (Accuracy):** %86.8
- **F1-Measure:** %86.8
- **Hassasiyet (Precision):** %86.9
- **Duyarlılık (Recall):** %86.8

Sonuçlar, Mahima Gupta ve arkadaşlarının çalışmasında elde edilen Random Forest (%93.2 doğruluk) ve KNN (%91.5 doğruluk) algoritmalarına kıyasla biraz daha düşük kalmıştır. Ancak, RStudio Pubs'daki çalışmada karar ağacı modeli ile elde edilen %92.8 doğruluk ve %90.5 F1-Measure değerlerine yakındır.

## Sonuç ve Tartışma
Bu çalışma, kural tabanlı yöntemlerin şarap türlerinin sınıflandırılmasında etkili bir araç olduğunu göstermektedir. Modelimizin elde ettiği sonuçlar tatmin edici olup, modelin performansını artırmak için hiperparametre optimizasyonu ve daha ileri veri ön işleme teknikleri uygulanabilir. Gelecekte yapılacak çalışmalar, modelin performansını artırmak ve daha geniş veri kümeleri üzerinde test etmek amacıyla daha gelişmiş tekniklerin uygulanmasını içerebilir.
