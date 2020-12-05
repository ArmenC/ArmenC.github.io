---
layout: post
title:  "Blog 12"
date:   2020-12-03 17:20:01 -0700
categories: jekyll update
---

<h1>Deploying Printers Using Group Policy Management</h1>

Let's say your office just got a new printer and you would like to install it on all the computers. This will manually take a long time, but using Group Policy you are able to install the printer drivers on all the computers from one centralized location.

1) Open up Windows Administrative Tools from the Start Menu like we have done before.

<img src="https://i.imgur.com/Ji9gQj3.png">

2) Select Print Management. 

<img src="https://i.imgur.com/oWYnYuQ.png">

3) Right click in the empty space on the newly opened window. Select Add printer

<img src="https://i.imgur.com/JZXR8ox.png">

4) Let's select t second opton to add a TCP/IP and then click next.

<img src="https://i.imgur.com/FUFHexF.png">

5) For the first box make sure you select TCP/IP Device. On the second box enter the Static IP of your printer. This is usually found on the printer network settings. Once you have inputted the information select Next.

<img src="https://i.imgur.com/Wd6tGCk.png">

6) The TCP port will eventually be detected if the IP is correct and the printer will be added.

<img src="https://i.imgur.com/Tew3d8b.png">

7) Back in the Print Management window you will now see your printer populate. Rigt click your new printer and select Deploy with Group Policy.

<img src="https://i.imgur.com/OABNuGs.png">

8) Select Browse to choose your Group Policy that will deploy the printer.

<img src="https://i.imgur.com/Npgl0Gf.png">

9) Select the Printers GPO as seen on the picture. This is a default GPO that comes with Group Policy. If it is not there, find it in the subfolders or create it.

<img src="https://i.imgur.com/7MgRXsW.png">

10) The Group Policy is ready to be deployed to the computers. Back in the Print Management window let's make sure to share the printer. Right click your printer again and this time select Manage Sharing.

<img src="https://i.imgur.com/x8XAezE.png">

11) Finally check the box as seen on the picture to share the printer and click OK.

<img src="https://i.imgur.com/ZQEJU67.png">

You are finished. The Group Policy has been created and the printer is ready to be deployed. Once a computer has been restarted, the Group policy will update and receive the drivers from the server and install the printer to the computer. The printer will populate device managent as if it is installed manually.

This is one way to use the powerful Group Policy Management tool. If Group Policy is mastered, there are lots of ways to optimize an IT environment and make everything easier and more efficient.

