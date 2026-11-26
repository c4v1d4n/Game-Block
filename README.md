# Kərpic Blok — Android

Oyun `app/src/main/assets/index.html` faylındadır və internetsiz işləyir.
Hədəf: Android 16 (API 36), minimum Android 7.0 (API 24).

## APK-nı necə almaq olar

### Yol 1 — Android Studio (kompüterdə)
1. Android Studio-nu quraşdırın (developer.android.com/studio).
2. File → Open → bu qovluğu seçin. Gradle özü lazım olanları yükləyəcək.
3. Build → Build App Bundle(s) / APK(s) → Build APK(s).
4. APK burada olacaq: `app/build/outputs/apk/debug/app-debug.apk`

### Yol 2 — GitHub (kompüterə heç nə quraşdırmadan)
1. GitHub-da yeni repo yaradın və bu qovluğun bütün fayllarını yükləyin.
2. Actions bölməsində "APK yığ" avtomatik işə düşəcək (~3-5 dəq).
3. Bitəndə həmin işin səhifəsində "KerpicBlok-apk" faylını yükləyin, içində APK var.

### Telefona quraşdırmaq
APK-nı telefona köçürün, açın və "naməlum mənbələrdən quraşdırmaya" icazə verin.

Qeyd: bu "debug" APK-dır — şəxsi istifadə üçün tam işləyir. Google Play-ə yükləmək
üçün Android Studio-da Build → Generate Signed Bundle ilə imzalı AAB lazımdır.
