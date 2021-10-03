# Brawl Stars v30

Brawl Stars v30.242 server emulator written in Python.

![ScreenShot](https://cdn.discordapp.com/attachments/874296198775853117/889128606113087488/Screenshot_20210919-153522_BS_v30.jpg) 

### Requirements:
- Python 3.7 or higher
- pymongo
- dnspython
- colorama

### MongoDB configuration
First you'll need to put your MongoDB connection string in `config.json`. If you don't know how to get it here's a quick tutorial: https://imgur.com/a/oXI34dA

### Running the server
In a terminal, type __`pip install -r requirements.txt`__ then run the server using __`python Main.py`__

### Configuring the client app
To connect to your server, a **patched client** is required. Download this [base APK](https://disk.yandex.ru/d/2caY4h8uzP8CiA) and change the IP in `libmg.config.so`. 
### Battles
We've enabled offline battles so you can directly press "PLAY" to start a match.
![ScreenShot](https://cdn.discordapp.com/attachments/874296198775853117/889128606926794752/Screenshot_20210919-153549_BS_v30.jpg) 
Unfortunately, the offline logic is mostly broken and some gamemodes might not work correctly.

### Got any question?
Contact @ShockWave#5158 on Discord or open an issue.
