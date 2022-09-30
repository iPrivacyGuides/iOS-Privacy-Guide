# iOS-Privacy-Guide
## Introduction

iOS is a closed-source operating system, meaning the source code is proprietary and not available to the public. Subsequently, we as the end users have no way of verifying that what Apple says about the way iOS functions is actually true. With that being said, Apple generally has a good reputation when it comes to privacy and security in comparison to other big tech companies. While there are other open source options which are more private, the task of implementing these setups is often beyond the scope of practicality for the average user who does not possess the necessary technical knowledge. iOS is generally easier to use and has a very high adoption rate, allowing for long-term support of all Apple products in comparison to other operating systems. Furthermore, iOS devices are often met with long term software and security updates, exceeding the lifespan of many Android devices running their default OS by years.

Despite the shortcomings of iOS, it can be a good choice given that some changes are made. In this guide, we will cover a wide array of default settings to change, apps to install, and ultimately help you adopt a more privacy-conscious mindset when using your iOS device. The end result will provide you with a more private, secure, and optimized device.

This text will serve as a practical guide to getting your iPhone to be as private and secure as possible given the constraints of the operating system. While this guide was written specifically with the iPhone in mind, most if not all principles would be applicable to the iPad as well. This guide has been designed to be as easy to follow as possible, while providing a concise summary of what each setting, feature, and app does. Many of the changes we discuss will have no impact on the daily usage of your device, while a few may require some getting used to. Despite this period of adjustment, all of the changes discussed remain practical and important for your device's privacy and security. Efforts have been made to have this guide cater to both complete beginners, as well as more tech savvy individuals; there’s something in this guide for everyone. At the time of publication, this guide has been thoroughly tested on iOS 15 and 16. With that said, most of the contents of this guide will also be useful for many past and future version of iOS. Efforts will be made to update this guide as new versions of iOS are released and changes are made.

---

## Settings to change within the Settings App

Before we dive into any apps, let’s go over the essential settings which should be changed. All of the following can be changed via the built-in "Settings" app on the device.

**Settings - Wi-Fi - Ask to Join Networks:**
Turn this **Off**

If this setting is on, you will be notified of available Wi-Fi networks through a pop-up window when a known Wi-Fi network is not in range. This is more of an annoyance than anything, and it's best to keep this option off to avoid accidentally selecting a malicious network. It’s also best to avoid public Wi-Fi networks in general, and when you want to connect to a Wi-Fi network, make it a deliberate choice by going to **"Settings -> "Wi-Fi"** and manually connecting to the network rather than iOS asking you.

**Settings - Wi-Fi - Auto join hotspot:**
Ensure this is set to **“Never”**. The same philosophy applies from the previous setting. 

**Settings - Bluetooth:**
Keep this off whenever possible. When not using a wireless protocol, it should always be disabled. The more unused protocols or services running, the larger the potential for exploitation. 

**Settings - Notifications - Show Previews:**
Change this to **“When Unlocked”**.
This will ensure that any notifications your device receives will not be shown in full until your device is unlocked. For example, if you receive a text message, the lock screen will show you received a text or iMessage, and how many, but will not show the contents of the message or the sender. This is very beneficial for the physical privacy of your device because people who are in close proximity to your screen won't be able to gain insight into who you're talking to or any personal information shared in the message.

**Settings - Siri & Search:**
It is recommended that you disable Siri entirely by disabling both **"Listen for “Hey Siri”"** and **"Press Side Button for Siri"**.

Also, disable everything under both **“Content from Apple”** and **“Suggestions from Apple”**. You do not need Apple monitoring how you use your iPhone and providing you with suggestions.

If you insist on keeping Siri enabled, at the very least turn off **"Listen for “Hey Siri”** to prevent your phone from always listening to you.

**Settings - Face ID & Passcode:**
For optimal security, you should completely disable Face ID and any biometrics on your device.  Not only can this be manipulated much easier than a strong passcode, in some jurisdictions you can be forced to unlock your device with biometrics if it is enabled. With that said, most people require the convenience of Face ID and don’t have a threat model in which they believe they’d need to disable biometrics. 

You should ideally have a passcode longer than six numbers; preferably an alphanumeric passphrase with letters, numbers, and symbols. You may think this will be inconvenient, however if you have Face ID enabled, you will only need to enter this password when you fully restart your phone or when there are numerous unsuccessful attempts with Face ID. 

To change your passcode, simply select **“Change Passcode”**, enter your old passcode, then select **"Passcode options" -> “Custom Alphanumeric Code”**. Enter your new password, confirm it, and complete.

It is also strongly advised to disable all of the options under **“Allow access when locked”**

Features such as Notification Center, Control Center, Wallet, etc. give anyone with physical access to your phone lots of control over the data about you and your device. It’s best to disable all these options for increased physical security of your device. It may also help make your device resistant to some potential Lock Screen bypass exploits related to these features as they will be disabled.

---

**Settings - Privacy:**
This is a place in your device settings which you should be well acquainted with. Settings here pertain to the permissions each third party app has access to within your device, as well as some Apple telemetry. We will now go through some settings here.

**Settings - Privacy - Location Services:**
This section will show a list of apps you have installed on your phone that request location services. Do not grant an app any location access unless it is crucial for the app to correctly function (e.g. a maps app). Apps such as games, calculators, and word processors do not need your location. If possible, always opt for manually entering in a location rather than granting location services.

Additionally, make sure the apps that don’t need location services are set to **“Never”**. If the app needs locations, set it to **“While using the app”** so it doesn’t send your location to them when the app is not in use. Depending on the app, you can disable **“Precise Location”** of the app if it doesn’t need your exact location to function properly.

Next, let’s scroll all the way down on the **"Settings" -> "Privacy" -> "Location Services"** area and select **“System Services”**. There are many built in services within iOS which use your location unnecessarily, primarily for Apple telemetry. Let’s go through each setting that should or should likely be disabled:

**Apple Pay Merchant Identification:**
If you don’t have or use a physical Apple credit card, this can be disabled as it simply helps provide more accurate merchant names when making purchases at physical stores with an Apple credit card.

**Cell Network Search:**
This should be disabled. It simply serves as a telemetry service to assist Apple in seeing which cell towers are in use.

**Compass Calibration:**
If you don’t use the compass app, it is safe to turn this off. Certain features of maps apps may be affected, however you are unlikely to experience any adverse effects.

**Device Management:**
If your device is not using the Apple Mobile Device Management (MDM) feature, which is a service IT administrators use to wirelessly configure Apple devices, turn it off.
This feature is only used in business environments, and you will likely be told by your employer if you require this to be on.

**HomeKit:**
If you are not using Apple’s HomeKit service, this setting should be disabled.

**Location-based Alerts:**
Unless you absolutely need to have apps send you notifications when you are at a certain location, it is strongly recommended to disable this.

**Location-based suggestions:**
You don’t need your phone constantly monitoring your activity and providing suggestions based on your location. It is best to disable this.
 
**Motion Calibration and Distance:**
Unless you’re using fitness related apps to monitor activity, this can be disabled.

**Networking & Wireless:**
Works similarly to the Cell Network Search setting discussed earlier, but for Wi-Fi and Bluetooth. Despite the warning that it may affect performance, it is safe to disable.

**Setting Timezone:**
Unless you are travelling on a very frequent basis to locations with different time zones, this should be disabled. Otherwise, your phone will be constantly broadcasting your current location to Apple's servers.

**Share My Location:**
Unless you’re allowing friends and family to track you, or you need to share your location in iMessage groups, this should be disabled.

**System Customization:**
This allows Apple to monitor your device and recommend tasks it thinks you might want based on your location. You likely don't need this in your daily life, so disable it.

**Significant Locations:**
When this is on, your device will monitor your location, as well as the frequency and duration of each visit and store it in iCloud and on your device. Unless you want Apple to have a detailed history of all the places and stores you visit, it's best to disable this. 

**iPhone Analytics:**
Disable this. It’s more unnecessary Apple telemetry.

**Routing & Traffic:**
Also Apple telemetry. Disable it.

*Now with this out of the way, let’s move on to some other privacy settings:*

**Settings - Privacy - Tracking:**
Turn off **“Allow Apps to Request to Track”**.

**Settings - Privacy - Contacts:**
It's generally a good practice to not grant access to your contacts to any app. Avoid giving any Facebook-related apps, such as WhatsApp or Messenger, any contacts permissions. The only exceptions are reputable end-to-end encrypted communication apps such as Signal.

**Settings - Privacy - Calendars:**
Unless you need specific apps to see your schedule for the week or important upcoming events, you should avoid giving apps permission to see your calendar.

**Settings - Privacy - Reminders:**
Same ethos as before; unless you need specific apps to see this, you should avoid giving them access to your reminders.

**Settings - Privacy - Photos:**
In the photo privacy settings page, you will see each app your device has installed that has requested photo permissions. No app needs the **“All Photos”** permission; avoid giving this to any app at all costs. The one exception to this would be third party photo syncing apps, which we generally discourage. Instead, you should go through each app individually and choose the **“Selected Photos”** option when applicable. This will ensure that the app will only have permission to access the photos you select, and nothing more. **"All Photos"** will give the app unrestricted access to your device’s entire photo library.

It is also important to be very cautious of which apps you give selected photo access to. Avoid giving access to ALL of your photos at all costs, including third party apps that backup your photos. It’s best to avoid them and rely on local backups instead. In other cases, a game or calculator app should not need access to any of your photos, period. As a best practice, try to limit the number of apps that have access to your photos in general, and ask yourself if granting this permission is necessary for the app in question to function correctly. In cases such as sharing a photo in a third party messaging app, you can copy the photo from your photo library and paste it into the app. Additionally, you can open the photo you want to send in the photos app and then click the button containing the square with the arrow facing up. A menu will appear showing you various messaging and social media apps you have installed where you can share the photo in.

**Settings - Privacy - Bluetooth:**
Only grant this permission to apps that absolutely require Bluetooth.

**Settings - Privacy - Local Network:**
Giving apps this permission will allow them to see other devices on your local network. Only enable this permission if absolutely necessary. For example, if a certain app needs to connect to a smartTV, or you need to connect a camera to an app.

**Settings - Privacy - Microphone:**
Take a look at all the apps on the list that have microphone permissions enabled. Ask yourself, "Do all these apps really need to hear my voice?" The answer is likely "No", so turn this option off for any of the apps that don't absolutely need microphone permissions.

**Settings - Privacy - Speech Recognition:**
If any apps are present here, always disable this permission. In almost all cases, there’s no reason for an app to have this sort of permission.

**Settings - Privacy - Camera:**
The same ethos applies from most of the options we have discussed. If the app doesn’t have a practical or functional purpose for having camera permissions, turn it off.

**Settings - Privacy - Analytics & Improvements:**
Share iPhone Analytics should be disabled. We don’t want or need our device sending reports and analytics to Apple servers.

**Settings - Privacy - Apple Advertising:**
While it may seem useful at first glance, personalized ads are not a positive thing. We don’t want big tech creating a profile of our device usage that is stored and sold on third party servers, then used to target us with invasive ads. Turn off **“Personalized Ads”**.

**Settings - Privacy - (The Other Options):**
The most essential options have now been covered. If you want to take things a step further and apply your new knowledge, go through the other privacy settings, such as Health, HomeKit, Media & Apple Music, and Files & Folders, and disable any app permissions you feel are unnecessary or overly invasive. It’s important to become well acquainted with the built-in privacy settings that iOS has to offer. You can always make new changes, or revert changes any time your circumstances or needs change.

---

**Settings - General - Airdrop:**
When not using Airdrop, always set it to **“Receiving off”**. When you need to use it, set it to **“Contacts Only”**. For easy access to these options, in Control Center, long press the first box containing Airplane Mode, Cellular, Wi-Fi, and Bluetooth, and you will see an option to easily change this AirDrop setting.

**Settings - General - AirPlay & Handoff:**
It’s a good idea to disable the Handoff feature. While it can be a useful feature, this requires that the info is sent through iCloud.

Unless you require these features, they can safely be turned off:
**"Automatically airplay to TVs"** - Never
**"Transfer to HomePod"** - Off
**"Continuity Camera"** - Off

**Settings - General - Background App Refresh:**
This allows apps to access the internet while running in the background. This is necessary for messaging apps, or anything that requires constant updates or notifications, however it generally isn't needed for most other apps. This setting should be disabled for any apps that you do not want to access the internet when closed.

**Settings - App Store:**
Under **“Automatic Downloads”**, ensure that only **“App Updates”** is selected. This will ensure that any apps you installed from the App Store are automatically updated when a new version is released.

**Settings - Messages:**
iMessage is a great alternative to conventional SMS text messages, and it's good to have it enabled. However, one thing to keep in mind is how you can be contacted by iMessage. Click on **“Send & Receive”**. This will show the email address and phone number associated with your Apple ID. It is strongly advised to unselect your email address. If your email address is enabled, this allows anyone with your email address to send you iMessages, which is basically the equivalent of giving out your phone number. If you don't want everyone who has your email address to be able to reach you in the same way as people who have your phone number, it’s best to disable this.

**Settings - FaceTime:**
The same philosophy applies here as in the previous section. Under **“You can be reached by FaceTime at”**, ensure only your phone number is selected.

**Settings - (Your name) - Media & Purchases - View Account:**
Turn off **“Personalized Recommendations”**. If this is on, it will allow Apple to use your history in the App Store, iTunes Store, and other applications to provide you with recommendations.

**Settings - General - About - Name**
This is more of a concern if you ever connect to public Wi-Fi. While this is not recommended, it is generally not a good idea to have your device’s name containing your real full name if you need to do so. This information could potentially be documented by other people on the network, and used to identify you on any given Wi-Fi network. It's best to stick to a generic, anonymous device name.

## DNS Firewall & Browser Content Blocking

Having a DNS Firewall will control how your device is allowed to access the internet, and will essentially act as a filter/content blocker for apps and your operating system in general. The apps we will discuss run locally on your device and filter all outbound connections your apps attempt to load. The app determines what requests it blocks based on its comprehensive blocklists, which are very accurate and prevent false positives. For example, if you open a game on your device which loads a Facebook tracker, the DNS firewall app of your choosing will block the connection to that tracker URL. Not only does this have extreme privacy benefits, it also prevents general annoyances such as advertisements, prevents known phishing or malicious sites and content from loading, and can save battery and data as unnecessary requests to the internet are no longer made.

Here’s a summary of how it works:
An App/OS/Browser requests to load a domain —> the request is sent to the local firewall app on your device to process —>  the firewall app then checks to see if that domain is on any of the enabled blocklists —> if the requested domain *is* on the blocklist, the DNS Firewall will not allow it to load. However, if the requested domain *is not* on the blocklist, the DNS firewall will forward the request to your DNS provider and send your device the necessary IP address to load the domain as it normally would. If you are using AdGuard Pro with Cloudflare’s DNS option, requests will be encrypted.

We will discuss two highly regarded options; one free option, and one paid option. The option you go with is entirely up to you, however we strongly recommend the small investment of the paid option. Although the free option is still sufficient and does a nice job, the paid option will provide significantly more functionality, protection, and features. If you’re willing to accept the small cost of AdGuard Pro, go for that option as it’s far superior. We highlight the many benefits of AdGuard over Lockdown Privacy below, including great ad and tracker blocking in Safari.

**Lockdown Privacy**

The Lockdown Privacy app can be found in the App Store free of charge. The app will ask you to enable notifications and also to sign up for an account, however neither of these are necessary for our purposes. Setup is as simple as opening it, then enabling the **"Firewall"** section. The app will then ask you to allow it to add VPN configurations. Click **"Allow"** and enter your iPhone passcode to complete the process. Keep their **“Secure Tunnel”** option disabled as it’s a paid VPN service which is not necessary. If you ever find yourself needing a VPN, we recommend ProtonVPN instead.

While this app is essentially a set-and-forget kind of solution, it is worthwhile to discuss the blocklists available.

In the Lockdown app, go to the Firewall section and click on **“Block Lists”**. It is recommended that you click on each blocklist available, and enable it by toggling the **“Blocking Enabled”** switch and clicking **"Save"**. The one thing to be mindful of is the **“Facebook & WhatsApp”** and **“Facebook Trackers”** blocklists. If you continue to use Facebook’s privacy invasive services, you may notice that implementing these blocklists may not allow some of their apps to function properly. In that case, you can simply disable the Facebook related blocklists. While not ideal, this is still a much better solution than allowing all trackers to mine your sensitive data.

The most obvious benefit to the Lockdown app is that it’s free, but let’s talk about some potential disadvantages:
* You can’t add custom blocklists, only additional specific domains to block individually
* You can’t whitelist domains. To elaborate, if you encountered a blocklist that works great except for one domain it’s blocking incorrectly, you would have to either disable the entire blocklist or accept the false positive
* The logs only display blocked domains and not all DNS queries your device is making, which doesn’t make it a great tool to be able to monitor your device’s total network activity
* You can’t use your own DNS provider. When Lockdown allows a domain to load, it will fetch its IP address as it would on the default iOS operating system; using whichever DNS provider your ISP or cellular service provides. These are usually not ideal for privacy
To learn more about the Lockdown App and to download it from the App store, refer to the  following links:

Lockdown Privacy’s official site: https://lockdownprivacy.com/                       

App Store link: https://apps.apple.com/us/app/lockdown-privacy-vpn-proxy/id1469783711

The next recommendation is a paid solution, but it effectively solves all of the issues mentioned above:

**AdGuard Pro**               

AdGuard Pro is a paid app available in the App Store. For a small one-time fee (prices may vary by region), you get lifetime access to the comprehensive protection the app provides. While there is a free version of this app, it is insufficient as it does not offer DNS protection, which is the main thing we’re after. On top of this, AdGuard Pro offers comprehensive Safari content blocking, which is very effective for blocking ads and trackers within the browser.

AdGuard Pro offers several additional benefits over Lockdown Privacy:
* Nicer user interface
* Significantly more detailed reports, allowing you to monitor all the network traffic on your device, including both blocked and allowed queries
* Offers the ability to set a custom DNS server, including encrypted DNS providers
* Extremely customizable DNS filtering as it allows you to use the built in AdGuard filter, which is sufficient for most users, and/or import your own blocklists via a URL where they are hosted. You can also add custom rules to either whitelist or blacklist specific domains.
* Serves as a highly effective content blocker in Safari

If you decide to go with AdGuard Pro, here's how to optimally set it up. Once installed, open the AdGuard Pro app. You will begin by looking at the bottom of the screen, which contains four tab options. Start by going to the **"Settings"** tab, which is the last tab of the four. Enable **“Advanced Settings”**. You will then want to click the second tab, which looks like a shield with a checkmark, and then click on **“DNS Protection”**. This will unveil the configuration options provided by this feature. 

First things first, we want to ensure that **“DNS implementation”** is set to **“AdGuard”**. As the description states, this will act as a local VPN on our device to intercept traffic which will allow the app to work to its full potential by allowing or blocking domains, and logging traffic locally. Next, we want to change the **“DNS server”** option. It is recommend to use the **“Cloudflare Secure DNS”** option which will provide the performance, privacy, and encryption benefits of Cloudflare’s DNS servers, but also provide some additional content blocking for phishing attacks. Now, go back and click on the **“Network settings”** option and ensure that both **“Filter Mobile data”** as well as **“Filter Wi-Fi”** are enabled to ensure the DNS protection we’ve implemented is enabled on both Wi-Fi and Cellular Data. Finally, lets take a look at the **“DNS filtering”** section. For **“DNS filters”**, we will want to turn on **“AdGuard DNS filter”**. This is the default blocklist provided by AdGuard which is a compilation of very thorough and accurate blocklists.

Now, let's go all the way back to the DNS protection area of the app and toggle the **“Disabled”** option to **“Enabled”**. You have now properly configured the app to give you the most privacy respecting experience across all apps and browsers on your device.

Let’s now briefly go over setting up AdGuard Pro to block ads and trackers in Safari.
Within the AdGuard Pro app, open the second tab on the bottom. Ensure that **“Safari Protection”** and **“Advanced Protection”** are toggled on. Next, click on **“Safari Protection”** so we can adjust some more of the settings. Now, click on **“Filters”**. We recommend enabling all of the blocklists for Ad Blocking, Privacy, Social Widgets, Annoyances, and Security.  Click on each of these options and toggle on each of the blocklists one by one. 

AdGuard Pro info on AdGuard’s official site: https://adguard.com/en/adguard-ios-pro/overview.html

App Store link: https://apps.apple.com/us/app/adguard-pro-adblock-privacy/id1126386264

## Web Browsing

**Firefox Focus**

Firefox Focus can be downloaded free of change in Apple’s App Store right from your device. This is a disposable web browser, meaning it’s not designed to retain your usage. Each completed session will erase the accumulation of history, cookies, and cache that inherently occurs while using the internet. This prevents every session from appearing as the same to sites, thus significantly reducing your chances of being tracked and profiled as you browse. Furthermore, the browser also has a built-in content blocker which blocks ads, trackers, and general annoyances. The benefit to this feature is it’s also available for integration in the built-in Safari web browser which is a great option if you did not opt for AdGuard Pro.

With that said, there are a few settings from within the app that you should change. On the top right of the app, touch the icon consisting of 3 horizontal lines, and click on **"Settings"**. Turn off both **"Send Usage Data"** and **"Studies"**, and change the default search engine to **"DuckDuckGo"**. A benefit to using Firefox Focus over Safari is that you are able to use any search engine of your choosing, even ones that are not listed in the default configuration. While we don’t get into this topic here, see here for more info if you’re interested:
https://support.mozilla.org/en-US/kb/add-search-engines-firefox-focus-ios

Mozilla Firefox Focus site: https://www.mozilla.org/firefox/browsers/mobile/focus/

App Store link: https://apps.apple.com/us/app/firefox-focus-privacy-browser/id1055677337

**Safari** 

As mentioned earlier, Safari is the built-in web browser for all Apple devices. This is the best choice for when you don't want your browsing session to be completely cleared. For example, to save bookmarks, stay logged into certain accounts, and keep important tabs open. Safari should be reserved strictly for this kind of browsing, and all other disposable web browsing should be done using Firefox Focus. With that said, Safari will need some modifications in order to make it more privacy respecting.

Lets begin by going back into the **"Settings"** app, scroll down and select **"Safari"**, then change the following settings:

**Default Browser App:** Change this to **"Firefox Focus"**, as the majority of your daily browsing will be disposable.

**Search Engine:** Change this to **"DuckDuckGo"**, as it’s the only privacy respecting option on the list.

**Safari Suggestions:** Disable this, as it prevents Safari from giving you personalized search options based on your browsing history. 

*Extensions:*
**If you purchased AdGuard Pro** as recommended in the previous step, you should see six options for AdGuard Pro under **"Content Blockers"**. Turn all of these on. In addition, scroll down until you see **"Allow these extensions"**. Click on **"AdGuard Pro"** and enable it. Ensure that under **"Permissions for "AdGuard Pro""** , **"All Websites"** is set to **"Allow"**.

**If you do not have AdGuard Pro**, you can use the Firefox Focus extension by doing the following:
Turn on **“Firefox Focus”** under **“Allow These Content Blockers”**. This will provide ad and content blocking protection similar to the Firefox Focus app, except without the disposable web browsing aspect.

*Privacy Preserving Ad Measurement* - Turn this off. This feature is designed to provide a “privacy respecting” way of reporting your interaction with ads. Having this off will help prevent all reporting.

**Content Blockers** - Ensure **"Use content blockers on".. "all websites"** is enabled
**Camera** - Ensure **"Camera access on all websites"** is set to **"Deny"**
**Microphone** - Ensure **"microphone access on all websites"** is set to **"Deny"**
**Location** - Ensure **"location access on all websites"** is set to **"Deny"**

Apple Pay is a convenient and safe way to pay online. However if you are not using it, feel free to disable it in Safari by changing the following setting:
**Check for Apple Pay - Off**

Finally, you should use Safari in private browsing mode as this will prevent history, cookies, and cache from accumulating overtime. This will both save storage and offer a huge privacy benefit as once the tab is closed, so will the cookies and cache of that page. To enable this, open Safari and click on the tab management button at the bottom right of the page. Click on **"Start page"** and a menu called **"Tab Groups"** will pop up. Simply select **"Private"** and Safari will no longer remember your search history, the pages you visited, or any other information you share during previous sessions. It's important to note that if you choose to use private browsing mode, Safari will log you out of all sites upon closing the browser. However, the benefit to this over Firefox Focus is that the tabs from your previous browsing session will remain open, so you can easily log in again upon next use. The only instance in which they will be cleared is if you manually close them one by one. If this is too much of an inconvenience for your browsing habits, you can get away with not enabling Private browsing mode and just limiting your browsing in Safari to essential sites.


## Recommended Apps/Services

**Bitwarden**

Bitwarden is a free and open source cloud-based password manager. In addition to the free service, there is a very inexpensive paid version which we highly recommend as it provides some very nice features, such as 2FA integration. You also help support the great team behind the project.

Since Bitwarden is open source, their claims can be put to the test and verified since anyone can view the code. Furthermore, it runs off a "zero knowledge" encryption system, meaning no one can access your password vault; not even Bitwarden. In fact, there is no "Forgot Password" button, meaning it is impossible to reset your master password if you forget it. This provides extra piece of mind as in the very rare chance Bitwarden were to be hacked, the attacker would not have the keys to unlock anyones vault. With that being said, it is critical that you write down your master password and keep it in a safe place in the unlikely event that you forget it. Otherwise, you will lose access to your vault and, subsequently, all of your accounts within the vault.

It is also very important to write down your account's recovery code if for some reason you lose access to your 2FA provider. To access this, log in to your Bitwarden account in your browser (bitwarden.com). Click your user icon on the top right hand of the page, and click **"Account Settings"**. On this page, click **"Security"**, then **"Two-Step Login"** and click **"Show Recovery Code"** within the warning box. If you choose to not write down this code and also lose access to your 2FA key, you will lose access to your vault **permanently**. Make sure this doesn't happen to you and take precautions before it's too late.

Bitwarden is a far superior option to using the built-in Passwords or iCloud Keychain feature in Apple products. Not only is Apple’s password manager not open source, but it is also not impartial to other operating systems. It’s only designed to work with Apple products, and on macOS it doesn’t even work with other browsers besides Safari. On the other hand, Bitwarden is OS agnostic and will function just as effective on any desktop OS, mobile OS, or web browser you decide to use. 

This guide will not be getting into setting up Bitwarden as they have great documentation on the setup process. Here are links to their official site for guidance on setting up your account, vault, and setting it as your default password manager in iOS:

https://bitwarden.com/help/get-started-individual-user/

https://bitwarden.com/help/auto-fill-ios/

App Store link: https://apps.apple.com/us/app/bitwarden-password-manager/id1137397744

**Proton Mail**

ProtonMail is an encrypted email service based in Switzerland. Their service not only protects your data, but it is absent of ads, trackers, and having the company's system read your emails unlike other big tech providers.

As a way to test out the service, there is a free plan which gives you 500MB-1GB of storage, along with more robust paid plans which provide 15GB or 500GB depending on the package you choose. Many people may think that paying for email is ridiculous when the vast majority of conventional email providers are free. Consider that those same email services that provide much more generous storage than Proton also display ads, read your emails, and sell or rent out your data. As the saying goes, if something is free, you are the product.

Proton’s official site: https://proton.me/

About Proton: https://proton.me/about

Getting started guide: https://proton.me/support/get-started-mail

App Store link: https://apps.apple.com/us/app/proton-mail-encrypted-email/id979659905

**Standard Notes**

Standard Notes is an end-to-end encrypted note taking app and service. It’s an alternative to the built in Notes app in iOS and offers a significant improvement in both privacy and security. The app’s user interface and functionalities are self-explanatory and it functions similarly to the familiar Notes app within iOS. Furthermore, the service is cross platform as it works as a web app, but also offers native apps for macOS, Linux, Windows, iOS, and Android.

Standard Notes official site: https://standardnotes.com/

App Store link: https://apps.apple.com/us/app/standard-notes/id1285392450

**Signal**

Signal is an alternative end-to-end encrypted messaging app. It’s extremely easy to use and setup. All it requires is a phone number and a PIN. The transparency and fact that Signal is open source makes it a superior option to iMessage. They also don’t store your messages on their servers; all data is stored on your local device and the device of the person you're communicating with, nothing more. Like many of the other recommendations, we don’t go into much depth about this particular app as it’s beyond the scope of this guide, however we encourage you to look further into it.

Signal’s official site: https://www.signal.org/

Getting started with Signal: https://support.signal.org/hc/en-us/sections/360001602712-Signal-Messenger-Basics

App Store link: https://apps.apple.com/us/app/signal-private-messenger/id874139669

**MySudo**

MySudo is an app that provides phone numbers and emails you can use to give out to people or services that you do not want to have your real number. As I’m sure you’re aware, changing your primary cell phone number is a huge inconvenience. MySudo allows you to easily create and remove phone numbers for a small cost. You are able to send and receive calls, text messages, and mail from your MySudo generated phone number and email address. 

While this is a paid service, the plans are very affordable and it's a very worthwhile option to consider. Another privacy benefit is you don’t need to provide any personal information to use MySudo. They do not require an email address, phone number, name, or any other personal identifiable information in order to use their service.

MySudo official site: https://mysudo.com/

About MySudo: https://support.mysudo.com/hc/en-us/articles/360019976014-What-is-MySudo-

App Store link: https://apps.apple.com/us/app/mysudo-private-secure/id1237892621


## iCloud

In the privacy community, there is controversy surrounding the privacy and security of big tech’s cloud services. iCloud is run by big tech, not all of the services are end-to-end encrypted, and it’s not open source. It’s also not fully OS agnostic as it really only works well on Apple devices, despite there being some compatibility with Windows. We would recommend reducing or eliminating your reliance on iCloud depending on what is practical for your setup.

There are services mentioned in the previous “Recommended Apps/Services” which can replace some of iCloud’s functionality. For example, using Standard Notes instead of Apple Notes. It’s also worth exploring services like the Proton ecosystem, as they offer an encrypted Calendar, Drive, and other substitutions for Apple services.

As for backups, we advise never using iCloud backups for your device. Instead you can create local encrypted backups of your device on your computer. For more info, please see here:

**How to back up your iPhone, iPad, and iPod touch with your Mac:**

https://support.apple.com/en-ca/HT211229

**How to back up your iPhone, iPad, or iPod touch with iTunes on your PC:**

https://support.apple.com/en-ca/HT212156

##Device Best Practices

**Installing Apps; keep it to a minimum**

Avoid installing apps when it can be avoided. For example, if you can get away with using a service in the web browser, go that route rather than installing the app. Nowadays, many sites such as Twitter offer progressive web apps, which allow for a seamless interaction with the service via the web browser without installing any application. For an even more native experience, when on a website you can select the box with an up arrow at the bottom of the URL bar in Safari, scroll down, and select **“Add to Home Screen”**. You will be able to add a convenient icon to your home screen for the site in question, and any progressive web app compatible site will load without the URL address bar for a more native experience.

The bottom line is if you don’t absolutely need an app, don’t install it. The more apps you have, especially considering many aren’t privacy respecting, the larger the privacy concerns and data collection. The Lockdown app we setup previously can help mitigate this, however it’s best not to make a mess of your app collection to begin with.

**Email Clients; only use the built in Mail app**
If you are still using privacy invasive email services such as Gmail, Outlook, or Yahoo, do not install their mail apps. They are incredibly unnecessary, and are void of many of the privacy and security benefits of using the built in mail app in iOS, such as Mail Privacy Protection which allows you to hide your IP address from senders.

The built in iOS Mail app is provider agnostic; it functions the same regardless of your email provider. You can setup multiple email accounts, even from different providers. You can setup your mail accounts for use within this app by going to your device’s **"Settings"** app, then clicking **"Mail"**, and manage your accounts under the **"Accounts"** section.

The only exception to this rule is privacy respecting email services such as ProtonMail or TutaNota. In these cases, their apps are necessary as your emails are encrypted and require their apps to decrypt their contents. The regular iOS Mail app only works with conventional email accounts which are not encrypted.

**Physical Device Safety; don’t share your device**

Avoid loaning your phone to anyone, and always ensure your phone is on your person, or at a trusted location at all times. If someone else must use your phone, ensure they are supervised by you and you are aware of what’s happening. A friend using your phone likely has no malicious intent to compromise the security or privacy of your device, however are they educated on privacy and security? No matter how careful and educated you are, someone close to you may not have that same knowledge or concern.

**Clicking Links; think first**

If you receive any text messages or emails from unrecognized senders containing a link or attachment, do not open or engage with it in any way and remove the message. While Apple tends to do a good job with patching security vulnerabilities, they can still exist within the message you received. Don’t take the potential risk.

**Public Wi-Fi; avoid it**

Public Wi-Fi can be incredibly convenient and economical. While using it will reduce your data plan usage, this comes with a trade off as connecting to public Wi-Fi can be a risk. Generally, man in the middle attacks are rare in this day in age with the vast majority of sites using HTTPS, however you have no idea who else is connected to the public Wi-Fi and if any exploits are being attempted. While these form of attacks may be unlikely, they are something to keep in mind. Not to mention, many larger public Wi-Fi networks require some form of personally identifiable information in order to connect such as a phone number or email address. It’s best practice to only connect your device to trusted networks.

**Software Updates; keep up to date**

We already covered App Store updates and setting them up to automatically install. The same is true by default for system updates. Checking for and installing system updates can be found in **"Settings" -> "General" -> "Software Update"**.
It is good to know about this as sometimes you will dismiss an update when told your device will need to be restarted, thinking you’ll come back to it later. It is crucial that you allow these updates to run as soon as possible. If you dismiss them, you can go back to them in your settings as mentioned above. You will likely want to connect your phone to a power source during the update. These updates generally feature important security and bug fixes.

One important consideration with updates is to delay upgrading to the next major iOS release. For example, if you’re on iOS 15, always make sure that you are running the latest version of iOS 15; the version number should start with 15, then any given number after depending on the order of the release. When the next major release of iOS is out, for example iOS 16, it is best to wait a few weeks to a couple months until there has been sufficient time to patch any bugs or potential security flaws present.

**Avoid giving out your number; use a burner or digital number**

As mentioned, apps like MySudo are a great option to generate a carefree number you can comfortably give to people or services that you may not want to give your real number too. Exercise your best judgement and common sense when giving out your number. If there’s a possibility you may not want the person or company in question to have your number any longer, always give them your digital number.

## Conclusion
This guide has covered a lot of ground. Not only have we discussed default settings baked into iOS to change, but we’ve also gone over apps to install and configure, as well as best practices for maintaining a private and secure device. As we didn’t have enough room to cover the configuration of each recommended app and service since they aren’t iOS specific but rather cross platform, such as Bitwarden, ProtonMail, and MySudo, we recommend researching these services yourself to learn more about them. It’s also advised that you read this guide a few times so the material really sinks in. Privacy and security best practices continue to change and evolve, so we encourage you to read further on these topics and stay up to date.

We appreciate you taking the time to read, digest, and implement the measures discussed and hope we are all more conscious of our online and technology usage and can live a more private and secure digital life.

  
  
