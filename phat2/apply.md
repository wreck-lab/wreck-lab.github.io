---
layout: default
parent: printHAT 2 Manual
title: Start the printer
nav_order: 9
has_children: false
---

## Start the printer

With the printHAT 2 fully wired on the printer it's now time to power it up.

In a little while, you will be able to connecte to OctoPrint or Mainsail via [http://wrecklab.local/](http://wrecklab.local/){:target="_blank"}, as already done before. Once on the web interface you can then Connect to the printer.

If the installation has been successful you will see the temperature log coming live. You can also check Klipper status issuing the STATUS command in the OctoPrint or Mainsail terminal.

> **IMPORTANT**  
When the printer is up and running it is advisable to **follow the Klipper configuration [check-list](https://github.com/KevinOConnor/klipper/blob/master/docs/Config_checks.md)** before attempting the first print.  


![octopi](../assets/img/octo_screen_1.jpg)
*Fig.1 - OctoPrint main screen ready for connection*

Once the edit is complete, save the file and the software will take care of restarting Klipper to make the changes effective. Upon restart you should see a fully populated and functional dashboard.

 ![mainsaildash](../assets/img/phat2_mainsail_dashboard.png)
 *Fig.2 - Mainsail dashboard fully populated with no error messages, ready for connection*
