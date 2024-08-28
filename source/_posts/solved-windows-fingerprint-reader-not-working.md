---
title: "[SOLVED] Windows Fingerprint Reader Not Working"
date: 2024-08-27T21:01:29.931Z
updated: 2024-08-28T21:01:29.931Z
tags:
  - win11
  - win10
  - win7
categories:
  - ScannerIssues
description: This Article Describes [SOLVED] Windows Fingerprint Reader Not Working
excerpt: This Article Describes [SOLVED] Windows Fingerprint Reader Not Working
thumbnail: https://thmb.techidaily.com/c47546ef14b433a853f147293a1e027910647d2b3c636b3d7439e396fc35c411.jpg
---

## How to Fix HP Scanner Not Working - 2022 Tips

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1678201865.jpg)
3. Scroll down and double click**Windows Image Acquisition (WIA)** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd167eed749a.jpg)
4. In the popup pane, ensure the**Startup type** is set**Automatic** , and the**Service status** is**Running** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd168549db26.jpg)  
 If the**Service status** is already**Running** , click**Stop** to stop the service, then click**Start** to re-enable the service.
5. Click**Apply** and**OK** to save the changes.  
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
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
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
### Fix 4: Troubleshoot hardware problems

 It’s possible that there’s something wrong with your scanner, so run a troubleshooter in your computer to fix the issue.

1. Type**cmd** in the Windows Search bar and select**Run as administrator** .  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/10/cmd-run-as-admin.jpg)
2. Copy & paste the following command line into the Command Prompt window and press**Enter** .  
`**msdt.exe -id DeviceDiagnostic**`
3. Click**Next** in the popped-up window and the troubleshooter will start detecting hardware problems automatically.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/10/next-step.jpg)
4. Follow the on-screen instructions to finish the troubleshooting and fix the detected issue.

 After that, try your scanner again and see if it’s working properly.

---

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-key-strategies-for-navigating-complex-youtube-discussions/"><u>[New] 2024 Approved  Key Strategies for Navigating Complex YouTube Discussions</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-essential-guide-to-iphone-voice-recording-techniques/"><u>[New] Essential Guide to iPhone Voice Recording Techniques</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-fostering-fast-visual-storytelling-with-google-imagery/"><u>[New] Fostering Fast Visual Storytelling with Google Imagery</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-the-complete-checklist-for-remotely-podcasters-delight/"><u>[New] The Complete Checklist for Remotely Podcaster's Delight</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-enhancing-video-content-step-by-step-cropping-and-export-guide/"><u>2024 Approved  Enhancing Video Content  Step-by-Step Cropping & Export Guide</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-streamline-multimedia-with-pip-in-apple-browsers/"><u>2024 Approved  Streamline Multimedia with PIP in Apple Browsers</u></a></li>
<li><a href="https://techtrends.techidaily.com/apples-revolutionary-foldable-iphone-explore-release-schedules-pricing-forecasts-and-leaked-specifications/"><u>Apple's Revolutionary Foldable iPhone? Explore Release Schedules, Pricing Forecasts, and Leaked Specifications.</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-from-apple-iphone-14-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code From Apple iPhone 14</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-on-your-phone-discover-five-key-reasons-not-to-install-the-app-just-yet/"><u>ChatGPT on Your Phone: Discover Five Key Reasons Not to Install the App Just Yet</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723014828616-clear-audio-happy-ears-troubleshoot-your-crackling-headphones-with-these-quick-fixes/"><u>Clear Audio, Happy Ears: Troubleshoot Your Crackling Headphones with These Quick Fixes!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/csgo-voice-chat-problems-discover-how-to-fix-your-in-game-mic/"><u>CS:GO Voice Chat Problems? Discover How to Fix Your In-Game Mic</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/tial-insights-for-integrating-hashtags-into-game-focused-yt-content-for-2024/"><u>Essential Insights for Integrating Hashtags Into Game-Focused YT Content for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/expert-tips-on-fixing-unresponsive-computer-speaker-issues-effectively/"><u>Expert Tips on Fixing Unresponsive Computer Speaker Issues Effectively</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/facebooks-most-impressive-new-additions-decoded/"><u>Facebook's Most Impressive New Additions Decoded</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015457968-fixing-microphone-issues-in-microsoft-teams-solutions-for-windows-11-and-10-users/"><u>Fixing Microphone Issues in Microsoft Teams: Solutions for Windows 11 and 10 Users</u></a></li>
<li><a href="https://sound-issues.techidaily.com/get-your-rec-room-microphone-back-on-track-for-pc-in-202n4-expert-solutions-unveiled/"><u>Get Your Rec Room Microphone Back on Track for PC in 202N4 - Expert Solutions Unveiled</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-fix-your-fortnite-microphone-problems-a-comprehensive-guide/"><u>How to Fix Your Fortnite Microphone Problems - A Comprehensive Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-repair-in-game-voice-chat-in-wow-complete-troubleshooter-tips/"><u>How to Repair In-Game Voice Chat in WoW – Complete Troubleshooter Tips</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-vivo-v29e-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Vivo V29e to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-nokia-130-music-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Nokia 130 Music to Roku | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-asus-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Asus FRP Without Computer</u></a></li>
<li><a href="https://sound-issues.techidaily.com/laptop-headphone-connection-woes-here-are-five-steps-to-restore-functionality/"><u>Laptop Headphone Connection Woes? Here Are Five Steps to Restore Functionality!</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-quieting-the-gusts-innovative-approaches-for-wind-noise-reduction-in-acoustic-files/"><u>New In 2024, Quieting the Gusts Innovative Approaches for Wind Noise Reduction in Acoustic Files</u></a></li>
<li><a href="https://sound-issues.techidaily.com/onikuma-headset-mic-problems-heres-how-you-can-fix-them/"><u>Onikuma Headset Mic Problems? Here's How You Can Fix Them</u></a></li>
<li><a href="https://sound-issues.techidaily.com/overcome-audio-glitches-ensuring-your-mic-works-with-counter-strike-2/"><u>Overcome Audio Glitches: Ensuring Your Mic Works with Counter-Strike 2</u></a></li>
<li><a href="https://sound-issues.techidaily.com/quick-solutions-how-to-eliminate-unwanted-humming-from-your-speakers/"><u>Quick Solutions: How to Eliminate Unwanted Humming From Your Speakers</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolving-mpow-microphone-failure-in-windows-environments/"><u>Resolving MPOW Microphone Failure in Windows Environments</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolving-the-issue-of-inactive-pclaptop-speakers-a-step-by-step-guide/"><u>Resolving the Issue of Inactive PC/Laptop Speakers: A Step-by-Step Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/silencing-intermittent-audio-in-bluetooth-devices-on-windows-10-and-11-pcs/"><u>Silencing Intermittent Audio in Bluetooth Devices on Windows 10 and 11 PCs</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solve-silent-pc-woes-effective-remedies-for-no-sound-and-audio-glitches-on-computers/"><u>Solve Silent PC Woes: Effective Remedies for No Sound and Audio Glitches on Computers</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-windows-7s-hdmi-sound-failure-quick-and-easy-repair-tips/"><u>Solving Windows 7'S HDMI Sound Failure - Quick and Easy Repair Tips</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-tutorial-to-get-your-windows-11-bluetooth-working-again/"><u>Step-by-Step Tutorial to Get Your Windows 11 Bluetooth Working Again</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-tutorial-how-to-set-up-the-idt-hd-audio-drivers-for-windows-10/"><u>Step-by-Step Tutorial: How to Set Up the IDT HD Audio Drivers for Windows 10</u></a></li>
<li><a href="https://sound-issues.techidaily.com/supercharge-speaker-settings-how-to-upscale-the-volume-on-windows-10/"><u>Supercharge Speaker Settings: How to Upscale the Volume on Windows 10</u></a></li>
<li><a href="https://data-wizards.techidaily.com/tips-for-smoother-video-performance-avoiding-skips-and-hiccups/"><u>Tips for Smoother Video Performance: Avoiding Skips and Hiccups</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-audio-issues-unplugging-headphones-or-speakers-in-windows/"><u>Troubleshooting Audio Issues: Unplugging Headphones or Speakers in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-device-control-for-sleep-state-wakefulness/"><u>Unlocking Device Control for Sleep State Wakefulness</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unveiling-smartwatch-capabilities-everything-you-need-to-know/"><u>Unveiling Smartwatch Capabilities – Everything You Need to Know!</u></a></li>
<li><a href="https://fox-that.techidaily.com/update-issues-for-iphones-and-ipads-discover-9-effective-workarounds/"><u>Update Issues for iPhones and iPads: Discover 9 Effective Workarounds</u></a></li>
<li><a href="https://sound-issues.techidaily.com/win7-hdmi-sounds-not-playing-heres-how-to-get-it-working-again/"><u>Win7 HDMI Sounds Not Playing? Here's How to Get It Working Again!</u></a></li>
</ul></div>
