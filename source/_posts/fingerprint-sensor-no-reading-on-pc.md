---
title: "Fingerprint Sensor: No Reading on PC"
date: 2024-08-13T10:55:17.930Z
updated: 2024-08-14T10:55:17.930Z
tags:
  - win11
  - win10
  - win7
categories:
  - ScannerIssues
description: "This Article Describes Fingerprint Sensor: No Reading on PC"
excerpt: "This Article Describes Fingerprint Sensor: No Reading on PC"
thumbnail: https://thmb.techidaily.com/3cb419f908d86ebe5088af418d006c72b036ec3f74f18e23c30cd46153ace618.jpg
---

## How to Fix HP Scanner Not Working - 2022 Tips

![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd167112d84d.jpg)

 If your**HP scanner is not working** , don’t worry. This is a common scanner problem and you can fix it quickly and easily.

## Why is my HP scanner not working?

 The HP scanner not working issues include**the** scanner won’t scan, the scanner not being detected by your computer, or errors popping**up** when you’re using your scanner, etc.

 The causes for these problems are various and sometimes hard to identify. As you can imagine, the connection problem can prevent your scanner from connecting to the computer, and the software and services problems in your computer are the possible reasons for this issue.

 But don’t worry. We’ll help you fix the scanner not working on HP.

## How to fix the HP scanner not working

 Here are solutions that have helped people resolve the same issue. You don’t need to try them all; just work your way down the list.

1. [**Check the connection issue**](#F1)
2. [**Enable Windows Image Acquisition (WIA) service and associated services**](#F2)
3. **[Update your scanner driver](#F3)**
4. [**Troubleshoot hardware problems**](#F4)
5. [**Run System File Checker**](#F5)

 The screenshots below come from Windows 10, and fixes apply to Windows11.

---

### Fix 1: Check the connection issue

 To use your scanner, you need to make sure that your scanner is**powered on** in the first place.

 Then you should check the**connection** **issue** . If you’re using a USB scanner, check the**USB ports** and**USB cables** to ensure it works properly. While you’re using a network scanner, ensure your computer has a good**Internet** **connection** , and your scanner connects to your computer under the Internet. In addition, if you’re using **[VPN](https://tools.techidaily.com/drivereasy/download/)**  on your computer, try**disconnecting VPN** from your computer and scanning again.

 If you’ve checked the above steps and your HP scanner still doesn’t work, don’t worry. There is something else to try.

---

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
### Fix 2: Enable Windows Image Acquisition (WIA) service and associated services

**Windows Image Acquisition** **(WIA)** is a Microsoft model that allows graphics software to communicate with imaging hardware such as scanners and cameras. So you should enable WIA service in your computer if your scanner stops working. Here’s what you need to do:

1. On your keyboard, press the**Windows logo key** and**R** at the same time to invoke the**Run** box.
2. Type**services.msc** and click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1678201865.jpg)
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
3. Scroll down and double click**Windows Image Acquisition (WIA)** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd167eed749a.jpg)
4. In the popup pane, ensure the**Startup type** is set**Automatic** , and the**Service status** is**Running** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd168549db26.jpg)  
 If the**Service status** is already**Running** , click**Stop** to stop the service, then click**Start** to re-enable the service.
5. Click**Apply** and**OK** to save the changes.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1688e0055e.jpg)

 Then restart your computer. Try to use your HP scanner again and see if it works now.

 If your HP scanner issue still persists, follow these steps to enable some more services:

1. On your keyboard, press the**Windows logo key** and**R** at the same time to invoke the Run box.
2. Type**services.msc** and click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1678201865.jpg)
3. Ensure these services are set to**Automatic** and the**Service status** is**Running** .  
   * **Remote Procedure Call RPC**  
   * **DCOM Server Process Launcher**  
   * **RPC Endpoint Mapper**  
   * **Shell Hardware Detection**  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd169897b1a1.jpg)  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
   **INFORMATION:**  
    The**Windows Image Acquisition (WIA)** service is dependent upon the**Shell Hardware Detection Service** , while the**Shell Hardware Detection Service** is dependent upon these services: Remote Procedure Call RPC, DCOM Server Process Launcher, and RPC Endpoint Mapper.
4. Save the changes and try your scanner again to see if it works.

---

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
### Fix 3: Update your scanner driver (Windows PC)

 A missing or outdated scanner driver can cause your HP scanner not to work, so you should update your scanner driver up to date.

 There are two ways to update your scanner driver:**manually** and**automatically** .

**Manually update scanner driver** – You can go to the website of your scanner manufacturer, find the latest driver for your scanner, and install it on your computer. This requires time and computer skills.

**Automatically update scanner driver** – If you don’t have time or patience, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can download and install your drivers by using either the Free or Pro version of Driver Easy. But with the Pro version, it takes only 2 clicks (and you get full support and a**30-day money-back guarantee** ):

1. [**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy and click**Scan Now** . Driver Easy will then scan your computer and detect any problem drivers.  

![](https://images.drivereasy.com/wp-content/uploads/2023/03/Driver-Easy-download-needed.jpg)
3. Click the Update button next to your scanner to download the latest driver (you can do this with the FREE version), then install it on your computer.  
 Or click**Update All** to automatically download and install all problem drivers in your system (this requires the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click**Update All** ).  

![](https://images.drivereasy.com/wp-content/uploads/2023/03/update-dell-touchpad-driver.jpg.png)
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**The Pro version of Driver Easy** comes with full technical support.  
 If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](https://bellelily.pxf.io/m5azgm) .**

4) Restart your computer to take effect.

Then try scanning with your scanner to see if it works.

---

### Fix 4: Troubleshoot hardware problems

 It’s possible that there’s something wrong with your scanner, so run a troubleshooter in your computer to fix the issue.

1. Type**cmd** in the Windows Search bar and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/cmd-run-as-admin.jpg)
2. Copy & paste the following command line into the Command Prompt window and press**Enter** .  
`**msdt.exe -id DeviceDiagnostic**`
3. Click**Next** in the popped-up window and the troubleshooter will start detecting hardware problems automatically.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/next-step.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
4. Follow the on-screen instructions to finish the troubleshooting and fix the detected issue.

 After that, try your scanner again and see if it’s working properly.

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Fix 5: Run System File Checker

 System File Checker (SFC) is a built-in Windows feature that scans corrupted system files and repairs it automatically.

 Your HP scanning is not working because of some corrupted system files, so you can try SFC to fix the problem.

1. Type**cmd** in the search box, right-click Command Prompt, and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd0319454560.jpg)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. In Command Prompt, type the following command, then press**Enter** .  
sfc /scannow  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd031d993e59.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
3. Then wait for**Verification 100% complete** . This can take a while.
4. Once complete, Type**exit** in Command Prompt and press**Enter** to close the window.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd036dad46be.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->

Restart your computer and see if your scanner begins to work.

 However, sometimes the System File Checker may fail to detect critical or even some minor issues. If running the tool didn’t give you any luck, you should use a more powerful tool such as **[Fortect](https://tools.techidaily.com/drivereasy/download/)**  , a more powerful tool that scans your computer for invalid registry issues, fragmented files, and Windows tweaks.

To fix your issues, follow the steps below to run a full scan of your PC:

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.
2. Open Fortect and it will run a free scan of your PC. Upon completion of the scan, the software will conduct a diagnosis and show you a summary of system issues. This will take a few minutes.
3. If Fortect detects any issues on your PC, click **Start Repair** to start the repair process.  

![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-repair.jpg)

 The repair is available with the paid version of Fortect which comes with full technical support. If you encounter any issues when using Fortect, feel free to contact their support team.

---

 So there you have it – Five effective methods to fix the**HP scanner not working** . Hope this post comes in handy and resolves your problem.

* [scanner](https://store.drivereasy.com/order/cart.php?PRODS=4731822&QTY=1&AFFILIATE=108875)
* [Windows](https://tools.techidaily.com/drivereasy/download/)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-direct.techidaily.com/new-step-by-step-audio-addition-for-impactful-instagram-visuals/"><u>[New] Step-by-Step Audio Addition for Impactful Instagram Visuals</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ag-tricks-to-triumph-youtube-gamers-edition-for-2024/"><u>[New] Tag Tricks to Triumph  YouTube Gamers Edition for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-the-best-5-devices-to-record-your-virtual-meetings/"><u>[New] The Best 5 Devices to Record Your Virtual Meetings</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-the-ultimate-sandbox-experience-playlist/"><u>[New] The Ultimate Sandbox Experience Playlist</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-unlocking-vsco-photo-editing-tips-and-tricks/"><u>[New] Unlocking VSCO  Photo Editing Tips & Tricks</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-mac-users-guide-to-snapchat-integration/"><u>[Updated] 2024 Approved  Mac Users' Guide to Snapchat Integration</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-expert-video-making-opt-for-studio-versus-beta-version-for-2024/"><u>[Updated] Expert Video Making  Opt for Studio Versus Beta Version for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-rapid-video-filming-techniques-for-tiktok-success/"><u>[Updated] In 2024, Rapid Video Filming Techniques for TikTok Success</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-key-sites-for-enhancing-youtube-video-popularity-for-2024/"><u>[Updated] Key Sites for Enhancing YouTube Video Popularity for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-unlocking-the-power-of-igtv-from-novice-to-pro-for-2024/"><u>[Updated] Unlocking the Power of IGTV  From Novice to Pro for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-realme-v30-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Realme V30 Wont Charge | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-infinix-note-30-pro-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Infinix Note 30 Pro</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015017771-airpods-not-recognizing-mic-in-windows-11-heres-what-to-do/"><u>AirPods Not Recognizing Mic in Windows 11? Here’s What to Do</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015713614-corsair-hs60-not-picking-up-sound-heres-what-you-can-do/"><u>Corsair HS60 Not Picking Up Sound? Here's What You Can Do</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/crafting-compelling-video-narratives-using-captivate-for-2024/"><u>Crafting Compelling Video Narratives Using Captivate for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723014897607-diagnosing-and-repairing-your-logitech-g633-mic-issues-solved/"><u>Diagnosing and Repairing Your Logitech G633 Mic Issues - Solved</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-infinix-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Infinix FRP Locks</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-a-locked-oneplus-nord-ce-3-lite-5g-phone-by-drfone-android/"><u>How to Reset a Locked OnePlus Nord CE 3 Lite 5G Phone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-nokia-c12-pro-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On Nokia C12 Pro</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-facebooks-2023-icon-fix-your-hidden-watch-symbol/"><u>In 2024, Facebook's 2023 Icon Fix  Your Hidden Watch Symbol</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-pattern-locks-are-unsafe-secure-your-infinix-hot-30-5g-phone-now-with-these-tips-by-drfone-android/"><u>In 2024, Pattern Locks Are Unsafe Secure Your Infinix Hot 30 5G Phone Now with These Tips</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723014789080-nvidia-hd-audio-not-working-heres-how-to-restore-your-sound/"><u>NVIDIA HD Audio Not Working? Here’s How to Restore Your Sound!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/revive-the-audio-on-your-astro-a10-headset-effective-solutions-inside/"><u>Revive the Audio on Your Astro A10 Headset: Effective Solutions Inside</u></a></li>
<li><a href="https://sound-issues.techidaily.com/reviving-the-battle-cries-troubleshooting-sound-issues-in-borderlands-npc/"><u>Reviving the Battle Cries: Troubleshooting Sound Issues in Borderlands nPC</u></a></li>
<li><a href="https://sound-issues.techidaily.com/simple-fixes-for-a-malfunctioning-google-hangouts-microphone-issue/"><u>Simple Fixes for a Malfunctioning Google Hangouts Microphone Issue</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-audio-problems-get-your-dota-n-microphone-back-on-track/"><u>Solving Audio Problems: Get Your Dota N Microphone Back on Track</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-dell-speaker-malfunctions-in-windows-eus/"><u>Solving Dell Speaker Malfunctions in Windows Eus</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-no-sound-problems-on-an-hp-notebook-under-the-latest-windows-version/"><u>Solving No Sound Problems on an HP Notebook Under the Latest Windows Version</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-your-laptops-sound-problem-tips-and-solutions-for-a-quick-fix/"><u>Solving Your Laptop's Sound Problem: Tips & Solutions for a Quick Fix</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-guide-to-restore-your-steam-voice-communication/"><u>Step-by-Step Guide to Restore Your Steam Voice Communication</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-solutions-for-non-working-mic-on-runmus-gaming-headsets/"><u>Step-by-Step Solutions for Non-Working Mic on Runmus Gaming Headsets</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/techniques-for-extracting-mp3-from-instagram-videos/"><u>Techniques for Extracting MP3 From Instagram Videos</u></a></li>
<li><a href="https://sound-issues.techidaily.com/the-2024-guide-to-restoring-your-malfunctioning-jabra-earpiece-fixes-and-tips-inside/"><u>The 2024 Guide to Restoring Your Malfunctioning Jabra Earpiece - Fixes & Tips Inside</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-novices-route-to-rapidly-play-videos-on-snapchat-for-2024/"><u>The Novice's Route to Rapidly Play Videos on Snapchat for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723014889570-the-specific-heat-capacity-of-water-is-approximately-418-jgk-which-is-relatively-high-compared-to-many-other-substances/"><u>The Specific Heat Capacity of Water Is Approximately 4.18 J/G·K, Which Is Relatively High Compared to Many Other Substances</u></a></li>
<li><a href="https://sound-issues.techidaily.com/the-ultimate-guide-to-fixing-no-sound-situations-on-windows-11-computers/"><u>The Ultimate Guide to Fixing No-Sound Situations on Windows 11 Computers</u></a></li>
<li><a href="https://sound-issues.techidaily.com/trouble-with-the-mic-in-fortnite-heres-how-to-get-crystal-clear-audio-again/"><u>Trouble with the Mic in Fortnite? Here's How to Get Crystal Clear Audio Again!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/trouble-with-your-razer-man-o-war-mic-heres-the-solution/"><u>Trouble with Your Razer Man O' War Mic? Here's the Solution</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-and-fixing-crackling-audio-problems-for-windows-10-and-windows-7-users/"><u>Troubleshooting and Fixing Crackling Audio Problems for Windows 10 and Windows 7 Users</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-and-repair-why-arent-my-headphones-working-on-windows-11/"><u>Troubleshooting and Repair: Why Aren't My Headphones Working on Windows 11?</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-sound-glitches-on-your-newworld-platform/"><u>Troubleshooting Sound Glitches on Your NewWorld Platform</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-tips-for-when-the-steelseries-arctis-3-microphone-fails-to-function/"><u>Troubleshooting Tips for When the SteelSeries Arctis ^3 Microphone Fails to Function</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/uncomplicated-steps-to-record-instagrams-story-feed-for-2024/"><u>Uncomplicated Steps to Record Instagram's Story Feed for 2024</u></a></li>
</ul></div>
