# Bookshelf-API
Dokumentasi pembuatan bookshelf API pada pembuatan aplikasi Back-End untuk pemula menggunakan framework hapi.js.


sebetulnya pada file ini sudah bisa langsung digunakan atau dijalankan.
namun jika ingin update terbaru dari node.js, hapi.js dan nanoid anda bisa menginstall dengan panduan berikut.

1. hapus node_modules, package.json, package-lock.json dan eslintrc.json.
2. instal ulang node js dengan instalasi (npm init --y)
3. instal framework hapi.js dengan instalasi (npm install @hapi/hapi)
3. instal Eslint dengan instalasi (npm install --save-dev eslint)
 3.1 membuat file pada folder dengan nama .eslintrc.js dengan kode sebagai berikut :
          module.exports = {
        extends: [
          'eslint:recommended',
          'plugin:hapi/recommended',
        ],
        parserOptions: {
          ecmaVersion: 'latest',
          sourceType: 'module',
        },
      };
4. instal nanoid untuk mengenerate id secara acak dengan instalasi (npm i nanoid)
5. buat file src sebagai resource dan buat file dengan nama : server.js, routes.js, handler.js, dan books.js
6. masukan kode yang ada pada repository ini
7. jalankan kode dengan cara (npm run start)
8. cek dengan metode CRUD pada POSTMAN dengan file yang sudah ada pada repository.
   anda hanya perlu mengImport file colletion dan Environment.
9. lalukkan metode crud untuk menambah,melihat,mengupdaate dan menghapus buku.

anda bisa mengganti Port sesuai dengan kebutuhan anda
