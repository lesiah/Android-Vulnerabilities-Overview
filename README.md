Android Vulnerabilities Overview (AVO) is a databse of known security vulnerabilities in Android.

The vulnerabilities database is splitted into seperate files to get an better/cleaner overview. 
The current list is avaible over [here](https://github.com/CHEF-KOCH/Android-Vulnerabilities-Overview/blob/master/2016.md).



_The security flaw gives hacker ability to spy on Android smartphone owners, steal login credentials, install malware, and many more, according to the latest research conducted by the researchers at the Pennsylvania State University and FireEye._



Contact
------------

Found something that isn't on the list? - Feel free to submit, maintainers/contributors are always welcome! 

Want to communicate secure, feel free - my eMail public key is stored in the 'eMail.txt' file.



Warning
--------

* Do not install security updates like _CVE-2015-1538.apk_ from untrusted sources! It's a trap! Security updates are rolled out by Google Play-services or as ROM directly from your provider and never comes as single .APK!


Attacks
--------

* Ransomware (User needs to confirm the device admin part)
* Distributed Denial of Service (DDoS)
* [Cyber-attacks](https://en.wikipedia.org/wiki/Cyber-attack) like (mass) surveillance (e.g. directly on telecommunication infrastructures), worms, viruses, trojans, ...
* Hijacking in Android is a common problem
* Cyberterrorism (Data Theft, DOS, ...)
* Remote Access Tools (RATs)
* Based on fingerprinting to _sniff_ metadata
* Other data leakage, exploits, ...
*  ...


Spyware Capabilities
--------

* Listening in to telephone conversations
* Accessing the Internet
* Viewing and copy contacts
* Installing unwanted apps
* Asking for location data
* Taking and copying images
* Recording conversations using the microphone
* Sending and reading SMS/MMS
* Disabling Anti-Virus software
* Listening in to chats via messaging services (Skype, Viber, WhatsApp, Facebook and Google+)
* Reading the browser history



Infected apps with Backdoors, Loggers or Ransomware
--------

* [Adult Player](http://bitcoinist.net/adult-player-android-app-takes-photos-users-extorts-money/) (not avb. via Google Play Store)
* FreePorn
* [LockerPin](http://www.welivesecurity.com/2015/09/10/aggressive-android-ransomware-spreading-in-the-usa/) (Ransomware)
* [Kemoge Malware which infects several apps]()https://www.fireeye.com/blog/threat-research/2015/10/kemoge_another_mobi.html), see all [affected apps](https://www.fireeye.com/blog/threat-research/2015/10/kemoge_another_mobi.html)
* Ghost Push, Braintest, Guaranteed Clicks, RetroTetri based on [Kemoge Malware](http://www.cmcm.com/blog/en/security/2015-10-10/814.html)


How to Get Rid of Android Ransomware?
--------

1. Boot your device into "Safe Mode," as it boots your device with default settings without running any third-party applications and allowing users to delete malicious software.

2. To uninstall the ransomware from your device, you need to first remove administrator privilege by going to Settings –> Security –> Device Administrator and then select ransomware app and deactivate it.


3. Once this is done, you can again go to Settings –> Apps –> Uninstall ransomware app.

4. (**optional**) If above steps not working, you can try to use an Ransomware Decryption and Malware Removal ToolKit from Google Play or search on the www how to get rid of it.  


General words aboout it and already can lower the attacks:

* Don't install apps from outside of the Google Play Store or F-Droid (no, also not from Aptoide!)
* Don't grant administrator privileges to apps unless you truly trust them!



Generally apps that often comes with security risks (due popularity and other weaknesses)
--------

* [WhatsApp Security Vulnerability (telegraph.co.uk)](http://www.telegraph.co.uk/technology/internet-security/11850817/WhatsApp-security-breach-lets-hackers-target-web-app-users.html) - this is only one example!



Research
--------

* [Official Android Security Updates News](https://groups.google.com/forum/#!forum/android-security-updates)
* [News from SecurityWeek](http:/www.securityweek.com)
* [Security | Android Open Source Project](https://source.android.com/devices/tech/security/)
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
* [The Difference Between a Vulnerability Assessment and a Penetration Test (danielmiessler.com)](https://danielmiessler.com/essays/vulnerability_assessment_penetration_test/)
* [Why SIM Cards Are at Risk--Rising Threat from Differential Power Analysis (semiengineering.com)](http://semiengineering.com/rising-threats-from-differential-power-analysis/)
* [Base clean architecture Android MVP (github.com)](https://github.com/thiagokimo/Base)
* [Muni.cz](https://www.muni.cz/research/publications/)
* [Securityinabox](https://securityinabox.org/)
* [Google Security Research](https://code.google.com/p/google-security-research/)
* [Stagefighter Source releases](https://blog.zimperium.com/the-latest-on-stagefright-cve-2015-1538-exploit-is-now-available-for-testing-purposes/) + [Source direct link](https://raw.githubusercontent.com/jduck/cve-2015-1538-1/master/Stagefright_CVE-2015-1538-1_Exploit.py)
* [AT&T says malware secretly unlocked hundreds of thousands of phones (techworld.com)](http://www.techworld.com/news/newswire/att-says-malware-secretly-unlocked-hundreds-of-thousands-of-phones-3625782/)
* [Most vulnerable Operating Systems and applications in 2014](http://www.gfi.com/blog/most-vulnerable-operating-systems-and-applications-in-2014/)
* [Discovered the first Android ransomware that sets the PIN lock (welivesecurity.com)](http://www.welivesecurity.com/2015/09/10/aggressive-android-ransomware-spreading-in-the-usa/)
* [The Android device fragmentation is getting, beautifully, out of control (opensignal.com)](http://opensignal.com/reports/2015/08/android-fragmentation/)


Papers
--------

* http://www.mcafee.com/us/resources/white-papers/wp-defeating-ssl-cert-validation.pdf
* https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-ren-chuangang.pdf
* http://www.pwc.com/en_US/us/financial-services/regulatory-services/publications/assets/sanctions-cyber-crime.pdf
* [Fingerprinting Web Application Platforms by Variations in PNG Implementations [pdf] (github.com)](https://github.com/isislovecruft/library/blob/master/computer%20science%20theory/Fingerprinting%20Web%20Application%20Platforms%20by%20Variations%20in%20PNG%20Implementations%20%282015%29%20-%20Bongard.pdf)
* https://mjanja.ch/2013/11/disabling-aes-ni-on-linux-openssl/
* http://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/Documentation/stable_api_nonsense.txt
* [Security Metrics for the Android Ecosystem](https://www.cl.cam.ac.uk/~drt24/papers/spsm-scoring.pdf)
* [Android Compatibility Definition Document v2015](https://static.googleusercontent.com/media/source.android.com/en//compatibility/android-cdd.pdf)


Videos
--------

* [This Mind-Blowing Hack allows Anyone to Control your Phone From 16 Feet Away](https://youtu.be/l9txd4a4tUE) (no CVE since this is by design from Google Now, but still a hack/problem)
* ['Shedun' gaining accessibility service privileges](https://www.youtube.com/watch?v=VDWmEUm6mQM)


Online tests
--------

* [FREAK test](https://freakattack.com/)
* [Panopticlick (Browser Fingerprint test)](https://panopticlick.eff.org/)
* [filldisk](http://www.filldisk.com/)
* [SSL Client test](https://www.ssllabs.com/ssltest/viewMyClient.html)
* [Evercookie test](http://samy.pl/evercookie/)
* [BrowserSpy.dk (Browser Fingerprint test)](http://browserspy.dk/)
* [Testing mixed content](https://people.mozilla.org/~tvyas/mixedcontent.html)
* [WebRTC check](http://mozilla.github.io/webrtc-landing/)
* <s>[Adobe Flash player version detector](https://www.adobe.com/software/flash/about/) no Flash support since Android 4.x</s> if you need it use FlashFox or Dolphin Browser
* [IP check](http://ip-check.info/?lang=en)
* [CORS and WebSocket test](http://cure53.de/leak/onion.php)
* [Browserrecon](http://www.computec.ch/projekte/browserrecon/)
* [WebGL check](http://get.webgl.org/)
* [Battery.js test](https://pstadler.sh/battery.js/)
* [RC4 fallback test](https://rc4.io/)
* [Battery API check](https://robnyman.github.io/battery/)
* [Testing TLS/SSL encryption (testssl.sh)](https://testssl.sh/)



Kernel
--------

* [Kernel Overview | Android Developers](https://source.android.com/devices/tech/kernel.html)
* [Kernel Security Overview | Android Developers](https://source.android.com/devices/tech/security/overview/kernel-security.html)


'Security' (pentesting) Apps
--------

* [Stagefright Detector App by Zimperium](https://play.google.com/store/apps/details?id=com.zimperium.stagefrightdetector)
* [TextSecure](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms&hl=en) (SMS encryption was removed)
* [RedPhone](https://play.google.com/store/apps/details?id=org.thoughtcrime.redphone&hl=en) (Stores the private key on there servers)
* [Crypt4All Lite (AES) - (Free File Encryption Software)](https://play.google.com/store/apps/details?id=com.codewell4.Crypt4AllLite)
* [Orbot](https://play.google.com/store/apps/details?id=org.torproject.android) alias Tor for Android 
* [(AppLock (Free Application Lock Utility)](https://play.google.com/store/apps/details?id=com.domobile.applock)
* [App Ops (Free App Permission Manager)](https://play.google.com/store/apps/details?id=com.findsdk.apppermission) On Android 6 (Marshmellow) obsolete
* [LastPass Password Manager Premium (Free)](https://play.google.com/store/apps/details?id=com.lastpass.lpandroid) personally I prefer [KeePass - alias KeePassDroid](https://play.google.com/store/apps/details?id=com.android.keepass&hl=en)
* [K-9 Mail (Free Secure Email Encryption Software)](https://play.google.com/store/apps/details?id=com.fsck.k9&hl=en) - I prefer [K-@ Mail Pro](https://play.google.com/store/apps/details?id=com.onegravity.k10.pro2&hl=en) [it's based on K-9 Mail but with a _better_ gui]
* [Android open source apps overview | GitHub](https://github.com/pcqpcq/open-source-android-apps)
* MyLocalAccount (app that doesn't need any cloud to store local contacts)


Forensics analysis software and apps
--------

In most cases Trojans/Malware only sending 'stuff' to there C&C's if you're on wifi (to not getting easier detected by the bandwith consumpation itself), of course they often drain your battery, so some tools are to detect such cases and identifys them (like Hush) such tools can be used to reveal what exactly going on behind the scenes. 

* [Androick](https://github.com/Flo354/Androick)
* [Android Forensics Open Source Android Forensics App and Framework](https://github.com/viaforensics/android-forensics)
* [Android Data Extractor Lite](https://github.com/mspreitz/ADEL)
* [BitPim](http://www.bitpim.org/)
* [LiME](https://github.com/504ensicsLabs/LiME)
* [OSAF - Open Source Android Forensics Community](http://www.osaf-community.org/)
* [P2P-ADB](https://github.com/kosborn/p2p-adb/)
* [Appie](https://manifestsecurity.com/appie)
* [Mobisec](http://sourceforge.net/projects/mobisec/)
* [pySimReader](https://www.isecpartners.com/tools/mobile-security/pysimreader.aspx)
* [Pixiewps](https://github.com/wiire/pixiewps)
* [Android Vulnerability Test Suite (github.com)](https://github.com/nowsecure/android-vts)
* [catch-it-quick - catch the firmware malware and spyware](https://code.google.com/p/catch-it-quick/)
* [Google Remote Encryption and wipping function analyzed](http://manhattanda.org/sites/default/files/11.18.15%20Report%20on%20Smartphone%20Encryption%20and%20Public%20Safety.pdf) see [here](https://plus.google.com/+AdrianLudwig/posts/JFPXLnV3M2f)



Vulnerability Databases
--------

* [KB.cert.org](https://www.kb.cert.org/vuls/id/924951) - KB Cert
* [Common Vulnerabilities and Exposures (CVE®) for Android](http://cve.mitre.org/cgi-bin/cvekey.cgi?keyword=android) - CVE Mitre
* [Android - CVE Details](http://www.cvedetails.com/product/19997/Google-Android.html?vendor_id=1224) - CVE Details
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
* [Exploit Exercises](https://exploit-exercises.com/) - Exploit Exercises
* [Seclist.org](http://seclists.org/fulldisclosure/2015/) - Seclist



Known Pre-Installed Backdoors (within firmware)
--------

* [CoolReaper](https://public.gdatasoftware.com/Presse/Publikationen/Malware_Reports/G_DATA_MobileMWR_Q2_2015_EN.pdf) (China and Taiwan)


Backdoor Discussion
--------

* [AB1681 suggestion](http://www.leginfo.ca.gov/pub/15-16/bill/asm/ab_1651-1700/ab_1681_bill_20160120_introduced.html)
* [Cooper Introduces Human Trafficking Evidentiary Access Legislation](http://asmdc.org/members/a09/news-room/press-releases/cooper-introduces-human-trafficking-evidentiary-access-legislation)
* [Assembly Bill A8093](http://www.nysenate.gov/legislation/bills/2015/a8093)

‘Stingrays’ Cell Phone Trackers
--------

Stingrays, made by the Harris Corporation, has capabilities to access user's unique IDs and phone numbers, track and record locations, and sometimes even intercept Internet traffic and phone calls, send fake texts and install spyware on phones. 
The authorities used these tracking tools for years to breach people's privacy and did everything to keep even the existence of these devices out of the public eye. They even avoid telling judges when they used them.

* [2015 FBI Statement](http://www.justice.gov/opa/pr/justice-department-announces-enhanced-policy-use-cell-site-simulators)
* [Confirmation](https://www.aclu.org/news/aclu-comment-new-justice-department-guidelines-secretive-stingray-surveillance-devices) & [full source](http://www.justice.gov/opa/file/767321/download)



Firewall Leak Tests
--------

* Not avb. for Android? (only some common pages but not really proper designed for Android)
* [2015 FBI Statement](http://www.justice.gov/opa/pr/justice-department-announces-enhanced-policy-use-cell-site-simulators)
* [Confirmation](https://www.aclu.org/news/aclu-comment-new-justice-department-guidelines-secretive-stingray-surveillance-devices) & [full source](http://www.justice.gov/opa/file/767321/download)
