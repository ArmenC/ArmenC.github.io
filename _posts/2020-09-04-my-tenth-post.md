---
layout: post
title:  "Blog 9"
date:   2020-11-05 17:20:01 -0700
categories: jekyll update
---

<h1>Installing Active Directory</h1>

Let's go to Server Manager from the Start Menu. 

<img src="https://i.imgur.com/G5XNcAQ.png">

Once in Server Manager, select "Manage" and click on "Add Roles and Features"

<img src="https://i.imgur.com/aVOETCp.png">

Click Next and select "Role Based or Feature-based installation" and press Next again.

<img src="https://i.imgur.com/8GOoWDm.png">

Select the server you are going to install it on and press Next.

<img src="https://i.imgur.com/jUqJf5z.png">

In the list of the features, find Active Directory Domain Services and select it. A window might pop-up, select "Add Features"

<img src="https://i.imgur.com/m27CWkO.png">

Select next until you get to the "AD DS" section. Stop and read the "Things to note"

<img src="https://i.imgur.com/1zdBTkW.png">

Select Next and press Install.

<img src="https://i.imgur.com/9AL5Ic9.png">

Once you Active Directory finishes installing select Close.

<img src="https://i.imgur.com/20kdep2.png">

Open up Server Manager again and select "Promote this server to a domain controller"

<img src="https://i.imgur.com/9lQuzbt.png">

Select The first option and type out your domain name.

<img src="https://i.imgur.com/wehzyal.png">

You have finished installing Active Directory Services. If you do not have a domain, ignore the last section. 
Next week we will focus on creating objects such as users, groups, and computers.