**Note, 26 June 2024** - this guide has languished for a bit. Some of the advice is still useful. Some of it is woefully out of date. I'll be updating it over the next few weeks/months to bring it current. When it's ready to go, I'll remove this note. **End Note**

Conversations about privacy and security often focus on technology and give scant attention to the human, non-technological factors that affect personal privacy. This post covers a range of concrete steps we can all take to regain control over what, when, and with whom we share. Some of the things we discuss will involve technology, and some of them won't. The majority of the suggestions we make involve tools or practices that are freely available. The vast majority of things we suggest are also designed to be accessible without a large amount of technical knowledge. The steps we outline here are intended as a solid starting point, and not a comprehensive solution, but with that said, the steps we define here minimize or eliminate many common issues.


Assessing Risk
--------------

When we think about protecting our privacy, we generally start with these questions:

-   What are you trying to keep private?
-   From whom are you trying to keep it private?
-   What are the consequences if the protections fail?
-   Do the consequences change or shift over time (short-, medium-, long-term)?
-   How much effort are we willing to put into making any needed changes?

These factors can help determine our priorities: What information is most important to protect? Why? How much effort should be put into protecting something? Should we prioritize easy changes over things that might be more important, yet more complicated? The right path will vary person by person, and that's normal. It's also normal to start down one path and change. Do what feels right, and do what's possible.

Use the questions listed above to structure decisions. In the conversations below, we will highlight how easy or hard some changes are to make.

In Person/Face-to-Face
----------------------

There are a range of ways people can access information if they're physically close to you. In this section, we will highlight ways to minimize the risk of people seeing information they don't need to see.

At the outset, I want to highlight that going into a public space means you will be caught up in [some form of observation](https://www.youtube.com/watch?v=npM-tWbyyiI). This can be as benign and accidental as being in the background of someone's photo in a public place, getting captured in a person's connected doorbell (ie, Ring, etc), or it could be as focused as having your [license plate scanned](https://www.aclu.org/feature/you-are-being-tracked) as part of [data collection by law enforcement](https://sls.eff.org/). It's also worth remembering that many public places (most stores, malls, supermarkets, gas stations, public transit, and the like) are covered by closed-circuit television cameras.

If you are accessing or working in a public space, one of the most common ways that people can get information about you is by watching your screen as you work. This hallmark of the perpetually nosy -- also known as "shoulder surfing" -- can range from simply annoying to potentially dangerous, depending on what you're doing. It's not difficult to imagine web searches where we wouldn't want some stranger, sibling, uncle, or other person reading over our shoulder.

Fortunately, a [privacy screen](https://duckduckgo.com/?q=computer+privacy+screen) will block shoulder surfing. For other people who work in public spaces -- from coffee shops to offices and libraries -- the following steps can minimize your risk:

-   If you're working and you leave your computer, lock your screen with your password or power it down. If you leave a computer when you're still logged in, anyone can sit down and access your computer and use all the information it has. Better yet, if working in a public space, don't leave your computer or phone unattended. The hassle from carrying your tech with you when you step into the bathroom is dwarfed by the hassle of having your stuff stolen, or your information compromised. **Note**: locking your desktop when you leave your desk/workspace applies for working in an office as well.  
-   Encrypt your hard drive on your computer. Instructions for [Mac](https://support.apple.com/guide/mac-help/protect-data-on-your-mac-with-filevault-mh11785/mac), instructions for [Windows](https://support.microsoft.com/en-us/windows/device-encryption-in-windows-ad5dcf4b-dbe0-2331-228f-7925c2a3012d), instructions for [Ubuntu linux](https://ubuntu.com/tutorials/install-ubuntu-desktop#6-type-of-installation). If your computer is lost or stolen, having an encrypted hard drive will prevent unauthorized access to any information on it. It's worth noting that encrypting your hard drive will not mean much if you have a weak password for your login.
-   If you're using a newer iPhone or iPad or a newer [Android device](https://source.android.com/docs/security/features/encryption), then your device is likely already encrypted by default. If you use an iPhone and are at higher risk, or if you want to experiment with a more secure setup, try [Lockdown mode](https://support.apple.com/guide/iphone/use-lockdown-mode-iph049680987/17.0/ios/17.0). Encrypting your phone or tablet prevents access to information stored on the device in case of loss or theft. It's worth noting that encrypting your phone will not mean much if you use fingerprint unlock or a weak password. It's also worth noting that protections on the device can be undermined by backing up to cloud based storage, or by installing apps with overly broad permissions. We talk about additional protections available on phones later in this writeup.
-   If you use external storage (ie, any USB storage), encrypt the drive and use a strong passphrase to protect it. [Windows instructions](https://www.howtogeek.com/encrypt-usb-flash-drive-windows/), [Mac instructions](https://support.apple.com/guide/disk-utility/encrypt-protect-a-storage-device-password-dskutl35612/mac), [Linux instructions]().
-	Be careful with -- to the point of never using -- [external USB storage](http://www.computerworld.com/article/2514934/security0/1-in-4-worms-spread-through-infected-usb-devices.html) where you do not know the source of the drive. This especially applies to any drive you find, but also to drives that vendors "helpfully" give out as swag at conferences. If you haven't bought the drive yourself from a vendor you trust, don't connect it to your computer. This also can apply to situations where someone asks you to print a file for them off a USB key. It can be awkward to say "no", but we are often only as secure as our least secure friend or relative.
-   Use a [password manager](https://en.wikipedia.org/wiki/Password_manager). At first blush, this doesn't seem to make a lot of sense for inclusion in a section on potential risks from someone being in the same physical space as you, but using password managers solves one common problem: writing usernames and passwords on paper where they can be read, photographed, or used by unauthorized people. (Fact: I have seen usernames and passwords written on a whiteboard get included in promotional videos.) Password managers are covered in more detail later in this blog series.

There are other steps you can take to minimize risks that arise from physical access, but using a **privacy screen**, **encrypting** devices, not leaving devices **logged in while they're unattended**, and being **careful with external storage devices** can eliminate many common issues. Privacy screens cost between $15 and $60, and the other options discussed today are free. As we stated at the outset, eliminating all risk is impossible, but these steps can reduce risks to which we're all commonly exposed.

General Maintenance When Using a Machine that Connects to the Internet
----------------------------------------------------------------------

Part of maintaining the security of our devices -- and our privacy -- involves making sure that our device or computer software is up to date.

On any device -- a phone, laptop, desktop, or tablet -- every installed app or service is (theoretically, potentially) an attack vector. Because of this, make sure that you only retain the apps and services you need and want on your device. If you tried out an app but didn't continue using it? Delete the app. You can't be compromised via a service that isn't installed. 

The first time you run through the Great Deletion, it might take a while, but once you make a first pass and delete unused apps, maintaining a cleaner device will be easier. It's similar to cleaning your kitchen -- not necessarily fun, but necessary, and you feel good afterwards. 

One additional note: deleting apps from your device does not delete any accounts associated with the service. You can delete an app while still retaining the account. I do this with travel apps from airlines; I delete them when I'm not flying for privacy reasons, and re-install them when I'm going to be travelling for work.

Opinions vary widely on the protections offered by malware and anti-virus software. The distrust and ambiguity has been exacerbated by the industry itself -- for example, [Avast sharing user data collected via their antivirus product](https://www.consumerreports.org/electronics/privacy/avast-shutters-data-selling-subsidiary-in-wake-of-privacy-complaints-a9105985168/) with an adtech company, [Norton Lifelock accounts being compromised](https://techcrunch.com/2023/01/15/norton-lifelock-password-manager-data) via credential stuffing, and nation state actors [compromising antirus by hijacking updates](https://www.bleepingcomputer.com/news/security/hackers-hijack-antivirus-updates-to-drop-guptiminer-malware/). Because anti-virus and anti-malware needs to see nearly everything happening on a device, it's an attractive target. 

Because of these issues, I do not have any specific recommendations for antivirus or anti-malware software. For some people -- especially people on Windows machines -- it can make sense. For others, it might not. The one thing I will say, which is less of a recommendation and more general advice: if you are running Windows, look at the options that are packaged with the operating system. Because you are already running Windows, you are effectively trusting Microsoft, and therefore, enabling any anti-virus and anti-malware that comes with Windows doesn't not substantially alter the reality that by virtue of using Windows you have no real option but to trust Microsoft.

Install operating system and software updates in a timely way. 
- [Windows FAQ](https://support.microsoft.com/en-us/help/12373/windows-update-faq) 
- [OSX FAQ](https://support.apple.com/en-us/HT201541).

Safe(r) Browsing
----------------

Going online exposes us to the [wonderfulness of the internet](https://duckduckgo.com/?q=omg+cat+videos&ia=videos), but that wonderfulness also brings the fetid practice of tracking and behavioral-advertising technology. Due to the [ongoing](http://arstechnica.com/security/2016/03/big-name-sites-hit-by-rash-of-malicious-ads-spreading-crypto-ransomware/) and [well-documented](http://www.computerworld.com/article/2987036/application-security/after-pushing-malware-ad-networks-also-used-for-ddos.html) overlap [between malware](https://threatpost.com/ad-networks-ripe-for-abuse-via-malvertising/111840/) and [adtech](http://www.theverge.com/2015/8/25/9202301/advertising-malware-malvertising-statistics-flash-vulnerability), we document protections against tracking as an effective [defense against exposure](http://www.businessinsider.com/android-malware-spreads-using-google-adsense-advertising-network-kaspersky-researchers-2016-8) to [various forms](https://arstechnica.com/security/2024/06/mac-info-stealer-malware-distributed-through-google-ads/) of malware.

And even if adtech wasn't commonly used to deliver malware, it should still be blocked for one core reason: unnamed companies, who we don't know, who haven't asked our consent, who don't have our best interests at heart, have no right to know what I'm doing online. I don't go online so The Trade Desk can exist. The data broker and adtech industries justify their ever-expanding quest to collect and retain more information about us with the disingenuous question of "where is the harm?"

When you hear this question, know that you are conversing with someone who -- either intentionally or unintentionally -- is parroting industry talking points. The better questions are "what is the need?" and "who benefits?" and "why is it necessary?" The answers to these questions help center the conversation in a way that values people over corporations, and exposes the surveillance embedded in many of the business models supporting adtech and data brokers.

### Choosing a Browser

Choosing a browser is becoming increasingly difficult. Firefox used to be a reliable choice, but with Mozilla's push into AI, the wisdom of using Firefox for the indefinite future is open for debate. 

I don't recommend using Chrome. Google has been threatening/promising to remove cookies for years, which sounds like a win for privacy, but will generally be a [win for Google](https://www.eff.org/deeplinks/2023/09/how-turn-googles-privacy-sandbox-ad-tracking-and-why-you-should).

I recommend splitting browser selection into two types of use: the Everyday browser, and the Research browser.

For the Everyday browser, I still recommend [Firefox](). I [wrote a post](https://archive.funnymonkey.com/2020/browser-hygiene-for-better-privacy---think-of-it-like.html) a few years back that still holds up on how to configure Firefox post-install.

For the Research browser, use Tor and/or the Mullvad browser (which is a collaboration between Mullvad and Tor.)

### Ad Blocking

Browser extension: Install uBlock Origin

Block via DNS: Use a service like [Quad9](https://www.quad9.net/).

As with all the sections in this post and in this series, the options described are not intended to be comprehensive. The full suite of options for securing computers running Windows, Mac OS X, or Linux are outside the scope of this post. However, checking for malware and installing updates regularly can help avoid some common problems. The sections that follow detail different areas that we need to think about when protecting our privacy.

Using Sites Where You Have an Account
-------------------------------------

When we visit any website, we generally are tracked by various methods. In this post, we lump different tracking methods and technologies into a blob that we will call "trackers." Technical differences exist between different types of trackers, but a thorough description of them all is outside the scope of this post.

It's also worth noting that when we go to a site where we have an account (or use an app on our phone that connects us to an account), our use of the service is generally tracked because we willingly identify ourselves to the site. Choosing to log into a site generally means that we are agreeing to be tracked by that site. The privacy policies of these sites describe how they use the data they collect from you. (Note: Most commercial sites can use and share your information with few restrictions, including sharing it with unnamed "partners" and combining it with data from other sources to create detailed tracking profiles.) It is possible to minimize tracking by browsing these sites without logging in whenever possible and only logging in when absolutely necessary.

When using social media, clicking on things such as [quizzes can expose huge amounts of personal data](http://www.bbc.com/news/technology-34922029) to trackers or provide answers to your password-reset security questions. In some cases, the companies behind the quizzes use the data to [compile personality profiles](http://www.nytimes.com/2016/11/20/opinion/the-secret-agenda-of-a-facebook-quiz.html) that are used in political campaigns. Even seemingly [simple things](http://www.pnas.org/content/110/15/5802.full) like the "like" button or [responding via emoji](https://mic.com/articles/136111/facebook-is-using-those-new-like-emojis-to-learn-a-whole-lot-more-about-you#.kVcPepL9g) can allow for fairly precise tracking. Fortunately, avoiding this form of tracking is simple: Stop taking the quizzes, and stop using emoji-based reactions (people [have experimented](https://www.wired.com/2014/08/i-liked-everything-i-saw-on-facebook-for-two-days-heres-what-it-did-to-me/) along [these lines](https://medium.com/swlh/i-quit-liking-things-on-facebook-for-two-weeks-heres-how-it-changed-my-view-of-humanity-29b5102abace#.4y3hmwuv2) in the past).

Criminals continue to [exploit bugs or flaws](http://arstechnica.com/security/2016/11/locky-ransomware-decoy-image-files-boobytrap-facebook-linkedin) on social media sites. While the patterns of different attacks may vary, many attacks can be thwarted by not opening files that you haven't explicitly downloaded from a trusted source. 

But in general, when we create an account on any site, that site will track our behavior or how we use that site to some extent. The best way to avoid this type of tracking is to use sites without logging in whenever possible and to clear your cookies and browser cache frequently. Later in this post, we will cover how to clear cookies and other methods of minimizing tracking.

Clearing your cookies, cache, and browsing history regularly minimizes the amount of data available to trackers (read our instructions for [Chrome](https://support.google.com/accounts/answer/32050?hl=en) and [Firefox](https://support.mozilla.org/en-US/kb/delete-browsing-search-download-history-firefox)).

Blocking JavaScript. In Firefox, the best option for this is [NoScript](https://noscript.net/). Using NoScript will break functionality on some sites.

In addition to these steps, disabling and removing unused browser plug-ins is strongly recommended. In some instances, advertising companies or criminals have bought moderately popular extensions and used them to push trackers and malware. Disabling and deleting unused browser extensions minimizes this risk (read our instructions for [Chrome](https://support.google.com/chrome_webstore/answer/2664769?hl=en) and [Firefox](https://support.mozilla.org/en-US/kb/disable-or-remove-add-ons)).

A final note here involves the use of so-called "private" or incognito browsing. Avoid it. If you want private browsing for everyday activities, use the steps outlined in this section. If you want truly private browsing, use Tor, as described in the next section.

Search
------

https://www.nytimes.com/2024/06/01/technology/google-ai-overviews-rollback.html

https://stract.com/

For many of us, if we have Gmail accounts (either a personal or work account, or both) and we use Google for search, we almost always search when we are logged in to Google. This gives Google a very complete view of what we search for, which allows them to "personalize" searches to what Google thinks we want to see (if you want to see a small subset of what Google knows about you, visit https://myactivity.google.com/myactivity when logged into a Google account. While this is only a fraction of what Google knows about you, a quick scan through your search history is often illustrative and petrifying). "Personalization" ensures that two people searching for the same topic won't get the same results. However, when results are invisibly tailored "for" us, [bias can appear](http://www.bbc.com/news/technology-21322183) in the results. There have also been [substantial charges that Google has abused](http://www.wsj.com/articles/inside-the-u-s-antitrust-probe-of-google-1426793274) its position as a leader in search.

-   [Duck Duck Go](https://duckduckgo.com/)

When searching for sensitive information that you don't want shared, the best approach is to use Tor/Mullvad browser and search via Duck Duck Go. Using this strategy helps protect you from having your personal data collected by data brokers while searching for information.

Email
-----

Email is one of the more convenient ways for bad things to happen to good people. While these steps won't solve all the problems with email, they can help address some of the more common issues. The risks in emails that are delivered to your inbox generally come from aggressive advertising or people trying to steal information, compromise your account, or even install ransomware.

Of course, there is always the low risk of your uncle or cousin sending you that *hilarious* chain email, but protection from that is beyond the scope of this post.

Be wary of links and downloads coming to you via email, even if they appear to come from friends. When you're sending links or files via email, describe what you're sending. This helps the recipients of anything you send know why you're sending it. When you receive a file or a link, look for that context. If all the email says is, "Hey! You gotta check this out!," you should probably avoid the link (and this advice is true for text messages as well).

To avoid a potentially malicious link, review the base URL and verify that it makes sense (mouse over any links before you click on them so you can review the URL that's displayed). People trying to steal your information will create website domains that look "right" but are actually fake (for example, "citibank.co" instead of "citibank.com").

[Expand shortened links](https://duckduckgo.com/?q=expand+short+url) before you click on them. People trying to steal your information will often use shortened URLs to obscure where they're sending you.

Use extreme caution when downloading files, especially [files that are compressed](https://en.wikipedia.org/wiki/List_of_archive_formats) (for example, they end with ".zip," ".gz," ".7z," and the like). Bad downloads are a common way of spreading malware and ransomware. Also, avoid files sent via email that are executable, meaning they can install software on your computer (for example, they end with ".exe" for Windows or ".dmg" or ".app" for Mac OS X).

The advice about using links and being suspicious of file downloads applies directly to using social media as well. Be very wary about expanding links sent via direct or private messages from acquaintances you follow. This is a common attack strategy: Compromise one account, then send malware to all the "friends" of that account.

Set your email client to strip or not display images. Marketers will often embed tracking technology called a "tracking pixel" in emails; by stripping or not displaying images, you can prevent the effectiveness of this tracking method.

Don't hesitate to ask for confirmation from someone about whether or not a message is legitimate. It's better to send a quick email response asking for confirmation than for your system to get compromised.

If you want an encrypted email account, use a service like [Protonmail](https://protonmail.com/). However, when using an encrypted email account, keep in mind that both the sender and receiver of the email need to use an encrypted email service. If you send an email from a Protonmail account to a Yahoo or Gmail account, your email and information will be accessible to the ad scanning in those services.

One of the advantages of a large email provider such as Gmail is they provide solid spam, phishing, and malware protection as a part of their service. For regular consumer accounts with Gmail (not educational accounts), you pay for that protection by allowing Google to scan all your email message content, and you allow Google to use that information to create an advertising profile and market services to you; but if your main concern is avoiding malware and phishing scams, then Gmail offers some benefits.

One "advantage" of both email and cloud-based file storage (discussed below) is that they offer a large amount of "invisible" storage. The more data we retain, the more data that can be compromised or accessed by people for whom that information was never intended. If you have important emails that you need to retain over time, archive them and store them offline and then delete the original emails from your email provider. Deleting old emails minimizes the risk to us and to the people we communicate with. It's good data hygiene.

On a practical level, in some instances email can be used in criminal cases or civil lawsuits. Deleting unneeded emails, and deleting older emails, provides a level of protection against frivolous legal action.

A final note about email: It is only as secure as the person you're sending it to, and the "security" of the message should be assessed against the sensitivity and value of the message. If you're using an encrypted email service and you're sending messages to a person using a personal Gmail account, that email is getting scanned by Google. We generally advise people to consider email an insecure service. Accordingly, sending information about a surprise party is probably pretty safe, whereas sending information about a Dark Family Secret is something you might want to save for an in-person conversation.

Clear Data From Google
----------------------

For people who use Google, you can control (to an extent) what Google retains, or [what Google shows you they retain](https://support.google.com/accounts/answer/7028918). 

While using the options Google provides is better than doing nothing, it's best to think about this as a mitigation strategy that needs to be verified periodically (every 3-6 months) to make sure that Google doesn't change any settings in an "update". If time is an issue, other steps can provide more return for the time required. 

Adjust Privacy Settings (Really, Visibility Settings)
-----------------------------------------------------

There are many posts that show how to lock down accounts. These steps are critical protection against stalkers, abusive partners, scammers, and other predatory and abusive behaviors that are furthered when bad actors access social media and other online accounts.

I'm not linking to any specific guides because the mechanisms change regularly, and any link I shared would be obsolete within weeks, days, or hours. Rather, use this search for the services you want to lock down:

- <code>SERVICE_NAME "privacy" "setting"</code>

The top results will generally highlight some guides, and a link to where you can access the privacy/visibility settings on the service.

For people going through a breakup, there are other factors to consider. I wrote about [this a while back](https://archive.funnymonkey.com/2021/locking-things-down-post-breakup.html), and Yael Grauer [wrote a thorough piece on this](https://www.consumerreports.org/dating-relationships/how-to-reclaim-online-accounts-after-a-relationship-ends-a1025933836/). 

And, while adjusting privacy settings is necessary to protect ourselves from the prying eyes of the general public, "privacy" settings are better understood as visibility settings. They largely govern what people can see, but they have little to no impact on what the company can see. There is no such thing as a privacy setting from Google, Facebook, Instagram, X, Tiktok, LinkedIn, etc. These companies can see information you mark as private, as seen when Facebook shared private messages that were used for [prosecuting people who needed to access medical care](https://www.npr.org/2022/08/12/1117092169/nebraska-cops-used-facebook-messages-to-investigate-an-alleged-illegal-abortion).


Secure Online File Storage
--------------------------

TBD

Virtual Private Networks (VPNs)
-------------------------------

For people who access the internet from outside their home or office, using a virtual private network (or VPN) can provide different levels of protection from a nosy kid playing at hacker on the coffee shop Wi-Fi network or from a person trying to steal private information as part of an attempt at identity theft. VPNs can also obscure which sites a person visits, thus hiding their browsing histories from people who might attempt to access it. Additionally, VPNs hide your IP address, which can make it appear as if you're in a different geographic location, which blocks location-based targeting.

I used to not recommend specific VPNs, because the choice of a VPN involves a range of factors. However, because the VPN space is a mess, and using an unscrupulous VPN can cause real harm, I now recommend Mullvad VPN. There are a few reasons for this, but the shortest version is that in April 2023, Mullvad was served with a search warrant requesting customer data. The police showed up demanding information, and left with nothing: no data, no equipment, nothing, because Mullvad as a matter of policy [didn't have it](https://mullvad.net/en/blog/2023/4/20/mullvad-vpn-was-subject-to-a-search-warrant-customer-data-not-compromised). Mullvad followed up by requesting more information from the authorities that issued the warrant, and then [published that correspondence](https://mullvad.net/en/blog/2023/5/2/update-the-swedish-authorities-answered-our-protocol-request) as well. 

While there are free VPN options, I do not recommend using them, as many of the free VPNs actually track and share your online behavior. A free VPN can cause more harm than good. One clear and obvious example of this is when [Facebook used a VPN they controlled](https://techcrunch.com/2019/01/29/facebook-project-atlas/) to spy on people between the ages of 13-35. In 2016, [researchers showed that multiple vulnerabities existed](https://research.csiro.au/isp/wp-content/uploads/sites/106/2016/08/paper-1.pdf) in free VPNs. These problems in free VPNs [continue to exist and evolve](https://www.bleepingcomputer.com/news/security/free-vpn-apps-on-google-play-turned-android-phones-into-proxies/).

Many companies provide VPNs for their employees. While these VPNs protect against people outside the company seeing traffic, people using a company-provided VPN should know and expect that their company's IT department can see all their online browsing activity and that in many cases that activity is logged.

Increased Anonymity and Tracking Protection
-------------------------------------------

### Tails

For people who work from multiple computers, or who for whatever reason don't want to use their computer or phone to browse privately, [Tails](https://tails.boum.org/) allows you to boot from a USB key and use Tor to browse the web without leaving any trace of your activity on your host computer.

Because Tails can be treated as a throwaway operating system, it offers a level of flexibility other options might not have. Tails can also be useful as a tool to access the internet securely when connecting from places where we might not trust the security of the internet connection.

Tails is a specialized tool that isn't needed by everyone, but it can be useful for people who need to communicate privately from a system that will be difficult to trace, and its preconfigured privacy protections allow people to get started quickly.

### Raspberry Pi

Another option for people who want a private, segmented way to access the internet is to use a Raspberry Pi. The Pi 5 is a very solid machine, and you can set it up as a standalone device to use for specialized work. Using a Pi for specialized work where you don't want to expose your main device can provide a level of safety and flexibility. Getting a Pi 5 (the latest as of June 2024) costs around $100-150 US, depending on the setup of the Pi you get.

Creating "Good" Passwords
-------------------------

Password advice has evolved. Complexity is out. Forced password changes [are out](https://grahamcluley.com/new-nist-guidelines-do-away-with-periodic-password-changes/). Both of these practices contribute to less secure passwords, and password reuse. Passphrases -- multiple random words -- are more effective. Both [NIST](https://www.nist.gov/blogs/taking-measure/easy-ways-build-better-p5w0rd) and [XKCD](https://xkcd.com/936/) agree, which is as close as we can ever hope to get to consensus.

Passphrases consist of multiple words, often with capitalization, often with numbers or special characters. To illustrate the point with two examples:

- Password one: Qevglm&%nGhkjkwjgf9p2479p24hcodh08qehcueh8q
- Password two: Table-Connection-Enigmatic-Squirrel-Manbun5

Both of these passwords are the same length - 43 characters, which is plenty long. One of these passwords is easier to remember, and to type into forms. Password two is a passphrase - basically a password that is just as hard for a computer to crack, but much easier for a human to remember. Choose words that make sense to you -- even made up words. 

Passphrases allow us to have longer passwords, which helps them be more secure.

Password Managers
-----------------

Our advice on password managers is straightforward: Use one. I generally recommend 1Password for sharing between multiple people or devices, and KeepassXC for local use.

I also [do not recommend using LastPass](https://www.wired.com/story/lastpass-breach-vaults-password-managers/).

While no single solution is perfect, password managers eliminate the problems of reusing the same password across multiple sites and using passwords that are too short or too simple. Password managers also generate passwords that are truly random and un-guessable. Additionally, many password managers have a mechanism wherein you can create secure notes to save important information.

To state the obvious, putting all this information in a single location is also a risk; this is why the password manager must also be protected by a strong password and two factor authentication. While writing passwords down is almost never a good idea, writing down only the password to your password manager and your primary device (i.e., computer or mobile phone), and then storing these passwords in a safe location, allows you to have a suitably strong password protecting these key services while eliminating the risk that you will forget the passwords. [This post contains tips](https://theintercept.com/2015/03/26/passphrases-can-memorize-attackers-cant-guess/) on creating both secure and memorable passwords.

Two-Factor Authentication
-------------------------

Two-factor authentication -- also called 2FA, or MFA (multi-factor authentication) -- is based on the idea that we can be more secure if we expand authentication to include two (or more) of the following criteria:

-   something we know (such as a username and password or a security question);
-   something we have (such as a phone, access to an email account, or a USB key); or
-   something we are (such as a fingerprint, an iris scan, a typing pattern on a keyboard, or other biometric indicators).

The most commonly used form of two-factor authentication involves the provider sending a text message to our mobile phone, in a process that works like this:

-   We log into a web site with our username and password;
-   a successful login forwards us to a screen that asks us for a second confirmation code;
-   we receive a text message with a one-time use code; and
-   we enter that code on the screen, and we are fully logged in.

However, there are three main issues with using a text message to support two-factor authentication. First, if one of our concerns is tracking by corporations, this form of two-factor authentication provides a direct connection among us, a mobile phone number, and our account - in other words, when we give Facebook or Twitter our mobile phone number to support two factor authentication, we have told them a phone number that we rely on, which can then be used to track us further.

Second, two-factor authentication can be tricky for people who travel to or live in locations with unpredictable cell phone reception. If our phone can't get an adequately strong signal to receive the text, we're out of luck.

Third, hackers have started to use a technique called [SIM hijacking](https://www.wired.com/2016/06/hey-stop-using-texts-two-factor-authentication/) to actually take over a phone and have texts forwarded to a different phone. While this technique is more complicated and requires a reasonably skilled and determined person to pull off, SIM hijacking appears to be occurring more frequently.

Services such as [Authy](https://www.authy.com/) address some of these issues but still involve sharing data with a third-party company. However, if our primary risk is getting hacked, and corporate or ad tracking is secondary, two-factor authentication via text or via a service provides an additional level of protection.

An additional option that has some advantages over using text or a service is to use a special USB key, such as the one offered by [Yubico](https://www.yubico.com/). These keys don't have the same privacy risks from tracking as other forms of two-factor authentication, which makes them an effective protection against hackers without them compromising other privacy concerns. Yubico keys can also be used to provide two-factor authentication when you're logging into a computer, which is most effective when the [hard drive is encrypted](https://www.commonsense.org/education/privacy/blog/five-days-of-privacy-2016-in-person#in-personface-to-face). Keys sold by Yubico currently cost between $18 and $50 for individuals.

But to summarize, any form of two-factor authentication adds a level of protection against unauthorized access. Using a USB key also protects against hackers and doesn't leak information to the other companies that will use personal information -- such as a phone number tied to an email address and other personal information -- to track us.

Passkeys versus Passwords
-------------------------

Passkeys have been promoted as a way to replace passwords, and all of the security concerns [related to passwords](https://blog.1password.com/passkeys-vs-passwords-differences/). 

[Passkeys](https://fidoalliance.org/passkeys/) have been under development for years, and the initiative to adopt them took on extra steam in 2022 when Google, Apple, and Microsoft [announced support for the standard](https://fidoalliance.org/apple-google-and-microsoft-commit-to-expanded-support-for-fido-standard-to-accelerate-availability-of-passwordless-sign-ins/).

If you use software or services from the major tech companies, Passkeys can have security benefits. Not every web site or service supports passkeys, however, which makes a complete switch for most people impossible. 

Additionally, the usability of passkeys -- like any new-ish technology that aims to replace a legacy technology that we are all familiar with -- [suffers in comparison](https://securityboulevard.com/2023/10/why-were-stuck-with-passwords/) with passwords. Some of the problems are related to user experience issues, and some of the problems are related to the simple reality that passkeys are less familiar than passwords, and that for passkeys to truly work they need to be broadly adopted. Passkeys are a new metaphor for what it means to authenticate and how we authenticate, while passwords are the devil that we know.

One core issue with passkeys is directly tied to how they are implemented. Passkeys are defined by a web standard, but the standard can be implemented differently. We see this in the education space all the time: the same standard is implemented in non-standard ways, which is why interoperability remains a marketing claim rather than a lived reality.

The big tech implementation of passkeys has received criticism as another way for big tech companies to [lock people into their closed systems](https://proton.me/blog/big-tech-passkey). Because of the past and current behavior of large tech companies, they don't make the most trustworthy partners, especially when it comes to handing them a central, controlling role in allowing access to all corners of our online life.

Technically, passkeys look promising. The reality of that promise remains to seen (and I'm old enough to remember when SXIP and OpenID were going to solve related problems).

1Password maintains a [searchable list of sites](https://passkeys.directory/) that support Passkeys. As of this writing, it shows 168 sites and services.

Phone/Tablet and Apps
---------------------

The tips in this section assume that you have evaluated the apps you have installed on their phones. For Android-based systems, you can review the permissions of apps in the Play store or [on your phone](http://fieldguide.gizmodo.com/how-to-fix-your-privacy-on-android-1780733516). For [iOS-based systems](http://ios.wonderhowto.com/how-to/23-important-ios-10-privacy-settings-everyone-should-double-check-0173873/), you need to review the privacy [settings on your phone](http://fieldguide.gizmodo.com/how-to-lock-down-your-privacy-settings-on-ios-1779406136), which allow you to control which apps can use tools such as location, contacts, and so on.

The advice given above about searching online and using a VPN while browsing the web applies to phone and tablet use as well. However, the use of apps on phones -- and the data they collect and share -- raises additional issues that need to be addressed for us to take control of our privacy.

One of the easiest things you can do to protect your privacy when using your phone is to install [Signal](https://whispersystems.org/). Signal is an encrypted text and voice app. Other texting apps ([WhatsApp](http://www.nytimes.com/2016/08/26/technology/relaxing-privacy-vow-whatsapp-to-share-some-data-with-facebook.html), [Telegram](http://gizmodo.com/why-you-should-stop-using-telegram-right-now-1782557415), [iMessage](http://investorplace.com/2016/09/imessage-security-shocker-apple-inc-aapl-tracks-everyone-chat/), [Allo](http://www.theverge.com/2016/9/21/12994362/allo-privacy-message-logs-google), and so on) all have greater or smaller issues that compromise privacy.

Using Signal on your phone also protects you from having the information in your texts logged and stored by your mobile phone carriers. As with email and file storage, deleting old text threads can protect against these threads being accessed.

While browsing the web, using a VPN will protect your communication, especially if you're connected to free wireless in a store or a coffee shop (wireless use is covered later in this post). Just as you would when using your browser on your computer, you should also clear cookies on your mobile browser ([Safari](https://support.apple.com/en-us/HT201265) and [Chrome](https://support.google.com/chrome/answer/2392709?co=GENIE.Platform%3DAndroid&oco=1)). For people using iPhones, you can also use the recently launched [Firefox Focus](https://blog.mozilla.org/blog/2016/11/17/introducing-firefox-focus-a-free-fast-and-easy-to-use-private-browser-for-ios/). While there are also tracker-blocking tools for Android, we are not making any explicit recommendations because some of the apps that are marketed as ad blockers are actually trackers. Before installing any blocking apps in Android, be sure to read through the permissions they require.

Mobile phones contain multiple tools that have privacy implications. Applications can use your phone's location services, wireless connection, and Bluetooth connection to track your location. This data is collected and stored and often shared with data brokers and advertisers. The process of [delivering ads based on a person's location](http://blog.artstorefronts.com/geo-fencing-facebook/) is called "geofencing." At times, however, this technique has been used to [compromise the privacy of people seeking health care](https://funnymonkey.com/2016/targeted-ads-compromising-privacy-in-healthcare).

Fortunately, this type of tracking can be minimized by turning off your phone's location services, Bluetooth connection, and wireless connection. If you turn these services off -- and then enable them only when you need them -- you minimize the amount of data you share and when you share it. Credit card companies have been [using the locations where we shop](http://www.creditcards.com/credit-card-news/how-shopping-can-affect-credit-1282.php) as a means to adjust our credit scores for years. The next frontier of this type of tracking appears to be [our location as we move](https://www.bloomberg.com/news/articles/2016-11-25/no-credit-history-no-problem-lenders-now-peering-at-phone-data) throughout our day. Minimizing the amount of location data we share, and with whom we share it, allows us a degree of control over this aspect of our privacy.

Of course, turning off your phone or tablet minimizes the risk of tracking from most sources. For those of us who want to ensure a higher level of privacy protection but want to be able to selectively use a phone or tablet, you can also use a [Faraday Bag](https://duckduckgo.com/?q=faraday+bag) to block wireless signals and any potential tracking.

Wireless
--------

Wireless internet or "hot spots" are now widely offered in many public places. As with anything that is free, the offers often come with strings. Be selective with free wireless. It is generally a tracking tool. The risks of using publicly available wireless can be mitigated by using a virtual private network (VPN) and/or Tor.

Free wireless internet with no password is the highest level of risk for wireless. If you're using a wireless connection that has no password, it's very easy for anyone to join that network and eavesdrop on your activity on the network. In many cases, stores that offer free wireless can use the information they collect about you when you're using their free wireless connection to track and target advertising to you, even while you're still in the store. Free wireless with a password is better, but not by much, and quality and safety will vary widely.

Institutional or organizational wireless is theoretically easier to secure, but the actual security will vary widely. In very general terms, the security within an organizational network will be set up to protect organizational assets first, personal privacy second. Institutional wireless often incorporates tracking, which is an appropriate security measure for the organization, but that can interfere with personal privacy. Additionally, if an organization leaves its wireless passwords unchanged for a significant amount of time, this erodes the value of security protections in place on this network.

Home wireless networks are as secure as the wireless encryption protocol and the passwords used to access the settings on the routers and the [passwords or security](https://www.theguardian.com/technology/2015/nov/26/hackers-can-hijack-wi-fi-hello-barbie-to-spy-on-your-children) on any connected devices. For most of us, home wireless networks are relatively safe. Generally, an attack on a home network would be part of a focused attempt against an individual.

It's also worth remembering that our devices will automatically connect to "recognized" wireless connections. This can be exploited by hackers who can create illicit networks in public places. Common names such as "attwifi," "xfinity," or "linksys" can easily be spoofed -- and once you connect to a wireless access point, the person who controls that access point has the ability to see and control your online activity. A VPN mitigates this risk, as does turning off wireless on your phone when you go out. You can also minimize risk by deleting wireless networks that are outside your regular locations.

Kill AI
-------

Microsoft, Google, Apple, Meta, Mozilla are all running headlong into the ethical and privacy morass that is data collection from their customers to support developing AI tools that they promise and pinky swear will be really helpful for us, and will only require that they get access to all of our data.

TBD: collect/curate guides that show how to blunt or (ideally) disable data collection that supports AI, and/or data collection that goes beyond the bare minimum required. 

Summary
-------

Conversations about privacy and security often focus on technology and give scant attention to the human, non-technological factors that affect personal privacy. In this brief post, we will cover some of the personal choices we can make and technical options we can use to take control over what we share and with whom we share it. This post is not comprehensive, but it provides some clear steps we all can take. We also attempt to ground the choices and options we recommend with additional context. When we talk about protecting our privacy, we need to consider what we're protecting -- and from whom we're protecting it.

Simple Steps
------------

When we discuss privacy, we often become too focused on the tools rather than on the behavioral shifts required to use the tools well. At the same time, when discussing how to improve privacy and security, we often get stuck in the details and fail to acknowledge that we all can do simple things to increase the control we have over our privacy. This post goes into detail well beyond these simple steps, but using these steps as a starting point would be a marked improvement for most of us.

Easy, free steps to protect our privacy start with blocking trackers when browsing the web:

-   [uBlock Origin](https://github.com/gorhill/uBlock) (blocks ad trackers)

Use alternatives to Google for search: Use [Duck Duck Go](https://duckduckgo.com/) or [Stract](https://stract.com/). While the results from Stract are less predictable than would be ideal, it can be a very useful option to find sources that other services might bury.. 

Whenever possible, set up [two-factor authentication](#two-factor-authentication) to protect accounts.

When using your phone or tablet, these free steps can increase your control over your privacy:

-   Use [Signal](https://whispersystems.org/) to send texts and make voice calls.
-   Turn off wireless, Bluetooth, and location services when you leave your home. Only turn them on when you need them.
-   If you use an iOS-based device, use [Firefox Focus](https://blog.mozilla.org/blog/2016/11/17/introducing-firefox-focus-a-free-fast-and-easy-to-use-private-browser-for-ios/) to block tracking.

Take these steps that are slightly more complex and still free:

-   Block JavaScript (adds additional protection but can add additional complexity; see options for both [Firefox](https://noscript.net/) and [Chrome](https://github.com/andryou/scriptsafe)).
-   Use [Tor](https://www.torproject.org/) when browsing for sensitive information.
-   Delete cookies from your browser.

Try these additional options that add privacy protection but are not free:

-   Use a virtual private network, or VPN, when browsing the internet from your computer, phone, or tablet.
-   Use a [privacy screen](https://duckduckgo.com/?q=computer+privacy+screen). This will help prevent people from reading over your shoulder.

A final step we all can take involves cleaning up the old files we have in our online file storage and deleting old emails we have stored online. No one needs to be a data hoarder. Setting up a time each month to delete emails and files we no longer need, and to archive items we don't have an immediate need for, helps minimize the risk of old information becoming compromised.

Conclusion
----------

It's easy to feel powerless when it comes to protecting our privacy. Companies, political organizations, and governments have a head start, and the fight to regain our privacy is often marked by distinct [information asymmetry](https://en.wikipedia.org/wiki/Information_asymmetry), where the organizations collecting, sharing, and storing our data know more about us than we know about them. However, as the Five Days of Privacy demonstrate, we have options. There are a broad range of concrete steps we can take now, and most of these steps are free and pretty low-tech.

As we continue to reclaim our rights to privacy, part of our work is normalizing behavior that protects privacy. If one person out of a thousand uses a VPN, that individual will stand out. If 200 people out of a thousand use a VPN, we begin to get some safety in numbers. Additionally, as more people use more privacy-protecting behaviors, we reduce the value of the data that is collected. If we pair privacy-protecting behavior with studying the companies that want to collect and use our information, we reduce the current state of information asymmetry. Reclaiming privacy is a choice. Sometimes it's not a convenient choice, but flossing, exercise, and eating well aren't always easy either. But when we make protecting our privacy a choice as an individual, we make it easier to protect ourselves and our communities.

Licensing Information
---------------------

This work is licensed under a [Creative Commons Attribution Share-Alike](https://creativecommons.org/licenses/by-sa/4.0/) License. The lead authors of this work are Bill Fitzgerald and Audrey Watters.
