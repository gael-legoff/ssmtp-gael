# [ssmtp-gael](https://snapcraft.io/ssmtp-gael)

_This is NOT an original piece of work, just a snap of ssmtp_

Extremely simple MTA to get mail off the system to a mail hub

A secure, effective and simple way of getting mail off a system to your mail hub. It contains no suid-binaries or other dangerous things - no mail spool to poke around in, and no daemons running in the background. Mail is simply forwarded to the configured mailhost. Extremely easy configuration.

**Usage**

* Configure ssmtp
```
sudo vi /var/snap/ssmtp-gael/current/ssmtp.conf
```

* Create aliases (if needed)
```
sudo snap alias ssmtp-gael.ssmtp ssmtp
sudo snap alias ssmtp-gael.ssmtp sendmail
sudo snap alias ssmtp-gael.ssmtp mailq
```

**2026-02-18**
* New build to resolve CVE-2025-9820/CVE-2025-14831/USN-8043-1

**2025-07-15**
* ssmtp-gael will now use core24 as most users are on Ubuntu 24.04
* New build to resolve CVE-2025-6395/CVE-2025-32988/CVE-2025-32989/CVE-2025-32990/USN-7635-1

**2025-03-12**
* New build to resolve CVE-2024-12243/USN-7281-1

**2024-04-16**
* New build to resolve CVE-2024-28834/CVE-2024-28835/USN-6733-1
* ssmtp-gael will now use core22 as most users are on Ubuntu 22.04

**2024-01-23**
* New build to resolve CVE-2024-0553/CVE-2024-0567/USN-6593-1

**2023-03-01**
* New build to resolve CVE-2023-0361/USN-5901-1

**2022-08-05**
* New build to resolve CVE-2021-4209/CVE-2022-2509/USN-5550-1

**2021-08-03**
* New build to resolve CVE-2021-20231/CVE-2021-20232/USN-5029-1

**2021-04-24**
* Initial release
