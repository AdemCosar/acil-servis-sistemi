# Hastane Acil Servis Sistemi

Bu proje, C dili ile geliştirilmiş bir hastane acil servis sistemidir. Sistem, hasta kayıtlarını yönetir, doktorların teşhis ve reçete yazmasını sağlar ve HL7 formatında hasta bilgilerini oluşturur.

## Özellikler

- **Kullanıcı Yönetimi:** Admin ve doktor giriş sistemi.
- **Hasta Kayıt:** Yeni hasta ekleme ve hasta bilgilerini yönetme.
- **Doktor Yönetimi:** Doktor kayıt işlemleri.
- **Teşhis ve Tedavi:** Doktorlar hasta şikayetlerini alıp teşhis koyabilir.
- **Reçete Yönetimi:** İlaç ekleme ve hastalar için reçete yazma.
- **HL7 Mesaj Desteği:** Hasta bilgileri HL7 formatında oluşturulur.

## Kurulum ve Kullanım

1. **Projeyi Derleme:**
   ```sh
   gcc main.c -o main
   ```
2. **Programı Çalıştırma:**
   ```sh
   ./main
   ```
3. **Giriş Bilgileri:**
   - Admin: `admin / admin123`
   - Doktorlar için kullanıcı adı ve şifre, admin tarafından eklenir.

## Kullanım Kılavuzu

- **Admin Menüsü:**
  - Doktor kaydetme
  - Hasta kaydetme
  - İlaç ekleme
- **Doktor Menüsü:**
  - Mevcut hastaları listeleme
  - Hasta kaydı yapma
  - Hasta teşhisi koyma
  - Reçete yazma
- **HL7 Mesaj Formatı:**
  - Hasta kayıt işlemi sonrası HL7 formatında mesaj üretilir.

## Bağımlılıklar

- Standart C Kütüphaneleri (`stdio.h`, `stdlib.h`, `string.h`, `time.h`)


