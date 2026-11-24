# Kantin Bu Rina (Pembeli + Kasir)

PHP + MySQL (XAMPP) dengan tampilan bergaya game 2D.

## Cara menjalankan
1. Pasang XAMPP, lalu Start **Apache** dan **MySQL**.
2. Salin folder ini ke `C:\xampp\htdocs\kantin-bu-rina`.
3. Import database:
   - phpMyAdmin: http://localhost/phpmyadmin -> tab **Import** -> pilih `database.sql` -> Go.
   - atau cmd: `C:\xampp\mysql\bin\mysql -u root < C:\xampp\htdocs\kantin-bu-rina\database.sql`
4. Buka folder di VS Code (File -> Open Folder).
5. Buka di browser:
   - Pembeli: http://localhost/kantin-bu-rina/
   - Kasir: http://localhost/kantin-bu-rina/kasir.html (PIN awal `1234`, ubah di `api/config.php`)

Jangan buka `index.html` dengan klik dua kali (file://) karena PHP harus lewat Apache.

## Struktur
- `database.sql` : tabel + data contoh
- `api/` : config, kantin, menu, order (pembeli), kasir
- `assets/style.css` : tema game 2D
- `assets/app.js` : halaman pembeli
- `assets/kasir.js` : halaman kasir
