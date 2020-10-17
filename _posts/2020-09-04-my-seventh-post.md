---
layout: post
title:  "Blog 6"
date:   2020-10-15 17:20:01 -0700
categories: jekyll update
---

In order to get started with Hyper-V, you will first need to install it on Server Administrator.

Let's get started first by clicking on the Start button and then selecting Server Manager.

<img src="https://i.imgur.com/0rAIqST.png">

Once in Server Manager, select "Manage" and click on "Add Roles and Features"

<img src="https://i.imgur.com/OTcNoaP.png">

Click Next and select "Role Based or Feature-based installation" and press Next again.

<img src="https://i.imgur.com/UtWr2aX.png">

Select the server you are going to install it on and press Next.

<img src="https://i.imgur.com/0oOSXqd.png">

In the list of the features, find Hyper-V and check the box, andselect "Add Features"

<img src="https://i.imgur.com/VYHPl5H.png">

Keep Selecting next until you get to "Create Virtual Switches" Select your NIC and click Next

<img src="https://i.imgur.com/ESyEYd7.png">

Select Next until you get to "Default Stores" then select where you would like the Virtual Disks to be stored. The default location is usually fine but it matters whether you have a separated drive for the VMs.

<img src="https://i.imgur.com/t1PoRvY.png">

Once you select the drives, press Next and select Install.

<img src="https://i.imgur.com/s43Y6mx.png">

Once it finished, you may select Finish and restart the server.

Hyper-V is now installed. Next week I will discuss how to launch and host machines in Hyper-V.