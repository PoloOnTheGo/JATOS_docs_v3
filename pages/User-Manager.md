---
title: Manage JATOS users
keywords: user manager, user, member, password, admin rights, admin, LDAP
tags:
summary:
sidebar: mydoc_sidebar
permalink: User-Manager.html
folder:
toc: true
last_updated: 23 Jun 2021
---

Each experimenter with access to the JATOS server (though the GUI) is a JATOS User. Users can create, modify and delete the studies they are members of. They can also export and delete results. Users may also have **admin rights**, which lets them access the _Administration_ page and control other users' access to JATOS. 


## Manage users

Only users with admin rights have access to the **User Manager** (located in the header on every GUI page or since v3.6.1 in the _Administration_ page). In the _User Manager_ an admin can create new users, change passwords of users, or delete users. Since v3.6.1 it also lets you deactivate/activate users and see information about the user's studies.

JATOS comes with one user out-of-box: **Admin** (with user name 'admin'). Admin always has admin rights that cannot be revoked. The initial password for Admin is 'admin' should be changed immediately after installation and kept safe!

Every user can be granted admin rights, by checking the corresponding box either during creation or in the _Admin_ column of the table. Only admins can access the _Administration_ pages (like _User Manager_ or _Study Info_).

![User manager screenshot](images/Screenshot_User_Manager1.png)

A user can be **deactivated** (and activated again) by clicking the checkbox in _Active_ column. A deactivated user cannot login anymore but their studies can still be run by participants (to prevent a study from running deactivate it in the study _Administration_ page).

Since v3.6.1: To see more information about a user's studies click on in the _Studies_ column. These infos, like _Result Data Size_ and _Result File size_, can give admins an idea of how much this user uses the resources of the JATOS server.

![User manager screenshot](images/Screenshot_User_Manager2.png)

Since v3.6.1: With the _Export_ button in the top of the page one can export user data in CSV format. 


## Authentication via LDAP (version >= 3.5.4)

JATOS allows password authentication via LDAP (which lets an institution manage their users in a centralized way). LDAP is disabled by default. To enable it [change the JATOS config file](Configure-JATOS-on-a-Server.html#ldap-authentication-since-jatos--354). 

Once LDAP is enabled, there will be an additional checkbox 'LDAP' when the Admin creates a new user. Check this box to enforce authentication by LDAP. Normal JATOS users (locally authenticated) and LDAP users can co-exist in the same JATOS instance.

At the moment it is not possible to let JATOS create LDAP users automatically - they must be created by an JATOS admin manually.
