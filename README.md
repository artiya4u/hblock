HBlock
==========
HBlock is a simple adblocker for Linux application and lets you control ads blocking on your system tray.

The inspiration for this came from [StevenBlack's hosts](https://github.com/StevenBlack/hosts).

##Installation
HBlock is distributed as a python package. Do the following to install:

``` sh
sudo pip install hblock
OR
sudo easy_install hblock
OR
#Download Source and cd to it
sudo python setup.py install
```

After that, you can run `hblock` from anywhere and it will run. You can
now add it to your OS dependent session autostart method. In Ubuntu, you can
access it via: 

1. System > Preferences > Sessions  
(OR)
2. System > Preferences > Startup Applications 

###Upgrade
The latest stable version is [the one on PyPi](https://pypi.python.org/pypi/hblock/)
To upgrade, run `pip install -U hblock`.

##Features
1. Block ads globally using hosts file on system.
2. Let you start or stop ad blocking in system tray.

###Troubleshooting

If the app indicator fails to show in Ubuntu versions, consider installing 
python-appindicator with

`sudo apt-get install python-appindicator`

###Development

To develop on hblock, or to test out experimental versions, do the following:

- Clone the project
- Run `(sudo) python setup.py develop` in the hblock root directory
- Run `hblock` with the required command line options from anywhere.

##Author Information
- Artiya Thinkumpang (<artiya4u@gmail.com>)

##Licence
Licenced under the [MIT Licence](http://nemo.mit-license.org/).

