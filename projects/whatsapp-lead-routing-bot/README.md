# WhatsApp Lead Bot

**Otomasyon araçları** · Proje incelemesi

Aynı gönderenden gelen mesajları zaman penceresinde birleştirip özet lead kaydını seçilen gruba ileten yerel otomasyon.

## Teknoloji

Node.js · whatsapp-web.js · yerel dashboard

## Mimari akış

Mesaj → zaman penceresinde birleştirme → lead özeti → grup iletimi → durum kaydı

## Mühendislik odağı

- Mesajlar gönderene göre birleştirilerek tek kayıt halinde ele alınır.
- Dashboard bağlantı, bekleyen kayıt, gönderim ve hata durumlarını gösterir.
- Yerel oturum ile gönderim kayıtları farklı operasyon sorumlulukları taşır.

## Kapsam ve sınırlar

Resmî WhatsApp Business API entegrasyonu değildir; çalışma davranışı hesap ve platform koşullarına bağlıdır.

Teknik özet mevcut proje dokümantasyonundan hazırlanmıştır. Bu vitrin kapsamında uygulama çalıştırma veya canlı ortam kabulü yapılmamıştır.

---

[← Proje kataloğu](../../README.md)

Bu sayfa tanıtım içindir. Uygulama kaynakları ve geliştirme geçmişi bu vitrinde dağıtılmaz.
