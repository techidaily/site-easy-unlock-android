---
title: In 2024, How to Show Wi-Fi Password on Poco X5
date: 2024-04-03 16:54:18
updated: 2024-04-05 10:34:23
tags: 
  - unlock
  - remove screen lock
categories:
  - android
description: This article describes How to Show Wi-Fi Password on Poco X5
excerpt: This article describes How to Show Wi-Fi Password on Poco X5
keywords: Poco X5 find lost phone with google map,unlock android phone password without factory reset,android device password reset,Poco X5 lock screen apps for android,Poco X5 how to use oem unlocking,how to change lock screen password,Poco X5 how to reset a phone that is locked,unlock android device phone password without factory reset,bypass android lock screen using emergency call,android device lock screen settings,Poco X5 delete gmail account with without password,android device screen lock
thumbnail: https://www.lifewire.com/thmb/sujrBq1SN6zkmNgqHTSAbFbTvKk=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/18-Hidden-Snapchat-Features-efa75dca521e4cf6bb321dc960276deb.jpg
---

## How to Show Wi-Fi Password on Poco X5

Since the invention of Android OS in 2008 by Andy Rubin, our world has faced a dramatic change. Android seems to be controlling a considerably high portion of our life. We have bought many gadgets that use this amazing OS and most of which are phones. But how much can you do with your Android phone? Developers are always making it more interesting to use this interface.

Most of the time, we use Android phones, we get faced with the need to access the internet. The Wi-Fi capability of these Android gadgets makes it super easy for us to surf the web. Throughout using Wi-Fi, we connect to a number of them. This could be at school, a sub-way café, the gym, buses, hospitals, hotels, towns, and the list is endless. A password secures most of this. Needless to say, our brain is weak to store all these passwords for future use, especially if you would want to connect with a different gadget you have recently bought or even your laptop. In this article, we will introduce you to how to find wifi password on rooted and also unrooted Android devices.

<iframe allowfullscreen="allowfullscreen" frameborder="0" src="https://www.youtube.com/embed/78mNMIr_wpI"></iframe>

## Part 1: Show Wifi Password on Rooted Android Device

### What is Rooting?

First of all, what does rooting mean? You have probably used a Windows computer or even Linux. For the case of Windows, when installing a new program or software, it always prompts a dialog box saying, "Administrator permission required to run this program." If you don't have the administrator permission, you won't install the program. In Android, this is called rooting. In simple terms, it means having the root permission to your phone. Some Android apps will require you the root permission, e.g., flashing your ROM. In this part, we will explain how you can show the Wi-Fi password on your Android with root.

To find the Wi-Fi passwords on your Android phone, you need to have an app to explore files which also supports a root user. In this case, ES FileExplorer or Root Explorer will come in handy. However, it turns out that the latter is offered at $3. Let's use the free ES File Explorer.

![android show wifi password](https://images.wondershare.com/drfone/others/14556285763404.jpg)

### Steps of getting Wi-Fi password on Android with root

In only four steps, we, at this moment, learn how we can find the password of a Wi-Fi on an Android phone.

Step 1: Install the ES File Explorer

Download the ES File Explorer from your play store, install it, and open it.

![android show wifi password](https://images.wondershare.com/drfone/others/14556286507084.jpg)

Step 2: Enable Root Explorer

The root explorer needs to be enabled so that you can reach the root folders of the Wi-Fi passwords you need. By default, the root feature in this ES explorer is not enabled. To enable it, just tap on the list menu on the top left corner.:

![android show wifi password](https://images.wondershare.com/drfone/others/14556292611536.jpg)

This will drop down a list of controls. Scroll down and find the **Root Explorer** option and enable it.

![android show wifi password](https://images.wondershare.com/drfone/others/14556293052566.jpg)

Step 3: Get the passwords' file.

Go back to ES file explorer, and this time, find the folder named **data**.

![android show wifi password](https://images.wondershare.com/drfone/others/14556293412707.jpg)

When this folder opens, find another one named **misc**. Open it and find another one named **wifi**. Here, find a file named **wpa\_supplicant.conf**.

![android show wifi password](https://images.wondershare.com/drfone/others/14556293762552.jpg)

Step 4: Retrieve the wifi password on Android

Make sure that you don't edit anything in the file. You might mess up with important data and fail to access the Wi-Fi(s) in the future.

![android show wifi password](https://images.wondershare.com/drfone/others/14556294042257.jpg)

As you can see above, we have found the Wi-Fi passwords on the android device. On each network profile, we have the name of the network represented by _name (ssid="{the name}")_, the network's password represented by _psk_, the network's access point represented by _key\_mgmt=WPA-PSK_ and its priority represented by _priority_.

## Part 2: Show Wifi Password on Android without Root

What if I don't have root access to my Android, can I still see Android Wi-Fi password? The short answer is yes. However, this is a bit involving but simple. You don't need to be a computer guru to do it, but you need to have a computer and some internet access of course. The key thing is to find a way through which we can fetch the password file from the phone without using a root access protocol in the Android. This is made possible by some little programming insight using the Windows Command prompt.

### Steps to show Wi-Fi password on Android without root

Step 1: Access the Developer authority

To access the files that Android uses to run passwords, you must first become a developer. This is very simple.

Get your Android phone and go to settings. Scroll down and find "About phone." Tap on it and scroll down again to find Build number.

![android show wifi password](https://images.wondershare.com/drfone/others/14556302638925.jpg)

Tap on this "build number" 5 to 6 times until a message pops up, saying, "You are now a developer".

![android show wifi password](https://images.wondershare.com/drfone/others/14556303263992.jpg)

Step 2: Enable the debugging.

Go back to Settings. Scroll down for developer options. Turn on the button for "Android/USB debugging".

![android show wifi password](https://images.wondershare.com/drfone/others/14556308665697.jpg)

Step 3: Install ADB drivers.

Now, open your Windows desktop. Download and install ADB drivers. (Use this download link [adbdriver.com](http://adbdriver.com/)). You need to download and install platform tools (minimal ADB and fastboot) from [http://forum.xda-developers.com/...](http://forum.xda-developers.com/showthread.php?t=2317790) Now open the folder where you've installed the above tools. By default, it is in the Local disc _C\\windows\\system32\\platform\_tools_ location. However, you might want to locate them by searching on the windows search engine. You have to hold the Shift key and right-click inside the folder to click on"Open Command Window Here."

![android show wifi password](https://images.wondershare.com/drfone/others/14556329561742.jpg)

Step 4: Test the ADB

Here, we would like to test whether the ABD is working properly. To do this, connect your phone to the PC using a USB. In the command prompt, type **adb services** and then press enter. If it's working properly, you should see a device on this list.

![android show wifi password](https://images.wondershare.com/drfone/others/14556329984622.jpg)

Step 5: Find the Android wifi password.

Now, it is time to type the given command in the command prompt and type: _adb pull /data/misc/wifi/wpa\_supplicant.conf c:/wpa\_supplicant.conf_. This will fetch the file from your phone to the local disc C drive of the PC.

Step 6: Get the wifi passwords.

Lastly, open the file with a notepad, and there you go.

![android show wifi password](https://images.wondershare.com/drfone/others/14556331232772.jpg)

Now you learned how to show the wifi password on your Android device.

## How to Unlock Poco X5 Phone without Google Account?

Uh oh – you’ve forgotten your Android Unlock code, and you can’t get it online to unlock using Google. Nothing could be more frustrating than gazing at your phone, knowing that it is essentially a paperweight at this point. Unless you can get it unlocked, your phone is useless, and all of your important photos, text messages, and content are all locked out of your reach. While right now, nothing can do without a Google account. But you can try to reset your Google account first.

## Part 1: How to Bypass Lock Screen on Android device with Google Account (Android Device Manager)

Even if you have a Google account, if your phone isn’t connected to the internet, you cannot access it to unlock your phone. If this sounds familiar, you can always try this method.

1\. First, navigate to the Android Device Manager page. You will need to sign in with the Google account that you use to set up your phone.

Android Device Manager link: <http://www.google.com/android/devicemanager>

![android Device Manager log in](https://images.wondershare.com/drfone/others/14637942446007.jpg)

2\. Once you have logged in, you will automatically be redirected to the Android Device Manager page. If this is your first time, click the “Accept” button.

![android Device Manager start](https://images.wondershare.com/drfone/others/14637942473262.jpg)

3\. A list of all of the Poco X5 devices registered to this Android account will pop up. Select the Poco X5 device in question from this list.

![android Device Manager list of devices](https://images.wondershare.com/drfone/others/14637942503282.jpg)

4\. The Android Device Manager will then locate your device. Make sure it is turned on!

![android Device Manager locating device](https://images.wondershare.com/drfone/others/14637942532352.jpg)

5\. After it has been located, you will have a few options for what to do next. If you do not know your phone's location, you can call it from this screen, but if you know where it is, click the ‘Enable Lock & Erase’ option.

![android Device Manager device located](https://images.wondershare.com/drfone/others/14637942568385.jpg)

6\. A notification will pop up on your device; confirm it.

![android Device Manager Erase & Lock](https://images.wondershare.com/drfone/others/14637942582896.jpg)

7\. At this point, you will be asked to create a new lock screen password. Once you have chosen one, press “Lock.”

![android Device Manager New Lock Screen](https://images.wondershare.com/drfone/others/14637943377629.jpg)

8\. Now, simply enter the new passcode on your device, and voila! It will open, and you can get back to your daily routine.

## Part 2: How to Reset Your Google Account on your Android Phone

If you have forgotten your Google Account password, it is still possible to unlock your account and access the information within. Here is how you can unlock your Google account on your Android phone.

1\. On your browser, go to the Google home page and try to sign in. You will fail, but that is good! It will lead you to the next step.

![android Google web page](https://images.wondershare.com/drfone/others/14637535742329.jpg)

2\. Since you cannot sign in on the sign-in page, you can now select the ‘Help’ link.

![android Goodle log in](https://images.wondershare.com/drfone/others/14637535763672.jpg)

3\. Choose the “forgot password” option. You will be prompted to enter your email address to proceed.

![android Google trouble signing in](https://images.wondershare.com/drfone/others/14637535788151.jpg)

4\. Two options will then appear: the first is your phone number, and the other asks you for your backup email.

![android Google forgot password](https://images.wondershare.com/drfone/others/14637535828239.jpg)![android Google forgot pssword enter email](https://images.wondershare.com/drfone/others/14637535857339.jpg)

5\. Enter either one of these options, and you will receive a verification code via email, SMS, or a telephone call from an operator. If you have chosen to enter your backup email, at this point, you will receive detailed instructions on how to access the ‘reset password’ page.

![android Google automated call verification](https://images.wondershare.com/drfone/others/14637561923476.jpg)![android Google automated call verification](https://images.wondershare.com/drfone/others/14637561995841.jpg)

6\. Once you have been redirected to the ‘reset password’ page, you can input your new login information.

![android Google reset link](https://images.wondershare.com/drfone/others/14637552475841.jpg)

7\. Finally, you can unlock your Google account on your Android! Confirm this by clicking the “Change Password” button. Success!

![android Google reset password input new password](https://images.wondershare.com/drfone/others/14637552534874.jpg)

## Part 3. How to Remove Locked Screen on Android using Dr.Fone

It supports removing screen lock from mainstream models, such as Samsung, LG, Lenovo, Xiaomi, etc. For some older version Samsung models, you can remove the lock without data loss. It will erase data after unlocking for other models.



### [Dr.Fone - Android Lock Screen Removal](https://tools.techidaily.com/wondershare-dr-fone-unlock-android-screen/)

Remove Android Screen Lock In One Click

- Pattern, PIN, password, fingerprints & face screen lock can all be unlocked.
- Bypass Android FRP lock without a PIN or Google account.
- No tech knowledge asked. Everybody can handle it.
- It will complete the unlocking process in minutes.

**3,981,454** people have downloaded it

### How to use Dr.Fone to unlock

**Step 1:** Install Dr.Fone toolkit and select Screen Unlock > Android > Unlock Android Screen.

![Reset your Android Lock Screen Password](https://images.wondershare.com/drfone/guide/android-screen-unlock-3.png)

Now connect your Android phone connected with the PC, and select the Poco X5 device brand from the list.

![Reset your Android Lock Screen Password](https://images.wondershare.com/drfone/guide/screen-unlock-any-android-device-2.png)

**Step 2:** Follow the on-screen instructions to put your Android device into the specific mode. Once the download is complete, Dr.Fone will start the unlocking process.

![Reset your Android Lock Screen Password](https://images.wondershare.com/drfone/guide/unlock-android-screen-google.png)

**Step 3:** After the process is complete, your Android device should be unlocked, and you can access it without the screen lock.

![Reset your Android Lock Screen Password](https://images.wondershare.com/drfone/guide/screen-unlock-any-android-device-6.png)

## Conclusion

We know that losing or forgetting your Android lock code can be a real pain, and so these solutions are sure to put the smile back on your face and get you using your phone again as usual. As you can see, the [Dr.Fone - Screen Unlock (Android)](https://tools.techidaily.com/wondershare-dr-fone-unlock-android-screen/) is a simple and reliable way to unlock your Android phone, but you can always try the Google option if you assess that it better suits your needs. No matter which solution you choose, your locked Android phone will be up and running again in no time at all.



## Unlocking the Power of Smart Lock: A Beginner's Guide for Poco X5 Users

Google constantly comes up with features to simplify the way users interact and complete tasks on the Android platform. One of the most important features that techies loved to debate about was the Smart Lock Android, a secure password manager functioning in sync with a Google account on the Android phone.

## Part 1: What is Android Smart Lock?

![smart lock android](https://images.wondershare.com/drfone/others/14555162221345.jpg)

Android Lollipop added a feature called Smart Lock, and the feature was devised as a smart tool to prevent the Android phone from locking once it was initially unlocked. In other words, the feature overrides an Android phone's Lock Screen feature, thereby saving users the need to enter passwords every time the Poco X5 device locks.

If you're at home, it's likely your android phone is locked out if you haven't accessed at for some time. Smart Locks solves the problem in many ways. It allows you to allocate trusted places. Once you within range of the trusted places, your phone won't lock. Trusted devices come next. Smart Lock is assigned to Bluetooth and Android NFC unlock devices.

![smart lock android](https://images.wondershare.com/drfone/others/14555162911081.jpg)

![smart lock android](https://images.wondershare.com/drfone/others/14555165271526.jpg)

Finally, trusted face unlocking is the ultimate face recognition system that unlocks your Android device as soon as you look at it across the front-facing camera. A face unlock first introduced with Android Jelly Bean and has been significantly improved in later versions.

_Turning On Smart Lock_

The feature is enabled by first accessing settings. For example, in a Samsung Galaxy S6:

Tap on Settings, which is the gear symbol.

![smart lock android](https://images.wondershare.com/drfone/others/14555171833750.jpg)

- • Click on Personal and tap on Security.
- • Go to Advanced and tap on Trust agents and make sure Smart Lock is turned on.

![smart lock android](https://images.wondershare.com/drfone/others/14555174399892.jpg)

- • Under Screen Security tap Smart Lock.
- • Here, you need to enter your Screen Lock. If you haven't done so, set up a password and PIN by following the on-screen prompts. The screen Lock is needed every time you have to change the Smart Lock settings.

![smart lock android](https://images.wondershare.com/drfone/others/14555175242280.jpg)

Within Smart Lock, there are three options for setting the system. You can set up trusted devices, trusted face, and trusted places individually, combining two or all three at the same time. You can choose just one trusted face, but you have the option to set up as many trusted devices and trusted places as needed.

![smart lock android](https://images.wondershare.com/drfone/others/14555176091774.jpg)

## Part 2: Turn On Smart Lock For Android with Trusted Devices

You can decide on a trusted device to be paired with Smart Lock Android.

![smart lock android](https://images.wondershare.com/drfone/others/14555177245258.jpg)

For example, you can set up a Smart Lock for Bluetooth in your Android Bluetooth settings. It can also be done for Android NFC unlock devices. Examples include the Bluetooth system in your car, NFC unlocks, android sticker on the car's phone dock, or Bluetooth in your watch.

- • Go to Settings.
- • Tap on Security and then Smart Lock.
- • Existing paired options are listed under Trusted Devices.
- • Initially, trusted devices will show None.

![smart lock android](https://images.wondershare.com/drfone/others/14555179612746.jpg)

Tap on Add Trusted Devices.

![smart lock android](https://images.wondershare.com/drfone/others/14555180455802.jpg)

The next screen is the Choose Device Type.

![smart lock android](https://images.wondershare.com/drfone/others/14555181196889.jpg)

Since you have already paired Bluetooth, it will ask you to choose the Poco X5 device from the list.

![smart lock android](https://images.wondershare.com/drfone/others/14555182031784.jpg)

- • As an example, let's take the case of LG HBS800. It may show Not connected until you add it.
- • It will show up under Trusted devices in the Smart Lock menu.
- • When you turn the added device on, Smart Lock now unlocks the Android mobile.

![smart lock android](https://images.wondershare.com/drfone/others/14555183103300.jpg)

Similarly, other Bluetooth and NFC unlock android supported gadgets can be added under the list of Trusted Devices.

## Part 3: Turn On Smart Lock For Android With Trusted Locations

You can also add locations or addresses to Smart Lock Trusted Locations, and the phone unlocks automatically as soon as you arrive at the desired location. For example, you can set up your home or work address under Trusted Locations.

Check current settings first.

![smart lock android](https://images.wondershare.com/drfone/others/14555198742115.jpg)

On a new Android phone, visit Settings>Personal.

![smart lock android](https://images.wondershare.com/drfone/others/14555199012102.jpg)

Then Lock Screen and Security.

![smart lock android](https://images.wondershare.com/drfone/others/14555199294567.jpg)

Then Secure Lock Settings.

![smart lock android](https://images.wondershare.com/drfone/others/14555200321422.jpg)

Tap Smart Lock.

![smart lock android](https://images.wondershare.com/drfone/others/14555200954549.jpg)

Tap on Trusted Places.

![smart lock android](https://images.wondershare.com/drfone/others/14555201755742.jpg)

Tap on Add Trusted Places

![smart lock android](https://images.wondershare.com/drfone/others/14555202394199.jpg)

- • Initiate the Google Maps app on the Android phone. Make sure the Internet and GPS are on.
- • Pick a place.

![smart lock android](https://images.wondershare.com/drfone/others/14555203265722.jpg)

- • Click on Settings.
- • Click on Edit home or work. You can now add or edit the required addresses.
- • As an example, click on the Enter work address.
- • You now have the option to type in the address or use the address listed on Google Maps as the required work address.

![smart lock android](https://images.wondershare.com/drfone/others/14555204276666.jpg)

- • A successful addition is listed and can be edited under the Edit work address.
- • Close the Google Maps app.
- • The work address is automatically propagated and configured with Smart Lock settings.
- • Go back to Settings> Security> Smart Lock> Trusted Places.
- • The work address you added is now listed under Work.

![smart lock android](https://images.wondershare.com/drfone/others/14555205535430.jpg)

- • However, it is not yet configured as a Smart Lock option. Tap the location once, and it is enabled.
- • The switch along the address to the right turns blue, indicating it is enabled.
- • The work address is now listed under Trusted places for Work.

![smart lock android](https://images.wondershare.com/drfone/others/14555206499484.jpg)

- • The phone is now configured for the work address and will unlock whenever you are at the location.
- • Since it works on Google Maps, the feature works through an Internet connection.

## Part 4: Turn On Smart Lock For Android With Trusted Face

![smart lock android](https://images.wondershare.com/drfone/others/14555207782388.jpg)

The feature recognizes your face and then unlocks the Poco X5 device. Once you set up the Poco X5 device to recognize your face as a trusted face, it will unlock the Poco X5 device as soon as it recognizes you.

![smart lock android](https://images.wondershare.com/drfone/others/14555208588486.jpg)

PRECAUTION:  At best, this can be the first level of security, as one who resembles you to some extent can unlock the Poco X5 device. Photographs are not stored in the system. The device does hold necessary data to recognize your face, and the security level is determined by how good the Poco X5 device is configured. The data is not accessed by any app or loaded onto a Google server for backup.

_Setting Up Trusted Face_

- • Go to Smart Lock and tap Trusted Face.
- • Tap on Setup. Follow on-screen instructions.

![smart lock android](https://images.wondershare.com/drfone/others/14555210728317.jpg)

The device begins to gather data about your face. The trusted face icon appears. As a backup, in case Smart Lock does not recognize your face, use the manual system by applying the PIN or password to unlock the Poco X5 device.

![smart lock android](https://images.wondershare.com/drfone/others/14555211623749.jpg)

In case Trusted Face is not required, tap on reset Trusted Face appearing under the Trusted Face menu. Tap on Reset to reset the option.

_How To Improve Facial Recognition In Your Bluetooth and Android NFC Unlock Devices_

![smart lock android](https://images.wondershare.com/drfone/others/14555212902436.jpg)

- • If you feel facial recognition is not up to the mark, go to Smart Lock and tap on a Trusted face.
- • Tap on Improve face matching.
- • Tap on Next and follow instructions on the screen to complete the task.

Smart Lock Android is a great feature and is only going to improve on time. With added security measures being introduced by Google for Bluetooth and NFC unlock android devices, including configuration to Google maps and Gmail, the feature may be one of the most important features to overcome constant blocking of devices even in protected places.

### Video on How to Remove Android Lock Screen Without Data Loss

<iframe frameborder="0" allowfullscreen="allowfullscreen" src="https://www.youtube.com/embed/qXw3JNztGVI" id="video-iframe-t"></iframe>


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

