---
id: webspace-mybb
title: Install MyBB forum software
description: Information on how to install the MyBulletinBoard forum software on your webspace from ZAP-Hosting - ZAP-Hosting.com documentation
sidebar_label: Install MyBB

---



## What is MyBB?

MyBB, previously MyBulletinBoard, is a free and open source forum software developed by the MyBB Group. In this guide we explain how to install this forum software on our webspace product. 

## Set up MyBB

### Preparation

Before the actual installation of MyBB can be performed, certain preparations must be made. This includes getting the forum software, setting up the database to be used and the mail server (email address).


**Software**

The forum software can be downloaded from the official website of MyBB. The download for it can be found here: [MyBB](https://mybb.com/download/)

![Bildschirmfoto vom 2022-05-15 23-16-59](https://user-images.githubusercontent.com/61953937/168512896-c6875564-621b-4f7c-b9d2-f22bd4eeb7d0.png)

The download contains a packed file, which must be unpacked on your local computer. Inside you will find a folder with the name **Upload**. Its content is needed and must be uploaded either via **FTP or File Manager**. Under **Websites & Domains** at **FTP-Access** you can create a FTP user.

After opening the file manager in the Pleskpanel, we navigate to the **httpdocs** directory and upload the files of the forum software.


![en-file](https://user-images.githubusercontent.com/61953937/168512909-1a4152f6-0f09-4590-ab13-dc5831836976.png)


**Database**

As next, the database must be created, which will later be used to store all information of the forum. To do this, click again on **Websites & Domains** and then on **Databases**. Then click on Add Database and create a database:  

![en-db](https://user-images.githubusercontent.com/61953937/168512917-45c5abc6-98d0-4b02-b0b1-f6dfbed2fce2.png)

Click on **OK** and the database will be created.



**Mail server (e-mail address)**

For registering an account at the forum a mail server with an e-mail address is needed, so that the registration mails can be sent to the users. Instructions for setting up such an email address can be found here: [Send e-mails](https://zap-hosting.com/guides/docs/en/webspace_plesk_sendmail/)



### Installation

If all the steps from the preparation have been fulfilled, then the actual setup of MyBB can be started. For this, the website must now be called up in the Internet browser. This should look like this: 

![mybbinstall](https://user-images.githubusercontent.com/61953937/168512932-33b88822-3885-4d87-bb63-85bddbd195ba.png)


Once there, we now have to configure the 9 categories during the setup. The configuration will check if all the requirements are met, configure the database and forum software, and so on. To begin with, we must first determine whether anonymous statistics should be forwarded to MyBB or not. After that, the license terms have to be agreed upon as well. 

An overview of the required system requirements should then be displayed. This includes PHP version, memory, etc. The webspace should already be configured to meet all of these requirements by default.


![install2](https://user-images.githubusercontent.com/61953937/168512942-03abc4f0-8285-477e-8541-db74e69772d1.png)


In case any requirements are not met, please contact the support. Otherwise you can click on **Next** and continue the setup. Now we have to configure the database, which has already been created in advance. The database information from the created database must be filled in there: 

![image](https://user-images.githubusercontent.com/13604413/159177023-e839a466-f66e-4bdf-a11a-d505734eecfc.png)



The database will be configured afterwards. This may take a moment.  After that, the implementation of the default data and themes takes place. All you have to do here is to click on **Next**.


Subsequently, we come to the general configuration. Here you can define the name of the website, forum, URL and more:


![install3](https://user-images.githubusercontent.com/61953937/168512963-7d22f131-8144-4732-9162-c83234d0d119.png)


Last but not least, a general administrator account must be created before the setup can finally be completed. 


![Install4](https://user-images.githubusercontent.com/61953937/168513003-c4814b61-f003-4d10-a26b-06f57b429145.png)


If you have done this and everything else has been configured successfully, then you should see the following message and be able to access your forum as well:

![image](https://user-images.githubusercontent.com/13604413/159177053-541b8e05-9fb5-4dfa-a536-ab1958a0f598.png)

![image](https://user-images.githubusercontent.com/13604413/159177056-647941dd-31f1-4c75-a656-da73c3edf2cc.png)
