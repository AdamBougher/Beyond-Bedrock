---
layout: page
title: Installation Guide
permalink: /instal-guide
---
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Installation Guide
1. Download the latest version of the pack from here:
    * https://drive.google.com/drive/folders/1j-Hn7Fqc0c-mggCLSiUcnRHcINrI9IMi?usp=sharing 
2. Download and Install the PrismLauncher. Most people will want the Windows 10/11 .exe version.
    * Try to install it to a faster drive (SSD) if you have one.
3. Open PrismLauncher, it will ask you to authorize with your Microsoft account into your in order to properly open and move past the Minecraft Launcher.
4. Open the settings -> Java:
    * Increase the maximum memory allocation if you can. Recommended is 8GB (8192 MiB)
        * You may be able to get away with less- performance is untested on lower RAM allocation. Would suggest not going lower than 4GB.
    * Java Runtime: Do Auto-Detect. Pick any Java 17 version.
        * **IF YOU DO NOT HAVE JAVA 17 IN THE AUTO-DETECT LIST**, you will need to go download and install it then repeat this step again: https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html 
5. On the main PrismLauncher menu, click Add Instance, then go to the Import tab. Browse for the modpack downloaded in step 1 then hit okay.


## Updating the Pack

Updating the pack is easiest done by repeating steps 1 and 5 of the above section with the new build of the pack and using the new instance to play.
However, you will also want to open your old instance folder and transfer along the following files / folders to keep your keybindings, settings, and local data (like maps)
* /.minecraft/options.txt
* /.minecraft/servers.dat
* /.minecraft/saves/
* /.minecraft/schematics/
* /.minecraft/journeymap/
* /.minecraft/notes/
* /.minecraft/config/jei/

## Configuration Guide
#### Shaders
Shaders can be activated by going to options > video settings > Oculus (Shaders) > Selecting Complementary Reimagined, then press Done.

You can edit the shader settings to your liking from this menu. One may want to increase the preset from Low to Higher settings.

## Server Info
* Minecraft Version: 1.20.1
* Forge Version: 47.4.0
* Memory Allocated: 12GB
* View Distance: 16 Chunks
* Sim Distance: 16 Chunks
* Seed: 1957568175802112430
* Difficulty: Normal
* Flight: Allowed
* Autopause: 10 minutes after last player disconnects
* Backups: Once every fourth hour of the day.
