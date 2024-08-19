---
title: How to Reset and Activate a Disabled Windows Scan Tool
date: 2024-08-18T08:07:52.766Z
updated: 2024-08-19T08:07:52.766Z
tags:
  - win11
  - win10
  - win7
categories:
  - ScannerIssues
description: This Article Describes How to Reset and Activate a Disabled Windows Scan Tool
excerpt: This Article Describes How to Reset and Activate a Disabled Windows Scan Tool
thumbnail: https://thmb.techidaily.com/470729e2db7d552929f896fede9bd2112971e2401fbcd66ce15df928f6be58b2.jpg
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

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Fix 1: Check the connection issue

 To use your scanner, you need to make sure that your scanner is**powered on** in the first place.

 Then you should check the**connection** **issue** . If you’re using a USB scanner, check the**USB ports** and**USB cables** to ensure it works properly. While you’re using a network scanner, ensure your computer has a good**Internet** **connection** , and your scanner connects to your computer under the Internet. In addition, if you’re using **[VPN](https://tools.techidaily.com/drivereasy/download/)**  on your computer, try**disconnecting VPN** from your computer and scanning again.

 If you’ve checked the above steps and your HP scanner still doesn’t work, don’t worry. There is something else to try.

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
### Fix 2: Enable Windows Image Acquisition (WIA) service and associated services

**Windows Image Acquisition** **(WIA)** is a Microsoft model that allows graphics software to communicate with imaging hardware such as scanners and cameras. So you should enable WIA service in your computer if your scanner stops working. Here’s what you need to do:

1. On your keyboard, press the**Windows logo key** and**R** at the same time to invoke the**Run** box.
2. Type**services.msc** and click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1678201865.jpg)
3. Scroll down and double click**Windows Image Acquisition (WIA)** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd167eed749a.jpg)
4. In the popup pane, ensure the**Startup type** is set**Automatic** , and the**Service status** is**Running** .  
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd168549db26.jpg)  
 If the**Service status** is already**Running** , click**Stop** to stop the service, then click**Start** to re-enable the service.
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Click**Apply** and**OK** to save the changes.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1688e0055e.jpg)

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
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

### Fix 4: Troubleshoot hardware problems

 It’s possible that there’s something wrong with your scanner, so run a troubleshooter in your computer to fix the issue.

1. Type**cmd** in the Windows Search bar and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/cmd-run-as-admin.jpg)
2. Copy & paste the following command line into the Command Prompt window and press**Enter** .  
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`**msdt.exe -id DeviceDiagnostic**`
3. Click**Next** in the popped-up window and the troubleshooter will start detecting hardware problems automatically.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/next-step.jpg)
4. Follow the on-screen instructions to finish the troubleshooting and fix the detected issue.

 After that, try your scanner again and see if it’s working properly.

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
### Fix 5: Run System File Checker

 System File Checker (SFC) is a built-in Windows feature that scans corrupted system files and repairs it automatically.

 Your HP scanning is not working because of some corrupted system files, so you can try SFC to fix the problem.

1. Type**cmd** in the search box, right-click Command Prompt, and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd0319454560.jpg)
2. In Command Prompt, type the following command, then press**Enter** .  
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-top-screen-capture-tools-explored-apowersoft-and-others-compared/"><u>[New] 2024 Approved  Top Screen Capture Tools Explored - Apowersoft and Others Compared</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-accelerated-learning-path-with-final-cut-pro/"><u>[New] Accelerated Learning Path with Final Cut Pro</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-glitch-canon-pixma-mp620-drivers-on-win11-unseen/"><u>[Technical Glitch] Canon Pixma MP620 Drivers on Win11 Unseen</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-bland-to-brilliant-elevate-your-images-in-canva/"><u>[Updated] From Bland to Brilliant  Elevate Your Images in Canva</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-your-free-tool-to-record-androids-precision/"><u>[Updated] In 2024, Your Free Tool to Record Android's Precision</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-mastering-spotify-promos-your-comprehensive-guide/"><u>2024 Approved  Mastering Spotify Promos  Your Comprehensive Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/cyberpunk-groans-with-crackling-noise-heres-how-to-fix-it/"><u>Cyberpunk Groans with Crackling Noise? Here's How to Fix It!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/defeat-no-sound-glitch-in-battlefield-4-with-these-pro-solutions/"><u>Defeat No-Sound Glitch in Battlefield 4 with These Pro Solutions!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diagnosing-and-correcting-mpow-microphone-problems-on-your-windows-computer/"><u>Diagnosing and Correcting MPOW Microphone Problems on Your Windows Computer</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diagnosing-and-repairing-the-broken-push-to-talk-command-in-overwatch/"><u>Diagnosing and Repairing the Broken Push-To-Talk Command in Overwatch</u></a></li>
<li><a href="https://sound-issues.techidaily.com/dota-2-pc-microphone-not-working-heres-how-you-can-fix-it-now/"><u>Dota 2 PC Microphone Not Working? Here's How You Can Fix It Now</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/elevate-your-diary-habits-with-our-selection-of-the-best-journaling-apps/"><u>Elevate Your Diary Habits with Our Selection of the Best ✍️ Journaling Apps</u></a></li>
<li><a href="https://sound-issues.techidaily.com/expert-advice-on-repairing-realtek-hd-audio-hardware-malfunctions/"><u>Expert Advice on Repairing Realtek HD Audio Hardware Malfunctions</u></a></li>
<li><a href="https://sound-issues.techidaily.com/expert-tips-to-resolve-logitech-g430-microphone-issues-quickly/"><u>Expert Tips to Resolve Logitech G430 Microphone Issues Quickly</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/full-guide-to-bypass-vivo-y200-frp-by-drfone-android/"><u>Full Guide to Bypass Vivo Y200 FRP</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015612812-google-meet-not-recognizing-mic-heres-how-to-fix-it-on-windows-11-and-10-devices/"><u>Google Meet Not Recognizing Mic? Here's How to Fix It on Windows 11 & 10 Devices!</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-vivo-y77t-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Vivo Y77t? | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-fix-audio-glitches-and-warping-sounds-in-windows-11-and-7-solutions-revealed/"><u>How to Fix Audio Glitches and Warping Sounds in Windows 11 & 7 - Solutions Revealed!</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-fix-oem-unlock-missing-on-itel-a60-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Itel A60?</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-get-your-logitech-g533-mic-working-again-a-comprehensive-guide/"><u>How to Get Your Logitech G533 Mic Working Again: A Comprehensive Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-resolve-overwatch-talk-on-demand-tod-connection-problems/"><u>How to Resolve Overwatch Talk-On-Demand (TOD) Connection Problems</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016713141-quick-fix-for-loud-popping-in-your-earbuds-expert-advice/"><u>Quick Fix for Loud Popping in Your Earbuds: Expert Advice</u></a></li>
<li><a href="https://sound-issues.techidaily.com/quick-guide-resolving-connectivity-issues-with-your-logitech-g633-mic/"><u>Quick Guide: Resolving Connectivity Issues with Your Logitech G633 Mic</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolve-your-skype-audio-problems-with-simple-fixes/"><u>Resolve Your Skype Audio Problems with Simple Fixes</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolved-overcoming-the-challenge-of-non-responsive-voice-chat-in-phasmophobia/"><u>Resolved: Overcoming the Challenge of Non-Responsive Voice Chat in Phasmophobia</u></a></li>
<li><a href="https://win11.techidaily.com/shuffling-monitors-order-in-modern-oses/"><u>Shuffling Monitors' Order in Modern OSes</u></a></li>
<li><a href="https://sound-issues.techidaily.com/silencing-sound-irregularities-expert-advice-on-correcting-pop-noises-in-windows/"><u>Silencing Sound Irregularities: Expert Advice on Correcting Pop Noises in Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/smartphone-evolution-the-top-8-android-and-ios-ai-apps/"><u>Smartphone Evolution: The Top 8 Android & iOS AI Apps</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solved-common-problems-and-fixes-for-non-functional-hyperx-cloud-alpha-microphones/"><u>Solved: Common Problems & Fixes for Non-Functional HyperX Cloud Alpha Microphones</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solved-how-to-restore-your-hyperx-cloud-alpha-s-headset-microphone-functionality/"><u>Solved: How to Restore Your HyperX Cloud Alpha S Headset Microphone Functionality</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solved-troubleshooting-common-issues-with-redragon-computer-microphone/"><u>Solved: Troubleshooting Common Issues with Redragon Computer Microphone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-audio-hitches-a-guide-to-fixing-zoom-mic-not-working-on-win-1110/"><u>Solving Audio Hitches: A Guide to Fixing Zoom Mic Not Working on Win 11/10</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-fixes-how-to-restore-microphone-functionality-on-your-steelseries-arctis-prime/"><u>Troubleshooting Fixes: How to Restore Microphone Functionality on Your SteelSeries Arctis Prime</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-guide-fixing-the-issue-when-your-steelseries-arctis-prime-microphone-fails/"><u>Troubleshooting Guide: Fixing the Issue When Your SteelSeries Arctis Prime Microphone Fails</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-windows-11-speaker-and-microphone-not-functioning-correctly/"><u>Troubleshooting Windows 11 Speaker & Microphone Not Functioning Correctly</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-fixing-issues-with-active-audio-services/"><u>Troubleshooting: Fixing Issues with Active Audio Services</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-xbox-mic-use-with-windows-11-app/"><u>Unblocking Xbox Mic Use with Windows 11 App</u></a></li>
</ul></div>
