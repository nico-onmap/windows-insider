---
title: What's new in the Windows 10 Insider Preview Builds (RS5)
description: How to get setup and perform first tasks for Windows Insider Program for Server Preview Builds
services: WIP-at-work
author: dawn.wood
manager: elizapo
ms.assetid: 
ms.service: WIP-at-work
ms.tgt_pltfrm: na
ms.devlang: na

ms.date: 04/10/2018
ms.author: dawn.wood
---

#  What's new in the Windows 10 Insider Preview Builds (RS5)
The [Windows Insider Program](https://insider.windows.com/en-us/) lets you preview builds of the upcoming release of Windows 10. This topic lists all new Windows 10 features for you to try. Unlike the [Windows Insider Program Blog](https://blogs.windows.com/windowsexperience/tag/windows-insider-program), this topic is organized by feature instead of by the build number. 

## Bluetooth battery percentage in Settings

In Bluetooth & other devices Settings, you can now check the battery level of your Bluetooth devices. For Bluetooth devices that support this feature, the battery percentage will update whenever your PC and the device are connected.

![alt text](images/bluetoothbattery.png "bluetooth battery")

## Cortana Show Me voice queries

 You can now launch the app through voice queries. Simply say to Cortana, “Show me how to change my background,” and you’ll get the previous help results, with a new “Let’s go” button below, which launches the guided help experience. Everything else is the same as last week – the app is available in English (US and Great Britain) and in German, and there are 15 settings guides. While most Insiders don’t need pointers like this, it’s for all the friends and family we have who need a pointer – please share it with them.

 You can download [Cortana Show Me](https://www.microsoft.com/en-us/store/r/cortana-follow-me/9pl1gmkcxm8c) from the Microsoft Store.

 Here are some voice queries to try:

* <b>Update Windows</b>– Try, “Update my Windows device”
* <b>Check if an app is installed</b> – Try, “How to see what apps are installed”
* <b>Uninstall an app</b> – Try “How to uninstall apps”
* <b>Change your desktop background</b>– Try, “Show me how to change my background”
* <b>Use Airplane Mode</b> – Try, “How do I turn on airplane mode”
* <b>Change your display brightness</b> – Try, “Show me how to change my screen brightness”
* <b>Add nearby printers or scanners</b> – Try, “How to add a printer”
* <b>Turn off Windows Defender Security Center</b> – Try, “Show me how to turn off Windows Defender Security Center”
* <b>Change Wi-Fi settings</b> – Try, “Show me how to change Wi-Fi network”
* <b>Change your power settings</b> – Try, “How to change when my computer goes to sleep”
* <b>Discover Bluetooth devices</b> – Try, “Show me how to discover devices”
* <b>Check your version of Windows</b> – Try, “How do I find my current version of Windows”

## External GPU Safe Remove Experience

<b>Safe remove experience for external GPUs</b> connected via Thunderbolt 3. The safe remove experience allows you to know which applications are running on an external GPU so that you can safely remove to prevent data loss during detach.

To safely remove an external graphics card, go to the “Safely Remove Hardware and Eject Media” icon and click to eject your GPU. If there are applications running on your external GPU, then a dialog will appear with the applications that are currently running. Close the applications to safely remove the device. If there are no applications currently running on your external graphics device then no dialog will appear and you can safely detach your external GPU.

## High Efficiency Image File Format (HEIF)

The <b>High Efficiency Image File Format (HEIF)</b> is supported in Windows 10 and the Photos app. [HEIF is an image container](https://en.wikipedia.org/wiki/High_Efficiency_Image_File_Format) that leverages modern codecs like HEVC to improve quality, compression, and capabilities compared to earlier formats like JPEG, GIF, and PNG. In addition to traditional single images, HEIF supports encoding image sequences, image collections, auxiliary images like alpha or depth maps, live images & video, audio, and HDR for greater contrast. We have heard your feedback that these features and the ability to share photos easily with other platforms is important to you. 

In order to try this out, you need to join the Windows App Preview Program for the Photos app and make sure you are running the March release of the Photos app (Version 2018.18022.13740.0 or newer). This version of the [Photos](https://www.microsoft.com/store/productId/9WZDNCRFJBH4) app has been updated to support viewing the primary image inside a HEIF file and to guide the install of dependencies like the HEIF and HEVC media extensions from the Microsoft Store. Once installed, these media extensions enable HEIF viewing in Photos as well as thumbnails and metadata in File Explorer.

Additionally, any application that uses [WIC](https://msdn.microsoft.com/en-us/library/windows/desktop/ee719654(v=vs.85).aspx), [WinRT Imaging APIs](https://docs.microsoft.com/en-us/uwp/api/windows.graphics.imaging), or the [XAML Image control](https://docs.microsoft.com/en-us/uwp/api/windows.ui.xaml.controls.image) can now add similar support for viewing single HEIF images.

[Click here](https://aka.ms/photosfb) to open Feedback Hub and send us feedback on the HEIF experience with the Photos app and Windows 10.

## Input 

<b>Emoji design updates</b> Based on your feedback and to improve consistency, we’ve made adjustments to the design of some of our emoji. Examples of updated emoji include:

<b>Before</b>

![alt text](images/before_emoji.png "emojis before")

<b>After</b>

![alt text](images/after_emoji.png "emojis after")

<b>Emoji search comes to more languages</b>: You can find an emoji by keyword in over 150 locales, including English (Great Britain), French (France), German (Germany), Spanish (Spain), and more. This will help you get the emoji you want easily and quickly. As a reminder, to bring up the Emoji Panel set focus to a text field and press WIN + (period) or WIN + (semicolon).

## Privacy settings layout in the set-up experience 

<b>Changes to the set up experience for privacy settings</b> This new design conveys focused information to help our customers make focused choices about their privacy and offers two new settings for Inking & Typing and Find my device.

## Search in Calendar

Now you can find past or future events by searching for the name, location, people included or words in the event body. Events that match your search will be clearly visible on your calendar, while those that don’t will be greyed-out so you can find what you need quickly.

![alt text](images/calendarwithsearch.png "productivity apps")

Search will work for Outlook, Hotmail, Live and Office 365 accounts. We do not yet support searching Exchange Server, Gmail, Yahoo or other IMAP calendars.

## Sets
Sets is designed to make sure that everything related to your task: relevant webpages, research documents, necessary files, and applications, is connected and available to you in one click. With Sets, 1st party experiences like Mail, Calendar, OneNote, MSN News, Windows, and Microsoft Edge become more integrated to create a seamless experience, so you can get back to what’s important and be productive, recapturing that moment, saving time – we believe that’s the true value of Sets. Here are some of the things you can do with sets.

<b>Drag and drop app tabs within and between Sets windows is now supported</b>: It works just like it sounds! You can now drag an app tab around within the Set or combine tabbed app windows into Sets.  

<i>Note: If you open a Microsoft Edge tab outside of a Set, you can’t drag and drop it into a Sets window. Drag and drop for Microsoft Edge web tabs within Sets isn’t supported yet and you may experience a crash if this is attempted.</i>  

<b>Tabs are now bubbled up in Alt + Tab</b>: Have Photos, Microsoft Edge, and OneNote tabbed together? You can now use Alt + Tab to switch between them. Prefer to only show the primary window in Alt + Tab? 

<i>Note: If you have multiple Microsoft Edge windows in a Set, only the one most recently accessed will be visible in Alt + Tab.</i>

<b>Support for desktop (Win32) apps.</b> Sets now supports File Explorer, Notepad, Command Prompt, and PowerShell. One of the top feature requests by Insiders has been tabs for File Explorer and with Sets you can get a tabbed File Explorer experience.

<b>Launch apps from the new tab page</b> by typing the app name into the search box.

<b>UWP apps are launched in the same window</b> replacing the new tab page.
The tab UI in Sets now shows icons including website favicons and app icons.
Resume your project with more control – When restoring your projects you’ll be prompted to restore related apps and webpages. In Timeline you’ll see when a project has multiple activities associated with it.

<b>Improved Settings for Sets</b>: We’ve updated the Settings for Sets via Settings > System > Multitasking. To start with, Sets now has its own section on this page, and is searchable (try typing “Sets” or “tabs” and it will appear in the dropdown). We’ve also added a setting to control the Alt + Tab behavior mentioned above.

![alt text](images/Win10Sets.png "Sets")

<b>File Explorer & Sets Improvements</b>: We’ve heard your feedback – you’d like it to be easier to get two File Explorer windows grouped together, and we’re working on it. To start with, you no longer need to hold CTRL on the new tab page to launch a File Explorer window in a tab (this was a temporary necessity with the last wave). We’ve also added a new keyboard shortcut to open a new tab when a File Explorer window is in focus: Ctrl + T. Remember, you can use Ctrl + N to open a new window, and Ctrl + W to close the window/tab.

<b>New UI for opening new tabs and windows</b> in the File Menu.

![alt text](images/tabsinfilewindow.png "tabs in file window")

<b>New UI</b> for easily opening new tabs and windows in the File Menu.

![alt text](images/tabsinfilewindow.png "tabs in file explorer")

<b>New context menu options for tabs in Sets</b>: If you right-click on a Sets tab, you’ll discover several options to leverage, including “close other tabs”, “move to new window”, and “close tabs to the right”.

![alt text](images/newcontextmenu.png "new context menu")

<b>Improvements to Previous Tabs</b>: We’ve done a few things to improve the experience in this space, including:

* <b>You can choose which Previous Tabs you want to restore</b>, in addition to being able to restore all tabs. 

* <b>You can now restore Previous Tabs from any type of activity</b> – in addition to restoring tabs when the primary window is a document.

![alt text](images/previoustabs.png "previous tabs")

* When you open a document that previously had tabs, a prompt will appear offering to restore those tabs, and the Previous Tabs button will be in the filled state. For things that aren’t documents, a prompt will not automatically appear, but you’ll know that there are tabs available to restore because the Previous Tabs button will be in the filled state.

* We added an animation to the experience when there are no Previous Tabs available to be restored.

<b>Keyboard shortcuts</b>

* <b>Ctrl + Win + Tab</b> – switch to next tab.
* <b>Ctrl + Win + Shift + Tab</b> – switch to previous tab.
* <b>Ctrl + Win + T </b>– open a new tab.
* <b>Ctrl + Win + N </b> - open a new window.
* <b>Ctrl + Win + W </b>– close current tab or window.

## Windows App Permissions 

You have more control so you can now decide which UWP apps can access your full file system. Particular UWP apps will be granted permission to have broad file system access. This capability will be granted on a per app basis by Microsoft. If a UWP app has the broad file system access restricted capability, you will receive a consent dialog prompting you to accept or deny the request. If at any time you change your mind about the decision, you can go to Settings > Privacy where you’ll find a new Settings page for File System Access. On this page, you can turn access on or off globally, and if it’s on you can also turn it on or off for each app that has requested the capability. UWPs with broad file system access will not appear in the Photos, Videos, or Documents privacy settings pages. If you grant broad file system access, this includes Photos, Videos and Documents.

## Windows Calculator 

Windows Calculator has been updated (version 10.1803.711.0) to now correctly calculate square roots for perfect squares (integers that are squares of other integers). Because of the [arbitrary precision arithmetic library](https://blogs.msdn.microsoft.com/oldnewthing/20160628-00/?p=93765) used by the Calculator app, the square root calculation is an approximation calculated using the [Exponential Identity](https://en.wikipedia.org/wiki/Methods_of_computing_square_roots%23Exponential_identity) function.
Previously, when you would calculate the square root of 4, the result would be 1.99999999999999999989317180305609 which would be rounded to 2 when displayed, because we calculated enough digits to do the rounding correctly. However, as soon as you subtract 2, you would see the remaining digits.
After this update, the square root calculation now recognizes perfect squares and correctly returns exactly 2 for the square root of 4.

## Windows Defender Application Guard (WDAG) Improvements

The Windows Defender Application Guard (WDAG) Team has introduced new improvements for users to have a better experience with our upcoming release. We have combed through our user feedback and acted to ensure your needs are met. On top of significant performance improvements, we have added an ability to download documents highlighted below.

<b>Performance improvements</b>: The teams at Microsoft are constantly working to improve performance for our users. Windows Defender Application Guard is no different. In this upcoming feature update, you will notice an improvement in the launch time for Application Guard. We have made the start process lighter and faster, which will provide our users with a better experience when accessing Microsoft Edge in Windows Defender Application Guard.

<b>Download files to the host</b>: One of the items our users voiced was an inability to “download files from within WDAG” to the host. This created an inconsistent experience for Edge overall as downloaded files were stuck inside the container. In this release, users can turn on a feature to download files from their WDAG browsing session onto the host file system. This feature is available in the Windows 10 Enterprise edition and must be turned on. Once the feature is enabled, users will be able to download files into a folder created in their Downloads folder and open all files on the host.

<i>How to enable and configure the Download to host feature</i>:

<b>Requirements:</b>
* Latest Windows 10 Enterprise RS4 Builds.
* Windows Defender Application Guard feature is installed.
* Network isolation policies are configured.

<b>Steps:</b>
1. Navigate to Local Group Policy Editor > Administrative Templates > Windows Components > Windows Defender Application Guard.

![alt text](images/wdag.png "App Guard")

2. Select Allow files to download and save to the host operating system from Windows Defender Application Guard
3. Select <b>Enabled</b> and <b>Apply<b/>

![alt text](images/enablewdag.png "Enable App Guard")

4. After this policy is enabled, you can download files from your Windows Defender Edge session to your Downloads folder. The files from Application Guard will be saved in a folder called “Untrusted files” nested inside the Downloads folder. This folder is created automatically when you first download a file from Application Guard after enabling the policy.

![alt text](images/untrustedfiles.png "untrusted files")

Notes:
* This feature is off by default.
* Users will need to assess the files they downloaded and assume any risks of opening on the host.
* We encourage you to try our download feature and assess our launch performance. Your feedback and suggestion are important to us as we continue to improve our products. You can click here to open Feedback Hub to give feedback on WDAG.
* We’ve also made updates to Windows Defender System Guard. With Windows Defender System Guard, we are making a leap forward in platform security with memory integrity by default and bringing a born secure device promise to our user base. To learn more about these changes and talk with product team, see their post in the Windows Insider Technical Community.

## Windows Defender Security Center gets a Fluent Design refresh
We’ve heard your feedback and we’ve updated Windows Defender Security Center (WDSC) to include the Fluent Design elements you know and love. You’ll also notice we’ve adjusted the spacing and padding around the app and will now dynamically size the categories on the main page if more room is needed for extra info. Last but not least, we’ve also updated the title bar of the app so that it will now use your accent color if you’ve enabled that option in Color Settings – with Sets enabled, you will see this color in the WDSC tab.

![alt text](images/defender.png "Windows Defender Security Center")

## Windows Defender Firewall now supports Windows Subsystem for Linux (WSL) processes 
You can add specific rules for a WSL process in Windows Defender Firewall, just as you would for any Windows process. Also, Windows Defender Firewall now supports notifications for WSL processes. For example, when a Linux tool wants to allow access to a port from the outside (like SSH or a web server like nginx), the Windows Defender Firewall will prompt to allow access just like it would for a Windows process when the port starts accepting connections. This was first introduced in [Build 17627](https://docs.microsoft.com/en-us/windows/wsl/release-notes#build-17618-skip-ahead).


## Windows 10 Pro for Workstations

<b>A new power scheme – Ultimate Performance</b>: Demanding workloads on workstations always desire more performance. As part of our effort to provide the absolute maximum performance we’re introducing a new power policy called Ultimate Performance. Windows has developed key areas where performance and efficiency tradeoffs are made in the OS. Over time, we’ve amassed a collection of settings which allow the OS to quickly tune the behavior based on user preference, policy, underlying hardware or workload.
This new policy builds on the current High-Performance policy, and it goes a step further to eliminate micro-latencies associated with fine grained power management techniques. The Ultimate Performance Power plan is selectable either by an OEM on new systems or selectable by a user. To do so, you can go to Control Panel and navigate to Power Options under Hardware and Sound (you can also “run” Powercfg.cpl). Just like other power policies in Windows, the contents of the Ultimate Performance policy can be customized.

![alt text](images/ultimate-power-scheme.png "Ultimate power scheme")

As the power scheme is geared towards reducing micro-latencies it may directly impact hardware; and consume more power than the default balanced plan. The Ultimate Performance power policy is currently not available on battery powered systems.

<b>Productivity focused out of box applications</b>: The out of box experience for Windows 10 Pro for Workstations display  productivity and enterprise focused applications in place of consumer applications and games. 

![alt text](images/productivity_apps.png "productivity apps")

