# app-grundgesetz-arabisch

mobile app for iOS and Android simply displaying the German Constitution in arabic

contribution to refugeehackathon

## Install on Smartphone

Will upload to app stores soon ...

## Build App from Source Code

The app is using cordova supported by the ionic framework. Make sure to have them installed:

```
npm install -g cordova@5.3.1 ionic@1.6.4
```

Then add platforms

```
cordova platform add android
cordova platform add ios
```

fire up a android simulator or connect a device and deploy app to it

```
ionic run android
```

if its running than you can build the APK for android

```
ionic build android
```

or the xcode project for iOS

```
ionic build ios
```

## Content Licenses

The arabic text of the Grundgesetz is taken from a PDF

http://www.fes.de/international/nahost/pdf/GGArabisch.pdf

by the Friedrich Ebert Stiftung (got OK by eMail to republish) converted with

http://www.zamzar.com/

to a one 1page-HTML5 file displayed in the app.

The icons are taken from the Wikipedia article about the German constitution

https://de.wikipedia.org/wiki/Grundgesetz_f%C3%BCr_die_Bundesrepublik_Deutschland#/media/File:N37W4N_255x400.jpg

## Code License

GNU GENERAL PUBLIC LICENSE Version 2

see LICENSE file for detailed info
