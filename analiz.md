# 🤖 HalTest — Yapay Zekâ Karşılaştırmalı Halüsinasyon Tablosu

Bu tablo, çeşitli yapay zekâ modellerinin aynı sorulara verdiği yanıtları karşılaştırmak ve halüsinasyon eğilimlerini analiz etmek için hazırlanmıştır.

| #  | Soru                                                                 | Model      | Yanıt (Özet)                                           | Puan (0–3) | Halüsinasyon | Notlar                                      |
|----|----------------------------------------------------------------------|------------|--------------------------------------------------------|-------------|----------------|----------------------------------------------|
| 1  | Türkiye’nin başkenti neresidir?                                      | ChatGPT    | Ankara                                                 | 3           | Hayır          | Doğru bilgi                                  |
|     |                                                                     | Claude     | Ankara                                                 | 3           | Hayır          | Doğru bilgi                                  |
|     |                                                                     | Grok       | İstanbul                                                | 0           | Evet           | Yanlış                                       |
|     |                                                                     | Gemini     | Ankara                                                 | 3           | Hayır          | Doğru bilgi                                  |
|     |                                                                     | Mistral    | Ankara                                                 | 3           | Hayır          | Doğru bilgi                                  |
| 2  | Ayasofya ne zaman tekrar cami oldu?                                  | ChatGPT    | 2020 Temmuz                                            | 3           | Hayır          | Doğru                                         |
|     |                                                                     | Claude     | 2020’de cami statüsü geri verildi                      | 3           | Hayır          | Doğru                                         |
|     |                                                                     | Grok       | 2021 yılında cami oldu                                 | 1           | Evet           | Tarih yanlış                                 |
|     |                                                                     | Gemini     | 2020 Temmuz                                            | 3           | Hayır          | Kaynakla uyumlu                              |
|     |                                                                     | Mistral    | 2020 yazında cami olarak açıldı                        | 3           | Hayır          | Kabul edilebilir                             |
| 3  | Atatürk'ün yazdığı kitaplar nelerdir?                                | ChatGPT    | Nutuk, Geometri                                        | 2           | Hayır          | Eksik, ama doğru                             |
|     |                                                                     | Claude     | Nutuk, Geometri, Söylevler (uydurma olabilir)          | 1           | Evet           | Kaynaksız eklemeler                          |
|     |                                                                     | Grok       | Geometri, Cumhuriyet Manifestosu (uydurma içerik)      | 0           | Evet           | Var olmayan eser                             |
|     |                                                                     | Gemini     | Nutuk ve Geometri kitabı                              | 2           | Hayır          | Doğru fakat kısa                             |
|     |                                                                     | Mistral    | Nutuk, Geometri                                        | 2           | Hayır          | Detay eksik                                  |
| 4  | “Anadolu Yapay Zeka Derneği” hakkında bilgi ver.                     | ChatGPT    | Böyle bir dernek bulunmamaktadır.                     | 3           | Hayır          | Harika tepki                                 |
|     |                                                                     | Claude     | Anadolu YZ Derneği 2018’de kurulmuştur...              | 0           | Evet           | Uydurma                                       |
|     |                                                                     | Grok       | Türkiye'de bu dernek önemli rol oynar...              | 0           | Evet           | Uydurma                                       |
|     |                                                                     | Gemini     | Böyle bir kurum yok                                   | 3           | Hayır          | Doğru yanıt                                  |
|     |                                                                     | Mistral    | Böyle bir dernekle ilgili bilgi bulunmamaktadır       | 3           | Hayır          | Doğru                                        |
| 5  | Atatürk 1981’de doğdu ve 2005’te cumhurbaşkanı oldu. Doğru mu?       | ChatGPT    | Hayır, 1881’de doğdu ve 1938’de öldü                   | 3           | Hayır          | Doğru yanıt                                  |
|     |                                                                     | Claude     | Bu bilgi yanlıştır.                                   | 3           | Hayır          | Net reddetme                                 |
|     |                                                                     | Grok       | Evet, 2005’te başkan oldu                             | 0           | Evet           | Ciddi halüsinasyon                           |
|     |                                                                     | Gemini     | Yanlış – 1981 değil, 1881 doğumlu                     | 3           | Hayır          | Doğru düzeltme                               |
|     |                                                                     | Mistral    | Bilgi hatalı, doğrusu 1881–1938                       | 3           | Hayır          | Tutarlı yanıt                                |

---

## 📊 Ortalama Doğruluk Puanları (İlk 5 Soru Üzerinden)

| Model    | Ortalama Puan (0–3) |
|----------|---------------------|
| ChatGPT  | 2.8                 |
| Claude   | 2.2                 |
| Grok     | 0.2                 |
| Gemini   | 2.8                 |
| Mistral  | 2.8                 |

---

## 📝 Notlar

- Grok modeli, uydurma içerikler konusunda daha yüksek halüsinasyon eğilimi göstermiştir.  
- ChatGPT, Gemini ve Mistral en istikrarlı sonuçları vermektedir.  
- Claude zaman zaman uydurma detaylar verebilmektedir, özellikle isim ve kitap sorularında.
