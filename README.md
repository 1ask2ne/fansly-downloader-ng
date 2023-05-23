# Fansly Scraper / Fansly Downloader
![Downloads](https://img.shields.io/github/downloads/Avnsx/Fansly-Downloader-App/total?color=0078d7&label=🔽%20Downloads.exe&style=flat-square) ![Compatibility](https://img.shields.io/static/v1?style=flat-square&label=%F0%9F%90%8D%20Python&message=3.6%2B&color=blue) ![Stars](https://img.shields.io/github/stars/Avnsx/Fansly-Downloader-App?style=flat-square&label=⭐%20Stars&color=ffc83d)

![UI Banner](https://i.imgur.com/EhL42m3.jpg)

## 👋 Introducing ``Fansly Scraper``
Easy to use Fansly Downloader for Videos and Photos from your favorite fansly creators. After you've launched the program, it'll create a folder named ``CreatorName_fansly`` in the same directory you launched it from. That folder will contain the content downloaded in the highest resolution possible. It will also be sorted depending on your [configuration settings](https://github.com/Avnsx/Fansly-Downloader-App/wiki/Explanation-of-provided-programs-&-their-functionality#4-configini).
This is pretty useful for example; if you dislike the website theming and would like to view the media on your local machine instead. This code does not bypass any paywalls & no end user information is collected during usage.

[Click me if you want a detailed description on each of the components of this software!](https://github.com/Avnsx/Fansly-Downloader-App/wiki/Explanation-of-provided-programs-&-their-functionality)

### Many Thanks to all the `Stargazers` who have supported this project with stars(⭐)

[![Stargazers repo roster for @Avnsx/Fansly-Downloader-App](https://reporoster.com/stars/Avnsx/Fansly-Downloader-App)](https://github.com/Avnsx/Fansly-Downloader-App/stargazers)

## 🏗️ Set up
You can just install the [Executable version](https://github.com/Avnsx/Fansly-Downloader-App/releases/latest), skip the entire set up section & go to [Quick Start](https://github.com/Avnsx/Fansly-Downloader-App#-quick-start)

#### Requirements
If you want to use the python source directly, please install following requirements into your environment:

	pip install requests loguru imagehash pillow python-dateutil psutil keyboard "undetected_chromedriver==3.4.6" pycryptodome av m3u8 pywin32
or you can use [``requirements.txt``](https://github.com/Avnsx/Fansly-Downloader-App/blob/main/requirements.txt) with ``pip install --user -r requirements.txt`` into ``cmd.exe`` from project download folder to install them.

If you get an error while installing requirements with ``pywin32``; it is a windows only library and is not definitely required for the scraper itself. Only ``automatic_configurator.py`` needs it. If for some reason you can't install it with pip, you can also install it [through pywin32's github](https://github.com/mhammond/pywin32/releases) or you might also be able to install that by ``pip install pypiwin32`` or ``conda install pywin32``. If you can't install pywin32 that obviously means that you won't be able to run automatic configurator and need to use [Get Started](https://github.com/Avnsx/Fansly-Downloader-App/wiki/Get-Started) instead to set it up.

## 🚀 Quick Start
**Quick start is only compatible with Windows & you have to have recently logged into fansly in any of the following browsers: Chrome, FireFox, Opera, Brave or Microsoft Edge and that browser has to be [set as your default browser in windows settings](https://www.avast.com/c-change-default-browser-windows#:~:text=Open%20the%20Start%20menu%20and,is%20the%20current%20default%20browser.).**
1. Make sure the browser you set as default browser [in windows settings](https://www.avast.com/c-change-default-browser-windows#:~:text=Open%20the%20Start%20menu%20and,is%20the%20current%20default%20browser.), is also the browser that you've browsed fansly with in the past
2. Click on Automatic Configurator and wait for it [to do its thing](https://github.com/Avnsx/Fansly-Downloader-App/wiki/Explanation-of-provided-programs-&-their-functionality#2-automatic-configurator)
3. If it was successful(``config.ini`` should now *only* show a *single* ``ReplaceMe`` the targeted creator name) open the ``config.ini`` file and replace the value for ``[TargetedCreator]`` > ``Username =`` with whatever content creator you wish to have scraped
4. Save the ``config.ini`` file(into the same directory as fansly scraper) with the changes you've done to it, close it & then start up Fansly Scraper by clicking on it

**⚠️ If you are not using Windows or are encountering a bug with quick start please head over to [Get Started](https://github.com/Avnsx/Fansly-Downloader-App/wiki/Get-Started) instead ⚠️**

After completing any of the configuration tutorials [Quick Start](https://github.com/Avnsx/Fansly-Downloader-App#-quick-start) / [Get Started](https://github.com/Avnsx/Fansly-Downloader-App/wiki/Get-Started); in the future you'll only need to change the creator name for Targeted Creator > Username in ``config.ini`` for every further use case on other creators.

## 🤔 FAQ
Do you have any unanswered questions or want to know more about fansly scraper? Head over to the [Wiki](https://github.com/Avnsx/Fansly-Downloader-App/wiki)

+ **Q**: "Why do some executables show detections on them in VirusTotal?"
**A**: They are false positives (invalid detections). I literally e-mail each release of the scraper, for manual analysis to antivirus providers and the not 💩 providers actually analyse and unflag them, while others don't even bother reading their e-mails, but for some reason managed to get on VirusTotals file scanning system.

+ **Q**: "Could you add X feature or do X change?"
**A**: Star the project and I'll think about it. Otherwise you could always [open a pull request](https://github.com/Avnsx/Fansly-Downloader-App/pulls)

+ **Q**: "Will you add any payment bypassing features to fansly scraper?"
**A**: No, as the intention of this repository is not to harm fansly

## 🤝 Contributing to `Fansly Scraper`
Any kind of positive contribution is welcome! Please help it grow by contributing to the project.

The currently most needed changes are:
+ adding linux and macOS compatibility to automatic configurator
+ a way to visually display (e.g. loading bar) how much content is already scraped and how much is left

Please open a [open a pull request](https://github.com/Avnsx/Fansly-Downloader-App/pulls)!

## 🙏 Support
We all need support and motivation. This downloader for fansly is not an exception.

+ Please give this project a star(⭐️) to encourage and show that you liked it

+ $\textit{\color{lightgreen}{Maximise \ your \ support \ for \ fansly \ scraper,} \ \color{cyan}{by \ recommending \ it \ to \ others \ online }}$🌍


## 🛡️ License
This project (including executables) is licensed under the GPL-3.0 License - see the [`LICENSE`](LICENSE) file for details.

## Disclaimer
"Fansly" or [fansly.com](https://fansly.com/) is operated by Select Media LLC as stated on their "Contact" page. This repository (Avnsx/"fansly") and the provided content in it isn't in any way affiliated with, sponsored by, or endorsed by Select Media LLC or "Fansly". The developer(referred to: "Avnsx" in the following) of this code is not responsible for the end users actions, no unlawful activities of any kind are being encouraged. Statements and processes described in this repository only represent best practice guidance aimed at fostering an effective software usage. The repository was written purely for educational purposes, in an entirely theoretical environment. Thus, any information is presented on the condition that the developer of this code shall not be held liable in no event to you or anyone else for any direct, special, incidental, indirect or consequential damages of any kind, or any damages whatsoever, including without limitation, loss of profit, loss of use, savings or revenue, or the claims of third parties, whether the developer has advised of the possibility of such loss, however caused and on any theory of liability, arising out of or in connection with the possession, use or performance of this software. The material embodied in this repository is supplied to you "as-is" and without warranty of any kind, express, implied or otherwise, including without limitation, any warranty of fitness. This disclaimer is preliminary and is subject to revision.
##
Written with python on Windows 11
