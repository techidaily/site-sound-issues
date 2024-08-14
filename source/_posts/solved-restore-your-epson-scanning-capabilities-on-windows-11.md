---
title: "[SOLVED] Restore Your Epson Scanning Capabilities on Windows 11"
date: 2024-08-13T10:50:58.602Z
updated: 2024-08-14T10:50:58.602Z
tags:
  - win11
  - win10
  - win7
categories:
  - ScannerIssues
description: This Article Describes [SOLVED] Restore Your Epson Scanning Capabilities on Windows 11
excerpt: This Article Describes [SOLVED] Restore Your Epson Scanning Capabilities on Windows 11
thumbnail: https://thmb.techidaily.com/0e797ac9495f1912f56b8317309a2339c9d64cc1198dac03501e79efeb25298f.jpg
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
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
### Fix 2: Enable Windows Image Acquisition (WIA) service and associated services

**Windows Image Acquisition** **(WIA)** is a Microsoft model that allows graphics software to communicate with imaging hardware such as scanners and cameras. So you should enable WIA service in your computer if your scanner stops working. Here’s what you need to do:

1. On your keyboard, press the**Windows logo key** and**R** at the same time to invoke the**Run** box.
2. Type**services.msc** and click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1678201865.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
3. Scroll down and double click**Windows Image Acquisition (WIA)** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd167eed749a.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
4. In the popup pane, ensure the**Startup type** is set**Automatic** , and the**Service status** is**Running** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd168549db26.jpg)  
 If the**Service status** is already**Running** , click**Stop** to stop the service, then click**Start** to re-enable the service.
5. Click**Apply** and**OK** to save the changes.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1688e0055e.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Copy & paste the following command line into the Command Prompt window and press**Enter** .  
`**msdt.exe -id DeviceDiagnostic**`
3. Click**Next** in the popped-up window and the troubleshooter will start detecting hardware problems automatically.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/next-step.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
4. Follow the on-screen instructions to finish the troubleshooting and fix the detected issue.

 After that, try your scanner again and see if it’s working properly.

---

### Fix 5: Run System File Checker

 System File Checker (SFC) is a built-in Windows feature that scans corrupted system files and repairs it automatically.

 Your HP scanning is not working because of some corrupted system files, so you can try SFC to fix the problem.

1. Type**cmd** in the search box, right-click Command Prompt, and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd0319454560.jpg)
2. In Command Prompt, type the following command, then press**Enter** .  
sfc /scannow  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd031d993e59.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-record-videos.techidaily.com/new-learning-ranks-top-10-education-centric-channels/"><u>[New] Learning Ranks  Top 10 Education-Centric Channels</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-leveraging-tech-for-efficient-facebook-to-whatsapp-video-sharing-for-2024/"><u>[Updated] Leveraging Tech for Efficient Facebook to WhatsApp Video Sharing for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-forge-corporate-icons-without-spending-a-dime/"><u>2024 Approved  Forge Corporate Icons Without Spending a Dime</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ai-face-off-comparing-notion-and-chatgpt-for-ultimate-productivity/"><u>AI Face-Off: Comparing Notion and ChatGPT for Ultimate Productivity</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-lava-yuva-3-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Lava Yuva 3 is off? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-secrets-5-entertaining-hacks/"><u>Command Prompt Secrets: 5 Entertaining Hacks</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diagnosing-and-repairing-no-sound-on-laptop-built-in-speakers-effective-fixes/"><u>Diagnosing and Repairing No Sound on Laptop Built-In Speakers – Effective Fixes</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diagnosing-and-repairing-windows-11s-bluetooth-connectivity-problems/"><u>Diagnosing and Repairing Windows 11'S Bluetooth Connectivity Problems</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diy-fixes-for-a-malfunctioning-corsair-void-microphone-step-by-step-tips/"><u>DIY Fixes for a Malfunctioning Corsair Void Microphone - Step-by-Step Tips</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diy-fixes-for-when-your-hyperx-cloud-alpha-mic-stops-working/"><u>DIY Fixes for When Your HyperX Cloud Alpha Mic Stops Working</u></a></li>
<li><a href="https://sound-issues.techidaily.com/effective-fixes-for-nonfunctioning-hdmi-sound-output-on-windows-7/"><u>Effective Fixes for Nonfunctioning HDMI Sound Output on Windows 7</u></a></li>
<li><a href="https://sound-issues.techidaily.com/effective-solutions-to-reactivate-a-non-responsive-corsair-hs70-mic/"><u>Effective Solutions to Reactivate a Non-Responsive Corsair HS70 Mic</u></a></li>
<li><a href="https://sound-issues.techidaily.com/enhance-your-video-calls-solving-the-dilemma-of-a-broken-skype-mic-on-windows-11/"><u>Enhance Your Video Calls: Solving the Dilemma of a Broken Skype Mic on Windows 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/epson-scanner-woes-on-windows-os/"><u>Epson Scanner Woes on Windows OS</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-issues-with-corsair-hs70-headset-mic-effective-solutions-inside/"><u>Fixing Issues with Corsair HS70 Headset Mic - Effective Solutions Inside</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-silent-system-solving-cyberpunk-2077-audio-issues-in-windows-10/"><u>Fixing Silent System: Solving 'Cyberpunk 2077' Audio Issues in Windows 10</u></a></li>
<li><a href="https://sound-issues.techidaily.com/guide-to-restoring-pc-mic-functionality-in-rec-room-updated/"><u>Guide to Restoring PC Mic Functionality in Rec Room [Updated ]</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-get-the-sound-back-in-pc-warzone-games-expert-fixes-and-advice/"><u>How to Get the Sound Back in PC Warzone Games - Expert Fixes & Advice</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-resolve-sound-problems-in-windows-11-easily/"><u>How to Resolve Sound Problems in Windows 11 Easily</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-restore-sound-using-the-conexant-smartaudio-hd-driver-in-windows-10/"><u>How to Restore Sound Using the Conexant SmartAudio HD Driver in Windows 10</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-15-pro-to-other-iphone-12-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 15 Pro to other iPhone 12 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-2-methods-to-add-effects-on-tiktok/"><u>In 2024, 2 Methods To Add Effects On TikTok</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-lava-blaze-pro-5g-location-on-twitter-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change your Lava Blaze Pro 5G Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/integrating-mobile-code-generators-in-fb-for-enhanced-safety/"><u>Integrating Mobile Code Generators in FB for Enhanced Safety</u></a></li>
<li><a href="https://sound-issues.techidaily.com/maximize-your-audio-experience-a-guide-to-amplifying-volume-in-windows-10/"><u>Maximize Your Audio Experience: A Guide to Amplifying Volume in Windows 10</u></a></li>
<li><a href="https://sound-issues.techidaily.com/microphone-diagnosis-a-fast-track-to-perfect-sound-quality/"><u>Microphone Diagnosis: A Fast Track to Perfect Sound Quality.</u></a></li>
<li><a href="https://sound-issues.techidaily.com/no-more-lag-with-these-simple-tweaks-to-your-bluetooth-audio-setup/"><u>No More Lag with These Simple Tweaks to Your Bluetooth Audio Setup</u></a></li>
<li><a href="https://sound-issues.techidaily.com/noise-back-successful-troubleshooting-steps-for-wows-sound-problem/"><u>Noise Back! Successful Troubleshooting Steps for WoW's Sound Problem</u></a></li>
<li><a href="https://sound-issues.techidaily.com/overcoming-the-challenge-of-a-silent-microphone-on-your-hyperx-cloud-alpha-setup/"><u>Overcoming the Challenge of a Silent Microphone on Your HyperX Cloud Alpha Setup</u></a></li>
<li><a href="https://sound-issues.techidaily.com/rec-room-headset-malfunction-fixing-mic-issues-on-pc/"><u>Rec Room Headset Malfunction: Fixing Mic Issues on PC</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolved-missing-headphones-in-device-list-during-media-playback-on-windows-11/"><u>Resolved: Missing Headphones in Device List During Media Playback on Windows 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/simple-troubleshooting-steps-for-a-non-functioning-hangouts-microphone/"><u>Simple Troubleshooting Steps for a Non-Functioning Hangouts Microphone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solve-the-mystery-of-a-quiet-logitech-g933-quick-fixes-revealed/"><u>Solve the Mystery of a Quiet Logitech G933 - Quick Fixes Revealed!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solved-how-to-restore-functionality-of-non-working-stereo-mixes/"><u>Solved! How to Restore Functionality of Non-Working Stereo Mixes</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-common-problems-with-the-sennheiser-headset-microphone-in-games/"><u>Solving Common Problems with the Sennheiser Headset Microphone in Games</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-the-bluetooth-not-working-error-for-windows-11-users/"><u>Solving the 'Bluetooth Not Working' Error for Windows 11 Users</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-fixes-when-your-hyperx-cloud-mic-fails-to-work-properly/"><u>Step-by-Step Fixes When Your HyperX Cloud Mic Fails to Work Properly</u></a></li>
</ul></div>
