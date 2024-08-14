---
title: How to Fix HP Scanner Not Working – 2022 Tips
date: 2024-08-13T10:45:57.694Z
updated: 2024-08-14T10:45:57.694Z
tags:
  - win11
  - win10
  - win7
categories:
  - ScannerIssues
description: This Article Describes How to Fix HP Scanner Not Working – 2022 Tips
excerpt: This Article Describes How to Fix HP Scanner Not Working – 2022 Tips
thumbnail: https://thmb.techidaily.com/d91c4abed318157a8b08fbc6c0ecb400619fc39e3e859b7ef1ec6d0563fa86aa.jpg
---

## How to Fix HP Scanner Not Working - 2022 Tips

![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd167112d84d.jpg)

 If your**HP scanner is not working** , don’t worry. This is a common scanner problem and you can fix it quickly and easily.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## Why is my HP scanner not working?

 The HP scanner not working issues include**the** scanner won’t scan, the scanner not being detected by your computer, or errors popping**up** when you’re using your scanner, etc.

 The causes for these problems are various and sometimes hard to identify. As you can imagine, the connection problem can prevent your scanner from connecting to the computer, and the software and services problems in your computer are the possible reasons for this issue.

 But don’t worry. We’ll help you fix the scanner not working on HP.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
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

### Fix 2: Enable Windows Image Acquisition (WIA) service and associated services

**Windows Image Acquisition** **(WIA)** is a Microsoft model that allows graphics software to communicate with imaging hardware such as scanners and cameras. So you should enable WIA service in your computer if your scanner stops working. Here’s what you need to do:

1. On your keyboard, press the**Windows logo key** and**R** at the same time to invoke the**Run** box.
2. Type**services.msc** and click**OK** .  
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1678201865.jpg)
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/03/Driver-Easy-download-needed.jpg)
3. Click the Update button next to your scanner to download the latest driver (you can do this with the FREE version), then install it on your computer.  
 Or click**Update All** to automatically download and install all problem drivers in your system (this requires the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click**Update All** ).  

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/03/update-dell-touchpad-driver.jpg.png)

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
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/10/next-step.jpg)
4. Follow the on-screen instructions to finish the troubleshooting and fix the detected issue.

 After that, try your scanner again and see if it’s working properly.

---

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
### Fix 5: Run System File Checker

 System File Checker (SFC) is a built-in Windows feature that scans corrupted system files and repairs it automatically.

 Your HP scanning is not working because of some corrupted system files, so you can try SFC to fix the problem.

1. Type**cmd** in the search box, right-click Command Prompt, and select**Run as administrator** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd0319454560.jpg)
2. In Command Prompt, type the following command, then press**Enter** .  
sfc /scannow  
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
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-trailblazing-pfp-concepts-to-secure-your-spotlight-on-tiktok/"><u>[New] 2024 Approved  Trailblazing PFP Concepts to Secure Your Spotlight on TikTok</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-leading-music-service-streaming-channels/"><u>[New] Leading Music Service Streaming Channels</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-rapidpace-timefreeze-film/"><u>[Updated] 2024 Approved  RapidPace TimeFreeze Film</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-building-impressive-pixelated-photo-combinations-for-2024/"><u>[Updated] Building Impressive Pixelated Photo Combinations for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-elevate-user-participation-via-personalized-ig-story-polls/"><u>[Updated] In 2024, Elevate User Participation via Personalized IG Story Polls</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-concoct-clever-caricatures/"><u>2024 Approved  Concoct Clever Caricatures</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/2024-approved-how-to-auto-translate-youtube-videos-into-different-languages/"><u>2024 Approved How To Auto Translate YouTube Videos Into Different Languages</u></a></li>
<li><a href="https://sound-issues.techidaily.com/amplify-sound-quality-on-your-pc-with-easy-tweaks-for-windows-users/"><u>Amplify Sound Quality on Your PC with Easy Tweaks for Windows Users</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015875415-apex-legends-and-voice-chat-woes-discover-simple-solutions-to-sound-off-in-the-game/"><u>Apex Legends and Voice Chat Woes? Discover Simple Solutions to Sound Off in the Game!</u></a></li>
<li><a href="https://fox-helps.techidaily.com/configure-streamlabs-on-your-mac-using-obs-for-2024/"><u>Configure Streamlabs on Your Mac Using OBS for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/effective-solutions-for-laptops-with-sound-malfunctions-now-fixed/"><u>Effective Solutions for Laptops with Sound Malfunctions - Now Fixed!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/effective-solutions-to-fix-your-hyperx-cloud-alphas-malfunctioning-mic/"><u>Effective Solutions to Fix Your HyperX Cloud Alpha's Malfunctioning Mic</u></a></li>
<li><a href="https://sound-issues.techidaily.com/expert-advice-on-repairing-unresponsive-realtek-mics/"><u>Expert Advice on Repairing Unresponsive Realtek Mics</u></a></li>
<li><a href="https://sound-issues.techidaily.com/expert-tips-for-fixing-a-non-functional-corsair-void-gaming-microphone/"><u>Expert Tips for Fixing a Non-Functional Corsair Void Gaming Microphone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/expert-tips-to-restore-sound-output-from-laptops-35mm-audio-socket-fixed/"><u>Expert Tips to Restore Sound Output From Laptop's 3.5Mm Audio Socket [FIXED]</u></a></li>
<li><a href="https://extra-information.techidaily.com/free-image-transformation-the-best-smartphone-editing-aids-unveiled/"><u>Free Image Transformation  The Best Smartphone Editing Aids Unveiled</u></a></li>
<li><a href="https://sound-issues.techidaily.com/getting-back-to-normalcy-a-step-by-step-guide-to-fixing-no-sound-on-windows-11/"><u>Getting Back to Normalcy: A Step-by-Step Guide to Fixing No Sound on Windows 11</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-realme-gt-neo-5-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Realme GT Neo 5 Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-activation-lock-from-the-iphone-13-mini-without-previous-owner-by-drfone-ios/"><u>How to Remove Activation Lock From the iPhone 13 mini Without Previous Owner?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-vivo-s17e-for-free-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track a Lost Vivo S17e for Free? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-rootjunky-apk-to-bypass-google-frp-lock-for-realme-by-drfone-android/"><u>In 2024, Rootjunky APK To Bypass Google FRP Lock For Realme</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-ultimate-12-selection-of-smart-flip-screen-vlog-cameras/"><u>In 2024, The Ultimate 12 Selection of Smart Flip-Screen Vlog Cameras</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-through-eyes-unseen-an-essential-vr-chronology/"><u>In 2024, Through Eyes Unseen  An Essential VR Chronology</u></a></li>
<li><a href="https://techidaily.com/is-your-samsung-galaxy-s23-tactical-edition-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Samsung Galaxy S23 Tactical Edition working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/leading-terraria-adjustments-and-tweaks-for-2024/"><u>Leading Terraria Adjustments and Tweaks for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/operating-system-update-resolves-opengl-error/"><u>Operating System Update Resolves OpenGL Error</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-audio-problems-in-outriders-a-comprehensive-guide/"><u>Solving Audio Problems in Outriders: A Comprehensive Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-blue-yeti-microphone-compatibility-issues-top-troubleshooting-techniques/"><u>Solving Blue Yeti Microphone Compatibility Issues: Top Troubleshooting Techniques</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-fixes-for-a-malfunctioning-logitech-g430-restore-your-sound-now/"><u>Step-by-Step Fixes for a Malfunctioning Logitech G430 - Restore Your Sound Now!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-fixes-for-your-broken-turtle-beach-stealth-70-mic-problems/"><u>Step-by-Step Fixes for Your Broken Turtle Beach Stealth 70 Mic Problems</u></a></li>
<li><a href="https://sound-issues.techidaily.com/the-ultimate-guide-getting-hdmi-sounds-back-on-your-older-windows-7-computer/"><u>The Ultimate Guide: Getting HDMI Sounds Back On Your Older Windows 7 Computer</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshoot-and-fix-windows-7-microphone-issues-ultimate-guide/"><u>Troubleshoot and Fix Windows 7 Microphone Issues - Ultimate Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshoot-fortnites-voice-chatting-glitches-fast-and-efficiently/"><u>Troubleshoot Fortnite's Voice Chatting Glitches Fast & Efficiently!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-guide-how-to-fix-a-non-functioning-mic-on-skype-for-windows-11-users/"><u>Troubleshooting Guide: How to Fix a Non-Functioning Mic on Skype for Windows 11 Users</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-guide-solving-fortnite-audio-issues/"><u>Troubleshooting Guide: Solving Fortnite Audio Issues</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-silent-screens-in-apex-legends-how-to-get-the-volume-back/"><u>Troubleshooting Silent Screens in Apex Legends: How to Get the Volume Back</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-unknown-speakers-a-step-by-step-guide-for-windows-10/"><u>Troubleshooting Unknown Speakers: A Step-by-Step Guide for Windows 10</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016704207-turtle-beach-headset-dilemma-heres-how-to-make-your-mic-work-again/"><u>Turtle Beach Headset Dilemma? Here's How to Make Your Mic Work Again!</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-nokia-110-4g-2023-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Nokia 110 4G (2023) on Mac?</u></a></li>
</ul></div>
