# Implementation of Hill cipher in Java
This program was written as an exercise of [MSc in Computer Information Systems](https://www.eap.gr/en/courses/132-master-s-in-information-systems-msc) of [Greek Open University](https://www.eap.gr/en/), course [PLS-62 Specialization in Networks and Communications](https://www.eap.gr/en/courses/228-master-s-in-information-systems-msc/course-stucture/1615-pls62-specialization-in-networks-and-communications). It is actually the answer of Question 3 of the 4th Exercise for academic year 2017-2018.

It works with a-zA-z english characters only, and supports encrypt/decrypt with either 0..25 or 1..26 vocabulary.

The program deletes characters other than a-zA-z and converts the string to upper case. If the string length is an odd number, it adds an extra 'Q' characters at the end. The result is displayed in character pairs, separated with dash.

Encryption example:

```
Input: meet me at the usual place at ten rather than eight oclock

Key Matrix: |9 5|
            |4 7|

Output 0..25: UK-IX-UK-YD-RO-ME-IW-SZ-XW-IO-KU-NU-KH-XH-RO-AJ-RO-AN-QY-EB-TL-KJ-EG-YG
Output 1..26: GV-UI-GV-KO-DZ-YP-UH-EK-JH-UZ-WF-ZF-WS-JS-DZ-MU-DZ-MY-CJ-QM-FW-WU-QR-KR
```

You can find more information on Hill cipher at [Wikipedia](https://en.wikipedia.org/wiki/Hill_cipher).
