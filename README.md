# Gotham: Revived
<img src="https://media.discordapp.net/attachments/1208513216238329916/1249470337490358332/image.png?ex=66676b6e&is=666619ee&hm=d8b789a31b3855ea3ef07b59d249b8f5ddb734cd748ffbfcff3b8347927cb3b1&=&format=webp&quality=lossless&width=1219&height=683" height="50%" width="50%">

Originally made by KiwifruitDev for Batman: Arkham Origins Online: https://github.com/KiwifruitDev/arkham-revived

Custom server authentication for accessing WBID services in Gotham City Impostors

Join the [[Discord]](https://discord.gg/ef62xneQ3s) for support, updates, and matchmaking.

# Requirements
- [Node.js](https://nodejs.org/en/)

# How to use
First off, this is really early alpha, as of now it currently supports logging in with a dummy WBID account. Community Challenges, Digital Camo, and Gangs aren't supported at the moment.

1. Go to your preferred IDE, download the repository and write the following
```
git clone https://github.com/VZPx/gotham-revive.git
cd gotham-revive
npm install
```
2. To start the server
```
node .
```
3. Launch the game normally through steam
4. Launch Cheat Engine, and look for this string 
```
https://cls.psn.turbine.com/cls
```
5. Replace the string with 
```
http://127.0.0.1:8080/CLS
```
6. Once you're in the main menu you should be logged into WBID, showing it as 'WBID Active' with a green light.

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).
