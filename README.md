Cordova Plugin for PDF Viewer
============================

### Plugin's Purpose
This plugin is aimed to provide features for viewing PDF files (online & local) for iOS and Android platforms.

## Overview
1. [Supported Platforms](#supported-platforms)
2. [Installation](#installation)
3. [Using the plugin](#using-the-plugin)
4. [Known issues](#known-issues)

## Supported Platforms ##
* iOS 9+
* Android 5+

## Installation ##

```bash
# ~~ from master branch ~~
cordova plugin add https://github.com/lingjunjiang/cordova-plugin-pdf-viewer.git
```

## Using the plugin ##

```javascript
// Open PDF viewer with either local / online URL, e.g. 'file:///...'
window.openPdf(pdfFileUrl);
```

## iOS ##

The plugin uses InAppBrowser (https://cordova.apache.org/docs/en/3.0.0/cordova/inappbrowser/inappbrowser.html) to view PDF files.

## Android ##

The plugin uses external PDF viewers on Android device.
 
TODO

- Add feature for iOS.
- Add online pdf file support for Android

## Credits ##

based on https://github.com/sitewaerts/cordova-plugin-document-viewer/

based on https://github.com/cyberkatze/pdfViewer
