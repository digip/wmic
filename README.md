# wmic

##WMIC gather windows info

```
systeminfo | find /i "install date" > wmic.html
wmic BIOS list full /format:htable >> wmic.html
wmic CSPRODUCT list full /format:htable >> wmic.html
wmic CPU list full /format:htable >> wmic.html
wmic os get ServicePackMajorVersion /format:htable >> wmic.html
wmic os get ServicePackMinorVersion /format:htable >> wmic.html
wmic COMPUTERSYSTEM list full /format:htable >> wmic.html
wmic BOOTCONFIG list full /format:htable >> wmic.html
wmic BASEBOARD list full /format:htable >> wmic.html
wmic DISKDRIVE list /format:htable >> wmic.html
wmic ENVIRONMENT list /format:htable >> wmic.html
wmic GROUP list /format:htable >> wmic.html
wmic USERACCOUNT list /format:htable >> wmic.html
wmic SYSACCOUNT list full /format:htable >> wmic.html
wmic SYSDRIVER list full /format:htable >> wmic.html
wmic STARTUP list full /format:htable >> wmic.html
wmic SHARE list full /format:htable >> wmic.html
wmic SERVICE list full /format:htable >> wmic.html
wmic SERVER list full /format:htable >> wmic.html
wmic NIC list full /format:htable >> wmic.html
wmic NICCONFIG list full /format:htable >> wmic.html
wmic NETLOGIN list full /format:htable >> wmic.html
wmic LOGICALDISK list full /format:htable >> wmic.html
```
