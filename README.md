## TL;DR
```
cd ~
git clone https://github.com/chatlamin/userside-docker.git
cd userside-docker
sudo mkdir -p /opt/userside /opt/backup
sudo make install

sudo cd /opt/userside
sudo git init
sudo git remote add origin bitbucket.org/zencom/userside.git
sudo git add --all .
sudo git commit -m "ЗДЕСЬ УКАЖИТЕ НОМЕР ВЕРСИИ"
git push -u origin master
```
