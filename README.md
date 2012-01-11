#Customize styles for chrome dev tools

In order to show a cleaner styles panel I've modified some styles in a very inception-esque exercise.

In this image you can see the differences, on the left the default style, on the right my custom styles panel.

![custom chrome dev tools](http://dl.dropbox.com/u/1223708/custom-chrome-dev-tools.png)

List of changes:

* Checkboxes to enable/disable properties on left
* Lighter grey for the name of css file in a properties block
* Grey background for read-only properties or inherited properties from other files
* Only show inherited properties from other files when moving mouse over the title sidebar
* Highlight with yellow background some "important" properties: float, position, margin, padding and width
* Changed value color
* Hide browser prefixes except -webkit
* Highlight with italic properties with -webkit prefix
* Removed grey line between block of properties

##Instructions to use these styles

###Mac

Copy the styles here:

1. **Chrome:** ~/Library/Application\ Support/Google/Chrome/Default/User\ StyleSheets/Custom.css 
2. **Chrome Canary:** ~/Library/Application\ Support/Google/Chrome\ Canary/Default/User\ StyleSheets/Custom.css

###Windows

Copy the styles here:

C:\Users\YourUsername\AppData\Local\Google\Chrome\User Data\Default\User StyleSheets\Custom.css

###Ubuntu (Chromium)

Copy the styles here:

~/.config/chromium/Default/User\ StyleSheets/Custom.css
