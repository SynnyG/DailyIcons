# DailyIcons
<p><strong>DailyIcons</strong> is a free application developped for Cydia users that allow you to change your Calendar's icons themes every day, allowing you to create wonderful setup on your iDevice !</p>

<p>Two DailyIcons theme are included by default with the tweak (you can find them at /Library/Themes/Default DailyIcons.theme and Default 2nd DailyIcons.theme. They have been created by my friend, a talented theme maker called Franchitouch. Big thanks to him ;)</p>

<p>To fully use DailyIcons, you must have either Anemone or Winterboard installed to see your calendar's icons change everyday. See instructions below for how to use it and for creating your own themes.</p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<h1><ins>How to use DailyIcons</ins></h1>

<p>1) Download your DailyIcons theme in Cydia</p>

<p>2) Apply it through Anemone or Winterboard. If the theme maker has included default icons, you will have them shown in SpringBoard but they are maybe not at the good date. You can actualize the day on your icon by going to the DailyIcons settings page and click on the "Refresh all DailyIcons themes" button, but you can also wait for a date change !</p>

<p>3) If the date hasn't changed, nothing will be done</p>
<p>3.2) If the date has changed, an alert will tell you at device unlock that you must respring to actualize your Calandar's icons</p>

<p>4) Enjoy your beautiful icons ;)</p>

<p>&nbsp;</p>

<h1><ins>How to create a cydia package for your DailyIcons Theme</ins></h1>

<p>If you want to submit your DailyIcons theme to Cydia, you have to create a .theme folder that only include the DailyIcons theme (you can include it to your existing theme or create a separate Cydia)</p>

<p>Your DailyIcons theme must follow these instructions for being compatible with the tweak :</p>

<p>1) The .theme folder that include the DailyIcons theme must include "DailyIcons" key in the name. This is needed for the tweak to detect it ! Exemple: "0bvious iOS9 DailyIcons.theme"</p>

<p>2) It must have the following file structure :</p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p>Your Theme DailyIcons.theme/</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /Bundles</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Info.plist</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /com.apple.mobilecal</p>

<p>(Until here nothing change for you :P)</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /ipad (folder that must contain 31 png for non-retina iPad, each one for one day of the month)</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /ipad@2x (folder that must contain 31 png for retina iPad, each one for one day of the month)</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /iphone@2x (folder that must contain 31 png for retina iPhone, each one for one day of the month)</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /iphone@3x (folder that must contain 31 png for iPhone 6 Plus/6S Plus, each one for one day of the month)</p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p>At the root of com.apple.mobilecal folder you have a choice: include some defaults icons as you usually do (I mean same names) or include nothing, but the user will have blank Calendar's icons until a refresh is done !</p>

<p>Each .png files placed into the devices folders (ipad, ipad@2x, iphone@2x, iphone@3x) must be named as 1.png, 2.png, 31.png, etc... The number corresponding to the day of the month. So you have certainly understood that you have to do 31.png for each supported devices ! If you don't want to support iPad, simply don't create the folders and the png files associated !</p>

<p>If you want concrete examples, go to the /Library/Themes folder and look at the default included themes (Default DailyIcons.theme and Default 2nd DailyIcons.theme). I will soon publish a download link for them !</p>

<p>&nbsp;</p>

<h1><ins>How to support both Anemone and Winterboard</ins></h1>

<p>If you want to support Anemone and Winterboard, you have to edit the Info.plist consequently. The only thing you have to do is to put the 2 following parts into your Info.plist (to remove the date generated by the system onto the incon) :</p>

![Alt text](http://i.imgur.com/DgpGLRf.png)

<p>&nbsp;</p>

<h1><ins>How to test your DailyIcons theme on your device before submitting</ins></h1>

<p>If you want to test your theme before submitting it to Cydia, you have to put the right ownership onto the .theme folder (for them to be writable, like if you download it from Cydia). You can do this with two ways : </p>

<p>1) After you have put your theme onto your device with SSH, launch one of the following command with mobile terminal onto your device or from your computer with SSH connection to your device in your favorite terminal app :</p>
<i>chown -R mobile:staff /Library/Themes/{YourThemeDailyIcons.theme}</i>

<i>or</i>

<i>chown -R mobile:staff /Library/Themes/* (this will fix all the themes ownership)</i>

<p>2) Create a .deb package that contain your theme and a postinst script. This script have to be in DEBIAN/postinst and must contain one of the above commands</p>

<p>&nbsp;</p>

<h1><ins>More to come :</ins></h1>

<p>Support for App Switcher, Spotlight, Settings icons. You will have nothing to do as DailyIcons will create them from one of the existing .png ;)</p>

<p>Support for others Calendar applications</p>

<p>&nbsp;</p>

<h1><ins>Credits :</ins></h1>

<h3>Frenchitouch</h3>

<p>Maker of several iOS themes, DailyIcons tweak thinker/designer. Take a look at frenchitouch.fr for more !</p>

<h3>SynnyG</h3>

<p>Developer of DailyIcons, BackupAZ apps, iAdministrator, SpringSounds... Take a look at @SynnyG_R in Twitter for apps info, giveraway, etc... !</p>

<p>&nbsp;</p>

<p>If you have any issue or suggestion, please contact me via the Cydia's contact form. I will reply to you as soon as possible !</p>

<p>&nbsp;</p>

<h3>SynnyG and Frenchitouch</h3>
