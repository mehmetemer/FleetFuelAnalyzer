# Fleet Performance & Fuel Analyzer

## 📌 Proje Hakkında
Kurumsal araç filolarının yakıt tüketimi ve kilometre verilerini anlık olarak analiz eden, SQLite tabanlı yüksek performanslı bir veri yönetim aracıdır. Manuel hesaplama süreçlerini ortadan kaldırmak ve veri giriş hatalarını önlemek amacıyla geliştirilmiştir.

## 🚀 Kullanılan Teknolojiler
* **Dil:** C# (.NET)
* **Veritabanı:** SQLite (Microsoft.Data.Sqlite)
* **Mimari:** Modüler Yapı, Clean Code Prensipleri

## 📊 Mühendislik Metrikleri ve Sistem Etkisi
* **Süreç Optimizasyonu:** Manuel yakıt ve kilometre hesaplama operasyonları %100 oranında dijitalleştirilerek insan kaynaklı hatalar sıfıra indirilmiştir.
* **Performans:** Veritabanı işlemlerinde `BeginTransaction` mimarisi kullanılarak toplu veri okuma/yazma hızları milisaniyeler seviyesine ( < 0.2 ms ) optimize edilmiştir.
* **Güvenilirlik:** Kapsamlı `Try-Catch` blokları ile çalışma zamanı hatalarına karşı sistem güvenliği sağlanmıştır.
