# AFSÜ Gazi Turgut Aslan Konferans Salonu — Etkinlik Talep Sitesi

afsu.com.tr'de yayınlanan talep formu ve yönetim paneli.

- `index.html` → https://afsu.com.tr/ (talep formu)
- `yonetim/index.html` → https://afsu.com.tr/yonetim/ (yönetim paneli)
- `.cpanel.yml` → cPanel Git Version Control ile `public_html`'e dağıtım

Veriler bu depoda değil; Google Apps Script (Code.gs) üzerinden Google E-Tablo ve Drive'da tutulur.
Sitenin bağlandığı adres `index.html` içindeki `var API = '…/exec'` satırındadır.

## Güncelleme
1. Değişiklikleri bu depoya gönderin (push).
2. cPanel → Git™ Version Control → depo → **Manage** → **Pull or Deploy**
   → **Update from Remote**, ardından **Deploy HEAD Commit**.
