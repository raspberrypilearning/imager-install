## Install Rasperry Pi OS on your SD card with the Raspberry Pi Imager

Many vendors sell SD cards with a simple Rasperry Pi OS installer called NOOBS preinstalled but you can really easily install Rasperry Pi O yourself using a computer that has an SD card port or using an SD card reader.

Using the Raspberry Pi Imager is the easiest way to install Rasperry Pi O on your SD card.

**Note:** More advanced users looking to install a particular operating system should use this guide to [installing operating system images](https://www.raspberrypi.org/documentation/installation/installing-images/README.md). 

### Download and launch the Raspberry Pi Imager

+ Visit the [Raspberry Pi downloads page](https://www.raspberrypi.org/downloads).
+ Click on the link for the Raspberry Pi Imager that matches your operating system.

![Downloads page](images/newInstaller_downloadsPage.png)

+ When the download finishes, click on it to launch the installer.

![Launch installer](images/newInstaller_launchInstaller.png)

### Using the Raspberry Pi Imager

All data stored on the SD card will be overwritten during formatting and lost permanently, so make sure that you back up the card or any files you want to keep before running the installer.

When you launch the installer, your operating system may try to block you from running it. For example, Windows may give the following message: 

![Windows warning](images/newInstaller_windowsWarning.png)

+ If you get this, click on `More info` and then `Run anyway`.

+ Insert your SD card into the computer or laptop’s SD card slot.

+ In the Raspberry Pi Imager, select the OS that you want to install. The first option, Rasperry Pi O, is the recommended OS.

![Raspberry Pi Imager in windows](images/newInstaller_selectOS.png)

+ Select the SD card you would like to install it on. Different platforms will display the drives in different ways. Mac OS, for example, will show you all drives including you main operating sysytem. 

**Note:** Make sure you are selcting the correct drive. The drives memory capacity can be a useful indication of which drive you are selecting.

![Raspberry Pi Imager in windows](images/newInstaller_select-SDCard.png)

Once you have selected both the OS and the SD card, a new `WRITE` button will appear.

![Raspberry Pi Imager in windows](images/newInstaller_osAndCardSelected.png)

+ Then simply click the `WRITE` button.

+ Wait for the Raspberry Pi Imager to finsh writing.

+ Once you get the following message, you can eject your SD card.

![Write successful message](images/newInstaller_writeSuccessful.png)
