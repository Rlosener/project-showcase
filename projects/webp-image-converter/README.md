# WebP Converter

**Native uygulamalar** · Proje incelemesi

Görselleri kalite ve boyut seçenekleriyle toplu olarak WebP biçimine dönüştüren Python masaüstü aracı.

## Teknoloji

Python · Pillow · masaüstü UI

## Mimari akış

Görsel seçimi → kalite / boyut ayarı → dönüşüm → çıktı klasörü → tasarruf özeti

## Mühendislik odağı

- Girdi dosyaları, dönüşüm seçenekleri ve çıktı konumu ayrı adımlarda ele alınır.
- Dosya ilerlemesi ve önce/sonra tasarruf özeti toplu işlemi görünür kılar.
- Pillow tabanlı dönüşüm desteklenen görsel biçimlerini ortak akışta işler.

## Kapsam ve sınırlar

AVIF okuma kurulu codec desteğine bağlıdır; sürükle-bırak ve hedef dosya boyutu mevcut kapsamda doğrulanmamıştır.

Teknik özet mevcut proje dokümantasyonundan hazırlanmıştır. Bu vitrin kapsamında uygulama çalıştırma veya canlı ortam kabulü yapılmamıştır.

---

[← Proje kataloğu](../../README.md)

Bu sayfa tanıtım içindir. Uygulama kaynakları ve geliştirme geçmişi bu vitrinde dağıtılmaz.
