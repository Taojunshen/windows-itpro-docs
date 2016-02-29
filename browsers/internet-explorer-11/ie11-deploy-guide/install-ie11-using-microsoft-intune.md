---
Description: How to add and deploy the Internet Explorer 11 update using Microsoft Intune.
ms.assetid: b2dfc08c-78af-4c22-8867-7be3b92b1616
ms.prod: IE11
ms.mktglfcycl: deploy
ms.sitesec: library
title: Install Internet Explorer 11 (IE11) using Microsoft Intune (Internet Explorer 11 for IT Pros)
---

#  Install Internet Explorer 11 (IE11) using Microsoft Intune
Internet Explorer 11 is available as an update in Microsoft Intune. Microsoft Intune uses Windows cloud services to help you manage updates, monitor and protect your computers, provide remote assistance, track hardware and software inventory, and set security policies. For more information, see the [Documentation Library for Microsoft Intune](http://go.microsoft.com/fwlink/p/?LinkId=301805).

## Adding and deploying the IE11 package
You can add and then deploy the IE11 package to any computer that's managed by Microsoft Intune.

**To add the IE11 package**

1.  From the Microsoft Intune administrator console, start the Microsoft Intune Software Publisher.

2.  Add your IE11 package as either an external link or as a Windows installer package (.exe or .msi). 

For more info about how to decide which one to use, and how to use it, see [Adding Software Packages](http://go.microsoft.com/fwlink/p/?LinkId=301806).

**To automatically deploy and install the IE11 package**

1.  From the Microsoft Intune administrator console, start and run through the Deploy Software wizard.

2.  Deploy the package to any of your employee computers that are managed by Microsoft Intune.

3.  After the package is on your employee's computers, the installation process runs, based on what you set up in your wizard. 

For more info about this, see [Automatically Deploying Software Packages to Devices and Users](http://go.microsoft.com/fwlink/p/?LinkId=301807)

**To let your employees install the IE11 package**

1.  Install the package on your company's Microsoft Intune site, marking it as **Available** for the appropriate groups.

2.  Any employee in the assigned group can now install the package. 

For more info about this, see [User Initiated Software Installation](http://go.microsoft.com/fwlink/p/?LinkId=301808)

 

 


