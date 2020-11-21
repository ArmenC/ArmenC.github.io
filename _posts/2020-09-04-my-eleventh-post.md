---
layout: post
title:  "Blog 11"
date:   2020-11-19 17:20:01 -0700
categories: jekyll update
---

<h1>Creating a Group Policy Object and configuring it</h1>

Let's create a simple Group Policy Object and add it to the general users.

1) Open up the start menu and select Windows Administrative Tools.

<img src="https://i.imgur.com/POHXRkx.png">

2) Open up Group Policy Management

<img src="https://i.imgur.com/TAbLiLj.png">

3) The Group Policy Management window will open. Let's select on Group Policy Objects. You will notice on the right side that only the Default Object is there.

<img src="https://i.imgur.com/ekjf63X.png">

4) Right click anywhere on the right side and select new

<img src="https://i.imgur.com/sUGWH5w.png">

5) Let's name this Power Settings and select OK

<img src="https://i.imgur.com/RoruwWZ.png">

6) Right click your newly created GPO, and select Edit.

<img src="https://i.imgur.com/y6nLXL9.png">

7) You will see a window with all the different options for your GPO. Let's change some power settings. Select Preferences under Computer Configuration

<img src="https://i.imgur.com/2PpxdvJ.png">

8) Select Power Options on the left tab, then right click on and Select New -> Power Plan (At least Windows 7)

<img src="https://i.imgur.com/JBdrYcV.png">

9) Let's make it so the computers/laptops will go to sleep mode ater 30 minutes. Check the box on #1, then select Sleep -> Sleep after and select 30 on both. Press OK to finish.

<img src="https://i.imgur.com/uTbTx6L.png">

10) You will see the new power option appear on the right side. Let's also make it so the computers have a shortcut added on all of their desktops. GO back to Preferences -> Windows Settings on the left side and select Shortcuts. Right click and select New -> Shortcut.

<img src="https://i.imgur.com/VsAPix5.png">

11) Lets create a shortcut of the Downloads folder to the Desktop. We selected the icon on step 3 by clicking on the "..." button. Once finished select OK, and close the editor.

<img src="https://i.imgur.com/nXJ6GTP.png">

12) Back to the Group Policy Management window, lets select our newly created/edited GPO and click on the Delegation tab. Select Add.

<img src="https://i.imgur.com/iLORJmw.png">

13) Write on the blank area "Accounting" ( We had created this on the previous blog) and select OK.

<img src="https://i.imgur.com/SspZ5Gl.png">

14) Make sure you change the permissions to the selected one in the picture, and click OK.

<img src="https://imgur.com/a/gjAXdIf">


Once this has finished you have created a new Group Policy Object and assigned it to the Accounting group. From now on any user/computer that is assigned to that group will have their computer/laptop go to sleep mode in 30 minutes, and also have a Downloads folder shortcut.

This is just one simple object, but if you look at the other policies and settings you will see that there are many things you can customize for the users.

Group Policy Management is an amazing tool to keep an organized, consistent, and secure AD environment.