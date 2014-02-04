#darktwitter

##On Firefox
Firefox users who don't like the new, bright, white Twitter design (as of 14-02-04) can download the above [userContent.css](userContent.css) file and save it to their FF profile directory (click through to the file and then on the "Raw" button to display it) to make the Twitter navigation bar and a few other boxes turn back to black.

The easiest way to find your profile folder is from within Firefox: click on the "Help" menu, select "Troubleshooting Information" and in the Troubleshooting tab that opens click the button next to where it says "Profile Folder" - this should open your Firefox profile directory in your file browser.

Now navigate to the "chrome" folder inside this directory, drop the .css file into it, restart Firefox and voilà!

(To get rid of #darktwitter again and switch back to #newtwitter, just delete the userContent.css file from your chrome folder and restart FF.)

##On Chrome
Because I was asked about this, I added a quick (and super dirty) hack for Chrome too, though it looks like Chrome will not be supporting customised stylesheets [for much longer](http://code.google.com/p/chromium/issues/detail?id=53596).

Download the above [Custom.css](Custom.css) file (click through to the file and then on the "Raw" button to display it) and drop it into **Default > User Stylesheets** in your Chrome installation folder (on Mac, the full path to your Chrome installation is YourUserName/Library/Application Support/Google/Chrome - I'd appreciate pointers on where it can be found on Windows).

The changes should take effect immediately, no need to restart Chrome.

(To get rid of #darktwitter again, just delete the Custom.css stylesheet from your User Stylesheets folder.)

