---
title: DSi Jailbreaking Guide
description: A jailbreaking guide explaining how to exploit your Nintendo DSi
published: true
date: 2024-01-30T23:39:21.547Z
tags: 
editor: markdown
dateCreated: 2024-01-29T23:45:33.703Z
---

# Nintendo DSi Jailbreak Guide
Like Me, You might be interested in modding your DSi and what better place to do it than cmrguides. Let’s Get Into It!

 
> <b>Things you'll need before you start:</b>
> SD Card (SanDisk is recommended)
> Unzipping software such as 7 zip
> SD Card reader
{.is-info}

## Prepping The SD Card

Download the latest version of <a href="https://bit.ly/twilgihtmenu">Twilight Menu</a> and <a href="https://bit.ly/dumptoolnds">DumpTool</a>

Extract _nds folder from TWiLightMenu DSi.7z to the root of your SD Card.

Extract the BOOT.NDS file from TWiLightMenu DSi.7z to the root of your SD Card.

Extract the dumpTool.nds file to the root of your SD Card.

<img src="https://images2.imgbox.com/17/2b/owLp2r94_o.png">


## Choosing An Exploit

<b>Memory pit:</b> Memory Pit is an exploit that uses the dsi’s camera, if you would like to view and save photos to the sd card this would not be recommended but can be changed later on

<b>Flipnote Lenny:</b> Flipnote Lenny is an exploit that uses the application “Flipnote Studio” if you do not have this application memory pit will be your only choice


## Checking Your Camera Version

Power on your console, open the DSi camera and view the album.

When viewing a photo, if you see a Facebook icon, download this file: <a href="https://bit.ly/iffacebookwaspresent">Facebook Present</a>

<img src="https://images2.imgbox.com/1e/ed/HuXQtd7c_o.png">

If you did not see a facebook icon download this file: <a href="https://bit.ly/iffacebooknotpresent">Facebook Not Present</a>

Navigate to sd private ds app 484E494A on your sd card If there is already a pit.bin file in that path, rename it to tip.bin

Put your pit.bin file in there

> If there's a folder named DCIM in the root of your sd card, make a backup of it so you don't lose the pictures inside, and then remove it from the SD Card
{.is-warning}

## Launching The Exploit

Insert the SD card into the Nintendo DSi system.

Turn on your DSi and launch the camera application.

Select the SD option on the top right.

Press The big “Album” button.

The screen should flash <font color="magenta"><b>magenta</b></font> if Memory Pit was copied correctly.

If the top screen turns <font color="green"><b>green</b></font>, you do not have BOOT.NDS on your SD card. Try the “SD Prepping” part again.

If you enter the album and nothing happens check that you have the correct version of unlaunch and that the DCIM folder doesn’t exist.

## Launching The Exploit (Flipnote Lenny)

> <b>Requirements:</b> 
> Flipnote Studio installed on your Nintendo DSi
{.is-info}

<i>If you do not have this you will have to use Memory Pit</i>

## SD Card Setup (Flipnote Lenny)

Download <a href="https://bit.ly/flipnotelenny">FlipnoteLenny</a>

Copy the private folder from Flipnote Lenny to the root of the SD Card.

## Executing Flipnote Lenny

Insert the SD card into the Nintendo DSi system.

Turn on your DSi and launch the “Flipnote Studio” application.

Open Flipnote Studio Settings and make sure “Start on Calendar” is disabled and “Frog” is enabled.

View the flipnotes stored on the SD Card.

Press the face corresponding to your region.

Edit the selected Flipnote.

Press the frog icon in the bottom left.

Tap on the film roll icon.

Select “Copy” then “Back” and finally “Exit”.

Press other Flipnote and select “Edit”.

Press the and press the film roll icon.

Press paste.

If the top screen turns <font color="green"><b>green</b></font>, you do not have TWiLight Menu's BOOT.NDS on the root of your SD card. 

## Dumping The DSi’s Nand

### Setting Up The SD Card

Download <a href="https://bit.ly/dumptoolnds">Dumptool</a>

Put dumptool.nds on the root of your SD card

### Dumping The Nand
Launch dumptool.nds and hit A

(This will take up to 8 minutes)

> <b>WARNING</b>
> Keep this backup safe as if you lose it and brick your DSi it won’t be recoverable!
{.is-danger}


## Extras

Installing Unlauch (optional)
This step is optional but helpful.

Make sure your console is charged when following this process. 

> <b>Note:</b>
> A sudden power loss could result in serious damage.
{.is-warning}


If you used lazy dsi file downloader before you can skip this section.

### Prepping the files
Download the latest version of <a href="https://bit.ly/unlaunch">Unlaunch</a>
Extract unlaunch.zip
Place unlaunch.dsi on the root of your sd card

### Installation Process
Open TwilightMenu and launch unlaunch.dsi
Select “Install Now” When Done Restart your Nintendo DSi
<br>
<img src="https://images2.imgbox.com/e7/10/8Qu0L0BA_o.png">
