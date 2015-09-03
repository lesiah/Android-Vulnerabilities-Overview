Android vulnerabilities overview (AVO) is a small list of security vulnerabilities in Android.


quote\
_The security flaw gives hacker ability to spy on Android smartphone owners, steal login credentials, install malware, and many more, according to the latest research conducted by the researchers at the Pennsylvania State University and FireEye._
/quote


Contact
------------

Found something that isn't on the list? - Feel free to submit, maintainers/contributors are always welcome! 

Want to communicate secure, feel free - my eMail is stored in the 'eMail.txt' file.



Warning
--------

* Do not install security updates like _CVE-2015-1538.apk_ from untrusted sources! It's a trap! Security updates are rolled out by Google Play-services or as ROM directly from your provider and never comes as single .APK!




Attacks
--------

* Ransomware (User needs to confirm the device admin part)
* Distributed Denial of Service (DDoS) 
* [Cyber-attacks](https://en.wikipedia.org/wiki/Cyber-attack) like (mass) surveillance (e.g. directly on telecommunication infrastructures), worms, viruses, trojans, ...
* Hijacking in Android is a common problem
* Cyberterrorism
* Based on fingerprinting to _sniff_ metadata 
* Other data leakage, exploits, ...
* ...



***2015***


Open
--------

- [ ] [AppLock](https://blogs.securiteam.com/index.php/archives/2558)
- [ ] Google Maps API](https://cryptome.org/2015/07/HT-Google-Maps-API.pdf) (mostly after each new upgrade)
- [ ] [Remote local compatibility check](https://cryptome.org/2015/07/ht-android-exploit.txt)
- [ ] [CVE-2015-3825](https://securityintelligence.com/one-class-to-rule-them-all-new-android-serialization-vulnerability-gives-underprivileged-apps-super-status/)
- [ ] [CVE-2015-3842](http://blog.trendmicro.com/trendlabs-security-intelligence/mediaserver-takes-another-hit-with-latest-android-vulnerability/) Android 2.3 Gingerbread to Android 5.1.1 Lollipop
- [ ] [Stagefright] (http://blog.zimperium.com/experts-found-a-unicorn-in-the-heart-of-android/) ~ 95% of all Android devices running version 2.2 to 5.1
- [ ] SS7, which is unfortunately vulnerable affect everyone (Man-in-the-Middle" (MitM) attacks)


Closed
--------

- [x] [CVE-2015-4945](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2015-4945)
- [x] [CVE-2015-5084](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2015-5084)
- [x] [CVE-2015-4171](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2015-4171)
- [x] [CVE-2015-3906](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2015-3906)
- [x] [CVE-2015-1474](http://www.cvedetails.com/cve/CVE-2015-1474/)
- [x] CVE-2015-1538
- [x] CVE-2015-1539
- [x] CVE-2015-3824 Android from 4.0.1 to 5.1.1
- [x] [CVE-2015-3864](http://home.mcafee.com/VirusInfo/VirusProfile.aspx?key=9609519)
- [x] CVE-2015-3823 Android from 4.0.1 to 5.1.1
- [x] [CVE-2015-0204](https://freakattack.com/) all systems, aka FREAK attack



Rolling out to manufacturers and carriers
--------

- [x] [CVE-2015-3824](https://blog.exodusintel.com/2015/08/13/stagefright-mission-accomplished/)] Stagefright, some providers like telecom disabled the entire MMS service
- [x] CVE-2015-0235 pending
- [x] CVE-2015-3829
- [x] CVE-2015-3828
- [x] CVE-2015-3827



Research
--------

* [News from SecurityWeek](http:/www.securityweek.com)
* [Security | Android Open Source Project](https://source.android.com/devices/tech/security/)
* ﻿[Security with HTTPS and SSL | Android Developers](https://developer.android.com/training/articles/security-ssl.html)
* [Crypzo Standard EDU](https://crypto.stanford.edu)
* [SS7 hack shown demonstrated to track anyone |60 Minutes](http://www.9jumpin.com.au/show/60minutes/stories/2015/august/phone-hacking/)
* https://source.android.com/devices/tech/index.html
* https://source.android.com/devices/tech/security/enhancements/enhancements44.html
* https://source.android.com/devices/tech/security/overview/app-security.html
* https://source.android.com/devices/tech/security/overview/updates-resources.html
* https://source.android.com/devices/tech/security/enhancements/index.html
* https://source.android.com/devices/tech/security/overview/acknowledgements.html
* [CIS security overview](http://www.cisecurity.org/)
* [Mozilla Security Blog](https://blog.mozilla.org/security/category/security/)
* [Chomium Security FAQ](https://www.chromium.org/Home/chromium-security/security-faq#)
* [Android Vulnerability overview | TheHackerNews](http://thehackernews.com/search/label/Android)
* [Beyond Security Team](https://blogs.securiteam.com/)




Papers:
* http://www.mcafee.com/us/resources/white-papers/wp-defeating-ssl-cert-validation.pdf
* https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-ren-chuangang.pdf
* http://www.pwc.com/en_US/us/financial-services/regulatory-services/publications/assets/sanctions-cyber-crime.pdf



Online tests:
* [FREAK test](https://freakattack.com/)
* [Panopticlick](https://panopticlick.eff.org/)
* [www.filldisk.com](http://www.filldisk.com/)
* [SSL Client Test](https://www.ssllabs.com/ssltest/viewMyClient.html)
* [Evercookie](http://samy.pl/evercookie/)
* [BrowserSpy.dk](http://browserspy.dk/)
* [Testing mixed content](https://people.mozilla.org/~tvyas/mixedcontent.html)
* [WebRTC check](http://mozilla.github.io/webrtc-landing/)
* <s>[Adobe Flash player version detector](https://www.adobe.com/software/flash/about/) no Flash since Android 4.x</s>
* [IP check](http://ip-check.info/?lang=en)
* [CORS and WebSocket test](http://cure53.de/leak/onion.php)
* [Browserrecon](http://www.computec.ch/projekte/browserrecon/)
* [WebGL check](http://get.webgl.org/)
* [battery.js](https://pstadler.sh/battery.js/)
* [RC4 fallback test](https://rc4.io/)
* [Battery API check](https://robnyman.github.io/battery/)



Kernel:
* [Kernel Overview | Android Developers](https://source.android.com/devices/tech/kernel.html)
* [Kernel Security Overview | Android Developers](https://source.android.com/devices/tech/security/overview/kernel-security.html)



Apps:
* [Stagefright Detector App by Zimperium](https://play.google.com/store/apps/details?id=com.zimperium.stagefrightdetector)
* [TextSecure](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms&hl=en) (SMS encryption was removed)
* [RedPhone](https://play.google.com/store/apps/details?id=org.thoughtcrime.redphone&hl=en) (Stores the private key on there servers)
* [Crypt4All Lite (AES) - (Free File Encryption Software)](https://play.google.com/store/apps/details?id=com.codewell4.Crypt4AllLite)
* [Orbot](https://play.google.com/store/apps/details?id=org.torproject.android) alias Tor for Android 
* [(AppLock (Free Application Lock Utility)](https://play.google.com/store/apps/details?id=com.domobile.applock)
* [App Ops (Free App Permission Manager)](https://play.google.com/store/apps/details?id=com.findsdk.apppermission) On Android 6 obsolete
* [LastPass Password Manager Premium (Free)](https://play.google.com/store/apps/details?id=com.lastpass.lpandroid) personally I prefer [KeePass - alias KeePassDroid](https://play.google.com/store/apps/details?id=com.android.keepass&hl=en)
* [K-9 Mail (Free Secure Email Encryption Software)](https://play.google.com/store/apps/details?id=com.fsck.k9&hl=en) - I prefer [K-@ Mail Pro](https://play.google.com/store/apps/details?id=com.onegravity.k10.pro2&hl=en) [it's based on K-9 Mail but with a _better_ gui]
* [Android open source apps overview | GitHub](https://github.com/pcqpcq/open-source-android-apps)



Forensics analysis software and apps:
* [Androick](https://github.com/Flo354/Androick)
* [Android Forensics Open Source Android Forensics App and Framework](https://github.com/viaforensics/android-forensics)
* [Android Data Extractor Lite](https://github.com/mspreitz/ADEL)
* [BitPim](http://www.bitpim.org/)
* [LiME](https://github.com/504ensicsLabs/LiME)
* [OSAF - Open Source Android Forensics](http://www.osaf-community.org/)
* [P2P-ADB](https://github.com/kosborn/p2p-adb/)
* [Appie](https://manifestsecurity.com/appie)
* [Mobisec](http://sourceforge.net/projects/mobisec/)
* [pySimReader](https://www.isecpartners.com/tools/mobile-security/pysimreader.aspx)



Vulnerability Databases:
* [Common Vulnerabilities and Exposures (CVE®) for Android](http://cve.mitre.org/cgi-bin/cvekey.cgi?keyword=android)
* [Android - CVE Details](http://www.cvedetails.com/product/19997/Google-Android.html?vendor_id=1224)
* [All vulnerabilities - Android Vulnerabilities](http://www.androidvulnerabilities.org/all)
* [NVD](http://nvd.nist.gov/) - US National Vulnerability Database
* [CERT](http://www.us-cert.gov/) - US Computer Emergency Readiness Team
* [OSVDB](http://osvdb.org/) - Open Sourced Vulnerability Database
* [Bugtraq](http://www.securityfocus.com/) - Symantec SecurityFocus
* [Exploit-DB](http://www.exploit-db.com/) - Offensive Security Exploit Database
* [Fulldisclosure](http://seclists.org/fulldisclosure/) - Full Disclosure Mailing List
* [MS Bulletin](https://technet.microsoft.com/security/bulletin/) - Microsoft Security Bulletin
* [MS Advisory](https://technet.microsoft.com/security/advisory/) - Microsoft Security Advisories
* [Inj3ct0r](http://1337day.com/) - Inj3ct0r Exploit Database
* [Packet Storm](http://packetstormsecurity.com/) - Packet Storm Global Security Resource
* [SecuriTeam](http://www.securiteam.com/) - Securiteam Vulnerability Information
* [CXSecurity](http://cxsecurity.com/) - CSSecurity Bugtraq List
* [Vulnerability Laboratory](http://www.vulnerability-lab.com/) - Vulnerability Research Laboratory
* [ZDI](http://www.zerodayinitiative.com/) - Zero Day Initiative
