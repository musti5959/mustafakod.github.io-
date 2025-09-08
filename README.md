# Profesyonel Terfi Sistemi (Node-RED)

Bu depo, bir terfi istasyonunun temel izleme fonksiyonlarını gösteren Node-RED örnek projesini içerir. Flow, sistem ayarlarını başlatır ve örnek bir istasyon için seviye ile motor durumunu rastgele üretip debug paneline yazar.

## Kurulum

1. Node.js ve Node-RED'i yükleyin:
   ```bash
   npm install -g node-red
   ```
2. Node-RED'i başlatın:
   ```bash
   node-red
   ```
3. Tarayıcınızda [http://localhost:1880](http://localhost:1880) adresine gidin.
4. **Import** menüsünden `flows.json` dosyasını yükleyin.
5. Deploy ettikten sonra debug panelinde simülasyon verilerini izleyebilirsiniz.

## Dosyalar

- `flows.json`: Profesyonel terfi sistemi için Node-RED flow'u.
- `index.html`: Örnek HTML sayfası.
