# HIKos
This is a very simple operation system, that can open, edit and save files, do basic stuff such as cd, dir, shutdown and logoff, run small games and apps (text editor, calculator). See all the commands **[here](https://github.com/HikBit/HIKos#commands)**

First time you boot HIKos you will have to create an user. Fill in a weird username and a short password. Next time you boot HIKos you will be asked for username and password. Safety First!! If you forgot your password there is only one option: Create a new user!!

HIKos is written in C# with [Cosmos](https://gocosmos.org). This is the fast way to make an os, if you don't want to create it from scratch.

![](http://ingvar.hahnkristensen.dk/assets/screenshot.PNG)

## Download, install and setup
**NOTE:** HIKos is not builded yet. You can’t download the .iso image.


HIKos can be booted on a virtual machine (VMware, VirtualBox etc.) or on real/physical hardware. The second option is a bit riscy, so i would reccomend booting it on a virtual machine. Here is what you will need:

- The .iso image. Download [here](https://google.com)
- A virtual machine ([VMware Workstation](https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html), [VirtualBox](https://www.virtualbox.org/wiki/Downloads))

In this example we will be using VirtualBox. Create a new virtual machine, name it HIKos and set the Operation System to Other/Unknown. Run it and you will probably see a file explorer-window popping up. Find the .iso image from before and click open. If everything goes well, HIKos will boot very soon.

## Commands
It's not easy to find a valid command if just typing random stuff. But you don't have to. Here is a complete list of commands you can use in HIKos.

- **info** Shows general info about the OS and the PC
- **help** List of basic commands. 
- **hacky color** Changes the textcolor to green
- **normal color** Changes the textcolor back to white
- not all are listet here yet...
