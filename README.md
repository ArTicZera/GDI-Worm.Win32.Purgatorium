# ❓ What is Purgatorium?
Purgatorium is a GDI Email-Worm made in C++ and 8086 Assembly for Windows XP (Tested on x86), if you run it in other OS, it'll shutdown the machine. Purgatorium it's by far, my best and biggest project I've ever created for educational &amp; entertainment purposes. I took me 1 month and 15 days to finish this work and I'm honestly very surprised with what I did...

# ⚠️ Important!!!
This is a potentially harmful program that can cause your system's death & data loss. This software also displays flashing lights and plays loud sounds, so if you have a photosensitive disease like epilepsy, don't run this or watch any video about it for your security.

By running this program, you accept full responsibility for any damages that may occur. So, the creator (ArTic a.k.a JhoPro) will not be responsible for anything caused by this software. By the way, this was created for educational and entertainment purposes, consequently, don't use it to do malicious acts like sharing with a friend.

# ⚙️ About the Payloads
I divided this malware in 3 parts: Restlessness, Collapse and Infernum. Know more informations below:

* <b>Restlessness part:</b> It happens after the first execution, where the malware infects the system and spreads through emails in Microsoft Outlook. This is the part where it creates and sets keys in the registry, creates copies of itself and disables task manager, regedit and cmd. Additionally, it displays the message "THE END IS NEAR" every 10 minutes.
<p align="center"><img src="Screenshots/Screenshot_1.png"></p>

* <b>Collapse part:</b> It happens when you run the worm in the year 2060. In this part it will try to delete all system32 files and will also overwrite the first 6 sectors of the disk (3072 bytes) for my bootloader + kernel. Then, GDI graphic payloads starts along with bytebeats sounds. The labels in the windows will also be randomized and your keyboard will start blinking (CAPSLK & SRCLK) synchronized with the bytebeats.
<p align="center"><img src="Screenshots/Screenshot_2.png"></p>

* <b>Infernum part:</b> This is the pos-destruction, made entirely in 8086 Assembly. After booting up the system, it will load my kernel fully wrote in 8086 Assembly, which displays 13 special effects using Mode 13h, incluiding PC Speaker support.
<p align="center"><img src="Screenshots/Screenshot_3.png"></p>

# Common problems

* <b>Boot payload isn't working:</b> If you use VMware, try desabling `Accelerate 3D Graphics` at `virtual machine settings >> Display`. If you use VBox, you can do the same in `virtual machine settings >> Monitor`.

If you relate some other problem, report at `Issues` or contact: ArTic🌊#1892 (my discord acc)

# 🚀 Execution tips
This malware has a better performance than my others, since the graphics are rendered in a slower resolution and then it's upscalled and displayed into your normal resolution. 

But in case you're having trouble running this malware because the payloads are too slow, try changing the resolution of your virtual machine to a low one or increase the amount of your CPU cores dedicated to the VM.

# 🤔 Fun facts
* The reason why the activation date of the last payloads is 2060 is because according to Isaac Newton, the end of the world would occur between the years 2060 and 2374, this occurred after his analysis of some books of the Bible and also after several mathematical calculations.

* This is my 4th and last contribution for this community. The other ones was Transpire, Chorume and Lixo!

* I almost gave up doing this because I was having problems with the bootsector's part. Fortunatelly I solve it!

* I had so many ideas that I had to wrote it in a txt file, unfortunatelly I couldn't put all in this malware... By the way I also did many cool things that I decided to not put in this work and keep it with myself only.

# ❤️ For skidders
I know that there will be some people skidding some effects after I release the source code of Purgatorium to put in their malwares, and even if I complain about it, nothing will change... So, for this reason, I added a GPLv3 license. In other words, if you use/modify a part of my code, you'll need to make your project open source!

Also, if you're a good ethical person you can credit me lol ^^

# 🤝 Credits


# 🎬 Lixo Showcase
