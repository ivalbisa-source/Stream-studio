# Stream Studio Android

Ini adalah bahan/source project Android Studio yang membungkus versi HTML terakhir menjadi aplikasi Android.

Fitur:
- Pilih video dengan menekan area video
- START / STOP / PLAY / RESTART
- Loop video
- Fullscreen
- Pilih audio
- Play/Stop/Loop audio
- Volume video dan audio terpisah
- Tombol Share ke Android share sheet
- Tidak ada kontrol kecepatan video

## Cara membuka
1. Buka folder ini di Android Studio.
2. Tunggu Gradle selesai sinkronisasi.
3. Jalankan pada HP Android atau emulator.

Catatan:
- Tombol Share menggunakan Android ACTION_SEND sehingga aplikasi tujuan seperti TikTok dapat muncul jika terpasang dan menerima video.
- Ini belum membuat virtual camera. Untuk virtual camera/MediaProjection diperlukan implementasi Android native tambahan.
