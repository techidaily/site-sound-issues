---
title: "[FIXED] Non-Operational Epson Printer in Windows 11 Environment"
date: 2024-08-18T08:08:25.957Z
updated: 2024-08-19T08:08:25.957Z
tags:
  - win11
  - win10
  - win7
categories:
  - ScannerIssues
description: This Article Describes [FIXED] Non-Operational Epson Printer in Windows 11 Environment
excerpt: This Article Describes [FIXED] Non-Operational Epson Printer in Windows 11 Environment
thumbnail: https://thmb.techidaily.com/0fde8be80e602ff65625842ff908df27188b320349e0a53c08ea2eca9a5b67ed.jpg
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
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
### Fix 1: Check the connection issue

 To use your scanner, you need to make sure that your scanner is**powered on** in the first place.

 Then you should check the**connection** **issue** . If you’re using a USB scanner, check the**USB ports** and**USB cables** to ensure it works properly. While you’re using a network scanner, ensure your computer has a good**Internet** **connection** , and your scanner connects to your computer under the Internet. In addition, if you’re using **[VPN](https://tools.techidaily.com/drivereasy/download/)**  on your computer, try**disconnecting VPN** from your computer and scanning again.

 If you’ve checked the above steps and your HP scanner still doesn’t work, don’t worry. There is something else to try.

---

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Click**Apply** and**OK** to save the changes.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd1688e0055e.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
 Or click**Update All** to automatically download and install all problem drivers in your system (this requires the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click**Update All** ).  

![](https://images.drivereasy.com/wp-content/uploads/2023/03/update-dell-touchpad-driver.jpg.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After that, try your scanner again and see if it’s working properly.

---

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://sound-issues.techidaily.com/fixed-redragon-headset-mic-not-working-on-pc/"><u>[Fixed] Redragon Headset Mic Not Working on PC</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-cutting-edge-tactics-for-sharing-video-content-from-twitter-and-whatsapp/"><u>[Updated] 2024 Approved  Cutting-Edge Tactics for Sharing Video Content From Twitter and WhatsApp</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-digital-dexterity-fine-tuning-funny-videos-for-facebook-and-insta-laughs/"><u>[Updated] 2024 Approved  Digital Dexterity  Fine-Tuning Funny Videos for Facebook and Insta Laughs</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-discovering-the-leading-speech-to-text-apps-for-ipads-3/"><u>[Updated] 2024 Approved  Discovering the Leading Speech-to-Text Apps for iPads #3</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-your-journey-to-curating-an-impressive-youtube-collection-for-2024/"><u>[Updated] Your Journey to Curating an Impressive YouTube Collection for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-box-it-up-right-10-online-haunts-for-tailored-gift-boxes/"><u>2024 Approved  Box It Up Right  10 Online Haunts for Tailored Gift Boxes</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-groundbreaking-photo-editor-photonshift-tech/"><u>2024 Approved  Groundbreaking Photo Editor  PhotonShift Tech</u></a></li>
<li><a href="https://facebook.techidaily.com/breakthrough-findings-from-whistleblowers-fb-data/"><u>Breakthrough Findings From Whistleblower's FB Data</u></a></li>
<li><a href="https://sound-issues.techidaily.com/bypass-the-hurdle-fix-microphone-problems-in-airpods-when-using-windows-11/"><u>Bypass the Hurdle: Fix Microphone Problems in AirPods When Using Windows 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/cod-vanguard-voice-communication-problems-resolved-a-comprehensive-guide/"><u>Cod: Vanguard Voice Communication Problems Resolved - A Comprehensive Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/common-fixes-for-voice-chat-not-working-on-back-4-blood-server/"><u>Common Fixes for Voice Chat Not Working on Back 4 Blood Server</u></a></li>
<li><a href="https://sound-issues.techidaily.com/comprehensive-fixes-to-restore-audio-on-your-window-7-device/"><u>Comprehensive Fixes to Restore Audio on Your Window 7 Device</u></a></li>
<li><a href="https://games-able.techidaily.com/decoding-and-resolving-gpu-distortion/"><u>Decoding and Resolving GPU Distortion</u></a></li>
<li><a href="https://sound-issues.techidaily.com/epson-printer-error-windows-11-workaround-and-solution/"><u>Epson Printer Error: Windows 11 Workaround and Solution</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-dolby-atmos-errors-on-windows-11-how-to-restart-dolby-sound-drivers/"><u>Fixing Dolby Atmos Errors on Windows 11 - How to Restart Dolby Sound Drivers</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-samsung-galaxy-s23-fe-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Samsung Galaxy S23 FE for Free? | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/hp-notebook-volume-issues-solutions-within-windows-11-ecosystem/"><u>HP Notebook Volume Issues: Solutions Within Windows 11 Ecosystem</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-xiaomi-redmi-note-12-pro-5g-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Xiaomi Redmi Note 12 Pro 5G FRP Locks</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-organize-your-fb-content-access-to-free-downloaders-online/"><u>In 2024, Organize Your FB Content  Access to Free Downloaders Online</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016757723-mac-no-volume-heres-how-you-can-get-the-sound-back/"><u>Mac No Volume? Here's How You Can Get the Sound Back</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016600424-optimizing-loudspeaker-performance-in-windows-pertinent-solutions-for-fixing-low-sound-output/"><u>Optimizing Loudspeaker Performance in Windows Pertinent Solutions for Fixing Low Sound Output.</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/pinterest-pin-square-advice-for-2024/"><u>Pinterest Pin Square Advice for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/quick-fixes-for-why-is-my-zte-axon-40-lite-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My ZTE Axon 40 Lite Black and White | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/realtek-hd-speaker-drivers-wont-open-here-are-the-solutions/"><u>RealTek HD Speaker Drivers Won't Open? Here Are the Solutions</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolving-earpods-microphone-issues-in-astro-a50-headsets-with-ease/"><u>Resolving EarPods Microphone Issues in Astro A50 Headsets with Ease</u></a></li>
<li><a href="https://howto.techidaily.com/solved-warning-camera-failed-on-infinix-smart-8-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Solved Warning Camera Failed on Infinix Smart 8 | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solved-common-issues-and-fixes-for-the-logitech-g533-usb-mic/"><u>Solved! Common Issues and Fixes for the Logitech G533 USB Mic</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-the-problem-when-discord-voice-communication-is-not-working/"><u>Solving the Problem When Discord Voice Communication Is Not Working</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-the-turtle-beach-headset-microphone-malfunction-step-by-step-solutions/"><u>Solving the Turtle Beach Headset Microphone Malfunction: Step by Step Solutions</u></a></li>
<li><a href="https://sound-issues.techidaily.com/the-complete-fix-for-astro-a1e-wireless-mouse-and-usb-adapter-mic-problems/"><u>The Complete Fix for Astro A1e Wireless Mouse & USB Adapter Mic Problems</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshoot-your-quiet-bluetooth-connection-easy-fixes-for-no-sound-issues/"><u>Troubleshoot Your Quiet Bluetooth Connection - Easy Fixes for No Sound Issues</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-tips-for-razer-man-o-war-mic-issues-and-solutions/"><u>Troubleshooting Tips for Razer Man O' War Mic Issues and Solutions</u></a></li>
<li><a href="https://sound-issues.techidaily.com/ultimate-solutions-for-high-performance-audio-settings-in-windows-11/"><u>Ultimate Solutions for High-Performance Audio Settings in Windows 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlocking-apple-iphone-14-plus-lock-screen-3-foolproof-methods-that-actually-work-drfone-by-drfone-ios/"><u>Unlocking Apple iPhone 14 Plus Lock Screen 3 Foolproof Methods that Actually Work | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/unparalleled-8-webcams-elevate-your-livestream-experience-for-2024/"><u>Unparalleled 8 Webcams Elevate Your Livestream Experience for 2024</u></a></li>
</ul></div>
