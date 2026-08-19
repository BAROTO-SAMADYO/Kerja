# Signature Generator — Windows EXE

Project ini membungkus `Generete Signature SHA.html` menjadi aplikasi Windows portable.

## Cara build tanpa Node.js di laptop kantor

1. Buat repository baru di GitHub.
2. Upload seluruh isi folder project ini, termasuk folder `.github/workflows/build.yml`.
3. Masuk ke tab **Actions**.
4. Pilih **Build Signature Generator EXE**.
5. Klik **Run workflow**.
6. Setelah selesai, buka hasil workflow dan download artifact:
   `Signature-Generator-Windows`
7. Di dalam ZIP artifact terdapat:
   `Signature-Generator.exe`
8. Salin EXE tersebut ke laptop kantor dan double-click.

Node.js hanya digunakan oleh GitHub Actions saat proses build; laptop kantor tidak perlu Node.js.
