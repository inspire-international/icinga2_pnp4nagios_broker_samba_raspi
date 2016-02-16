# Icinga2 pnp4nagios &amp; Naming Server plugins coming with samba on Raspberry Pi 2 Model B
Provide you RASPBIAN JESSIE (2015-11-21) image which includes Icinga2, pnp4nagios and Naming server plugins, and samba.

![Naming server plugin for Icinga in action](http://www.inspire-intl.com/images/miezou_overview.jpg)

[Asset tracking & Motoring solution](http://www.inspire-intl.com/product/nextra/doc/monitoring_en.pdf)


# Prerequisite
- Raspberry Pi 2 Model B

- MicroSD card => 8GiB

# Preparation
1) [Click here to download the image in zip format and unzip it on your PC.](https://drive.google.com/file/d/0BzoHG_c1WjF5R2JFaFZDWXhzUE0)

2) [Use Win32DiskImager burning the image into your microSD card.](http://www.raspberry-projects.com/pi/pi-operating-systems/win32diskimager)

3) Insert your microSD to your Raspberry Pi slot and boot it.



# Icinga test drive
1) Open your browser and access to http://localhost or replace localhost string with the IP address assigned to your Raspberry Pi. You will see the top page like this.

![image](http://www.inspire-intl.com/images/miezou_top.jpg)


2) Click Performance Monitoring for Icingaweb2 and enter __icingaadmin__ for Username and __icinga__ for Password. Click Service Controller in order to add network services you want to monitor.


# File server
Samba is also included in this image.  So please type in UNC (Universal Naming Convention) on your explore and enter __pi__ for Username and __raspberry__ for password.

![image](http://www.inspire-intl.com/images/miezou_samba.jpg)

---

[Nextra Naming Server](http://inspire-intl.com/product/product_nextra.html#icinga)

#### Copyright (C) 1998 - 2016  Inspire International Inc.
