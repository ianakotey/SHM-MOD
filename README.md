# SHM MOD - Everything you need to know about the MOD...
> Don't forget to show some support if you are happy with what I am doing, it is highly appreciated...

The main purpose of this Repo is to allow the SHM MOD Companion to read Changelog as I don't want to update the companion all the time just to update the Changelog...
But I decided to make it as an alternative presenation to XDA, It might be more organized here...

## What's SHM MOD \*gasp\*...?

just kidding lol, well, it's a tool for BP & ECG for Samsung Watches, but this tool has restrictions such as region lock and works only on Samsung Devices, and for that, I found it to be unfair, health is important, this tool should be accessapble to everyone, it saves lives... Anyway, Install the MOD according to the Watch you own:
| Tizen (Active2 & Watch3 Only)  | WearOS (Watch4, Watch5 & Newer) |
| ------------- | ------------- |
| https://forum.xda-developers.com/t/restrictions-removed-shm-mod-tizen-updated.4202685/  | https://forum.xda-developers.com/t/restrictions-removed-shm-mod-wearos-updated.4322527/  |

## Pairing Problems with huawei
might work for others, china roms need to have google services, you can try installing WearOS by Google but don't use it
	<table>
		<thead>
			<tr>
				<th><font color="#313030">Original Solution</font></th>
				<th><font color="#313030">Additional Solution</font></th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>The solution is from reddit by Reddit u/Relative_Comparison2 &amp; u/MelodicMaintenance: <a href="https://www.reddit.com/r/WearOS/comments/p82h39/comment/h9rpsob/?utm_term=37596048491&amp;context=3&amp;utm_medium=comment_embed&amp;utm_source=embed&amp;utm_name=d5a31db0-a614-11ed-8594-aed5afdf7c67" target="_blank">reddit link</a><br>
    Original Instructions:<br>
    You need Galaxy Wearables & Watch4 Plugin installed, now do the following steps:<br>
Download Samsung Health.<br>
start Samsung health then go to accessories and search for your watch (scan).<br>
Samsung Health will call Galaxy Wearables to set up the connection and a normal setup is performed.</td>
				<td>This solution is provided by me:<br>
It was Explained that you need to have the following apps installed:<br>
Galaxy Wearable & Watch 4 plug-in<br>
Give all permissions to Galaxy Wearables and the Watch4 plugin by going app info, scroll down, permission and grant all...<br>
Now Clear the data of the following applications:<br>
 - Google Play Services<br>
 - Google Play Framework<br>
 - Google Play Store<br>
 - HwWifiproBqeService (For Huawei devices only, skip if you are not Huawei)<br>

The phone will start acting up, that's normal, so restart your phone to allow system app to rebuild itself, when the phone starts, do not configure your google account yet, first try connecting to the Watch4 again through Samsung Health and it should work, after that you can do whatever you want for google...<br>
<br>
One last note, disable any battery optimization, some phones have aggressive optimization, they will kill background services, this will stop the watch4 from pairing, if you can't disable it, then whitelist galaxy wearble and the watch4 plugin!</td>
			</tr>
		</tbody>
	</table>

## Message to Samsung Root Users
| Rooted without Disabling Encryption  | Rooted and want to use latest Samsung Health |
| ------------- | ------------- |
| Device encryption will play a big role if you leave it, you most likely will end up with error ERR_INTEGRITY which makes shm refuse to communicate with the watch, so the solution would be flashing encryption disabled... | Please use the Knox Patch Module: https://github.com/BlackMesa123/KnoxPatch |

## Features:
	- Device Restriction Removed...
	- Country Restriction Removed...
	- Root Detection Removed...
	- Age Restriction lowered from 22 to 16 years old...
	- Force Update to latest version removed...
	- Lock screen requirement removed...
	- Removed different restrictions related to hiding BP or ECG...
## Languages added with help of members:
	- Chinese simplified -> (values-zh-rCN)
	- Japanese -> (values-ja)
	- Malay -> (values-ms)
	- Punjabi -> (values-pa)
	- Hindi -> (values-hi)
	- Persian -> (values-fa)
	- Filipino -> (values-fil)

## Want My Drive Links?
| Tizen (Active2 & Watch3 Only)  | WearOS (Watch4, Watch5 & Newer) |
| ------------- | ------------- |
| ![alt text](https://forum.xda-developers.com/data/attachments/3987/3987761-7dc49a030f60a468ba29d559aa389158.jpg "Tizen Phone App Logo") ![alt text](https://forum.xda-developers.com/data/attachments/3987/3987759-a5bbd202adce03db4d55c50525d9087c.jpg "Tizen Watch App Logo") | ![alt text](https://forum.xda-developers.com/data/attachments/3987/3987605-8f90c24f868731f21eb42ea90df74b72.jpg "WearOS Phone App Logo") ![alt text](https://forum.xda-developers.com/data/attachments/3987/3987607-dd87ef6e629693d0e1d1fd6431d79a55.jpg "WearOS Watch App Logo") |
| https://drive.google.com/open?id=11ievXT0p86Py9vEAz9y8zh5ve9yLgQLn  | https://drive.google.com/open?id=138thPYPMbZIp2Us0Unx_h-SqJQEDxZ-0  |

# What's SHM MOD Companion...?
Start with these video:

| What is SHM MOD Companion?  | Latest Companion Update - 2.0.0 |
| ------------- | ------------- |
| [![What is SHM MOD Companion?](https://img.youtube.com/vi/a0FO9pwqMkQ/0.jpg)](https://www.youtube.com/watch?v=a0FO9pwqMkQ)  | [![Latest Companion Update - 2.0.0](https://img.youtube.com/vi/Qx6Jorgbj0k/0.jpg)](https://www.youtube.com/watch?v=Qx6Jorgbj0k)  |

## Don't want to watch...?
No problem...

It's an All-In-One Tool I have developed to make things easier for you:
 1. Get latest SHM MOD Updates...
 2. Read F.A.Q and Features...
 3. Read "What's New"...
 4. Find out latest bugs...
 5. Read the guide of how to use the companion...
 6. How To Reach Me and Support Me...
 7. (WearOS Watches Only) ADB Connect to Sideload or Remove/Restore Stock SHM...
 8. BP Sync Enabler...
 
 ## Oh and if you want to enjoy other things I developed, then visit my website: https://geminiman.net/
 
 ## Want to Support Me...?
 
 + PayPal: https://paypal.me/dante63
 + Patreon: https://www.patreon.com/xda_dante63
 + Google Play: https://play.google.com/store/apps/details?id=com.geminiman.watchfaces
 
 Have a great day...
