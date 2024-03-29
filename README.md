# Google 2009 theme
Theme Google (XHTML Mobile version) to look like 2009 Google

# How to activate XHTML Mobile version of Google?
Use the following user agent for Google: ```Mozilla/4.0 (compatible; MSIE 6.0; Windows CE; IEMobile 7.11)```

# How do I change my user agent?
On Firefox(-based) browsers: https://addons.mozilla.org/en-US/firefox/addon/user-agent-string-switcher  
On Chromium(-based) browsers, there is a similar addon if you look it up.  
**Make sure to set it up that the user agent only applies to Google!**

# How do I make it only apply on Google and how do I even use the extension? (Firefox)
Click the extension's icon (
<img src="https://addons.mozilla.org/user-media/addon_icons/853/853731-64.png" alt="User Agent String Switcher icon" width="16" height="16">
) then on userAgent put the useragent above (```Mozilla/4.0 (compatible; MSIE 6.0; Windows CE; IEMobile 7.11)```), press enter then click Options. Check the ratiobox "White-List Mode" and put "www.google.com" inside it. Scroll down and click "Save". Right click the extension's icon (
<img src="https://addons.mozilla.org/user-media/addon_icons/853/853731-64.png" alt="User Agent String Switcher icon" width="16" height="16">
) and then click "Switch to "white-list" mode". It should change the user agent.

# Recommended
https://addons.mozilla.org/en-US/firefox/addon/dont-track-me-google1/  
This is to prevent from sites thinking you are visiting on Windows CE (because of Google's tracking redirect)

# How do I use this?
Apply the user agent for Google above and use a extension (like Stylus) to apply it. If you are on Firefox, you can use UserContent.css.

# Warning
Code is really messy.

# Screenshots
Homepage  
![image](https://user-images.githubusercontent.com/80153347/209447907-22ed7098-d5ac-4f5b-9a19-75c70d357fef.png)  
Search page  
![image](https://user-images.githubusercontent.com/80153347/209447926-99a94fc6-f483-430c-bfa9-10c2954948a3.png)
<s>Preferences page (far from done)</s> Not skinned anymore since the preferences page got updated.
![Preferences page](preferences.png "Preferences page")  


# References used
https://oldgoogle.neocities.org/2009  
http://web.archive.org/web/20090901000000*/www.google.com

# NsFAQ
**Does this work with other languages?**  
Yes, however RTL languages seem to break a bit.  

**Why?**  
Why not?  
  
**The theme is broken. Please fix it.**  
Report the issue on GitHub issues.
