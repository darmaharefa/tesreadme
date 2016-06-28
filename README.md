Tweet Analysis Express Js + MongoDB

  [![NPM Version][npm-image]][npm-url]
  [![NPM Downloads][downloads-image]][downloads-url]
  

```js
var express = require('express')
var app = express()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)
```
## Demo
Untuk [demo](http://ngitwologic-67563.onmodulus.net/) 
, kami menggunakan [modulus](https://modulus.io/) sebagai hosting project nodejs kami

## Website Repo
[https://github.com/darmaharefa/-Nodejs-funfind-tags](https://github.com/darmaharefa/-Nodejs-funfind-tags)

## Cara Menjalankan Project

Clone repository
```bash
$ git clone https://github.com/darmaharefa/-Nodejs-funfind-tags.git ngitwologi
```

Masuk ke directory project
```bash
$ cd ngitwologi
```

Jalankan Aplikasi
```bash
$ node app.js
```

Buka browser dan arahkan ke 
```bash
localhost:3000
```

## Fitur (user)

/login
  * Login dengan akun twitter
  * Set Cookie ke browser

/dashboard
  * Menampilakn info user dari twitter
  * Menampilakn User Timeline
  * Menampilkan Home Timeline

/profile
  * Menampilkan user profile (follower, following, images, background-img, follower ratio, etc)
  * Menampilkan perhitungan user mention, replay, hastag, retweet, etc
  * Menampilkan analisis tweet per bulan
  * Menampilkan analisis tweet per hari
  * Menampilkan list url yang pernah digunakan
  * Menampilkan list hastag yang pernah digunakan
  * Menampilkan user mention yang pernah digunakan

/account
  * Menampilakn info akun ngitwologi dari user

/premium 
  * Fitur untuk request akun upgrade ke premium

/logout 
  * Destroy cookie di browser


## Fitur (admin)

/alogin
  * Login dengan username "weareadmin", password "weareadmin"
  * Set Cookie ke browser

/weareadmin
  * Menampilakn info user yang pernah menggunakan aplikasi
 
/logout 
  * Destroy cookie di browser

## Database
Untuk database, kami menggunakan [mlab](https://mlab.com/)
untuk login ke database, bisa menggunakan akun berikut :
username : weareadmin
password : weareadmin123


[npm-image]: https://img.shields.io/npm/v/express.svg
[npm-url]: https://npmjs.org/package/express
[downloads-image]: https://img.shields.io/npm/dm/express.svg
[downloads-url]: https://npmjs.org/package/express
