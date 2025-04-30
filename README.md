# HalTest 🧠🔍

**HalTest**, yapay zeka modellerinin halüsinasyon (uydurma bilgi) üretme eğilimlerini test etmek amacıyla geliştirilmiş açık kaynaklı bir web aracıdır.  
Kullanıcılar, AI yanıtlarını manuel olarak değerlendirebilir, doğruluk puanları verebilir ve modelin tutarlılığını analiz edebilir.

- 🔗 [Soru Havuzu (sorular.md)](./sorular.md) — Halüsinasyon test cümleleri listesi  
- 🔗 [Örnek Değerlendirme Tablosu (ornek.md)](./ornek.md) — Puanlama ve analiz örneği
- 🔗 [Örnek Karşılaştırma Tablosu (analiz.md)](./analiz.md) — Karşılaştırmalı analiz örneği

---

## 🎯 Özellikler

- Sorular ve AI yanıtlarını kolayca girme
- Halüsinasyon var/yok işaretleme
- 0–3 arası puanlama sistemi
- Ortalama doğruluk puanı hesaplama
- Karanlık mod, sade tasarım
- Hiçbir bağımlılık olmadan doğrudan tarayıcıda çalışır

---

## 🚀 Canlı Demo

> [📎 Tıkla ve dene](https://makalin.github.io/HalTest)

---

## 🧪 Kullanım

1. `index.html` dosyasını bir tarayıcıda aç
2. Her satıra bir soru ve AI yanıtı gir
3. Doğruluk puanını ve halüsinasyon olup olmadığını seç
4. "Skorları Hesapla" butonuna tıkla – ortalama puan ekranda gösterilir

---

## 📁 Dosya Yapısı

```
HalTest/
├── index.html    # Ana uygulama dosyası
├── README.md     # Proje açıklaması
```

---

## 🔧 Geliştirme Fikirleri

- Excel/CSV dışa aktarma
- AI yanıtları için otomatik kaynak kontrolü (örnek: Wikipedia API)
- Kategoriye göre filtreleme
- OpenAI/Gemini entegrasyonu ile yanıtları doğrudan test etme

---

## 💡 Neden "HalTest"?

"Hal" kelimesi, *hallucination* (halüsinasyon) ifadesinden gelir. Bu araç, AI çıktılarının gerçekle ne kadar tutarlı olduğunu test etmek için geliştirilmiştir.

---

## 📄 Lisans

MIT Lisansı.  
Katkıda bulunmak serbesttir — PR'lar, öneriler ve yıldızlar ⭐ memnuniyetle karşılanır.

---

## 👨‍💻 Geliştirici

Made with 🖤 by [@makalin](https://github.com/makalin)
