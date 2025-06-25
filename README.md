# WebSequencer

Bu proje, modern bir MIDI sequencer web uygulamasıdır. Sadece HTML, CSS (Tailwind ile) ve JavaScript kullanır. Herhangi bir ek derleme veya bağımlılık gerektirmez.

## Kurulum ve Çalıştırma

1. **Dosyaları İndir:**
   - `index.html` dosyasını bu klasöre kaydedin.

2. **Çalıştırma:**
   - `index.html` dosyasına çift tıklayarak veya bir tarayıcıda açarak uygulamayı kullanabilirsiniz.
   - Alternatif olarak, bir terminalde bu klasöre gelip basit bir sunucu başlatabilirsiniz:
     - Python ile:
       ```sh
       python -m http.server 8000
       ```
     - Node.js ile (http-server yüklüyse):
       ```sh
       npx http-server .
       ```
   - Ardından tarayıcınızda `http://localhost:8000` adresine gidin.

## Özellikler
- Modern ve responsive arayüz
- Piano roll ve zaman çizelgesi
- Sürükle-bırak ile nota düzenleme
- Track ayarları ve efektler
- Tamamen istemci tarafında çalışır

## Gereksinimler
- Modern bir web tarayıcısı (Chrome, Firefox, Edge, Safari)

## Notlar
- Tüm stiller ve ikonlar CDN üzerinden yüklenir, ek kurulum gerekmez.
- Geliştirme için kodu dilediğiniz gibi düzenleyebilirsiniz. 