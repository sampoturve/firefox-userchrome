# firefox-userchrome
Small tweaks to Firefox UI.

## Current tweaks
- Move the container indicator to the bottom of the tab
- Dim the text on non-selected tabs

## Installation
- Open `about:config`, search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set the value to `true`
- Open `about:profiles`, find the `Root Directory` of your profile in use and copy the path
- Navigate to the path copied
- Clone the repository contents under a new `chrome` directory
- Restart Firefox

