---
title: "Resolving: Epson Scanner Error on Windows 11"
date: 2024-08-27T21:14:43.033Z
updated: 2024-08-28T21:14:43.033Z
tags:
  - win11
  - win10
  - win7
categories:
  - ScannerIssues
description: "This Article Describes Resolving: Epson Scanner Error on Windows 11"
excerpt: "This Article Describes Resolving: Epson Scanner Error on Windows 11"
thumbnail: https://thmb.techidaily.com/5d3b16b34799fd4027e4ade17484dcb7de0969abd15218a509c4db117b716df9.jpg
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
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
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
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd168549db26.jpg)  
 If the**Service status** is already**Running** , click**Stop** to stop the service, then click**Start** to re-enable the service.
5. Click**Apply** and**OK** to save the changes.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1688e0055e.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 Then restart your computer. Try to use your HP scanner again and see if it works now.

 If your HP scanner issue still persists, follow these steps to enable some more services:

1. On your keyboard, press the**Windows logo key** and**R** at the same time to invoke the Run box.
2. Type**services.msc** and click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1678201865.jpg)
3. Ensure these services are set to**Automatic** and the**Service status** is**Running** .  
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
   * **Remote Procedure Call RPC**  
   * **DCOM Server Process Launcher**  
   * **RPC Endpoint Mapper**  
   * **Shell Hardware Detection**  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd169897b1a1.jpg)  
   **INFORMATION:**  
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
    The**Windows Image Acquisition (WIA)** service is dependent upon the**Shell Hardware Detection Service** , while the**Shell Hardware Detection Service** is dependent upon these services: Remote Procedure Call RPC, DCOM Server Process Launcher, and RPC Endpoint Mapper.
4. Save the changes and try your scanner again to see if it works.

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
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
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
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
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-data.techidaily.com/n-2024-influencing-factors-for-popular-youtube-videos/"><u>[New] In 2024, Influencing Factors for Popular YouTube Videos</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-steps-for-retrieving-personal-hidden-snapchat-photos/"><u>[New] In 2024, Steps for Retrieving Personal, Hidden Snapchat Photos</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-optimizing-zoom-video-fidelity-comprehensible-guides/"><u>[New] Optimizing Zoom Video Fidelity  Comprehensible Guides</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-enhance-your-gopros-battery-health/"><u>[Updated] How to Enhance Your GoPro's Battery Health</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-ps4-screen-recording-techniques-for-professional-gamers-for-2024/"><u>[Updated] Ps4 Screen Recording  Techniques for Professional Gamers for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/astro-a50-quiet-conundrum-swift-audio-troubleshooting-techniques/"><u>Astro A50 Quiet Conundrum: Swift Audio Troubleshooting Techniques</u></a></li>
<li><a href="https://sound-issues.techidaily.com/bluetooth-sound-delay-fast-fixes-and-solutions/"><u>Bluetooth Sound Delay: Fast Fixes and Solutions</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chaos-in-ai-is-gpt-too-free/"><u>Chaos in AI: Is GPT Too Free?</u></a></li>
<li><a href="https://sound-issues.techidaily.com/comprehensive-fixes-for-running-into-issues-with-audio-services-resolved/"><u>Comprehensive Fixes for Running Into Issues with Audio Service(s) [Resolved]</u></a></li>
<li><a href="https://sound-issues.techidaily.com/effective-strategies-to-resolve-sound-issues-in-your-laptop-a-step-by-step-approach/"><u>Effective Strategies to Resolve Sound Issues in Your Laptop: A Step-by-Step Approach</u></a></li>
<li><a href="https://sound-issues.techidaily.com/eliminating-audio-problems-in-windows-11-effective-solutions-and-advice/"><u>Eliminating Audio Problems in Windows 11: Effective Solutions and Advice</u></a></li>
<li><a href="https://sound-issues.techidaily.com/essential-steps-for-repairing-your-skype-mic-on-windows-11-systems/"><u>Essential Steps for Repairing Your Skype Mic on Windows 11 Systems</u></a></li>
<li><a href="https://sound-issues.techidaily.com/expert-tips-for-resolving-sudden-sound-cutoffs-in-windows-10-now-fixed/"><u>Expert Tips for Resolving Sudden Sound Cutoffs in Windows 10 - Now Fixed</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fix-windows-media-player-volume-issues-ultimate-guide-with-solutions/"><u>Fix Windows Media Player Volume Issues: Ultimate Guide with Solutions</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015852929-fix-your-oculus-rift-s-microphone-issues-in-minutes-top-solutions-of-2024/"><u>Fix Your Oculus Rift S Microphone Issues in Minutes: Top Solutions of 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/gradual-volume-reduction-in-studio-projects-using-logic-pro-for-2024/"><u>Gradual Volume Reduction in Studio Projects Using Logic Pro for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/rical-insights-the-most-relevant-youtube-channels-for-learners/"><u>Historical Insights - The Most Relevant YouTube Channels for Learners</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/how-to-add-audio-to-mkv-2023-update-for-2024/"><u>How to Add Audio to MKV-2023 Update for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-fix-a-crackling-speaker-issue-on-your-pc-with-windows-10-or-7/"><u>How to Fix a Crackling Speaker Issue on Your PC with Windows 10 or 7</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-restore-functionality-of-your-logitech-g935-headset-microphone-in-a-windows-environment/"><u>How to Restore Functionality of Your Logitech G935 Headset Microphone in a Windows Environment</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-revive-your-unresponsive-turtle-beach-recon-70-microphone-a-step-by-step-guide/"><u>How to Revive Your Unresponsive Turtle Beach Recon 70 Microphone - A Step-by-Step Guide</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-nubia-z50s-pro-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Nubia Z50S Pro to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-honor-x7b-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Honor X7b | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-hover-and-watch-utilizing-the-float-feature-on-netflix/"><u>In 2024, Hover & Watch  Utilizing the Float Feature on Netflix</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-realme-v30-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Realme V30 | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-innovative-lecture-title-composing-system/"><u>In 2024, Innovative Lecture Title Composing System</u></a></li>
<li><a href="https://extra-information.techidaily.com/instant-signature-background-erasure-techniques/"><u>Instant Signature Background Erasure Techniques</u></a></li>
<li><a href="https://sound-issues.techidaily.com/lost-in-silence-a-step-by-step-strategy-for-reactivating-your-nvidia-hd-speakers/"><u>Lost in Silence: A Step-by-Step Strategy for Reactivating Your Nvidia HD Speakers</u></a></li>
<li><a href="https://sound-issues.techidaily.com/mastering-stable-discord-sound-quality-expert-strategies-and-fixes-for-the-modern-user/"><u>Mastering Stable Discord Sound Quality - Expert Strategies and Fixes for the Modern User</u></a></li>
<li><a href="https://sound-issues.techidaily.com/mastering-voice-chat-with-in-game-audio-on-discord-platforms/"><u>Mastering Voice Chat with In-Game Audio on Discord Platforms</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/maximizing-twitter-video-quality-full-hd-tips-for-2024/"><u>Maximizing Twitter Video Quality  Full HD Tips for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/overcoming-realtek-hd-audio-manager-startup-errors-expert-solutions-revealed/"><u>Overcoming Realtek HD Audio Manager Startup Errors: Expert Solutions Revealed</u></a></li>
<li><a href="https://sound-issues.techidaily.com/quick-fix-for-broken-headphone-connection-in-windows-10-operating-system/"><u>Quick Fix for Broken Headphone Connection in Windows 10 Operating System</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/record-your-mac-view-in-minutes-for-2024/"><u>Record Your Mac View in Minutes for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/reinstating-soundscape-troubleshooting-conexant-smartaudio-hd-issues-in-win10/"><u>Reinstating Soundscape: Troubleshooting Conexant SmartAudio HD Issues in Win10</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015866090-resolve-your-mic-problems-while-playing-dota-2-on-pc-today/"><u>Resolve Your Mic Problems While Playing Dota 2 on PC Today</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solve-razer-mic-issues-instantly-a-five-step-fix-guide/"><u>Solve Razer Mic Issues Instantly: A Five-Step Fix Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-common-problems-with-your-logitech-g933-headset-mic-a-step-by-step-guide/"><u>Solving Common Problems with Your Logitech G933 Headset Mic: A Step-by-Step Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-the-mystery-of-unwanted-sounds-how-to-eliminate-buzzing-from-your-headphones/"><u>Solving the Mystery of Unwanted Sounds: How to Eliminate Buzzing From Your Headphones</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshoot-and-repair-your-hyperx-cloud-alpha-s-mic-expert-tips/"><u>Troubleshoot and Repair Your HyperX Cloud Alpha S Mic - Expert Tips</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-guide-fixing-the-issue-with-overwatchs-push-to-talk-functionality/"><u>Troubleshooting Guide: Fixing the Issue with Overwatch's Push-to-Talk Functionality</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015559920-windows-10-audio-problems-quick-solutions-for-bringing-back-the-sound/"><u>Windows 10 Audio Problems: Quick Solutions for Bringing Back the Sound!</u></a></li>
</ul></div>
