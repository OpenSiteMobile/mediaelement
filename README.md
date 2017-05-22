mediaelement
============

MobileSiteOS's HTML5 Media Player demo, as adapted from MediaElement and MediaElementPlayer

This repository contains our demo index and debug pages, plus configuration file for utilizing the
MobileSiteOS version of MediaElement/MediaElementPlayer, by John Dyer (http://mediaelementjs.com/).
The orginal working files can be found at https://github.com/johndyer/mediaelement/. The MobileSiteOS
files are a highly modified derivation of MediaElementPlayer.js. The original MediaElementPlayer.js script
and CSS has been broken up into many individual modules that are loaded on an "as needed" basis by MobileSiteOS.
Mobile versions get less features, while a desktop can easily accomodate as many as you like. Only the files
needed are downloaded to the browser, based on it's capabilities and the features assigned to each type of
device. That is, if the browser has HTML5 capabilities, then the Flash plugin player is not needed or loaded.

The actual files for the MobileSiteOS MediaElement derived player are founed at https://github.com/OpenSiteMobile/osm_mep,
while the demo content and javascript pages (as view through our msos.page driven SPA) are found at https://github.com/OpenSiteMobile/mobilesiteos/tree/gh-pages/apps,
in the "mediaelelement" folder.

It should be noted that this is NOT a direct replacement for the original MediaElementPlayer, since it
is entirely dependent on MobileSiteOS. And it is also a more experimental, "mobile focused" version
(lacks IE7, 8, 9 support). It does however incorporated our version of FitMedia.js for negociating
different display sizes, similar to the way the FitImage (https://github.com/kpobococ/FitImage/blob/master/Source/FitImage.js)
script does for images presented in a responsive web design website.

Our demo can be run from http://opensitemobile.com/mediaelement/

Note: This demo is incomplete due to changes in Google's Youtube API and other software changes.
