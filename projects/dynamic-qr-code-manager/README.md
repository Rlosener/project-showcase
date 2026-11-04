# Dinamik QR Kod Yöneticisi

**Native uygulamalar** · Proje incelemesi

Hedef URL’leri düzenlenebilir kısa kodlarla eşleştiren, QR görselleri üreten yerel masaüstü uygulaması.

## Teknoloji

Python · Tkinter/ttk · SQLite · qrcode · Pillow · http.server

## Mimari akış

Hedef URL → kısa kod kaydı → QR → yerel yönlendirme → güncel hedef

## Mühendislik odağı

- QR görseli doğrudan değişken hedef yerine yönlendirme kaydını temsil eder.
- SQLite kısa kod ve hedef eşleşmelerini saklar.
- Masaüstü arayüzünde kayıt yönetimi ve seçili QR önizlemesi birlikte sunulur.

## Kapsam ve sınırlar

Yerel HTTP servisi, internete açık ve yüksek erişilebilir bir yönlendirme hizmeti değildir.

Teknik özet mevcut proje dokümantasyonundan hazırlanmıştır. Bu vitrin kapsamında uygulama çalıştırma veya canlı ortam kabulü yapılmamıştır.

---

[← Proje kataloğu](../../README.md)

Bu sayfa tanıtım içindir. Uygulama kaynakları ve geliştirme geçmişi bu vitrinde dağıtılmaz.
