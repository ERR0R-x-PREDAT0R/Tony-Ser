# <!-- Typing SVG -->
<p align="center">
    <a href="https://git.io/J0hKr">
        <img
        src="https://readme-typing-svg.herokuapp.com?size=30&width=800&lines=Tony-Ser+Is+A+WhatsApp+Bot+By+Alinshan."
            alt="Typing SVG"
        />
    </a>
</p>



<div align="center">
  <img border-radius: 15px src="https://www.linkpicture.com/q/Tony-Ser.jpg" width="200" height="200"/>
  <p align="center">
<a href="#"><img title="Tony-Ser" src="https://img.shields.io/badge/-Tony%20Ser-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
  <p align="center">
<a href="https://github.com/ERR0R-x-PREDAT0R"><img title="Author" src="https://img.shields.io/badge/AUTHOR-ALINSHAN-grey%2Fblue?color=blue&style=for-the-badge&logo=whatsapp">
</p>
  <p align="center"> 
  <a href="https://wa.me/919383491460"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
</p>
</div>
<p align="center">
Project created by <a href="https://github.com/CYBER-DASHAMOOLAN">ALINSHAN</a>
    <br>
       | © |
        Reserved |
    <br> 
</p>


----------

----------

```
Tony Ser - Userbot is Open Source software open to development. 
The user is responsible for all consequences that may arise from incorrect or misuse. 
Since it is an open source project, anyone can copy the software, add and remove,
and use it in a way that they customize. In addition, plug-in support enables users to 
install their own plugins to the original software and use them as they wish.
Using the bot out of purpose will explicitly ban you.
Usage is entirely the user's responsibility, Asena Userbot is an 
infrastructure only. Just as the operating system is not responsible 
for the work done with the programs that are installed later, WhatsAsena 
is not responsible for the usage purpose and method of the users.
Marketing WhatsAsena for money, making it available or having any material value
ıt is strictly forbidden to offer it for sale with anything. All legal investigations that may arise
the user is responsible.
```

## Setup
<div align="center">

  ### Simple Method
  
[![Run on Repl.it](https://repl.it/badge/github/quiec/whatsAlfa)](https://replit.com/@afnanplk/PinkyMwol-QR)
 
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://github.com/ERR0R-x-PREDAT0R/Tony-Ser)   
 
  </div>
 

            
### NO ERROR DEPLOY
            
```
  for easy deploy fork this repo & add the given link in your readme by changing repository link - [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=your repository link here)
```
## F.A.Q
Answer a few frequently asked questions;
### Can you read my messages?
This project is open source so all the codes are clear. Neither less nor more; you can look what you want. **We absolutely do not have access to your accounts.**

### What about our security?
If you are concerned about security, you can install it on your own computer. If you think someone else has captured your data, simply click on **Whatsapp> Three Dots> Whatsapp Web> Logout** from all sessions button.

### Is it paid?
**Of course not.** It will never happen. But you can donate to us. You can reach me via [Telegram](https://t.me/fusuf) .

### ⚠️ Warning! 
```
Due to Userbot; Your WhatsApp account may be banned.
This is an open source project, you are responsible for everything you do. 
Absolutely, Asena executives do not accept responsibility.
By establishing the Asena, you are deemed to have accepted these responsibilities.
```
  
## Developers
  <div align="center">
    
  [![Farhan-Dqz](https://github.com/farhan-dqz.png?size=100)](https://github.com/farhan-dqz) |  [![TOXIC4L!3N](https://github.com/Alien-alfa.png?size=100)](https://github.com/AI-VIKI) | [![afnanplk](https://github.com/afnanplk.png?size=100)](https://github.com/afnanplk) | [![ALINSHAN](https://github.com/ERR0R-x-PREDAT0R.png?size=100)](https://github.com/ERR0R-x-PREDAT0R)
----|----|----|----
[farhan-dqz](https://github.com/farhan-dqz)  | [TOXIC4L!3N](https://github.com/AI-VIKI) | [afnanplk](https://github.com/afnanplk) | [ALINSHAN](https://github.com/ERR0R-x-PREDAT0R)
Base, Bug Fixes, Modules | Modifiying  as   public | Bug Fixes, Modules | Bug Fixes, Modules
  </div>


## License
This project is protected by `GNU General Public Licence v3.0` license.

### Disclaimer
`WhatsApp` name, its variations and the logo are registered trademarks of Facebook. We have nothing to do with the registered trademark
  
### when forking  
```
add your own heroku button
  
  example :
  [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=your repository link here)
  
  change it into your repo link
```
  
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
