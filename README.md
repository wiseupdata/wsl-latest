<a href="https://github.com/wiseupdata/wsl-latest">
  <img align="left" alt="Wise Up Data's Instagram" width="22px" src="https://raw.githubusercontent.com/wiseupdata/wsl-latest/main/assets/instagram.png" />   
</a> 
<a href="https://github.com/wiseupdata/wsl-latest">
  <img align="left" alt="wise Up Data's Discord" width="22px" src="https://raw.githubusercontent.com/wiseupdata/wsl-latest/main/assets/discord.svg" />
</a>
<a href="https://github.com/wiseupdata/wsl-latest">
  <img align="left" alt="wise Up Data | Twitter" width="22px" src="https://raw.githubusercontent.com/wiseupdata/wsl-latest/main/assets/twitter.svg" />
</a>
<a href="https://github.com/wiseupdata/wsl-latest">
  <img align="left" alt="wise Up Data's LinkedIN" width="22px" src="https://raw.githubusercontent.com/wiseupdata/wsl-latest/main/assets/linkedin.svg" />


</a>

![visitors](https://visitor-badge.glitch.me/badge?page_id=wiseupdata.wsl-latest&left_color=green&right_color=black)
![license](https://img.shields.io/github/license/wiseupdata/wsl-latest)

---

<a name="readme-top"></a>

<h1>
<img align="left" alt="DP-203" src="https://raw.githubusercontent.com/wiseupdata/wsl-latest/main/assets/20230402_120516_image.png" width="400" />

# Useful commands and tips

</h1>

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

## Google Chrome - Ubuntu and Debian <img align="left" alt="wise Up Data | CHrome" width="22px" src="https://raw.githubusercontent.com/wiseupdata/wsl-latest/main/assets/chrome.png" />

<details>
<summary>
    Install Chrome with GUI - Graphic User Interface 
</summary>

### Update the wsl

> run the command as powershell adm.

```
wsl --update
wsl --shutdown
```

### Let's install the Chrome 🚀️

> update your distr

```
sudo apt update
```

> install - Run the following commands one by one.

```
cd /tmp
sudo wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
```

> Ignore errors messages in next step, just run!

```
sudo dpkg -i google-chrome-stable_current_amd64.deb
```

> keep the installation

```
sudo apt install --fix-broken -y
sudo dpkg -i google-chrome-stable_current_amd64.deb
```

### lauch and have fun! ❤️

```
google-chrome
```

https://user-images.githubusercontent.com/127680030/229356481-20513938-d00c-44a4-8387-85e3541e40d2.mp4


> launch without blocking the terminal
```
nohup google-chrome www.google.com > /dev/null &
```

> let's create a shorcut!
```
cp ~/.bashrc ~/.bashrc-backup
echo "alias google='nohup google-chrome www.google.com > /dev/null &'" >> ~/.bashrc
source ~/.bashrc
```

> test it!
```
google
```

</details>

<br>

# References

1. [Microsoft Documentation - 01](https://learn.microsoft.com/en-us/windows/wsl/tutorials/gui-apps)

---

<br>
<br>




---

#### Maintainer 🤗 👨‍💻

Sivio Liborio

📧 silvio.liborio@wiseupdata.com

<a href="https://www.linkedin.com/in/silvio-de-melo-liborio">silvio-de-melo-liborio <img align="left" alt="LinkedIN" width="18px" src="https://raw.githubusercontent.com/wiseupdata/wsl-latest/main/assets/linkedin.svg" />
</a>
