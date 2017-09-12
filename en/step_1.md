### Downloading NOOBS

Using NOOBS is the easiest way to install Raspbian on your SD card. To get hold of a copy of NOOBS:

+ Visit [https://www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![Downloads page](images/downloads-page.png)

+ You should see a box with a link to the NOOBS files. Click on the link.

![Click on NOOBS](images/click-noobs.png)

+ The simplest option is to download the zip archive of the files.

![Download zip](images/download-zip.png)

### Writing NOOBS to an SD Card

If the SD card you wish to install Raspbian on currently has an older version of Raspbian, you may wish to back up the files from the card.


### Windows


# Preparing the SD card

If you have a fresh SD card that has never been used, then you can probably skip this step, but it won't hurt to complete it if you are not sure.

Insert your SD card into your computer and wait for it to be recognised. The first thing to do is to make sure there are no existing partitions on the SD card. A partition is just a section of the card that can be used to store files.

1. Click on the *Windows* icon in the bottom left of the screen or tap the *Windows* key on your keyboard to open the *Start Menu*, and type the word **partition**:

  ![Start](images/windows/partition1.png)

2. Now click on the *Create and format hard disk partitions* program, which should be at the top of the menu.

3. The *Disk Management* program that opens can potentially delete all the files on your computer, so be careful. You should see a *disk* (here labelled disk1) that is approximately the same size as the SD card you inserted. Here an 8GB SD card has been used, and is showing as having 7.29GB of space:

  ![partition](images/windows/deletePartition.png)

4. The SD card shown here has two partitions. Any partitions you see need to be deleted. This can be achieved by clicking on the partition and selecting the *delete* option from the menu bar (the black cross). Once all the partitions have been deleted, right-click on the *Unallocated* space and select *New Simple Volume* from the context menu:

  ![create a volume](images/windows/createVolume.png)

5. A new window will open. All the default options can now be selected, but the guide below will take you through, step by step, in case you are unsure. First, click on *Next*:

  ![create a volume 2](images/windows/createVolume2.png)

6. At the next screen, make sure the *Simple volume size in MB* is equal to the *Maximum disk space in MB* and click on *Next*:

  ![create a volume 3](images/windows/createVolume3.png)

7. At the next stage it doesn't matter which *drive letter* is assigned, and will depend on the disk you have plugged into your computer. Just accept the default and click *Next*:

  ![create a volume 4](images/windows/createVolume4.png)

8. At the next screen, just accept the default *File system* and *Volume label* and click on *Next*:

  ![create a volume 5](images/windows/createVolume5.png)

9. That's it! You have re-partitioned and formatted the SD card. Click on *Finish*:

  ![create a volume 6](images/windows/createVolume6.png)

10. You should now see the formatted SD card in the *Disk Management* program with a single partition and a new label:

  ![create a volume 7](images/windows/createVolume7.png)

## Extracting NOOBS from the zip archive

Next, you will need to extract the files from the NOOBS zip archive you downloaded from the Raspberry Pi website.

1. Go to your *Downloads* folder and find the zip file.

2. Right-click on the the zip file and select *Extract All...* from the context menu:

  ![extract 1](images/windows/extract1.png)

3. A new window will open, offering a choice of extraction locations; the default is fine, so click on the *Extract* button:

  ![extract 2](images/windows/extract2.png)

4. You should now see a new folder in your *Downloads* called *NOOBS*, with some version numbers after it. Open this folder to view the extracted files:

  ![extracted](images/windows/extracted.png)

## Copying the files

5. Now open a new Explorer window and navigate to the SD card. It's best to position the two windows side by side:

  ![copy 1](images/windows/copy1.png)

6. You can now select all the files from the *NOOBS* folder and drag them onto the SD card:

  ![copy 2](images/windows/copy2.png)

7. Eject the SD card, using the Safely Remove Hardware and Eject Media tool in the taskbar.

8. That's it: you're finished. Click on the link below the image to learn how to install Raspbian Jessie on your Raspberry Pi.

  ![finished](images/windows/finished.png)

### Mac

## Preparing the SD card

If you have a fresh SD card then the following steps may not be necessary, but they won't do any harm if you are unsure.

1. Start *Spotlight* either by clicking on the magnifying glass in the top right hand corner of the screen, or by tapping the *Command Key* and *Space* on your keyboard.

2. Type *Disk Utility* into the search bar.

  ![Disk Utility](images/osx/1_diskutil.png)

3. Choose the *Disk Utility* program, which should be the the top result.

4. In the *Disk Utility* program, the available disks should be listed in the left-hand panel. Select the available disk reoresenting the SD card, and check that the *Capacity* matches the SD card that you inserted.

  ![SD Card](images/osx/2_sdcard.png)

5. Click the *Erase* button in the menu bar.

6. Change the *Format* to **MS-DOS (FAT)** and click on *Erase*.

  ![DOS](images/osx/3_dos.png)

7. When the format has completed, click on *Done*.

  ![Format](images/osx/4_format.png)

## Copying over the files

1. OS X automatically extracts downloaded zip files, so in your Downloads folder you should see a folder titled *NOOBS* with some version numbers after it.

  ![NOOBS files](images/osx/5_files.png)

2. Open up a new *Finder* window and navigate to the SD card. It is best to position the two windows side by side.

  ![Ready to copy](images/osx/6_precopy.png)

3. Select all the files in the *NOOBS* folder and drag them into the SD card window.

  ![copying](images/osx/7_copy.png)

4. Eject the SD card.

4. That's it: you're finished. Click on the link below to learn how to install Raspbian Jessie on your Raspberry Pi.

## Booting from NOOBS

  - Once the files have been copied over, insert the micro SD Card into your Raspberry Pi and then plug it into a power source.

  2. You will be provided with a single option, once the installer has loaded. You should check the box for **Raspbian**, and then click **Install**.

    ![install](images/install.png)

  3. Click **Yes** at the warning dialog, and then sit back and relax. It will take a while, but Raspbian will install.
