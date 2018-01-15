CVE-2017-11400
==============

Description:
------------
An issue has been discovered on the Belden Hirschmann Tofino Xenon Security Appliance 3.10 and earlier. 
An incomplete firmware signature allows a local attacker to upgrade the equipment (kernel, file system)
with unsigned, attacker controlled, data.


Vulnerability type:
-------------------
Incomplete firmware signature


Vendor of Product:
------------------
Belden Hirschmann


Affected Product Code Base:
---------------------------
Tofino Xenon Security Appliance - 3.10 and earlier


Affected Component:
-------------------
USB firmware


Attack Type:
------------
Local


Impact Code execution:
----------------------
Yes


Attack Vectors:
---------------
Attacker has physical access to the device and ability
tu plug USB device into it


Reference:
----------
https://www.belden.com/hubfs/support/security/bulletins/Belden-Security-Bulletin-BSECV-2017-14-1v1-1.pdf
https://www.belden.com/support/security-assurance


Discoverer:
-----------
Julien Lenoir of Airbus


CVE-2017-11401
==============

Description:
------------
An issue has been discovered on the Belden Hirschmann Tofino Xenon 
Security Appliance 3.10 and earlier. Improper handling of the 
mbap.length field of ModBus packets in the ModBus DPI filter allows an 
attacker to send malformed/crafted packets to a protected asset, bypassing
function code filtering.


Vulnerability type:
-------------------
DPI ModBus filter bypass


Vendor of Product:
------------------
Belden Hirschmann


Affected Product Code Base:
---------------------------
Tofino Xenon Security Appliance
Firmware 3.10 and prior


Affected Component:
-------------------
Modbus enforcer DPI filter


Attack Type:
------------
Remote


CVE Impact:
-----------
Bypass DPI filter on industrial firewall


Attack Vectors:
---------------
To exploit the vulnerability, attacker is able to send UDP or TCP
packets to a protected asset, on a LAN.


Reference:
----------
https://www.belden.com/hubfs/support/security/bulletins/Belden-Security-Bulletin-BSECV-2017-14-1v1-1.pdf
https://www.belden.com/support/security-assurance


Discoverer:
-----------
Julien Lenoir of Airbus


CVE-2017-11402
==============

Description:
------------
An issue has been discovered on the Belden Hirschmann Tofino Xenon 
Security Appliance 3.10 and earlier. Design flaws in OPC classic and 
in custom netfilter modules allow an attacker to remotely activate 
rules on the firewall and to connect to any TCP port of a protected 
asset, thus bypassing the firewall.

Vulnerability type:
-------------------
Firewall bypass


Vendor of Product:
------------------
Belden Hirschmann


Affected Product Code Base:
---------------------------
Tofino Xenon Security Appliance
Firmware 3.10 and prior


Affected Component:
-------------------
Netfilter custom filter combined with OPC Classic DPI filter


Attack Type:
------------
Remote


Attack Vectors:
---------------
To exploit the vulnerability, someone must connect to a protected 
asset over OPC Classic port


Reference:
----------
https://www.belden.com/hubfs/support/security/bulletins/Belden-Security-Bulletin-BSECV-2017-14-1v1-1.pdf
https://www.belden.com/support/security-assurance


Discoverer:
-----------
Julien Lenoir of Airbus