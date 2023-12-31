# Kali Linux on Android Without Root - Installation Guide 📱💻

I had faced numerous challenges and failures while attempting to install Kali Linux on my Android device using various methods. After extensive research and experimentation, I finally discovered a solution that worked reliably. 

This repository provides a step-by-step guide on how to achieve this setup using Andronix, Termux, and Real VNC Viewer.

If you found this guide helpful and appreciate the effort put into creating it, please consider giving this repository a star (⭐) on GitHub. Your support means a lot and will help others discover this resource.

## Prerequisites 🛠️

Before getting started, ensure that you have the following prerequisites:

- An Android device (phone or tablet) with at least 2GB of RAM (4GB or more recommended) 📱
- Sufficient storage space available on your device (around 5GB) 💾
- Android version 10+ 🌐

## Installation Steps 🛠️

### Installing ANDRONIX TERMUX RVNCviewer 📲

[Press Here To Download Andronix](https://play.google.com/store/apps/details?id=studio.com.techriz.andronix&pcampaignid=web_share)

[Press Here To Download Termux](https://play.google.com/store/apps/details?id=com.termux&pcampaignid=web_share)

[Press Here To Download RVNC Viewer](https://play.google.com/store/apps/details?id=com.realvnc.viewer.android&pcampaignid=web_share)

### Open Andronix And Follow Instructions: 💻
Step 1 & 2 :

<div style="text-align: center;"><img src="images/photo1.jpg" style="width: 40%;"> <img src="images/photo2.jpg" style="width: 40%;"></a></div> 

Step 3 & 4 :

<div style="text-align: center;"><img src="images/photo3.jpg" style="width: 40%;"> <img src="images/photo4.jpg" style="width: 40%;"></a></div> 

Last Step :

<div style="text-align: center;"><img src="images/photo5.jpg" style="width: 40%;"></a></div> 
<hr>

### Open Termux And Follow Instructions: 💻

1. Open Termux and Paste the code you copied and press enter (You Have To be online for this to work)
   (If you see any prompts, press enter key to choose the defaults)
2. Once its downloading and setting up linux, it'll start running the vnc server (PORT 5901 localhost)
3. Provide a password for the vnc server
4. You can Start VNC server by:
   
```bash
$ vncserver-start
```
5. You can Stop VNC server by running:
```bash
$ vncserver-stop
```
(You may need to run this command to start os after stopping and exiting)
```bash
$ ls 
$ ./start-kali.sh 
```
<hr>

### Open VNC viewer And Follow Instructions: 💻

1. Press On the + in the corner down
2. Enter Address and Name It Whatever you want
```bash
127.0.0.1:5901
```
3. Then Press connect to establish connection with server
4. Type the Password you set earlier
5. And Now You're Done , Congrats !!
!! Consider giving this repository a star , if you found it helpful (⭐) !!

## Troubleshooting 🛠️

If you encounter any issues during the installation or usage of Kali Linux on your Android device, please refer to the troubleshooting guide in this repository for common solutions to known problems.

## Contributing 🤝

Contributions to this repository are welcome. If you have any improvements, bug fixes, or additional documentation to contribute, please fork this repository and submit a pull request.
