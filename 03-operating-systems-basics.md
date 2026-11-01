# Operating Systems basics

**Module:** Operating Systems basics
**Completed:** October 2026

## Room: [Operating Systems:Introduction](https://tryhackme.com/room/operatingsystemsintroduction)
The OS (big buh buh) runs the kernel with full hardware access, handles all the daily grind (processes, memory, files, drivers), and acts as the bouncer enforcing permissions and isolation before any other security tool 
even gets involved. Also gained hands-on experience with a virtual machine to explore the OS on a deeper level.

## Room: [Windows Basics](https://tryhackme.com/room/windowsbasics)
Got hands-on with a Windows Server 2019 VM: navigating the GUI, reading files, installing programs, and running security scans. Basically: learning the layout before you have to go find the virus. 

## What Tripped Me Up
OS Intro tripped me up when it was asking how many directories exist in the virtual machine (my free PC!) that was given by imaginary friend Alex. I thought it was only counting the folders called "Alex" and "Guest". But as it turns out it was also including the Ubuntu Applications folder. I got tripped up in the second room when I was trying to find the folder that was affected by a virus in the VM. Only did I realize that even though there is more than one file affected there was one that looked right. I forgot that the file: C:\Users\ is just the pathway to whatever it is you are looking for. I felt a little silly that it took me a hot minute to connect the dots.

## What I Learned
1. I realize how terrifying it is to give an app kernel access (AKA Riot Vanguard). That's also the reason kernel/user space separation exists. If every app had that access, your PC would be one bad update away from
getting bricked. Talk about scurry... please be gentle. 
2. Free resources get you started, but the deeper material (Linux CLI, etc.) sits behind a paywall. I'm not paying, so I'm just working with what I've got.
3. Windows isn't scary, it's just a bunch of tools with a GUI on top. File Explorer, Task Manager, Windows Security. Once you know where they are, it's just clicking the right thing.
4. I didn't know you could do a custom scan on a specific folder or app! Honestly, it helped me understand how to read what a quarantine report is actually telling you.
