# Kali-On-Android
## Installing kali Linux in android without rooting your device

![download (1)](https://user-images.githubusercontent.com/73324896/129390639-a471a60a-17bf-4af9-baa3-129d8e77a8fe.jpg)
### Kali Linux (formerly known as BackTrack Linux) is an open-source, Debian-based Linux distribution aimed at advanced Penetration Testing and Security Auditing. Kali Linux contains several hundred tools targeted towards various information security tasks, such as Penetration Testing, Security Research, Computer Forensics and Reverse Engineering. Kali Linux is a multi platform solution, accessible and freely available to information security professionals and hobbyists. 

# Now Let's know how to install Kali in Android without rooting your device

## Required Apps

- Termux App
- NetHunter-KeX Client
- Hacker's keyboard

## Do this

- So just go to the playstore and download the required apps which is given.
- So after installing those apps we are now going to install nethumter in termux.
- To install the NetHunter in termux follow the given steps :- 

### Install NetHunter

Now use these commands to install nethunter in Termux

- $ apt update -y
- $ apt upgrade -y
- $ termux-setup-storage
- $ pkg install wget
- $ wget -O install-nethunter-termux https://offs.ec/2MceZWr
- $ chmod +x install-nethunter-termux
- $ ./install-nethunter-termux

### After running all these commands, a window will appear with a big Kali written on it.

### You now need to set password, press enter for that type "Kex password" and press enter.

### Now it will ask you type password of minimum 6 characters, type your password and press enter.

### Now you need to run this command to start kex server "Kex"

### Minimize termux and open Kex client app (which you've downloaded initially) and fill it as shown inn image below

![IMG-20210812-WA0045](https://user-images.githubusercontent.com/73324896/129392578-e5d7806e-5701-4b5e-ad1d-5bcf8837a83f.jpg)

### Enter the password you created in initial steps and click on CONNECT icon.

![Screenshot_2021-08-13-22-18-38-25](https://user-images.githubusercontent.com/73324896/129392882-9262d291-2b93-4dc6-b1fc-04394b768c24.jpg)

# WOOHOO!!! You have successfully installed Kali linux in your Android.
