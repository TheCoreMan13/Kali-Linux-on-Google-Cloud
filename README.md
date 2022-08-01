# Kali-Linux-on-Google-Cloud

- sudo apt-get update
- sudo apt-get upgrade -y

Add the "kali-rolling" repository to your sources.
-  echo "deb http://http.kali.org/kali kali-rolling main non-free contrib" | sudo tee /etc/apt/sources.list

Download the repository's key for the system to verify Kali Linux packages and add it with apt-key.
- curl https://archive.kali.org/archive-key.asc | sudo apt-key add

Update again. The new "kali-rolling" repository should be recognised
- sudo apt update

# Install all the things

The "kali-linux-default" package contains all the tools in a standard Kali Linux distribution.
- sudo apt install kali-linux-default

Once done, you need to install a desktop environment. The preferred desktop environment for Kali Linux is Xfce.
- sudo apt install kali-desktop-xfce

Finally, you need to install Xrdp. This will allow you to access and interact with the GUI via Remote Desktop Protocol (RDP).
- sudo apt install xrdp

Create a username
- sudo adduser (name of the username)

- sudo adduser (name of the username) sudo

- reboot

- Enjoy! 
