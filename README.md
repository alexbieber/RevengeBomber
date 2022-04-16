## REVENGEBOMBER🔴🔴🔴🔴


<h1 align="center">
  <br>
  <a href="https://github.com/AlexBieber/RevengeBomber"><img src="https://horoshop.ua/content/images/16/kak-sdelat-chtoby-pisma-ne-popadali-v-spam-11248663734326.jpg" alt="RevengeBomber"></a>
  <br>
  RevengeBomber🔴🔴🔴🔴
  <br>
</h1>



## Compatibility
Check your Python version by typing in
```shell script
$ python --version
```
If you get the following
```shell script
Python 3.8.3
```
or any version greater than or equal to 3.4, this script has been tested and confirmed to be supported. For obsolete versions of Python (eg 2.7), use discretion while executing the script as it has not been tested there.

## Features

- Over 15 integrated messaging and calling APIs included with JSON
- Unlimited (with abuse protection) and super-fast bombing with multithreading
- Possibility of international API support (APIs are offline)
- Flexible with addition of newer APIs with the help of JSON documents
- Actively supported by the developers with frequent updates and bug-fixes
- Intuitive auto-update feature and notification fetch feature included
- Recently made free and open-source for community contributions
- Modular codebase and snippets can be easily embedded in other program


## Usage:

### Install by PIP (Recommended)

Before continuing make sure following requirements are satisfied:

- Python version greater than or equal to 3.4 is installed
- pip is installed for Python 3

Install `revengrbomber` package by running:

```shell script
pip3 install revengebomber
```

Run RevengeBomber by just typing:
```shell script
revengebomber
```

### Install from GIT

#### NOTE 

Git installation methods are not universal and are likely to differ between distributions so installing Git as per the given instructions below may not work. Please check out how to install Git for your Linux distribution [here](https://git-scm.com/). Commands below provide instructions for Debian-based systems.

>Running `revengebomber.sh` as sudo miscofigures files ownership. It is recommended not to run it as sudo

Run these commands to clone and run RevengeBomber.

#### For Termux

To use the bomber type the following commands in Termux:
```shell script
pkg install git -y 
pkg install python -y 
git clone https://github.com/AlexBieber/RevengeBomber.git
cd RevengeBomber
./revengebomber.sh
```

#### For iSH

To use the application, type in the following commands in iSH.
```shell script
apk add git
apk add python3
apk add py3-pip
apk add ruby
gem install toilet
git clone https://github.com/Alexbieber/RevengeBomber.git
cd RevengeBomber
pip3 install -r requirements.txt
chmod +x revengebomber.sh
./revengebomber.sh
```

#### For Debian-based GNU/Linux distributions

To use the application, type in the following commands in GNU/Linux terminal.
```shell script
sudo apt install git
git clone https://github.com/AlexBieber/RevengeBomber.git
cd RevengeBomber
bash revengebomber.sh
```

#### For MacOS

To use the application, type in the following commands in MacOS terminal:

##### Install via Homebrew

```shell script
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
````

##### Install dependencies:

```shell script
brew install git
brew install python3
sudo easy_install pip
sudo pip install --upgrade pip
git clone https://github.com/AlexBieber/RevengeBomber.git
cd RevengeBomber
bash revengebomber.sh
```


##### Missing Tools on MacOS

The package `toilet` cannot be installed yet on macOS. But TBomb does still work.


### TODO:

- [x] Make Code More Readable and Extensible
- [ ] Add More Mail Spam APIs
- [ ] Add More SMS Spam APIs
- [ ] Add More Call Spam APIs
- [ ] Resolve threading issue in some devices


