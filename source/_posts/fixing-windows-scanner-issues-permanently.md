---
title: Fixing Windows Scanner Issues Permanently
date: 2024-08-18T08:02:18.925Z
updated: 2024-08-19T08:02:18.925Z
tags:
  - win11
  - win10
  - win7
categories:
  - ScannerIssues
description: This Article Describes Fixing Windows Scanner Issues Permanently
excerpt: This Article Describes Fixing Windows Scanner Issues Permanently
thumbnail: https://thmb.techidaily.com/9f7aaa7e93668c79f588e2bdc07bd0199fd9952e273ede775f53891cdecae42d.jpg
---

## How to Fix HP Scanner Not Working - 2022 Tips

![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd167112d84d.jpg)

 If your**HP scanner is not working** , don’t worry. This is a common scanner problem and you can fix it quickly and easily.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Why is my HP scanner not working?

 The HP scanner not working issues include**the** scanner won’t scan, the scanner not being detected by your computer, or errors popping**up** when you’re using your scanner, etc.

 The causes for these problems are various and sometimes hard to identify. As you can imagine, the connection problem can prevent your scanner from connecting to the computer, and the software and services problems in your computer are the possible reasons for this issue.

 But don’t worry. We’ll help you fix the scanner not working on HP.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Fix 2: Enable Windows Image Acquisition (WIA) service and associated services

**Windows Image Acquisition** **(WIA)** is a Microsoft model that allows graphics software to communicate with imaging hardware such as scanners and cameras. So you should enable WIA service in your computer if your scanner stops working. Here’s what you need to do:

1. On your keyboard, press the**Windows logo key** and**R** at the same time to invoke the**Run** box.
2. Type**services.msc** and click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1678201865.jpg)
3. Scroll down and double click**Windows Image Acquisition (WIA)** .  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd167eed749a.jpg)
4. In the popup pane, ensure the**Startup type** is set**Automatic** , and the**Service status** is**Running** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
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
   **INFORMATION:**  
    The**Windows Image Acquisition (WIA)** service is dependent upon the**Shell Hardware Detection Service** , while the**Shell Hardware Detection Service** is dependent upon these services: Remote Procedure Call RPC, DCOM Server Process Launcher, and RPC Endpoint Mapper.
4. Save the changes and try your scanner again to see if it works.

---

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
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

**The Pro version of Driver Easy** comes with full technical support.  
 If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](https://bellelily.pxf.io/m5azgm) .**

4) Restart your computer to take effect.

Then try scanning with your scanner to see if it works.

---

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
### Fix 4: Troubleshoot hardware problems

 It’s possible that there’s something wrong with your scanner, so run a troubleshooter in your computer to fix the issue.

1. Type**cmd** in the Windows Search bar and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/cmd-run-as-admin.jpg)
2. Copy & paste the following command line into the Command Prompt window and press**Enter** .  
`**msdt.exe -id DeviceDiagnostic**`
3. Click**Next** in the popped-up window and the troubleshooter will start detecting hardware problems automatically.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/next-step.jpg)
4. Follow the on-screen instructions to finish the troubleshooting and fix the detected issue.

 After that, try your scanner again and see if it’s working properly.

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
### Fix 5: Run System File Checker

 System File Checker (SFC) is a built-in Windows feature that scans corrupted system files and repairs it automatically.

 Your HP scanning is not working because of some corrupted system files, so you can try SFC to fix the problem.

1. Type**cmd** in the search box, right-click Command Prompt, and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd0319454560.jpg)
2. In Command Prompt, type the following command, then press**Enter** .  
sfc /scannow  
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd031d993e59.jpg)
3. Then wait for**Verification 100% complete** . This can take a while.
4. Once complete, Type**exit** in Command Prompt and press**Enter** to close the window.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd036dad46be.jpg)

Restart your computer and see if your scanner begins to work.

 However, sometimes the System File Checker may fail to detect critical or even some minor issues. If running the tool didn’t give you any luck, you should use a more powerful tool such as **[Fortect](https://tools.techidaily.com/drivereasy/download/)**  , a more powerful tool that scans your computer for invalid registry issues, fragmented files, and Windows tweaks.

To fix your issues, follow the steps below to run a full scan of your PC:

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.
2. Open Fortect and it will run a free scan of your PC. Upon completion of the scan, the software will conduct a diagnosis and show you a summary of system issues. This will take a few minutes.
3. If Fortect detects any issues on your PC, click **Start Repair** to start the repair process.  

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-top-grossing-youtube-titans/"><u>[New] 2024 Approved  Top-Grossing YouTube Titans</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-a-complete-walkthrough-on-editing-your-videos-covers-on-fb-for-2024/"><u>[New] A Complete Walkthrough on Editing Your Videos' Covers on FB for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-awesome-mac-mkv-decode-options/"><u>[New] Awesome Mac MKV Decode Options</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-comedic-content-concepts-7-hilarious-vlog-ideas-for-laughter-lovers-for-2024/"><u>[New] Comedic Content Concepts  7 Hilarious Vlog Ideas for Laughter Lovers for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-unravel-the-secrets-of-crafting-engaging-snapchat-boomerangs/"><u>[New] In 2024, Unravel the Secrets of Crafting Engaging Snapchat Boomerangs</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-artists-blueprint-10-tips-for-podcast-cover-success/"><u>[New] The Artist's Blueprint  10 Tips for Podcast Cover Success</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-the-experts-guide-to-effortless-video-submissions-on-igtv-for-2024/"><u>[Updated] The Expert's Guide to Effortless Video Submissions on IGTV for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016744164-audacity-sound-device-malfunction-here-are-5-reliable-fixes/"><u>Audacity Sound Device Malfunction? Here Are 5 Reliable Fixes!</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/best-pokemons-for-pvp-matches-in-pokemon-go-for-infinix-note-30-5g-drfone-by-drfone-virtual-android/"><u>Best Pokemons for PVP Matches in Pokemon Go For Infinix Note 30 5G | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/bluetooth-connected-but-cant-hear-a-thing-expert-solutions-inside/"><u>Bluetooth Connected, but Can't Hear a Thing? Expert Solutions Inside</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016706337-corsair-hs35-microphone-troubles-heres-how-to-fix-it-on-your-windows-machine/"><u>Corsair HS35 Microphone Troubles? Here's How to Fix It on Your Windows Machine!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diagnose-and-repair-why-isnt-my-logitech-g6letec-g633-mic-working/"><u>Diagnose and Repair: Why Isn't My Logitech G6letec G633 Mic Working?</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diagnosing-and-correcting-the-steam-voice-chatting-problem/"><u>Diagnosing and Correcting the Steam Voice Chatting Problem</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723017046838-diagnosing-and-fixing-the-problem-of-unplugged-speakersheadphones-in-windows-os-a-step-by-step-guide-for-windows-10-8-and-7-users/"><u>Diagnosing and Fixing the Problem of Unplugged Speakers/Headphones in Windows OS: A Step-by-Step Guide for Windows 10, 8 & 7 Users</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diagnosing-and-repairing-disrupted-audio-playbacks-in-windows-11/"><u>Diagnosing and Repairing Disrupted Audio Playbacks in Windows 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/effective-solutions-for-a-broken-turtle-beach-microphone-a-step-by-step-guide/"><u>Effective Solutions for a Broken Turtle Beach Microphone - A Step-by-Step Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/effortless-nvidia-graphics-driver-setup/"><u>Effortless Nvidia Graphics Driver Setup</u></a></li>
<li><a href="https://sound-issues.techidaily.com/effortlessly-end-pc-quietness-top-tricks-for-immediate-audio-recovery/"><u>Effortlessly End PC Quietness: Top Tricks for Immediate Audio Recovery</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fix-the-no-sound-in-it-takes-two-game-troubleshooting-steps-for-pcs-with-audio-issues/"><u>Fix the 'No Sound in It Takes Two' Game - Troubleshooting Steps for PCs with Audio Issues</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016802341-fixing-common-issues-how-to-restore-voice-communication-in-destiny-2/"><u>Fixing Common Issues: How to Restore Voice Communication in Destiny 2</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-idt-high-definition-sound-codec-issues-on-windows-11-a-comprehensive-guide/"><u>Fixing IDT High Definition Sound Codec Issues on Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/headphones-acting-up-heres-how-to-silence-the-crackles-swiftly-and-efficiently/"><u>Headphones Acting Up? Here's How to Silence the Crackles Swiftly & Efficiently</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>How to Detect and Stop mSpy from Spying on Your Apple iPhone 11 Pro Max | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-fix-headphones-not-recognized-errors-in-windows-7-computers/"><u>How to Fix 'Headphones Not Recognized' Errors in Windows 7 Computers</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016909872-logitech-g935-microphone-not-functional-on-windows-heres-the-fix/"><u>Logitech G935 Microphone Not Functional on Windows? Here's the Fix!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/mastering-communication-how-to-fix-the-apex-legends-voice-chat-problem/"><u>Mastering Communication - How to Fix the Apex Legends Voice Chat Problem</u></a></li>
<li><a href="https://sound-issues.techidaily.com/no-audio-no-worries-solving-it-takes-two-computer-speaker-issues/"><u>No Audio? No Worries: Solving 'It Takes Two' Computer Speaker Issues</u></a></li>
<li><a href="https://sound-issues.techidaily.com/overcoming-silence-solutions-for-a-broken-logitech-g925-wireless-gaming-mic/"><u>Overcoming Silence: Solutions for a Broken Logitech G925 Wireless Gaming Mic</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolve-cutting-out-audio-problems-for-a-seamless-experience-on-windows-11/"><u>Resolve Cutting Out Audio Problems for a Seamless Experience on Windows 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolving-logitech-g935-mic-connectivity-challenges-in-windows-environments/"><u>Resolving Logitech G935 Mic Connectivity Challenges in Windows Environments</u></a></li>
<li><a href="https://sound-issues.techidaily.com/simple-troubleshooting-guide-solving-logitech-g933-microphone-issues/"><u>Simple Troubleshooting Guide: Solving Logitech G933 Microphone Issues</u></a></li>
<li><a href="https://sound-issues.techidaily.com/smooth-beats-again-expert-advice-to-fix-stuttering-bluetooth-sound-in-windows-operating-systems-1011/"><u>Smooth Beats Again: Expert Advice to Fix Stuttering Bluetooth Sound in Windows Operating Systems (10/11)</u></a></li>
<li><a href="https://sound-issues.techidaily.com/the-ultimate-troubleshooting-guide-for-installing-idt-high-quality-sound-card-drivers-on-windows-10-pcs/"><u>The Ultimate Troubleshooting Guide for Installing IDT High-Quality Sound Card Drivers on Windows 10 PCs</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-steps-resolving-headphones-wont-work-on-windows-7/"><u>Troubleshooting Steps: Resolving 'Headphones Won't Work' On Windows 7</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-tips-solving-issues-with-your-corsair-virtuosity-mic/"><u>Troubleshooting Tips: Solving Issues with Your Corsair Virtuosity Mic</u></a></li>
<li><a href="https://sound-issues.techidaily.com/ultimate-solution-for-onikuma-headset-mic-problems-and-malfunctions/"><u>Ultimate Solution for Onikuma Headset Mic Problems and Malfunctions</u></a></li>
<li><a href="https://sound-issues.techidaily.com/why-wont-people-hear-me-comprehensive-fixes-for-discord-sound-issues/"><u>Why Won’t People Hear Me? Comprehensive Fixes for Discord Sound Issues</u></a></li>
</ul></div>
