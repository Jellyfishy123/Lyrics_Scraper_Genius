### **Contributors:**
@devlocalhost from https://github.com/devlocalhost/pylyrical
<br> Nguyen Tien Dat

### **About:**
I was instructed by my supervisor to scrap the song lyrics for Vietnamese songs. We needed a few hundred songs so it is not feasible to manually download the songs. I found this program and made some changes to it to suit my needs, where I can save the songs as text files into specific folders of the song artist name, instead of just printing them out onto the console.

## **This part below was taken from @devlocalhost on Github and all credit goes to this user.**

## **Setup**

First, you will need to get an **access token** to use pylyrical by [creating a client](https://genius.com/api-clients), clicking **Generate Access Token** and copying the token. After that, you will need to paste it on line 15 on the "pylyrical.py" file. (*you need to replace "S3CR3T0K3N" of course*)

Then you will need to install:

1. [rich](https://github.com/willmcgugan/rich)
2. [requests](https://pypi.org/projects/requests/)
3. and [bs4](https://pypi.org/projects/beautifulsoup4/)

You can install them by opening a terminal window, and typing **pip3 install bs4 requests rich**

After that, you will need to git clone this module (git clone https://github.com/devlocalhost/pylyrical.git), then you will need to change your directory to pylyrical, and run the python file


