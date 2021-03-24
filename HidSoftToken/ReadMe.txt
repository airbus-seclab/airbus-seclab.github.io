Nowadays, many companies tend to deploy two factors authentication means to remotely access their infrastructure. 
Lately, the use of Soft Token applications instead of Hardware tokens seduces more and more, especially in regards to financial aspects (deployment and maintenance costs). 
In This current talk I will present a security study of the Android version of HID Soft Token application (HID Global). 
This study covers the mechanisms that are used by the application to protect the main functional processing as generating encryptions keys, OTP keys, etc.
Besides, the study lays the groundwork for shedding light on two vulnerabilities that affect the application.

Indeed, the cryptographic operations that are implemented by the application suffer from a certain weaknesses that allow an attacker (under certain circumstances) to retrieve the main resources of an enrolled HID Soft Token application that belongs to a legitimate user, clone its configuration and particularly discover the victim’s PIN by the means of a brute force attack.
