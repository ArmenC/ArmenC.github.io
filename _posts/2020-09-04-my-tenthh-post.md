---
layout: post
title:  "Blog 10"
date:   2020-11-12 17:20:01 -0700
categories: jekyll update
---

<h1>Creating AD Objects</h1>

Lets get started on creating objects in Active Directory.

1) Open up the start menu and click on "Windows Administrative Tools"

<img src="https://i.imgur.com/uFROAoY.png">

2) Double click on "Active Directory Users and Computers"

<img src="https://i.imgur.com/7hotWlH.png">

3) Lets start by creating a User. Right click Users and go to New -> User

<img src="https://i.imgur.com/rFAaqrq.png">

4) Fill out the information for the empty blanks and the Full Name will be automatically appear. Choose a username and select your domain. Click Next.

<img src="https://i.imgur.com/KXuv9jx.png">

5) Enter a password that the user will input to sign in. A good practice is to put a temporary password and let the user change it after log-in. If you want the passworn to not change, check the box "Password never expires"

<img src="https://i.imgur.com/9a4hKPq.png">

6) Click Finish to finalize the process. A new user has been created. Lets create a group and add the user to the group. Right click User again and select Group.

<img src="https://i.imgur.com/KXiAwgP.png">

7) Enter a name for your Group. In my case I want to create a group for Accounting and put all the employees in it. Click Okay when you are finished.

<img src="https://i.imgur.com/zsfRjx8.png">

8) Now let's double click on the user we created earlier. In my case, this is John Dough.

<img src="https://i.imgur.com/whxhaP8.png">

9) Select on the "Member Of" tab.

<img src="https://i.imgur.com/uvdun26.png">

10) Press on "Add" to add this user to a new group. Type out the name of the group on the box, in my case this is "Accounting". Next click on "Check Names".

<img src="https://i.imgur.com/92N6ven.png">

11) Select "Ok" after making sure the name is entered correctly. Select "Ok" again to close out the user. If we check the "Accounting" group, we will see that John Welsh is in it.

<img src="https://imgur.com/a/9tb0yjq">

We have learned how to create users and groups in Active Directory and how to add users in those groups. The reason you create groups is to set permissions on them and choose what programs to install. 
We control these using Group Policy Management. This is another service by Microsoft and I will show you how to install it next week.