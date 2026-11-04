# Kıbrıs Emlak Intelligence

**Veri ve gayrimenkul** · Proje incelemesi

Gayrimenkul ilanlarını zaman içinde izleyen; fiyat, durum ve veri kalitesi değişimlerini analiz eden yerel masaüstü platformu.

## Teknoloji

SwiftUI · Swift Charts · FastAPI · Pydantic · SQLAlchemy · SQLite/PostgreSQL · Ollama

## Mimari akış

Kaynak adaptörü → kalıcı tarama işi → tekilleştirme → snapshot → analiz → Mac arayüzü

```mermaid
flowchart LR
  A[Kaynak adaptörleri] --> B[Kalıcı işler]
  B --> C[Tekilleştirme]
  C --> D[Snapshot ve geçmiş]
  D --> E[Analiz API]
  E --> F[SwiftUI istemci]
```

## Mühendislik odağı

- İlan kimliği ve kaynak bağlantısı üzerinden tekilleştirme yapılır; değişimler snapshot ve olay geçmişine yazılır.
- Tarama kapsamı ile hata durumları ayrı tutulur; geçici erişim hatası ilanın pasif olduğu anlamına gelmez.
- Native istemci, API, işçiler ve veri katmanı ayrıdır; kaynakta bulunmayan alanlar tahminle doldurulmaz.

## Kapsam ve sınırlar

Kaynak erişimi ve kapsamı değişebilir; yerel AI isteğe bağlıdır ve canlı kaynak kabulü bu vitrinle kanıtlanmaz.

Teknik özet mevcut proje dokümantasyonundan hazırlanmıştır. Bu vitrin kapsamında uygulama çalıştırma veya canlı ortam kabulü yapılmamıştır.

---

[← Proje kataloğu](../../README.md)

Bu sayfa tanıtım içindir. Uygulama kaynakları ve geliştirme geçmişi bu vitrinde dağıtılmaz.
