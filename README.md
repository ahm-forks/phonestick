# Deprecation notice
I've completely lost interest in Android development, and I am therefore unwilling to keep maintaining this project.
There are multiple issues related to differences between devices that I simply can't properly address, and keeping up
with changes in the Android SDK every time I try to work on it is just a pain.

This repo will be archived, and I'm not interested in giving it away to a new maintainer. This is an open source
project, feel free to fork it and publish new releases anywhere you want as long as you comply with the license.
Please don't bother sending me emails about anything remotely related to USB Mountr, I will delete them without
looking.

Sayonara,  
Streetwalrus

# USB Mountr
A helper application to set the Mass Storage Device gadget up in Android kernels  
[<img src="https://f-droid.org/badge/get-it-on.png"
      alt="Get it on F-Droid"
      height="80">](https://f-droid.org/app/streetwalrus.usbmountr)  
![Screenshot](/screenshot.png?raw=true)

## How it works
Android kernels still include a USB MSD component in their device gadget nowadays, though it is mostly unused since
Android started using MTP. Some OEM ROMs still use it to provide a drivers installation "disc", but it is otherwise
useless.  
This application leverages the module in order to let you use your device as a standard USB thumbdrive for the purpose
of, e.g., booting a distro ISO.

## Building
Standard gradle build process.

## Contributions...
...are welcome, I'm looking for a better icon, and if you feel like implementing it before I do, a menu to create blank
images. Feel free to translate the application to your own language as well.

## See also
- @morfikov has written up [a tutorial](https://gist.github.com/morfikov/0bd574817143d0239c5a0e1259613b7d) on setting up
  your phone as a boot device for a LUKS setup

## Donations
I've been asked for donation info, so here it is.  
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=SHUNWU2HDU7EY)  
BTC: 199wYd9jB9yfBdXsfCXXESjzDHLHoKpBdd
