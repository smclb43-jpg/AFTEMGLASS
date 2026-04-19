AFTEM Mobil İstasyon - EKSİKSİZ GitHub / Android Studio Paket

Bu paket şunları içerir:
- Android Studio proje klasör yapısı
- AFTEM logo ikonları
- Mobil üretim ekranı (Müşteri, Proje, Cam Türü, Adet, m2)
- server.py
- AFTEM_MOBIL_SERVER_BASLAT.bat
- GitHub Actions workflow
- gradlew
- gradlew.bat
- gradle/wrapper/gradle-wrapper.properties

Önemli:
- Bu sürüm GitHub Actions ile APK üretmek için hazırlandı.
- Workflow, wrapper jar zorunluluğu olmadan sistem gradle ile derleme yapar.
- Android Studio içinde de açılabilir.

GitHub'dan APK alma:
1. Bu klasörün tamamını repo'ya yükle
2. Actions > Build Android APK
3. Run workflow
4. Bitince artifact içinden APK indir

Canlı kullanım:
1. PC'de server.py ya da AFTEM_MOBIL_SERVER_BASLAT.bat çalıştır
2. Telefon ve bilgisayar aynı ağda olsun
3. Uygulamada API adresi olarak http://BILGISAYAR_IP:8765 yaz
