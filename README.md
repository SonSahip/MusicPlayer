<h1 align= center><b>⭐️ Sahip Music Player ⭐️</b></h1>
<h3 align = center>  Python ile yazılmıştır.
<p align="center">
    ✨ <a name="features"></a>Features

### ⚡️ Hızlı ve Hafif

Girişlerinizi indirirken ve dönüştürürken yayınlamaya başlar. Ayrıca o
üretim dosyaları yapmaz.

### 👮🏻‍♀️ Güvenli ve kullanışlı

Kontrol ve hassas komutları yöneticilerle sınırlar.

### 🗑 Temiz ve spam ücretsiz

Sohbetlerinizi temiz tutmak için eski çöplerini siler.

### 😎 
Harika kontrolleri var

İstediğiniz zaman akış modunu değiştirmenize, döngüye almanıza, duraklatmanıza, devam ettirmenize, sesini kapatmanıza, sesini açmanıza olanak tanır.

### 🖼 Harika küçük resimleri var
Response your commands with cool thumbnails on the chat.

### 😉 Ne istersen onu yayınlar

Ses veya video dosyalarını, YouTube videolarını istediğiniz süre boyunca yayınlayabilirsiniz,
YouTube canlıları, YouTube oynatma listeleri ve hatta radyolar veya m3u8 bağlantıları veya içindeki dosyalar gibi özel canlı akışlar.
barındırıldığı yer!

### 📊 
Birden fazla yerde akışlar
Aynı anda birden fazla sohbette farklı şeyler yayınlamanıza izin verir. Her biri
sohbetin kendi şarkı sırası olacaktır.

### 🗣 Farklı diller konuşur

Müzik Çalar çok dillidir ve [çeşitli dilleri](#diller)  konuşur,
çevirmenlere teşekkürler.

## 🚀 <a name="deploy"></a>Deploy

[![Deploy on Heroku](https://www.herokucdn.com/deploy/button.svg)](https://deploy.safone.tech)

Note: `Önce Repo'yu Çatallayın Sonra Heroku Düğmesine Dağıt'a tıklayın!`


## ☁️ <a name="self_host"></a>Self Host

- Legecy Method
```bash
$ git clone https://github.com/SonSahip/MusicPlayer
$ cd MusicPlayer
$ sudo apt install git curl python3-pip ffmpeg -y
$ pip3 install -U pip
$ curl -sL https://deb.nodesource.com/setup_16.x | sudo -E bash -
$ sudo apt install -y nodejs
$ sudo apt install build-essential
$ sudo npm install pm2@latest -g
$ pip3 install -U -r requirements.txt
$ cp sample.env .env
# < edit .env with your own values >
$ python3 main.py
```

- Docker Build Method
```bash
$ git clone https://github.com/SonSahip/MusicPlayer
$ cd MusicPlayer
$ cp sample.env .env
# < edit .env with your own values >
$ sudo docker build . -t musicplayer
$ sudo docker run musicplayer
```

## ⚒ <a name="configs"></a>Configs

- `API_ID`: Telegram app id from https://my.telegram.org/apps.
- `API_HASH`: Telegram app hash from https://my.telegram.org/apps.
- `SESSION`: Pyrogram string session. You can generate from [here](https://replit.com/@AsmSafone/genStr).
- `SUDOERS`: ID of sudo users (separate multiple ids with space).
- `BOT_TOKEN`: Telegram bot token from https://t.me/botfather. (optional)
- `QUALITY`: Custom stream quality (high/medium/low) for the userbot in vc. Default: `high`
- `PREFIX`: Bot commad prefixes (separate multiple prefix with space). Eg: `! /`
- `LANGUAGE`: An [available](#languages) bot language (can change it anytime). Default: `en`
- `STREAM_MODE`: An stream mode like audio or video (can change it anytime). Default: `audio`
- `ADMINS_ONLY`: Put `True` if you want to make /play commands only for admins. Default: `False`
- `SPOTIFY_CLIENT_ID`: Spotify client id get it from [here](https://developer.spotify.com/dashboard/applications). (optional)
- `SPOTIFY_CLIENT_SECRET`: Spotify client secret get it from [here](https://developer.spotify.com/dashboard/applications). (optional)


## 📄 <a name="commands"></a>Commands

Konutlar | Açıklamalar
:--- | :---
• !ping | yaşayıp yaşamadığını kontrol et
• !start / !help | Komutlar için yardımı göster
• !mode / !switch | Akış modunu değiştirin (ses/video)
• !p / !play [şarkı adı veya youtube bağlantısı] | Bir şarkıyı vc'de çal, zaten çalıyorsa sıraya ekle
• !radio / !stream [radyo url'si veya akış bağlantısı] | Play a live stream in vc, if already playing add to queue
• !pl / !playlist [playlist link] | Tüm youtube oynatma listesini aynı anda oynatın
• !skip / !next | Bir sonraki şarkıya geç
• !m / !mute | Akışı sustur
• !um / !unmute | Sustarılan akşı devam ettir.
• !ps / !pause | Akışı durdur
• !rs / !resume | Duraklatılmış akışı devam ettir
• !list / !queue | Sıradaki şarkıları göster
• !mix / !shuffle | Sıraya alınmış çalma listesini karıştır
• !loop / !repeat | Döngü modunu etkinleştirin veya devre dışı bırakın
• !lang / language [dil kodu] | Bot dilini grupta ayarlayın
• !ip / !import | Dışa aktarılan dosyadan sırayı içe aktar
• !ep / !export | Gelecekte içe aktarmak için kuyruğu dışa aktarın
• !stop / !leave | vc'den ayrıl ve kuyruğu temizle
• !update / !restart | Müzik çalarınızı güncelleyin ve yeniden başlatın
## 🗣 <a name="languages"></a>Languages

```text
en    English
tr  ✖️ Turkey( Closed / Kapalı)
```

## 🛫 <a name="supports"></a>Supports

Yakında Açılacaktır / Coming Soon
## ✨ <a name="credits"></a>Credits

- [Me](https://t.me/sonsahip) for [Noting](https://github.com/SonSahip/MusicPlayer) 😬
