## Case studies
This chapter gives examples of case studies that happened in the past, in order to illustrate some of the various ways that social media can be exploited to collect personal information on people, to suppress information, to influence opinions, etc.

### The arrest of Saddam Hussein
The former Iraqi president Saddam Hussein showed up after the fall of his reign in the Al-Adhamiya district in Baghdad at 9th of April 2003, it was his last show on the media, accompanied by a beefy man which he was the main bodyguard for Saddam at the time. The guards where protecting Saddam Hussein from the supporters around him, and then the beefy man went with him into the car; Saddam Hussein disappeared after that day.

> "In the immediate aftermath of Saddam Hussein's capture on Dec. 13, 2003, network theory got a brief moment of glory. The Washington Post ran a [story](http://pqasb.pqarchiver.com/washingtonpost/access/499330771.html) about the role of "link diagrams" in Hussein's capture, and a handful of other articles made reference to the chart that Jim Hickey and Brian Reed had constructed." ([1](http://www.slate.com/articles/news_and_politics/searching_for_saddam/2010/02/searching_for_saddam.html))

The U.S intelligence services considered The Colonel Mohammed Ibrahim Al-Musslit - or "The Fat Man" as they called it - will be the primary gate to access Saddam Hussein's place, and on that basis, U.S Intelligence has to bring experts in the analysis of social networks in order to find Saddam.

The story began when the social networking experts draw the family and friends tree for Saddam's bodyguard (Fat Man) and trying to find and do the same for the closer people in the network. 
Indeed, arrests began, according to the network's levels closest to the Fat man, starting from the sons of his brother through to his younger brother. 
The Wanted list at that time included 20 names of people who U.S Intelligence studied their movements too, and discovered that most of them were providing support for Saddam Hussein. 
This support ranged between daily needs coordination and coordination of movement for the relocation.
All the previous analyzes, had been done in less than 24 hours after the first arrest in the network, brought intelligence by tracking phone call for the "Fat Man", which in turn, under Pressure, he directed U.S the hiding place of Saddam Hussein which it was farm, then they found him hiding underground.

### Investigation on staff in charge of surveillance and censorship in Syria
Around the affair of the [Fortinet devices present in Syria](http://bluecabinet.info/wiki/Blue_cabinet/Fortinet/Syria) under the control of the Syrian government, investigations allowed to pinpoint a few names of people responsible or potentially responsible of being charge of those devices.

The peculiarity of this investigation is that, unlike the capture of Saddam Hussein, it did not involve any official authorities with special capabilities or allowances. Information was obtained for its greatest part by searching into publicly available data and combining it with informal discussions (on publicly reachable IRC networks and channels) and to a lower extent privately obtained intelligence.

It led to the very precise identification of a [small number of people](http://bluecabinet.info/wiki/Blue_cabinet/Fortinet/Syria#People_involved_in_massive_surveillance) closely involved with the regime's surveillance and censorship systems, to some of their relationships and to a large part of their past which enabled to understand more deeply their relations with the central power.

Publicly available exploited information included:

- Facebook pages to retrieve information on people's past, political orientation, job, etc.;
- published PGP signatures as an evidence of closeness between two key people;
- websites of institutions such as schools, companies and events like conferences to further identify the persons' background and social environment;
- information from DNS _whois_ databases.

### The DarkComet RAT dissemination to Syrian activists via Skype and Facebook
Syrian authorities spread to anti-regime groups and activists links to a malicious application called DarkComet RAT. It is a software that allows to fully monitor and access a computer remotely (opened windows, keystrokes, hard disk content, etc.). In the Syrian context, its goal is to catch more social media credentials in order to access data that people aim at keeping private: conversations, contact lists, etc.

In this case, social media is seen by the regime both as a way to spread a malicious applications and as a target to fetch more personal data.

To push people to download the software application, the main idea is to abuse their credulity. The regime used, for instance, these methods:

- registering fake Facebook accounts and spreading messages saying that the software linked [would actually protect activists against regime's intrusion attempts](https://www.eff.org/deeplinks/2012/05/fake-skype-encryption-tool-targeted-syrian-activists-promises-security-delivers);
- using activists' accounts (stolen, for instance, after torturing them to obtain their password) and benefiting of their trusted position from their contact to spread malicious links, saying in the same way that it would protect them against regime's intrusions;
- making a [fake Youtube page](https://resources.telecomix.ceops.eu/material/reports/2012-03-07-fake-youtube-spyware.jpg) and advertising it as showing regime's violence, but asking the user to download a fake "Flash update" on the page it self, fake update which contains the malware;
- building a variety of other fake pages to fool users into downloading the software;
- embedding the malicious software in a good-looking software installer to avoid users' suspiscion after installing it.

It has been reported that people were trapped and imprisoned as a result of the spreading of this malware.

### Collaboration of Microsoft and Ben Ali's Tunisia to eavesdrop on activists' connections to social media
In this case, social media activity is targeted by the use of eavesdropping equipment and software by authorities. By eavesdropping on internet traffic, Tunisian authorities were able to catch, among a lot of other data, users' credentials on websites, in turns use to infiltrate accounts and gather more information.

Such eavesdropping is very easy to setup in an infrastructure like in Tunisia because all the internet traffic leaving the country passes through the same physical place under direct control of authorities. Observing passively the traffic is a silent operation for any who is located where it passes.

Decent social media services must provide the possiblity to use an end-to-end secure connection (_HTTPS_ for _HTTP over SSL_), theoretically preventing traffic eavesdropping by third parties located between the user's station and the end website. For instance, Facebook and Twitter use _HTTPS_ connections by default. For a third party to pierce through a SSL encrypted connection, passive monitoring is not enough: it requires an active traffic perturbation called [Man-in-the-Middle attack](https://en.wikipedia.org/wiki/Man-in-the-middle_attack) (MITM) which, in normal conditions, implies that the user will have a warning displayed on his browser.

However, in Tunisia, [Microsoft and Ben Ali's government](https://en.wikipedia.org/wiki/Microsoft_Tunisia_Scandal) concluded a commercial partnership which led Microsoft to ship [a special version of their browser Internet Explorer that allowed the Tunisian government to perform MITM attacks on encrypted connections](https://news.ycombinator.com/item?id=2138565) without yielding any warning on users' browsers.

In short, not only the Tunisian government was known to eavesdrop on non-secure traffic, but through their collaboration with a Western company they could eavesdrop on a traffic that users were legitimately thinking to be secure, with dramatic consequences.


