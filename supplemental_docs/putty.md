# Logging onto CHPC from a Windows PC

You need to download two different softwares

### Downloads

1. [Putty](https://putty.org/)
1. [Xming](https://sourceforge.net/projects/xming/)

![](./images/putty.png)
![](./images/putty2.png)

<hr>

![](./images/xming.png)



### Run Xming
In the search or start menu, run Xming. Note: this doesn't open a program window, but it does put an xming logo in the bottom right corner of your computer.

### Open Putty to log onto CHPC computers
Open Putty. It should look like this...
![](./images/putty3.png)


Enable x11 forwarding (this is why we needed to install Xming first)
![](./images/putty4.png)

Back on the session section, type in `meteo07.chpc.utah.edu`. Also, name the session something like `meteo07`. Click `save`.
![](./images/putty5.png)

Now click `Open`.

When it asks for host keys, select `yes`.
![](./images/putty7.png)

Enter your uNID and your password.

You are now in the linux terminal. If you installed and are running Xming, you should also be able to use gedit to edit files.

