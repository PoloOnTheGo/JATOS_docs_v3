---
title: Administration
keywords: administration, user manager, studies, study info, logs, tests, system info, update, latest users, latests study runs, studies
tags:
summary:
sidebar: mydoc_sidebar
permalink: Administration.html
folder:
toc: false
last_updated: 23 Jun 2021
---

Since JATOS v3.6.1 JATOS has the _Administration_ page. Here [users with admin rights](/User-Manager.html) can get an overview of a JATOS installation, like **logs** and **system info**, or do **tests** to check if JATOS runs correctly. It is also the place where the **update info** is shown, if a new JATOS version is available and where [admins can trigger an update](/Update-JATOS.html#automatic-updates).

![Administration screenshot](images/Screenshot_Administration1.png)

### User Manager

... has [its own page](/User-Manager.html)


### Study Administration

By clicking the _Studies_ button one gets to an overview about what studies are installed on this JATOS, to whom the studies belongs to (the study members), how much disk space they use, and when they were last active.

![Studies Administration](images/Screenshot_Study_Admin1.png)

A study can be **deactivated** (and activated again) by an admin by clicking the checkbox in the 'Admin' column, e.g. if the study uses to many server resources. A deactivated study cannot be started by participants (workers) anymore, but an already started study can be continued. The member users can still see and edit the study and export its result data. 

Other columns are:
* **Study Assets Size** - The disk size of all files that are necessary to run this study (HTML, JS, CSS, images, videos, etc.)
* **Result Count** - The number of study results gathered so far on this JATOS
* **Result Data Size** - The size of all result data that are stored in the database. In brackets is the size per result count.
* **Result File Size** - The size of all result files that are stored in the server's file system. In brackets is the size per result count.
* **Last Started** - When was this study last started by a participant.
