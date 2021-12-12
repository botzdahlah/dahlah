<p align="left">
	<img src="https://user-images.githubusercontent.com/93814760/145718289-6aa56b68-14a1-4f3a-ab65-7178b1d0e7fe.jpeg" width="35%" style="margin-left: auto;margin-right: auto;display: block;">
</p>
<h1 align="left">Bot-WhatsApp</h1>

Note: Untuk sementara repo ini belum mendapatkan update dari versi RLP-BOT terbaru. Silahkan tunggu hingga repo ini menerima beberapa update.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/FadliDarmawan/haruno)

[![Run on Repl.it](https://repl.it/badge/github/FadliDarmawan/haruno)](https://repl.it/github/FadliDarmawan/haruno)

[![Grup WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://chat.whatsapp.com/LIX42RUhLi15MBXhfvrF6K)

# RLP-BOT
rlp-bot adalah bot whatsapp hasil pe-nggarapan ulang dari ariffb25/stikerinbot yang sudah di edit agar bisa di jalankan di termux.
Rlp-bot juga dapat di jalankan di RPP/VPS/Windows, Heroku, Replit.

# Termux
```
apt install ffmpeg
apt install imagemagick
apt install nodejs
apt install git
git clone https://github.com/Laksmana27/rlp-bot
cd rlp-bot
npm i
node . (option)
````

# RDP/VPS/Windows
* Unduh & Instal Git [`Klik Disini`](https://git-scm.com/downloads)
* Unduh & Instal NodeJS [`Klik Disini`](https://nodejs.org/en/download)
* Unduh & Instal FFmpeg [`Klik Disini`](https://ffmpeg.org/download.html) (**Jangan Lupa Tambahkan FFmpeg ke variabel lingkungan PATH**)
* Unduh & Instal ImageMagick [`Klik Disini`](https://imagemagick.org/script/download.php)
```
git clone https://github.com/Laksmana27/rlp-bot
cd rlp-bot
npm i
node . (option)
```
# Replit
[![Run on Repl.it](https://repl.it/badge/github/Laksmana27/rlp-bot)](https://repl.it/github/Laksmana27/rlp-bot)
* Klik button
* Buka console
```
npm i
node . (option)
```
# Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Laksmana27/rlp-bot)

*install buildpack
* heroku/nodejs
* https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git
* https://github.com/DuckyTeam/heroku-buildpack-imagemagick.git

# Option

## Arguments `node . [--options] [<session name>]`

#### Contoh: `node . --self --restrict --autoread`

### `--self`

Aktifkan mode self (Mengabaikan yang lain)

### `--prefix <prefixes>`

* `prefixes` dipisahkan oleh masing-masing karakter
Setel awalan

### `--server`

Digunakan untuk [heroku](https://heroku.com/) atau pindai melalui situs web

### `--db <json-server-url>`

Gunakan db eksternal alih-alih db lokal, 
Contoh Server `https://json-server.nurutomo.repl.co/`
Code: `https://repl.it/@Nurutomo/json-server`

`node . --db 'https://json-server.nurutomo.repl.co/'`

Server harus memiliki spesifikasi seperti ini

#### GET

```http
GET /
Accept: application/json
```

#### POST

```http
POST /
Content-Type: application/json

{
 data: {}
}
```

### `--big-qr`

Jika qr unicode kecil tidak mendukung

### `--restrict`

Mengaktifkan plugin terbatas (yang dapat menyebabkan nomor Anda **diblokir** jika digunakan terlalu sering)

* Administrasi Grup `add, kick, promote, demote`

### `--img`

Aktifkan pemeriksa gambar melalui terminal

### `--no autoread`

Jika diaktifkan, semua pesan masuk tidak akan ditandai sebagai telah dibaca

### `--nyimak`

Tidak ada bot, cukup cetak pesan yang diterima dan tambahkan pengguna ke database

### `--test`

**Development** Testing Mode

### `--trace`

```js
conn.logger.level = 'trace'
```

### `--debug`

```js
conn.logger.level = 'debug'
```

---------

 [![Nurutomo](https://github.com/Nurutomo.png?size=100)](https://github.com/Nurutomo) | [![Ariffb](https://github.com/ariffb25.png?size=100)](https://github.com/ariffb25) | [![Laksmana.27](https://github.com/Laksmana27.png?size=100)](https://github.com/Laksmana27)
----|----|----
[Nurutomo](https://github.com/Nurutomo) | [Ariffb](https://github.com/ariffb25) | [Laksmana.27](https://github.com/Laksmana27)
 Penulis / Pencipta | Penulis ulang | Pengembang ulang
