<h1 align="center">🧹 Downloads Cleaner</h1>

<p align="center">
	<b><i>Quick and simple python script to help with the frustrating clutter happening inside the 'Downloads' folder.</i></b><br>
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/>
</p>

## 📚 Table of Contents

- [📚 Table of Contents](#-table-of-contents)
- [📣 Introduction](#-introduction)
- [📦 Installation](#-installation)
- [📝 Usage](#-usage)

## 📣 Introduction

Are you tired of having a messy 'Downloads' folder ? No ? Well... I am ! That is where this cute little script comes in handy.

It iterates through the 'Downloads' directory and moves files based on their extensions
(.pdf → '/Documents', .png → '/Pictures', etc...).

"Why did you write it yourself ?" you may ask, "Surely there is already a program/software available that does this simple job better right ?". Yes... definitely... BUT since I want to learn how to use python, you may call this a "two birds with one stone" situation.

## 📦 Installation

> [!WARNING]
> This script assumes you have Linux default directories with their default name. If needed, modify the paths in the script to match with the name of your folders. (example on Apple: 'Movies' instead of 'Videos')

Clone the repository from GitHub:
```sh
git clone https://github.com/RedWrks/downloadsCleaner.git
```

## 📝 Usage

Execute the script with python3:
```sh
python3 path/to/cleanDownloads.py
```
Messages will appear notifying you of which files have been moved to which directory:
```sh
something.pdf moved to folder /home/user/Documents
confidential.pdf moved to folder /home/user/Documents
weird.png moved to folder /home/user/Pictures
webcam-toy-photo1.jpg moved to folder /home/user/Pictures
```
No messages = no files have been moved
