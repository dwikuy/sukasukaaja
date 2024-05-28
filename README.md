## SUKASUKAAJA Bot

### Ikhtisar
Bot ini dirancang untuk berinteraksi dengan..................................................................................................................................................................................................

### Persyaratan
- Telegram Desktop atau Web Telegram
- Node.js terinstal di sistem Anda

### Instruksi Pengaturan

#### Langkah 1: Ambil Access Token
1. **Aktifkan Webview Inspecting**
    - Untuk Telegram Desktop:
        1. Buka `Settings`.
        2. Pilih `Advanced`.
        3. Buka `Experimental settings`.
        4. Aktifkan `Webview inspecting`.

2. **Akses Bot Gamee**
    - Buka bot gamee nya di Web Telegram.

3. **Buka Developer Tools**
    - Tekan `F12` atau `CTRL + SHIFT + I` untuk membuka developer tools (devtools).

4. **Inspeksi Aktivitas Jaringan**
    - Pilih tab `Network` di devtools.
    - Aktifkan `Preserve log`.
    - Bersihkan data jaringan yang ada untuk kejelasan.

5. **Refresh Halaman Bot Gamee**
    - Refresh halaman bot Gamee.

6. **Tangkap Data yang Diperlukan**
    - Cari `fetch/xhr` di aktivitas jaringan.
    - ![cari_xhr](https://github.com/dwikuy/sukasukaaja/assets/58757890/2efd46bd-aed6-411c-8a21-8a9cbe4cde4c)

    - Ambil `x-install-uuid` di paling bawah.
    - ![header](https://github.com/dwikuy/sukasukaaja/assets/58757890/ca33055b-1809-4625-ad21-643e49a4bea4)

    - ke payload dan cari `initData` terus lu copy.
    - ![init](https://github.com/dwikuy/sukasukaaja/assets/58757890/b60a4aed-32c3-4b71-bc18-4a23b83f4ff3)

    - Simpan di `loot.txt` dengan format: `initData|x-install-uuid`.
      

#### Langkah 2: Kloning Repository dan Instal Dependensi
```sh
git clone https://github.com/dwikuy/sukasukaaja
cd sukasukaaja
npm install
```

#### Langkah 3: Jalankan Bot
```sh
node index.js / npm start
```
![image](https://github.com/dwikuy/sukasukaaja/assets/58757890/9c7eb9f7-d29a-4534-b0d6-a4c6ed4fe7b8)

### Penggunaan
1. Pastikan `loot.txt` berisi nilai `initData` dan `x-install-uuid` yang benar.
2. Jalankan bot menggunakan perintah yang telah disediakan di atas.

### CONSOLE LOG EMG JELEK, YG PENTING WORK ................................................
