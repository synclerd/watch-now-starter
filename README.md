# Watch now starter

Watch now is a Kosmos package for Syncler that that returns a list of select few streaming services (Netflix, Amazon prime, Disney+ etc) installed on device where desired content may be played. It shows a list of apps and lets the user directly open those apps all in one place conveniently. 

Users may choose to further extend or optimize the list of install apps to search for by modifying this package or use it as is.

Please note that this package is not meant to work out of the box as is. This is meant to be a starting point for users to customize their streaming experience.  For example:
1.	Users must add their Streaming services in the JS file if it’s not already included.
2.	Users must have specified apps installed on device. Otherwise the apps will appear as failed in the app list.
3.	Users may additionally want to filter out any streaming service that may not have their content available for their location by reading the media metadata and matching it with any 3rd party APIs of their choice.


Please refer to the JS file comments to customize it to your liking.

## Installation
1. Open Syncler.
2. From left Navigation menu, click 'Settings'.
3. Navigate to 'Provider packages'.
4. Click 'Kosmos' Under 'Install'.
5. Visit the website as per instruction, enter code displayed and click next.
6. Enter this url as package url: https://raw.githubusercontent.com/synclerd/watch-now-starter/main/package.js
7. Return to app and click ‘Done’.
