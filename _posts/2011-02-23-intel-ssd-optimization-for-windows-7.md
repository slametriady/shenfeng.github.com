---
author: feng
date: '2011-02-23 22:28:11'
layout: post
status: draft
published: false
title: Intel SSD optimization for windows 7
---

[http://www.cucirca.com/2006/12/08/how-to-disable-windows-logging/](http://www.cucirca.com/2006/12/08/how-to-disable-windows-logging/)

Start the registry editor by clicking “**Start**” -\> “**Run**…”
and type “**regedit**“. Navigate to
“**HKEY\_LOCAL\_MACHINE SOFTWARE Microsoft WBEM CIMOM**“. In the
right window find the string called “**EnableEvents**“,
double-click on it and change its value to **0**. Now, do the same
for the string “**Logging**“. Change the value to **0**, click
“**OK**” and close the registry editor. Finally, you can **delete**
all log files in the folder mentioned above.
[http://www.ocztechnologyforum.com/forum/showthread.php?67056-Just-what-tweaks-are-needed-in-win7-with-SSD&](http://www.ocztechnologyforum.com/forum/showthread.php?67056-Just-what-tweaks-are-needed-in-win7-with-SSD&)
[http://www.ocztechnologyforum.com/forum/showthread.php?63273-\*-Windows-7-Ultimate-Tweaks-amp-Utilities-\*&p=442159\#post442159](http://www.ocztechnologyforum.com/forum/showthread.php?63273-*-Windows-7-Ultimate-Tweaks-amp-Utilities-*&p=442159#post442159)
[http://forums.extremeoverclocking.com/showthread.php?t=340129](http://forums.extremeoverclocking.com/showthread.php?t=340129)
1.  Disable Drive-Indexing
2.  Disable Disk Defragment Schedule
3.  Turn Off Windows Write-Cache Buffer Flushing
4.  Turn Off Pagefile
5.  Turn Off Multi-Boot Selection
6.  Turn Off Hibernation
7.  Power settings
8.  Enable Faster Booting sequence (msconfig)
9.  Disable Recycle Bin
10. Disable Windows Search and Superfetch (Services.msc)
11. Disable ClearPageFileAtShutdown and LargeSystemCache
12. Disable Superfetch and Prefetch
13. Disable System Restore



