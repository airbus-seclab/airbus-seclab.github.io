CVE-2019-12091
==============

Description:
------------
The Netskope client service, running with NT\SYSTEM privilege, accepts network connections from localhost.
The connection handling function in this service suffers from command injection vulnerability.
Local users can use this vulnerability to execute code with NT\SYSTEM privilege.


Vulnerability type:
-------------------
CWE-78 Command injection


Vendor of Product:
------------------
Netskope


Affected Product Code Base:
---------------------------
* Netskope client v57 before 57.2.0.219
* Netskope client v60 before 60.2.0.214


Affected Component:
-------------------
Netskope Client on Windows 


Attack Type:
------------
Local


Impact Code execution:
----------------------
Yes


Attack Vectors:
---------------
An authenticated user can interract with the Netskope Client service through
a local network socket and trigger an command injection.


Reference:
----------
* https://www.netskope.com/
* https://www.netskope.com/vulnerability-disclosure-policy
* https://support.netskope.com/hc/article_attachments/360033003553/Sprint_62_Release_Notes.pdf
* https://support.netskope.com/hc/en-us/articles/360014589894-Netskope-Client


Discoverer:
-----------
Julien Lenoit, Benoit Camredon, Mouad Abouhali from Airbus Security Lab.


CVE-2019-10882
==============

Description:
------------
The Netskope client service, running with NT\SYSTEM privilege, accepts network connections from localhost.
The connection handling function in this service suffers from a stack based buffer overflow in "doHandshakefromServer" function.
Local users can use this vulnerability to trigger a crash of the service and potentially cause additional impact on the system.


Vulnerability type:
-------------------
Stack based buffer overflow


Vendor of Product:
------------------
Netskope


Affected Product Code Base:
---------------------------
* Netskope client v57 before 57.2.0.219
* Netskope client v60 before 60.2.0.214


Affected Component:
-------------------
Netskope Client on Windows 


Attack Type:
------------
Local


CVE Impact:
-----------
Memory corruption and denial of service


Attack Vectors:
---------------
An authenticated user can interract with the Netskope Client service through
a local network socket and trigger an command injection.


Reference:
----------
* https://www.netskope.com/
* https://www.netskope.com/vulnerability-disclosure-policy
* https://support.netskope.com/hc/article_attachments/360033003553/Sprint_62_Release_Notes.pdf
* https://support.netskope.com/hc/en-us/articles/360014589894-Netskope-Client


Discoverer:
-----------
Julien Lenoit, Benoit Camredon, Mouad Abouhali from Airbus Security Lab.
