# 大人Lab (Adult Lang Lab)

Yetişkinlikte dil öğrenmenin mümkün ve ölçülebilir olduğunu göstermek için tasarlanmış, AI destekli deneysel bir web uygulaması.

## Proje Hakkında

Bu proje, "Yetişkinler dil öğrenmede dezavantajlıdır" iddiasını pratikte test etmeyi hedefler.
Uygulama Japonca ve Korece odaklıdır; kısa döngülü öğrenme, anlık geri bildirim ve motivasyon takibiyle düzenli ilerlemeyi görünür hale getirir.

## Amaç

- Yetişkin öğrenenlerin dil ediniminde sürdürülebilir bir model sunmak
- Öğrenmeyi küçük, tekrarlanabilir adımlara bölmek
- Öğrenme performansını (doğru oranı, seri, toplam etkileşim) takip etmek
- Bilimsel bulguları ürün deneyimiyle birleştirmek

## Öne Çıkan Özellikler

### 1) Flashcard Modu
- Karaktere tıklayarak anlam ve okunuşu açığa çıkarma
- "Bildim / Bilmedim" akışıyla seri (streak) takibi
- İlerleme çubuğu ile set tamamlama görünürlüğü

### 2) Quiz Modu
- 4 seçenekli çoktan seçmeli test
- Doğru/yanlış için anlık geri bildirim
- Doğru cevabın otomatik vurgulanması

### 3) AI Sensei Modu
- Kullanıcı sorularına yapay zeka destekli yanıt akışı
- Japonca/Korece karakter, kelime, kısa cümle açıklamaları
- Yetişkin öğrenme motivasyonunu destekleyen konuşma deneyimi

### 4) Bilim Sekmesi
- Kritik dönem hipotezi ve karşı araştırmaların özetlenmesi
- Yetişkin öğrenme avantajlarına dair kısa, anlaşılır içerik

## Dil Kapsamı

- Japonca: Hiragana + temel Kanji örnekleri
- Korece: Hangul + temel kelime örnekleri
- Üst bölümdeki dil anahtarı ile anlık geçiş

## Kullanıcı Metrikleri

Uygulama arayüzünde canlı olarak izlenir:

- Görülen karakter sayısı
- Doğru cevap sayısı
- Seri (streak)
- Başarı oranı

## Teknoloji

- Tek dosya frontend prototipi: HTML + CSS + Vanilla JavaScript
- Harici fontlar: Google Fonts
- AI sohbet akışı: Anthropic Messages API (istemci tarafı örnek entegrasyon)

## Proje Yapısı

Bu sürüm tek sayfalık bir prototip olarak hazırlanmıştır:

- `Untitled-1.html`: Uygulamanın tüm arayüzü, stilleri ve etkileşim mantığı
- `README.md`: Proje dokümantasyonu

## Kurulum ve Çalıştırma

1. Depoyu klonlayın:

```bash
git clone https://github.com/sahika-aleyna-yener/language-web.git
cd language-web
```

2. `Untitled-1.html` dosyasını bir tarayıcıda açın.

Not: AI Sensei bölümündeki API çağrısı, güvenli üretim kullanımı için backend proxy ve API anahtar yönetimi gerektirir.

## Ürün Vizyonu

Bu uygulama bir MVP/deney prototipidir. Sonraki iterasyonlarda hedef:

- Çoklu ders setleri ve seviyeleme
- Kalıcı kullanıcı ilerleme kaydı
- Aralıklı tekrar algoritması (SRS)
- Daha güvenli AI entegrasyonu (server-side)
- Performans analitiği ve kişiselleştirme

## Katkı

Katkıya açıktır.

1. Depoyu fork edin
2. Yeni bir branch açın (`feature/ozellik-adi`)
3. Değişikliklerinizi commit edin
4. Pull request oluşturun

## Lisans

Henüz lisans eklenmedi. Uygun lisans türü belirlendikten sonra bu bölüm güncellenecektir.