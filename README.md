# **mp3-download-script**
This is a python script that uses a specific python package **youtube-dl**. It will download the audio file from any video/audio link provided during the execution of the program, and if necessary converts it to **.mp3** format of high quality.
___

## **Table Of Contents**
1.  [General](#General)
2.  [Options](#Options)
2.  [Customizing](#Customizing)
3.  [Authors](#Authors)
4.  [Acknowledgement](#Acknowledgement)
***



<a name="General"></a>
## General

*   The system must have **python** installed and set to the global path. _(downlaod [python](https://www.python.org/downloads/) as per your Operating System. **check** the 'Add Python to system PATH' option while installing)_

*   Download the **mp3-download-script** folder from [here](https://github.com/poseidon-code/mp3-download-script/archive/master.zip "mp3-download-script").

*   Open up **cmd** (**terminal** for Linux/macOS).

*   **cd** into the directory where you have downloaded the **mp3-download-script** folder.

    _**otherwise** if your **DEFAULT** Downloads location is C:\Users\YOUR-PC-NAME\Downloads (as of most Windows PC), then write this in **cmd**._
    ```cmd
    C:\Users\YOUR-PC-NAME> cd downloads\mp3-download-script
    C:\Users\YOUR-PC-NAME\Downloads\mp3-download-script>
    ```
* Copy the video URL that you want to download. _e.g.: https://www.youtube.com/watch?v=U2NN3tmCVI8_

*   While inside the **mp3-download-script** directory, run the `python mp3.py` command:

    ```cmd
    C:\Users\YOUR-PC-NAME\Downloads\mp3-download-script> python mp3.py
    ```
    and paste the URL _(mouse right-click)_: 

    ```cmd
    C:\Users\YOUR-PC-NAME\Downloads\mp3-download-script> python mp3.py https://www.youtube.com/watch?v=U2NN3tmCVI8
    ```

    you can add multiple URLs _(just add space between URLs)_:

    ```cmd
    C:\Users\YOUR-PC-NAME\Downloads\mp3-download-script> python mp3.py https://www.youtube.com/watch?v=U2NN3tmCVI8 https://www.youtube.com/watch?v=kddC4gi72UE
    ```

    then press **Enter**.

*   All the files will be downloaded to the **DEFAULT** Downloads location :  _C:\Users\YOUR-PC-NAME\Downloads (as of most Windows OS)_

*   You are GOOD NOW 😊
---


<a name="Options"></a>
## Options


---


<a name="Customizing"></a>
## Customizing

Various options of downloading can be added directly to the **mp3.py** script. To add custom options, follow these steps _(make sure **python** is installed in your system & PATH is set)_:

*   Open **mp3.py** with a suitable text editor.
*   Press **Ctrl + F** or start **Find** feature of your editor and search for **" OPTIONAL "**.
*   Under **OPTIONAL** you can add multitude of Custom Options to make your script unique.
*   Enter your desired options by adding a ' **,** ' _(comma)_ at the end of every option you add.
*   The list of all options that can be added are found [here](#Options).

---


<a name="Authors"></a>
## Authors

*   _Creator of **mp3-download-script**_ : [poseidon-code](http://poseidon-code.github.io/portfolio)
*   _Creator of **youtube-dl** library_ : [ytdl-org](http://www.github.com/ytdl-org)
*   _Creator of **ffmpeg** converter_ : [ffmpeg Team](http://ffmpeg.org)
---


<a name="Acknowledgement"></a>
## Acknowledgement

***