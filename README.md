# Setting-up-Apache-web-server

### Im using an Arch VM

### Using pacman, I installed Apache and ufw

```sudo pacman -S apache ufw```

### I configured the firewall to allow traffic through ports 80 and 443

```sudo ufw enable``` ```sudo ufw allow 80``` ```sudo ufw allow 443``` ```sudo ufw reload```

### Started apache and checked that it was working by going through local host in my web browser

### I cloned the files from https://github.com/simon-sass/Cinnamon-Misc.git into /srv/http

### I went back to my local host and played a game of simon says
![Screenshot_20240712_012838](https://github.com/user-attachments/assets/b8266f1d-d844-4e97-ae19-a09e70b16d65)
