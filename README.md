# WhatsSender

## Share WhatsApp Status Audio Like a Pro 😎

**Install Termux**

[Download](https://github.com/termux/termux-app/releases/download/v0.119.0-beta.1/termux-app_v0.119.0-beta.1+apt-android-7-github-debug_universal.apk)


*Open Termux and enter this commands*

```bash
pkg update
pkg upgrade
```

*Then Install Git*

```bash
pkg install git
```

*install ffmpeg*

```bash
pkg install ffmpeg
```

*install nodejs*

```bash
pkg install nodejs
```

*git clone*

```bash
git clone https://github.com/SafwanGanz/WhatsSender
```

*Open WhatsSender*

```bash
cd WhatsSender
```

*Install dependencies*

```bash
npm install
```

## Prepare Files

1. Go to your file manager.


2. Create a new folder named Notes in the root directory.


3. Add an MP3 file (e.g., song.mp3) to the Notes folder.



## Upload a Voice Note to WhatsApp Status

1. Open WhatsApp and turn off your internet connection or WiFi.


2. Upload a voice note as a status.

## Run WhatsSender

Back in Termux, run:
```bash
node index.js
```


Note:
Do not turn on the internet before you see the success message in Termux.
