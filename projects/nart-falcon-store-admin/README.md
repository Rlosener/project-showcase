# Adatekno — Mağaza ve Yönetim

**Web ürünleri** · Proje incelemesi

Türkçe ürün kataloğu, varyantlı sepet ve veri tabanına bağlı yönetim işlemlerini birleştiren mağaza projesi.

## Teknoloji

Next.js/Node.js · SQLite · alternatif PHP çalışma zamanı

## Mimari akış

Katalog verisi → ürün / varyant → sepet → yönetim işlemleri → kalıcı veri

## Mühendislik odağı

- Mağaza sayfaları, veri sorguları, yönetim işlemleri ve ortak bileşenler ayrı katmanlarda düzenlenir.
- Node ve PHP sürümleri farklı çalışma zamanlarıdır; değişikliklerin iki sürümde ayrı ele alınması gerekir.
- Kalıcı disk, veri yedekleme ve katalog aktarımı mağaza operasyonunun parçalarıdır.

## Kapsam ve sınırlar

Çalışma zamanı seçimi hosting desteğine bağlıdır; yerel örnek veri canlı katalog kabulü değildir.

Teknik özet mevcut proje dokümantasyonundan hazırlanmıştır. Bu vitrin kapsamında uygulama çalıştırma veya canlı ortam kabulü yapılmamıştır.

---

[← Proje kataloğu](../../README.md)

Bu sayfa tanıtım içindir. Uygulama kaynakları ve geliştirme geçmişi bu vitrinde dağıtılmaz.
