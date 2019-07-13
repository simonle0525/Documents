## Reinstall My Laptop

### Install Fedora 27

- Insert Fedora 27 bootable USB

- Follow the instructions on the screen and **Make yourself as Administrator**

### Install Google Chrome

- Open Firefox browser search for google chrome and install it.


### Git and GitHub setup

- Generate ssh key
```
ssh-keygen -t rsa -b 4096 -C "simonle0525@gmail.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
```

- Config git
```
git config --global user.name "Simon H Le"
git config --global user.email "simonle0525@gmail.com"
git config --list
```

- Sign in into github.com
- Select Settings
- Select SSH and GPG keys
- Select New SSH key
- Copy the content of your workstation machine's ~/.ssh/id_rsa.pub and paste it into the new key
```
vi ~/.ssh/id_rsa.pub
```
- Click on Add SSH key

- Clone My respository
```
git clone 
```



Link: https://fedoramagazine.org/play-minecraft-fedora/

sudo dnf install java-1.8.0-openjdk

Check java:
java -version

Download Minecraft.jar from https://minecraft.net/en-us/download/

mkdir ~/minecraft
cp ~/Download/Minecraft.jar ~/minecraft/

cd ~/minecraft
java -jar Minecraft.jar

Running Minecraft on Ubuntu https://www.lynda.com/articles/running-minecraft-ubuntu-linux

Do this when your done (down there)

                                     cd minecraft/ <- first this one

  			  java -jar Minecraft.jar <-then this one
