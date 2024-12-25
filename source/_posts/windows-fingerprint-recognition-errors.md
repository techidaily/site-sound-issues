---
title: Windows Fingerprint Recognition Errors
date: 2024-12-24T19:08:40.168Z
updated: 2024-12-25T19:29:23.212Z
tags:
  - win11
  - win10
  - win7
categories:
  - ScannerIssues
description: This Article Describes Windows Fingerprint Recognition Errors
excerpt: This Article Describes Windows Fingerprint Recognition Errors
thumbnail: https://thmb.techidaily.com/2531084f8c85679ae61e8759b52e3fe4836202538838ce8ab82c47df34846229.jpg
---

## How to Fix HP Scanner Not Working - 2022 Tips

![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd167112d84d.jpg)

 If your**HP scanner is not working** , don’t worry. This is a common scanner problem and you can fix it quickly and easily.

## Why is my HP scanner not working?

 The HP scanner not working issues include**the** scanner won’t scan, the scanner not being detected by your computer, or errors popping**up** when you’re using your scanner, etc.

 The causes for these problems are various and sometimes hard to identify. As you can imagine, the connection problem can prevent your scanner from connecting to the computer, and the software and services problems in your computer are the possible reasons for this issue.

 But don’t worry. We’ll help you fix the scanner not working on HP.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1678201865.jpg)
3. Scroll down and double click**Windows Image Acquisition (WIA)** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd167eed749a.jpg)
4. In the popup pane, ensure the**Startup type** is set**Automatic** , and the**Service status** is**Running** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd168549db26.jpg)  
 If the**Service status** is already**Running** , click**Stop** to stop the service, then click**Start** to re-enable the service.
5. Click**Apply** and**OK** to save the changes.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1688e0055e.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then restart your computer. Try to use your HP scanner again and see if it works now.

 If your HP scanner issue still persists, follow these steps to enable some more services:

1. On your keyboard, press the**Windows logo key** and**R** at the same time to invoke the Run box.
2. Type**services.msc** and click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1678201865.jpg)
3. Ensure these services are set to**Automatic** and the**Service status** is**Running** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**The Pro version of Driver Easy** comes with full technical support.  
 If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](https://bellelily.pxf.io/m5azgm) .**

4) Restart your computer to take effect.

Then try scanning with your scanner to see if it works.

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-access.techidaily.com/updated-trailblazing-top-zooid-beginnings-list-for-2024/"><u>[Updated] Trailblazing Top Zooid Beginnings List for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/5-must-have-mkv-tools-for-macos/"><u>5 Must-Have MKV Tools for macOS</u></a></li>
<li><a href="https://sound-issues.techidaily.com/effective-solutions-for-dealing-with-a-broken-microphone-in-windows-11-systems/"><u>Effective Solutions for Dealing with a Broken Microphone in Windows 11 Systems</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-the-issue-how-to-troubleshoot-a-non-functional-mpow-mic-in-windows/"><u>Fixing the Issue: How to Troubleshoot a Non-Functional MPOW Mic in Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-easy-ways-to-copy-contacts-from-xiaomi-14-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Easy Ways to Copy Contacts from Xiaomi 14 to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Motorola Moto E13? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-hidefake-snapchat-location-on-your-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Hide/Fake Snapchat Location on Your Oppo A58 4G | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-techniques-to-procure-free-visual-frame-videos/"><u>In 2024, Techniques to Procure Free Visual Frame Videos</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolving-sound-glitches-and-quality-issues-in-windows-11-and-7-a-comprehensive-guide/"><u>Resolving Sound Glitches and Quality Issues in Windows 11 & 7: A Comprehensive Guide</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/skyrocketing-fame-here-are-the-top-30-creative-tiktok-usernames/"><u>Skyrocketing Fame? Here Are the Top 30 Creative TikTok Usernames</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-guide-resolving-hdmi-speaker-malfunctions-on-windows-7/"><u>Step-by-Step Guide: Resolving HDMI Speaker Malfunctions on Windows 7</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/top-rated-mp4-video-encoders-of-202e-a-comprehensive-guide-to-optimize-your-video-content/"><u>Top Rated MP4 Video Encoders of 202E: A Comprehensive Guide to Optimize Your Video Content</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-pc-audio-issues-boosting-your-windows-10-systems-speakers/"><u>Troubleshooting PC Audio Issues: Boosting Your Windows 10 System's Speakers</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unveiling-the-least-expensive-ssl-choices/"><u>Unveiling the Least Expensive SSL Choices</u></a></li>
</ul></div>

