---
title: Wii Jailbreak [Twilight Hack]
description: A guide on how to jailbreak you Wii using the Twilight Hack expliot. 
published: true
date: 2024-02-02T16:47:07.991Z
tags: 
editor: markdown
dateCreated: 2024-02-02T14:37:03.666Z
---

# Wii Jailbreak Guide - Twilight Hack
<!--START GUIDE CONTENT UNDER THIS LINE-->
> This guide has been catergorised as a 'Legacy' guide. This is because it does not work with the latest system software version. It will still work under the correct conditions, but if in doubt, please use the LetterBomb guide instead.
{.is-danger}

## Introduction
<b>This guide will show you how use the Twlight Hack to jailbreak your Wii and how to install the Homebrew Channel.</b>

This was the first jailbreak created for the Wii and is probablt the most well known. It uses a modified game save for the game The Legend of Zelda: Twilight Princess.

It works by using a data overflow to load data that isn't supposed to be loaded. The name of Links 

> This method should work with both the original wii (with GC ports), and the second revision (without GC ports). 
<br>It will only work on System Menu verions 3.4 and 3.3!
<br><b>It will not work on the Wii Mini.</b> 
{.is-info}

## Things you'll need
Before starting you'll need to ensure you have:
- An SD Card which is 2GB or smaller. You cannot use SDHC cards.
- A computer with an SD card reader or a USB SD card reader.
- A copy of The Legend of Zelda: Twilight Princess.
- A Nunchuck. You'll need this to load into the game. 
- The Twilight Hack files. <a href="https://hbc.hackmii.com/get.php?file=twilight-hack-v0.1-beta1.zip&key=b9b4ef58c8c97c78f1692efe937beade6a6f5596">Click Here</a> for system versions 3.3 and earlier. <a href="https://hbc.hackmii.com/get.php?file=twilight-hack-v0.1-beta2.zip&key=37c2ee737421cce4853958da72849e16f34e2122">Click Here</a> for system version 3.4. See <br><b>'Checking your Wii System Software version'</b> prior to downloading.
- <a href="https://bootmii.org/get.php?file=hackmii_installer_v1.2.zip&key=50c0cfefc556e3098e9fb6c69da0c744d2696804">HackMii</a> installer to install the Homebrew Channel. 

---

## Preparing the SD Card
To start, you'll need to prepare your SD Card so that the Wii can read it. To do this, you'll need to format the SD Card. In this case you'll need to format it using the FAT32 / FAT16 file system. 

> Other file system types will not work!
{.is-warning}

<center><img src="/guide-assets/administrator-assets/wii-jailbreak-twilight/format.png"></center>

---

## Checking your Wii System Software version
Next, you'll need to check your Wii System Software Version. 

<b>This is important, so make a note of this. </b>

Click the Wii button thats on the bottom-left of the Wii menu, then select Wii Settings. You'll see it in the top-right corner.

> It needs to be version 3.3 or 3.4 for this exploit to work.
{.is-info}

If you're running a later version, this exploit will not work. Consider using LetterBomb instead. 
<br>
<center><img src=/guide-assets/administrator-assets/wii-jailbreak-twilight/wiimenu.png></center>

---

## Playing the game
Next, you'll need to play the first section of the game. You'll need to wait for the intro to load, and load fully into the game. 

> You will lose your prevous Twilight save, so please back this up if you have one. Use a different SD Card for this. 
{.is-warning}

Once you reach this screen you'll want to save your game.
<br>
<center><img src=/guide-assets/administrator-assets/wii-jailbreak-twilight/firstload.png height="500"></center>

Double check your Save Data to make sure it's present. 

---

## Copying the files to the SD Card. 
Now it's time to copy over the downloaded files to your SD Card.

Extract the contents of the Twilight Hack ZIP file you downloaded to the root of your SD Card. 

Extract the boot.elf from the HackMii Installer ZIP file you downloaded to the root of your SD Card. 

> Please make sure you use the boot.elf file and not boot.dol as this won't work.
{.is-warning}


---

## Preparing the exploit
> Remove your SD Card from your computer and insert it into your Wii. 
{.is-info}

First of all you'll need to delete the current save data for Twlight Princess. 

Wii button on the bottom left > Data management > Save files:
<br>
<center><img src=/guide-assets/administrator-assets/wii-jailbreak-twilight/erasesave.png></center>

---
Check the inner ring on your game disc. You'll need this to determine the save file version to use. 

Use this table to determine the version you'll need to run:
<br>
<center>
<table><tbody><tr><th>Region</th>
<th>Inner circle text</th>
<th>Save slot
</th></tr><tr><td>Europe/Australia (EUR)</td>
<td>RVL-RZDP-0A-0 JPN</td>
<td>Twilight Hack
</td></tr><tr><td>Asia (JPN)</td>
<td>RVL-RZDJ-0A-0 JPN</td>
<td>Twilight Hack
</td></tr><tr><td>America (USA)</td>
<td>RVL-RZDE-0A-0 JPN</td>
<td>TwilightHack0
</td></tr><tr><td>America (USA)</td>
<td>RVL-RZDE-0A-0 USA</td>
<td>TwilightHack0
</td></tr><tr><td>America (USA)</td>
<td>RVL-RZDE-0A-2 USA</td>
<td>TwilightHack2
</td></tr></tbody></table>
  </center>

Switch over to the SD Card tab and choose the 'Twlight Hack' save file suitable for your games region. 

Selet 'Copy' and then select 'Yes'. 

Now you can exit out of the menu.

---

## Executing the exploit
Now you can insert your copy of The Legend of Zelda: Twilight Princess.

When you reach the title screen, press A and B to get to the main menu. 

Now load the 'Twilight Hack' save file.
<br>
<center><img src=/guide-assets/administrator-assets/wii-jailbreak-twilight/gameload.png></center>

---

Once you've loaded in, walk over to the first character you see and interact with them. 

You'll begin the conversation, the the Elf Launcher will load, followed by the HackMii installer.
<br>
<center><img src=/guide-assets/administrator-assets/wii-jailbreak-twilight/interact-homebrew.png></center>

Choose 'Install The Homebrew Channel', then confirm your choice with 'Yes, continue'.

> It is heavily advised that you also install BootMii / PriiLoader at this point as it's an important brick protection software.
{.is-warning}

When it's finished, click continue.

## Finished

If everything went well, you should now be running the Twilight Hack with the Homebrew Channel!
<br>
<center><img src="/guide-assets/administrator-assets/wii-jailbreak-letterbomb/images/brew.webp" height=""></center>

<!--DO NOT EDIT THIS FOOTER. ALL GUIDE CONTENT SHOULD GO ABOVE!-->
<br>
<br>
<br>
<br>
<br>
<br>
<footer>
  <div class="waves">
    <div class="wave" id="wave1"></div>
    <div class="wave" id="wave2"></div>
    <div class="wave" id="wave3"></div>
    <div class="wave" id="wave4"></div>
  </div>
  <center><img src="/book_purple.png" height=50></center>
  <p><font color="white">Official Guide - <b><font color="a582b2">cmr</font></b>guides</font></p>
</footer>
<!--DO NOT EDIT THIS FOOTER-->