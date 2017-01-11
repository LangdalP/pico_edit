# Changes done for Ovase.no

- Set password in config file
- Started using epiceditor.js instead of the minified version
    * Parser now handles metadata (encased in "---" above and below)
    * Parser now removes "%base_url%" from URLs to show images in preview
- Added a little Ovase header at the top of the side bar
- Changed the "Clear cache" function to use pure PHP instead of system()