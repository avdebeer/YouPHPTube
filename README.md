# NO NONSENSE INSTALL GUIDE

git clone https://github.com/avdebeer/YouPHPTube.git

sudo docker build -t youphptube YouPHPTube

Successfully tagged youphptube:latest


```
# LOCAL CHANGES
1. Brute Force subtitles. Manually add a file of the format:\<base file name\>.\<type\>.\<lang\>.vtt <BR>
    Where: <BR> 
    \<base file name\> = The file name of the video you want subtitles for, minus its extension. <br>
    \<type\> = The type of subtitle, either "subs" or "chap" or "desc". <br>
    \<lang\> = The language code, eg, 'en' = English. <br><br>
    The player will then find these and automatically make them available.  There is no way currently to add these through the web interface.  They need to be added manually through the file system, and they need to live with your video files.

### Mobile APP 
Android: https://play.google.com/store/apps/details?id=mobile.youphptube.com
