# DailyIcons
<p><strong>DailyIcons</strong> is a free application developped for Cydia users that allow you to change your Calendar's icons themes every day, allowing you to create wonderful setup on your iDevice !</p>

<p>Two DailyIcons theme are included by default with the tweak (you can find them at /Library/Application Support/Default DailyIcons and Default 2nd DailyIcons. They have been created by my friend, a talented theme maker called Franchitouch. Big thanks to him ;)</p>

<p>See instructions below for how to use it and for creating your own themes.</p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<h1><ins>How to use DailyIcons</ins></h1>

<p>1) Download your DailyIcons theme in Cydia</p>

<p>2) Apply it through the DailyIcons's settings page and Respring</p>

<p>3) If the date hasn't changed, nothing will be done</p>
<p>3.2) If the date has changed, just look at your Calendar's icon, it has been changed accordingly to the date change, and without a respring ;)</p>

<p>4) Enjoy your beautiful icons ;)</p>

<p>&nbsp;</p>

<h1><ins>How to create a cydia package for your DailyIcons Theme</ins></h1>

<p>If you want to submit your DailyIcons theme to Cydia, you have to create a package that contain the 31 png, one for each day of the month (simply create 31 png, DailyIcons will know if the 31th have to be shown)</p>

<p>The package must have the following file structure :</p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /DEBIAN (where the control fil have to be and potential scripts)</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /Library</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /Application Support</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /DailyIcons</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /Your Theme folder (exemple: 0bvious DailyIcons, you can name it as you want)</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Here place your 31 png files that will be loaded by DailyIcons to show any date change. PLEASE NOTE: There is no need to create several png for several devices (@2x, @3x), DailyIcons will apply the icons normally for your resolution. But for this, you have to create your png with the highest resolution possible (228px => iPad pro icons' resolution), thanks to that, your theme will be compatible with all iOS devices ;)</p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p>If you want concrete examples, go to the /Library/Application Support/DailyIcons folder and look at the default included themes (Default DailyIcons and Default 2nd DailyIcons). I will soon publish a download link for you to have a template for creating your own theme easily !</p>

<p>&nbsp;</p>

<h1><ins>How to test your DailyIcons theme on your device before submitting, without creating .deb package</ins></h1>

<p>Simply put your Theme folder under /Library/Application Support/DailyIcons/ and select it under DailyIcons's settings page</p>

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
