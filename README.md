# BTK Todo App

BTK Todo App, BTK Akademi İleri Seviye Flutter Atölyesi 2024 kapsamında geliştirilen modern bir görev yönetimi uygulamasıdır. Bu proje, en güncel Flutter teknolojilerini ve best practice'leri kullanarak geliştirilmiş olup, gerçek dünya senaryolarına uygun bir yapı sunmaktadır.

## 🌟 Özellikler

- Kullanıcı Kimlik Doğrulama (Kayıt, Giriş, Çıkış)
- Görev Oluşturma, Düzenleme ve Silme
- Kullanıcı Profil Yönetimi
- Görevleri Kategorilere Ayırma
- Görev Önceliklendirme
- Koyu/Açık Tema Desteği
- Çoklu Dil Desteği

## 🛠 Kullanılan Teknolojiler

- **Flutter & Dart**: UI geliştirme ve uygulama mantığı
- **BLoC Pattern**: Durum yönetimi
- **GetIt & Injectable**: Bağımlılık enjeksiyonu
- **Retrofit & Dio**: API entegrasyonu
- **JSON Serializable**: JSON işleme
- **Formz**: Form validasyonu
- **GoRouter**: Navigasyon yönetimi
- **Flutter Secure Storage & Shared Preferences**: Yerel veri depolama
- **FlutterGen**: Asset yönetimi
- **Envied**: Ortam değişkenleri yönetimi
- **Flutter Localizations**: Çoklu dil desteği

## 🏗 Mimari Yapı

Proje, temiz mimari prensiplerini takip ederek aşağıdaki katmanlara ayrılmıştır:

- **Presentation**: UI bileşenleri ve BLoC'lar
- **Domain**: İş mantığı ve repository arayüzleri
- **Data**: API iletişimi, yerel depolama ve model sınıfları
- **Core**: Uygulama genelinde kullanılan yardımcı sınıflar ve uzantılar
