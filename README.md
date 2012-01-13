#Customize styles for chrome dev tools

In order to show a cleaner styles panel I've modified some styles in a very inception-esque exercise (inspecting the inspector).

In this image you can see the differences, on the left the default style, on the right my custom styles panel.

![custom chrome dev tools](https://github.com/hunab/custom-chrome-dev-tools/blob/master/custom-chrome-dev-tools.png)

List of changes:

* Checkboxes to enable/disable properties on left
* Lighter grey for the name of css file in a properties block
* Grey background for read-only properties or inherited properties from other files
* Only show inherited properties from other files when moving mouse over the title bar
* Highlighted with yellow background some "important" properties: float, display, position, margin, padding and width
* Changed value color
* Highlighted with italic properties with -webkit prefix
* Hidden browser prefixes except -webkit
* Hidden all prefixes for *border-radius* and *box-shadow*
* Removed grey line between block of properties

##Instructions to use these styles

###Mac

Copy the styles here:

* **Chrome:** ~/Library/Application\ Support/Google/Chrome/Default/User\ StyleSheets/Custom.css 
* **Chrome Canary:** ~/Library/Application\ Support/Google/Chrome\ Canary/Default/User\ StyleSheets/Custom.css

###Windows

Copy the styles here:

C:\Users\YourUsername\AppData\Local\Google\Chrome\User Data\Default\User StyleSheets\Custom.css

###Ubuntu (Chromium)

Copy the styles here:

~/.config/chromium/Default/User\ StyleSheets/Custom.css
