# Efe Can Akbulut — Portfolyo

**Web ürünleri** · Proje incelemesi

Proje ve içerik sunumunu React arayüzü ile PHP/MySQL CMS katmanında birleştiren kişisel portfolyo.

## Teknoloji

React 19 · TypeScript · Vite · PHP 8 · PDO · MySQL

## Mimari akış

CMS → içerik API’si / statik yedek → içerik cache → sayfalar → medya ve SEO derlemesi

## Mühendislik odağı

- Route seviyesinde lazy loading ile sayfa yükleri ayrılır.
- ETag destekli içerik akışı ve statik içerik yedeği API erişimiyle birlikte ele alınır.
- Derleme aşamasında responsive WebP türevleri, rota metaverileri ve medya manifesti üretilir.

## Kapsam ve sınırlar

Statik içerik yedeği form gönderimi veya canlı CMS bağlantısının çalıştığı anlamına gelmez.

Teknik özet mevcut proje dokümantasyonundan hazırlanmıştır. Bu vitrin kapsamında uygulama çalıştırma veya canlı ortam kabulü yapılmamıştır.

---

[← Proje kataloğu](../../README.md)

Bu sayfa tanıtım içindir. Uygulama kaynakları ve geliştirme geçmişi bu vitrinde dağıtılmaz.
