# Notice
This is a fork of a fork of a fork of streetwalrus' USB Mountr application.
I am planning to call it PhoneStick, but this project is still in its infancy.

forked from Swyter/phonestick
who forked it from dratini0/phonestick
who forked it from donfanning/android\_usb\_msd (aka streetwalrus.usbmountr)

I've also added filepicker fixes from kodiak-it/USB\_Mountr/
and replaced the USB gadget code with Swyter/android-usb-mass-storage-enable


Below is the original README of USB Mountr.

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

