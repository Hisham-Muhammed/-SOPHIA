# Sophia
Simple whatsapp bot | Reedited from whatsasena 


<div align="center">
  <img border-radius: 15px src="https://i.imgur.com/1CjbIG8.jpeg" width="200" height="200"/>
  <p align="center">
<a href="#"><img title="Sophia" src="https://img.shields.io/badge/Sophia-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
  <p align="center">
<a href="https://github.com/Hisham-muhammed"><img title="Author" src="https://img.shields.io/badge/Author-hisham-muhammed/Sophia?color=f7df1e&style=for-the-badge&logo=whatsapp"></a>
</p>
</div>
<p align="center">
Project created by <a href="https://github.com/Hisham-Muhammed/Sophia-Mwol">Hisham-muhammed</a> to make it public
    <br>
       | Â© |
        Reserved |
    <br> 
</p>

----

  <p align="center">
  <a href="httsp://github.com/ameer-kallumthodi/pikachu">
    <img src="https://img.shields.io/github/repo-size/Hisham-muhammed/Sophia?color=green&label=Repo%20total%20size&style=plastic">
<p align="center">
<a href="https://github.com/ameer-kallumthodi/followers"><img title="Followers" src="https://img.shields.io/github/followers/Hisham-muhammed?color=f7df1e&style=flat-square"></a>
<a href="https://github.com/ameer-kallumthodi/pikachu/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/Hisham-muhammed/Sophia-1?color=f7df1e&style=flat-square"></a>
<a href="https://github.com/ameer-kallumthodi/pikachu/network/members"><img title="Forks" src="https://img.shields.io/github/forks/Hisham-muhammed/sophia-1?color=f7df1e&style=flat-square"></a>
<a href="https://github.com/ameer-kallumthodi/pikachu/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/Hisham-muhammed/Sophia-1?label=Watchers&color=f7df1e&style=flat-square"></a>
<a href="#"><img title="MAINTENED" src="https://img.shields.io/badge/UNMAINTENED-YES-f7df1e.svg"</a>
</p>

<h3 align="center">Contact Me:</h3>
<p align="center">
<a href="https://instagram.com/hisham___muhammed__?utm_medium=copy_link" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/instagram.svg" alt="kyrie.baran" height="30" width="40" /></a>
</p>
<h4 align="center">Support Video For Deploy Bot ðŸ‘‡:</h4>
<p align="center">
<a href="https://youtu.be/JzTpSfw6jcM" target="blank"><img align="center" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/Logo_of_YouTube_%282015-2017%29.svg/1200px-Logo_of_YouTube_%282015-2017%29.svg.png" height="45" width="90" /></a>
</p>
  

<div align="center">
<p align="center">&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=Hisham-muhammed&show_icons=true&theme=nightowl" alt="Hisham-muhammed" /></p>

<p align="center"><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=Hisham-muhammed&theme=nightowl" alt="Hisham-muhammed" /></p>
</details> </div>


## ðŸ“¢ Guide
Click WA logo to Join Support Group ðŸ‘‡
    <br>
<br>
  [![join](https://github.com/Alien-alfa/PublicBot/blob/main/wlogo.svg.png)](https://chat.whatsapp.com/CYGahR3hC1DHq44n4ri5J6)

## 
  <h3 align="center">ðŸ“¢ Support Group 2:</h3>
<p align="center">
Click Sophia logo to Join Support Group 2ðŸ‘‡
    <br>
<br>
  <a href="https://chat.whatsapp.com/Kne4KggCeYoE9vIc6iZLZJ" target="blank"><img align="center" src="https://i.imgur.com/1CjbIG8.jpeg" alt="kyrie.baran" height="200" width="200" /></a>
</p>
    
## Setup
<div align="center">

  ### Simple Method
  
[![Run on Repl.it](https://repl.it/badge/github/quiec/whatsAlfa)](https://replit.com/@ichu786780/SOPHIA)

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Hisham-Muhammed/-SOPHIA.git)
     </div>
<br>
<br >
If Repl.it not working Try Termux for Qr scanning.Just Copy the Link Below in Termux
```
bash <(curl -L https://t.ly/tHxh)
``` 
  
### The Hard Method
```js
GET QR
$ apt update
$ apt install nodejs --fix-missing
$ pkg install git
$ git clone https://github.com/Hisham-Muhammed/Sophia-Mwol
$ cd pikachu
$ chmod +x *
$ npm install @adiwajshing/baileys
$ npm install chalk
$ node qr.js
```
      
```js
SETUP
$ git clone https://github.com/Hisham-Muhammed/Sophia-Mwol
$ cd Sophia-Mwol
$ chmod +x *
$ npm install @adiwajshing/baileys
$ node qr.js
   // scan the qr using whatsapp web on your phone
$ node bot.js
```


### âš ï¸ Warning! 
```
Due to Userbot; Your WhatsApp account may be banned.
This is an open source project, you are responsible for everything you do. 
Absolutely, Asena executives do not accept responsibility.
By establishing the Asena, you are deemed to have accepted these responsibilities.
```
### thanks for your help and support guys
    `saidalli, amal ser, Afnan sir, karthik, lyf, farhan, ihsan, hyper, muhsin, sahal, cherry 🥰🥰, plk`

### when forking 
```
 If you want add bgm (voice auto reply),sticker (auto reply)

 create 3 files name them bgmone,bgmtwo,stick
 upload your mp3/sticker to created folder

 open plugins/filter.js , change path    
     for bgm one 
        change line 133 in filter.js to 

          await message.client.sendMessage(message.jid, fs.readFileSync('./bgmone/' + a + '.mp3'), MessageType.audio, { mimetype: Mimetype.mp4Audio, quoted: message.data, ptt: true}) //dont forget to add in const array ['mp3 name']
    
     for bgm two
        change line 165 in filter.js into

          await message.client.sendMessage(message.jid, fs.readFileSync('./bgmtwo/' + a + '.mp3'), MessageType.audio, { mimetype: Mimetype.mp4Audio, quoted: message.data, ptt: true})  //dont forget to add in const array ['mp3 name']

    for sticker
        change line 193 in filter.js

          await message.client.sendMessage(message.jid, fs.readFileSync('./stick/' + a + '.mp3'), MessageType.audio, { mimetype: Mimetype.mp4Audio, quoted: message.data, ptt: true})  //dont forget to add in const array ['sticker name']
```

## Developers
  <div align="center">
    
  [![ameer-kallumthodi](https://github.com/ameer-kallumthodi.png?size=100)](https://github.com/ameer-kallumthodi) |  [![Hisham-Muhammed](https://github.com/Hisham-Muhammed.png?size=100)](https://github.com/Hisham-Muhammed) | [![saidalisaid2](https://github.com/saidalisaid2.png?size=100)](https://github.com/saidalisaid2) 
----|----|----
[ameer-kallumthodi](https://github.com/ameer-kallumthodi)  | [Hisham-Muhammed](https://github.com/Hisham-Muhammed) | [saidalisaid2](https://github.com/saidalisaid2)
Base, Bug Fixes, Modules |Â Modifiying  as   public, Bug Fixes, Modules| Bug Fixes, Modules
  </div>
    


## License
This project is protected by `GNU General Public Licence v3.0` license.

### Disclaimer
`WhatsApp` name, its variations and the logo are registered trademarks of Facebook. We have nothing to do with the registered trademark

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fhisham-Muhammed%2F-SOPHIA&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
