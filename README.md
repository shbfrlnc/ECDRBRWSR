# ECDRBRWSR

ECDRBRWSR adalah aplikasi browser yang dapat diprogram.

Untuk mendownloadnya, kunjungi bagian Releases.

Untuk menjalankannya, ekstrak file zipnya, kemudian jalankan:

```
npm install
```

Kemudian, jalankan:

```
npm run dev // untuk menjalankan aplikasi dengan script plaintext
```

Atau

```
npm run obfuscate
npm run start // untuk menjalankan aplikasi dengan script yang sudah di-obfuscate
```

Untuk mem-build aplikasi ini menjadi installer (aplikasi Windows):

```
npm run obfuscate // obfuscate dulu, karena yang di production bukan dalam bentuk plaintext
npm run dist // build installer, hasilnya ada di ../_Release/ECDRBRWSR
```

Ketika aplikasi ini sudah berjalan, Anda bisa mempelajari penggunaan API-nya melalui menu "Open Examples".
