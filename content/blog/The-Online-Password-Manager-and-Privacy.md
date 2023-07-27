---
title: "The Online Password Manager and Privacy"
date: 2022-01-06T11:18:32+06:00
featureImage: images/blog/blog-thumb-1.jpg
tags: ["News", "Web Security"]
---

  Most of the Internet users do not know how to manage their passwords well for the plenty of websites online. Experienced Internet users have chosen Online Password Managers to simplify the complexity and experience the conveniences. But nothing is perfect. 

### The privacy issue of the popular online Password Managers
- 1Password has none, KeePass has none… So why are there seven embedded trackers in the LastPass Android app? [1]
- LastPass for Android Includes 7 Third Party Trackers and Earlier Versions Had More [Updated] [2]
- LastPass Android App Contains 7 Trackers [3]
- Security researcher recommends against LastPass after detailing 7 trackers [4]

>

### The idea of Password Manager

Even though Password Manager is a good solution, how can I use it wisely? 
Let’s start with the pain points that Password Manager solves for users

- Single Password Breach Risk

  Almost every website has the potential to compromise passwords to some degree, including online password manager sites, and websites do not really keep your data and privacy as safe as promised in user contracts or privacy protection pages. Whether for technical reasons or for human factors, there are many websites that have leaked their databases after which Internet users’ login or identity information is listed for sale on the dark web. Based on this supporting information, this can greatly increase the likelihood that your other accounts will be compromised by Internet miscreants, such as bank accounts, credit card information, email accounts, iCloud accounts, Google accounts, Microsoft accounts, and even your home camera access accounts. Obviously, this makes using the same password several exponential times higher than the risk level of setting different passwords for different websites.

- Risk of plaintext storage

  As one of the most common risks of losing a cell phone, the loss of a cell phone means the loss of the SIM. SMS is the most common means of password recovery in many cell phone settings, and it is possible to read SMS messages without unlocking the phone screen. In addition, if you use the phone Note app storage, the password is not encrypted by the program, if the phone password is obtained, by accessing the phone device can access the corresponding information. If the other party controls the cloud where it is located (Google, Microsoft, iCloud) also increases the possibility of accessing the password file, because the files on the phone are usually synchronized to the cloud.

- Complex Password Generation

  Because of the requirement for password complexity, and the different encryption algorithms, password managers come with a password generator function to facilitate password generation.

### Password management strategy

  The best practice for password management should be a reliable password management tool plus a controllable password grading strategy. Through such a loosely coupled structure, it is possible to effectively protect your password.

#### Password classification
>
**Level I information**

- Bank and investment login information
- Email account information
- Cell phone account related
    - Apple ID
    - Google ID
- Computer login password
- Cell phone unlock password
>
The above belongs to the basic information, or used to recover the password to use. It is recommended to use a password generator to generate a password for each account, stored inside a special local password manager with a good memory, using the brain to remember the best.

**Level II information**

- Consider using a privacy-friendly online password manager such as Bitward.com.
- General Internet accounts such as Netflix, Disney, etc.
>
Other account information and server information that is not used to restore access.

### Open-Source Solutions

Here we do not talk about the way to use traditional password book, this is the best way to protect privacy, in some occasions is still necessary. So besides online password management software like Lastpass, what other open source software options do I have?

**Software recommendation**

- Keepass [5] open source software, with clients for each system.
- Bitwarden [6], open source software, self-hosted server in office/home service/private cloud. Self-hosted on Raspberry Pi can also run smoothly, with a mobile app client.
>

### Conclusions

The best practice for password management should be a reliable password management tool plus a controllable password grading strategy. Through such a loosely coupled structure, it is possible to effectively protect your password.

The link above mentions that LastPass, one of the most popular modern online Password Manager, a software that stores users’ passwords, is tracking and collecting many of information about users’ devices, geographic information, and various other meta information to track users. Obviously it’s not just a diagnostic application as the official says, it’s a data analysis service to make a profit, otherwise how to pay for its “free” users.

### Reference

- [1] [1Password has none, KeePass has none… So why are there seven embedded trackers in the LastPass Android app?](
https://www.theregister.com/2021/02/25/lastpass_android_trackers_found/)
- [2] [LastPass for Android Includes 7 Third Party Trackers and Earlier Versions Had More [Updated]](
https://www.groovypost.com/unplugged/lastpass-for-android-includes-7-third-party-trackers-earlier-versions-had-more/)
- [3] [LastPass Android App Contains 7 Trackers](
https://www.pcmag.com/news/lastpass-android-app-contains-7-trackers)
- [4] [Security researcher recommends against LastPass after detailing 7 trackers](
https://www.theverge.com/2021/2/26/22302709/lastpass-android-app-trackers-security-research-privacy)
- [5] [Keepass](
https://en.wikipedia.org/wiki/KeePass)
- [6] [Bitwarden](https://en.wikipedia.org/wiki/Bitwarden)