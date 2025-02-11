---
title: Quick Fixes to Enable Your Windows Scanner
date: 2025-02-06T08:27:58.579Z
updated: 2025-02-10T22:16:57.176Z
tags:
  - win11
  - win10
  - win7
categories:
  - ScannerIssues
description: This Article Describes Quick Fixes to Enable Your Windows Scanner
excerpt: This Article Describes Quick Fixes to Enable Your Windows Scanner
thumbnail: https://thmb.techidaily.com/a50833de398a016d5f4384db8ba343a7a22c031d122aae5cba2e71718d3b50f6.jpg
---

## How to Fix HP Scanner Not Working - 2022 Tips

![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd167112d84d.jpg)

 If your**HP scanner is not working** , don’t worry. This is a common scanner problem and you can fix it quickly and easily.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why is my HP scanner not working?

 The HP scanner not working issues include**the** scanner won’t scan, the scanner not being detected by your computer, or errors popping**up** when you’re using your scanner, etc.

 The causes for these problems are various and sometimes hard to identify. As you can imagine, the connection problem can prevent your scanner from connecting to the computer, and the software and services problems in your computer are the possible reasons for this issue.

 But don’t worry. We’ll help you fix the scanner not working on HP.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click**Apply** and**OK** to save the changes.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1688e0055e.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then restart your computer. Try to use your HP scanner again and see if it works now.

 If your HP scanner issue still persists, follow these steps to enable some more services:

1. On your keyboard, press the**Windows logo key** and**R** at the same time to invoke the Run box.
2. Type**services.msc** and click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1678201865.jpg)
3. Ensure these services are set to**Automatic** and the**Service status** is**Running** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
3. Then wait for**Verification 100% complete** . This can take a while.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-blog.techidaily.com/aster-youtube-monetization-tips-to-boost-income-via-shorts/"><u>[New] Master YouTube Monetization Tips to Boost Income via Shorts</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-harnessing-online-platforms-beyond-youtube-to-30plus-communities/"><u>[Updated] 2024 Approved Harnessing Online Platforms Beyond YouTube to 30+ Communities</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-top-ranked-e-learning-presentation-palette/"><u>[Updated] 2024 Approved Top-Ranked E-Learning Presentation Palette</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-visual-description-programmer/"><u>[Updated] 2024 Approved Visual Description Programmer</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-authoritative-resource-streamlining-screencasts-on-the-go-with-mobizen/"><u>2024 Approved Authoritative Resource Streamlining Screencasts on the Go With Mobizen</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-hue-mastery-interface/"><u>2024 Approved Hue Mastery Interface</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/different-methods-to-unlock-your-apple-iphone-15-by-drfone-ios/"><u>Different Methods To Unlock Your Apple iPhone 15</u></a></li>
<li><a href="https://sound-issues.techidaily.com/effective-solutions-for-resolving-pubgs-voice-chat-connectivity-issues/"><u>Effective Solutions for Resolving PUBG's Voice Chat Connectivity Issues</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-your-razer-man-o-war-microphone-issues-a-step-by-step-guide/"><u>Fixing Your Razer Man O' War Microphone Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-elevate-your-chat-with-discord-recording-techniques/"><u>In 2024, Elevate Your Chat with Discord Recording Techniques</u></a></li>
<li><a href="https://sound-issues.techidaily.com/it-takes-two-no-sound-or-audio-issue-on-pc-fix/"><u>It Takes Two No Sound or Audio Issue on PC Fix</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolved-issue-audio-misdirection-headphones-connected-yet-sound-emerges-from-speakers/"><u>Resolved Issue: Audio Misdirection - Headphones Connected, Yet Sound Emerges From Speakers</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solved-why-is-my-apex-legends-voice-chat-on-pause-get-it-running-today/"><u>Solved: Why Is My Apex Legends Voice Chat on Pause? Get It Running Today</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ltimate-youtube-music-replay-tracks-2023-for-2024/"><u>The Ultimate YouTube Music Replay Tracks, 2023 for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-your-microsoft-teams-audio-on-pcs-windows-11-and-10-solutions/"><u>Troubleshooting Your Microsoft Teams Audio on PCs: Windows 11 & 10 Solutions</u></a></li>
<li><a href="https://sound-issues.techidaily.com/windows-10-airpods-mic-issues-quick-fix-solutions/"><u>Windows 10 AirPods Mic Issues - Quick Fix Solutions</u></a></li>
<li><a href="https://sound-issues.techidaily.com/windows-10-gaming-audio-problem-anchor-yourself-with-the-ultimate-anthem-soundfix-guide/"><u>Windows 10 Gaming Audio Problem: Anchor Yourself with the Ultimate Anthem Soundfix Guide</u></a></li>
</ul></div>

