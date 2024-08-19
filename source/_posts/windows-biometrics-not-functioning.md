---
title: Windows Biometrics Not Functioning
date: 2024-08-18T08:19:23.520Z
updated: 2024-08-19T08:19:23.520Z
tags:
  - win11
  - win10
  - win7
categories:
  - ScannerIssues
description: This Article Describes Windows Biometrics Not Functioning
excerpt: This Article Describes Windows Biometrics Not Functioning
thumbnail: https://thmb.techidaily.com/9e54865f3f57ec57dc69d69631538169245afb52f02b58f105955b7146a11c16.jpg
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
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
### Fix 1: Check the connection issue

 To use your scanner, you need to make sure that your scanner is**powered on** in the first place.

 Then you should check the**connection** **issue** . If you’re using a USB scanner, check the**USB ports** and**USB cables** to ensure it works properly. While you’re using a network scanner, ensure your computer has a good**Internet** **connection** , and your scanner connects to your computer under the Internet. In addition, if you’re using **[VPN](https://tools.techidaily.com/drivereasy/download/)**  on your computer, try**disconnecting VPN** from your computer and scanning again.

 If you’ve checked the above steps and your HP scanner still doesn’t work, don’t worry. There is something else to try.

---

### Fix 2: Enable Windows Image Acquisition (WIA) service and associated services

**Windows Image Acquisition** **(WIA)** is a Microsoft model that allows graphics software to communicate with imaging hardware such as scanners and cameras. So you should enable WIA service in your computer if your scanner stops working. Here’s what you need to do:

1. On your keyboard, press the**Windows logo key** and**R** at the same time to invoke the**Run** box.
2. Type**services.msc** and click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1678201865.jpg)
3. Scroll down and double click**Windows Image Acquisition (WIA)** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd167eed749a.jpg)
4. In the popup pane, ensure the**Startup type** is set**Automatic** , and the**Service status** is**Running** .  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd168549db26.jpg)  
 If the**Service status** is already**Running** , click**Stop** to stop the service, then click**Start** to re-enable the service.
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**The Pro version of Driver Easy** comes with full technical support.  
 If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](https://bellelily.pxf.io/m5azgm) .**

4) Restart your computer to take effect.

Then try scanning with your scanner to see if it works.

---

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After that, try your scanner again and see if it’s working properly.

---

### Fix 5: Run System File Checker

 System File Checker (SFC) is a built-in Windows feature that scans corrupted system files and repairs it automatically.

 Your HP scanning is not working because of some corrupted system files, so you can try SFC to fix the problem.

1. Type**cmd** in the search box, right-click Command Prompt, and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd0319454560.jpg)
2. In Command Prompt, type the following command, then press**Enter** .  
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
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
<li><a href="https://sound-issues.techidaily.com/solved-realtek-microphone-not-working/"><u>[Solved] Realtek Microphone Not Working</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-spotlight-on-best-selling-ae-plugins-for-instagram/"><u>[Updated] Spotlight on Best-Selling AE Plugins for Instagram</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-unleashing-creative-potential-in-minecraft-with-circles-and-spheres/"><u>[Updated] Unleashing Creative Potential in Minecraft with Circles & Spheres</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-world-server-smash-off-seeking-ruthless-gamers-to-test-their-mettle-against-machines/"><u>2024 World Server Smash-Off: Seeking Ruthless Gamers to Test Their Mettle Against Machines</u></a></li>
<li><a href="https://sound-issues.techidaily.com/audio-alignment-achieved-direct-sound-to-headphones-not-speakers-a-fix-guide/"><u>Audio Alignment Achieved: Direct Sound to Headphones, Not Speakers - A Fix Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/audio-perfection-achieved-step-by-step-solutions-for-eliminating-windows-711-sound-problems/"><u>Audio Perfection Achieved: Step-by-Step Solutions for Eliminating Windows 7/11 Sound Problems</u></a></li>
<li><a href="https://extra-resources.techidaily.com/become-a-video-quality-guru-with-vce-22-knowledge-for-2024/"><u>Become a Video Quality Guru with VCE 2.2 Knowledge for 2024</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-itel-p55t-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Itel P55T Hard Reset | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/boost-your-pcs-audio-a-step-by-step-guide-to-enhancing-sound-on-windows-1/"><u>Boost Your PC's Audio: A Step-by-Step Guide to Enhancing Sound on Windows 1</u></a></li>
<li><a href="https://fox-info.techidaily.com/chromatic-confluence-music-and-photography-online/"><u>Chromatic Confluence  Music & Photography Online</u></a></li>
<li><a href="https://sound-issues.techidaily.com/common-problems-and-solutions-for-unresponsive-realtek-microphones/"><u>Common Problems and Solutions for Unresponsive Realtek Microphones</u></a></li>
<li><a href="https://sound-issues.techidaily.com/conquer-communication-breakdowns-a-guide-to-restoring-sound-on-discord/"><u>Conquer Communication Breakdowns: A Guide to Restoring Sound on Discord</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diagnosing-and-repairing-tozo-t6-connectivity-problems-under-windows-11/"><u>Diagnosing and Repairing Tozo T6 Connectivity Problems Under Windows 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diy-repairs-get-your-corsair-void-mic-working-again/"><u>DIY Repairs: Get Your Corsair Void Mic Working Again</u></a></li>
<li><a href="https://sound-issues.techidaily.com/eliminate-unwanted-noise-in-your-computers-speakers-fix-for-popping-sounds/"><u>Eliminate Unwanted Noise in Your Computer's Speakers - Fix for Popping Sounds</u></a></li>
<li><a href="https://sound-issues.techidaily.com/eliminating-cyberpunk-2077-sound-glitches-for-a-smoother-gaming-experience/"><u>Eliminating Cyberpunk 2077 Sound Glitches for a Smoother Gaming Experience</u></a></li>
<li><a href="https://sound-issues.techidaily.com/epson-printer-error-on-windows-1011/"><u>Epson Printer Error on Windows 10/11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016906776-fix-phasmophobias-voice-chat-gone-silent-heres-what-works/"><u>Fix Phasmophobia's Voice Chat Gone Silent? Here’s What Works!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-mic-malfunctions-a-users-guide-to-restoring-logitech-g935-in-windows/"><u>Fixing Mic Malfunctions: A User's Guide to Restoring Logitech G935 in Windows</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-silent-issues-resolving-lack-of-audio-in-borderlands-3-for-windows/"><u>Fixing Silent Issues: Resolving Lack of Audio in Borderlands 3 for Windows</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-the-astro-a50-microphone-issue-troubleshooting-steps/"><u>Fixing the Astro A50 Microphone Issue: Troubleshooting Steps</u></a></li>
<li><a href="https://sound-issues.techidaily.com/hdmi-problem-solutions-preventing-device-access-by-competing-software/"><u>HDMI Problem Solutions: Preventing Device Access by Competing Software</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-itel-p55-5g-drfone-by-drfone-virtual-android/"><u>How to Change Netflix Location to Get More Country Version On Itel P55 5G | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-eliminate-bluetooth-audio-glitches-in-your-windows-pc-step-by-step-fixes/"><u>How to Eliminate Bluetooth Audio Glitches in Your Windows PC: Step-by-Step Fixes</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-resolve-the-problem-when-your-steelseries-arctis-1-microphone-fails-to-function-properly/"><u>How to Resolve the Problem When Your SteelSeries Arctis 1 Microphone Fails to Function Properly</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-restore-push-to-talk-functionality-for-a-smooth-gameplay-experience-in-overwatch/"><u>How to Restore 'Push-to-Talk' Functionality for a Smooth Gameplay Experience in Overwatch</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-top-5-from-oppo-a1x-5g-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Top 5 from Oppo A1x 5G to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016548802-internal-laptop-speakers-not-working-heres-how-you-can-get-them-back-on-track/"><u>Internal Laptop Speakers Not Working? Here’s How You Can Get Them Back on Track!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016706536-jabra-bluetooth-earphones-malfunction-heres-the-ultimate-repair-manual/"><u>Jabra Bluetooth Earphones Malfunction? Here's the Ultimate Repair Manual !</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/perfecting-the-art-of-itunes-video-recording/"><u>Perfecting the Art of iTunes Video Recording</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolving-intermittent-audio-dropping-issues-in-windows-11-a-comprehensive-guide/"><u>Resolving Intermittent Audio Dropping Issues in Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolving-sound-problems-after-installing-the-latest-windows-update/"><u>Resolving Sound Problems After Installing the Latest Windows Update</u></a></li>
<li><a href="https://sound-issues.techidaily.com/restoring-audio-functionality-to-your-g435-headset-expert-tips-and-tricks/"><u>Restoring Audio Functionality to Your G435 Headset: Expert Tips & Tricks</u></a></li>
<li><a href="https://sound-issues.techidaily.com/revive-your-audio-restore-google-meet-microphone-functionality-on-windows-1110-systems/"><u>Revive Your Audio: Restore Google Meet Microphone Functionality on Windows 11/10 Systems</u></a></li>
<li><a href="https://sound-issues.techidaily.com/silence-the-pop-effective-solutions-to-fix-crackling-sound-problems-with-your-pcs-audio-windows-107-edition/"><u>Silence the Pop: Effective Solutions to Fix Crackling Sound Problems with Your PC's Audio - Windows 10/7 Edition</u></a></li>
<li><a href="https://sound-issues.techidaily.com/silent-anthem-easy-steps-to-restore-sound-on-windows-10-gaming-pcs/"><u>Silent Anthem: Easy Steps to Restore Sound on Windows 10 Gaming PCs</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solve-computer-sound-failures-in-minutes-with-these-tips/"><u>Solve Computer Sound Failures in Minutes with These Tips</u></a></li>
<li><a href="https://techtrends.techidaily.com/solving-the-puzzle-a-step-by-step-guide-to-resolve-netflix-error-nw-1-19/"><u>Solving the Puzzle: A Step-by-Step Guide to Resolve Netflix Error NW-1-19</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-diy-fixes-to-restore-speaker-functionality-on-your-personal-computer/"><u>Step-by-Step DIY Fixes to Restore Speaker Functionality on Your Personal Computer</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-guide-how-to-fix-an-unresponsive-mic-in-your-headset/"><u>Step-by-Step Guide: How to Fix an Unresponsive Mic in Your Headset</u></a></li>
</ul></div>
