# #darktwitter

If you don't like the new, bright, white Twitter design and would like to switch your navigation bar (and a few other boxes) back to black, you've come to the right place.

To see what #darktwitter looks like, check the Screenshots folder above. **Pro tip:** you can change the colour of all links (including coloured elements in your top navigation bar and your stats bar) to something else in your [Twitter settings](https://twitter.com/settings/design).

If you find this solution useful, consider spreading the word on Twitter using the hashtag #darktwitter (and namechecking @kkvie to let me know about it!).


## Firefox
Download the above [userContent.css](userContent.css) file (click through to the file and then press the "Raw" button to display it) and save it to your FF profile. 

You can find your profile folder from within Firefox by clicking on the "Help" menu, selecting "Troubleshooting Information" and, in the Troubleshooting tab that opens, clicking the button next to where it says "Profile Folder". This should open your Firefox profile directory in your file browser.

Now navigate to the `chrome` folder inside this directory, drop the .css file into it, restart Firefox and voilà!

(To get rid of #darktwitter again and switch back to #newtwitter, simply delete the userContent.css file from your chrome folder and restart FF.)

## Chrome & chromium
The CSS hack for Chrome (and chromium) isn't as clean as the Firefox one and it looks like Chrome will not be supporting customised stylesheets [for much longer](http://code.google.com/p/chromium/issues/detail?id=53596), but do give it a try for as long as you can still use it!

Download the above [Custom.css](Custom.css) file (click through to the file and then press the "Raw" button to display it) and save it to `Default > User Stylesheets` in your Chrome installation folder.

The full paths to the Chrome installation folder are:<br>
on Mac: `YourUserName/Library/Application Support/Google/Chrome`<br>
on Win7 & Vista: `C:\Users\%USERNAME%\AppData\Local\Google\Chrome\User Data\Default`<br>
(More paths for both Chrome and chromium on different OS, including Linux, are listed [on this page](http://www.chromium.org/user-experience/user-data-directory).)

The changes should take effect immediately, no need to restart Chrome.

(To get rid of #darktwitter again and switch back to #newtwitter, simply delete the Custom.css file from your `User Stylesheets` folder.)

