# SociAI

**AI ve operasyon** · Proje incelemesi

Ajans ve müşteri kapsamlarında içerik taslaklarını, yayın takvimini ve mesajlaşmayı yöneten sosyal medya operasyon MVP’si.

## Teknoloji

Node.js · SQLite · Docker · Meta WhatsApp Cloud API · SSE

## Mimari akış

Müşteri alanı → içerik taslağı → yetkili planlama → sağlayıcı yanıtı → yayın geçmişi

## Mühendislik odağı

- Müşteri üyeliği ve roller sunucuda denetlenir; bağlantı bilgileri istemciye geri verilmez.
- Yayınlama ve mesajlaşma adaptörleri ürün arayüzünden ayrılır.
- Webhook doğrulama, idempotent mesaj kaydı ve müşteri kapsamlı olay akışı gelen kutusunu besler.

## Kapsam ve sınırlar

Reels/Story/Carousel üretimi ve WhatsApp şablon gönderimi bu MVP kapsamında değildir; sağlayıcı izinleri belirleyicidir.

Teknik özet mevcut proje dokümantasyonundan hazırlanmıştır. Bu vitrin kapsamında uygulama çalıştırma veya canlı ortam kabulü yapılmamıştır.

---

[← Proje kataloğu](../../README.md)

Bu sayfa tanıtım içindir. Uygulama kaynakları ve geliştirme geçmişi bu vitrinde dağıtılmaz.
