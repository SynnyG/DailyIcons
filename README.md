# DailyIcons
<p><strong>DailyIcons</strong> is a free application developped for Cydia users that allow you to change your Calendar's icons themes every day, allowing you to create wonderful setup on your iDevice !</p>

<p>Two DailyIcons theme are included by default with the tweak (you can find them at /Library/Themes/Default DailyIcons.theme and Default 2nd DailyIcons.theme. They have been created by my friend, a talented theme maker called Franchitouch. Big thanks to him ;)</p>

<p>To fully use DailyIcons, you must have either Anemone or Winterboard installed to see your calendar's icons change everyday. See instructions below for how to use it and for creating your own themes.</p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<h1><ins>How to use DailyIcons</ins></h1>

<p>1) Download your DailyIcons theme in Cydia</p>

<p>2) Apply it through Anemone or Winterboard. If the theme maker has included default icons, you will have them shown in SpringBoard but they are maybe not at the good date. You can actualize the day on your icon by going to the DailyIcons settings page and click on the "Refresh all DailyIcons themes" button, but you can also wait for a date change !</p>

<p>3) At every device unlock, DailyIcons will check if the date has changed. If no, nothing will be done. If yes, an alert will tell you that you must respring to actualize your Calandar's icons</p>

<p>4) Enjoy your beautiful icons ;)</p>

<p>&nbsp;</p>

<h1><ins>How to create a cydia package for your DailyIcons Theme</ins></h1>

<p>If you want to submit your DailyIcons theme to Cydia, you have two solutions :</p>

<p>1) Create a separate package only for your DailyIcons theme (submit only the .theme to your favorite repo or create a .deb package for it)</p>

<p>2) Update your existing theme by creating a seperate .theme folder that only include the DailyIcons theme. With this solution, the users will only have to download one package from Cydia, this is a time saver !</p>

<p>Your DailyIcons theme must follow these instructions for being compatible with the tweak :</p>

<p>1) The .theme folder that include the DailyIcons theme must include "DailyIcons" key in the name. This is needed for the tweak to detect it ! Exemple: "0bvious iOS9 DailyIcons.theme"</p>

<p>2) It must have the following file structure :</p>

<p>Your Theme DailyIcons.theme/</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /Bundles</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Info.plist</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /com.apple.mobilecal</p>

<p>(Until here nothing change for you :P)</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /ipad (folder that must contain 31 png for non-retina iPad, each one for one day of the month)</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /ipad@2x (folder that must contain 31 png for retina iPad, each one for one day of the month)</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /iphone@2x (folder that must contain 31 png for retina iPhone, each one for one day of the month)</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /iphone@3x (folder that must contain 31 png for iPhone 6 Plus/6S Plus, each one for one day of the month)</p>

<p>Here you have a choice: include some defaults icons as you usually do (I mean same names) or include nothing, but the user will have blank Calendar's icons until a refresh is done !</p>

<p>Each .png files placed into the devices folders (ipad, ipad@2x, iphone@2x, iphone@3x) must be named as 1.png, 2.png, 31.png, etc... The number corresponding to the day of the month. So you have certainly understood that you have to do 31.png for each supported devices ! If you don't want to support iPad, simply don't create the folders and the png files associated !</p>

<p>If you want concrete examples, go to the /Library/Themes folder and look at the default included themes (Default DailyIcons.theme and Default 2nd DailyIcons.theme)</p>

<p>&nbsp;</p>

<h1><ins>More to come :</ins></h1>

<p>Support for App Switcher, Spotlight, Settings icons. You will have nothing to do as DailyIcons will create theme from one of the existing .png ;)</p>

<p>Support for others Calendar applications</p>

<p>&nbsp;</p>

<h1><ins>Credits :</ins></h1>

<h3>Frenchitouch</h3>

<p>Original idea come from him. He has been my beta tester, and also has created the 2 default themes included in DailyIcons and all the settings icons. Big thanks to him (don't forget to follow him in Twitter at @frenchitouch ;) ) !</p>

<h3>SynnyG</h3>

<p>Developer of DailyIcons. Don't forget to follow me on Twitter for news, app giveaway, etc... at @SynnyG_R ;) !</p>

<p>&nbsp;</p>

<p>If you have any issue or suggestion, please contact me via the Cydia's contact form. I will reply to you as soon as possible !</p>

<p>&nbsp;</p>

<h3>SynnyG and Frenchitouch</h3>
