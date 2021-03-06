# apk-signer

* Version: 1.8.5

### Feel free to contact us at:

* [Homepage](http://www.haibison.com)
* E-mails  :
    - haibisonapps[at]gmail.com


### We sincerely thank:

* All of our friends, who have been contributing to this project.
* The authors of external modules/ libraries which are used in this project.

We hope this project will be always useful for everyone.


# CREDITS

* Hans Bickel
    + Library [TinyLaF](http://www.muntjak.de/hans/java/tinylaf/index.html)
    + License: [GNU Lesser General Public License](http://www.gnu.org/licenses/lgpl.html)
* Leo Chien (contributor)
    + [Google+ page](https://plus.google.com/118055781130476825691?prsrc=2)
* Robert Harder and his friends
    + Module [FileDrop](http://www.iharder.net/current/java/filedrop/)
    + License: Public Domain
* The Android Open Source Project
    + Module [AOSP Base64](https://android.googlesource.com/platform/frameworks/base/+/master/core/java/android/util/)
    + License: [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
* Paul D. Hunt
    + Font [Source Code Pro](https://www.google.com/fonts/)
    + License: [SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007](http://scripts.sil.org/OFL)
* Christian Robertson
    + Font [Roboto](https://www.google.com/fonts/)
    + License: [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)


# HISTORY

* Version 1.8.5
    + *Release:* February 8th, 2014
    + Fix module Signer.

* Version 1.8.4
    + *Release:* February 7th, 2014
    + Update to support JDK 7.

* Version 1.8.3
    + *Release:* October 11th, 2013

* Version 1.8.3 beta
    + *Initialize:* August 11th, 2013

* Version 1.8.2:
    + *Release:* July 26th, 2013
    + Fix and upgrade module Updater.

* Version 1.8.2 beta
    + *Initialize:* July 23rd, 2013

* Version 1.8.1
    + *Release:* July 22nd, 2013
    + Improve module Updater, now it supports redirection URLs (302) from server.
    + Use new font Source Code Pro instead of Droid Sans Mono.

* Version 1.8.1 beta
    + *Initialize:* July 22nd, 2013

* Version 1.8
    + *Release:* July 22nd, 2013
    + Optimize/ improve UI.

* Version 1.8 beta
    + *Initialize:* July 21st, 2013

* Version 1.7.9
    + *Release:* July 21st, 2013
    + Use AOSP Base64 instead of Apache Commons Codec (to reduce binary size).

* Version 1.7.8
    + *Release:* July 21st, 2013
    + Fix encryption module on some (poor) JVMs  :|
    + Fix i18n Vietnamese translation.
    + Use ProGuard to shrink final executable JAR file.

* Version 1.7.8 beta
    + *Initialize:* July 20th, 2013

* Version 1.7.7
    + *Release:* July 20th, 2013
    + Add Settings (menu File > Settings).
    + Improve code.

* Version 1.7.6
    + *Release:* July 6th, 2013
    + Remove unused logging code.
    + Shrink final output JAR file with ProGuard.

* Version 1.7,5
    + *Release:* July 6th, 2013
    + Improve UI reactions.

* Version 1.7.4
    + *Release:* July 4th, 2013
    + Add module FileDrop. Thanks to Robert Harder and his friends.

* Version 1.7.3
    + *Release:* July 1st, 2013
    + Improve performance when reading/ writing files.
    + Module Signer: fix bug where the user cannot set his own alias name.

* Version 1.7.2
    + *Release:* July 1st, 2013
    + Optimize code...

* Version 1.7.1
    + *Initialize:* July 1st, 2013
    + *Release:* July 1st, 2013
    + Optimize code, fix some bugs...

* Version 1.7
    + *Release:* July 1st, 2013
    + Add new tab `APK Alignment` which helps you align APKs and verify aligned
      APKs.
    + Optimize code and UI reactions.

* Version 1.6.8
    + *Release:* June 28th, 2013
    + Add i18n Vietnamease translation.

* Version 1.6.7
    + *Release:* June 28th, 2013
    + Improve UI and performance.

* Version 1.6.6
    + *Release:* June 27th, 2013
    + Fix module Updater.

* Version: 1.6.5
    + *Release:* June 27th, 2013
    + Fix module Updater.
    + Optimize code.

* Version 1.6.4
    + *Release:* June 26th, 2013
    + Fix some bugs.
    + Panel Signer: adds file filters for APK/ JAR/ ZIP files.

* Version 1.6.3
    + *Release:* June 26th, 2013
    + Fix some bugs  :-(

* Version 1.6.2
    + *Release:* June 26th, 2013
    + Fix Updater service.

* Version 1.6.1
    + *Release:* June 26th, 2013
    + Fix storing/loading preferences.

* Version 1.6
    + *Release:* June 26th, 2013
    + Add auto-update feature.
    + Port entire project from NetBeans based to Eclipse WindowBuilder based.

* Version 1.6 beta
    + *Initialize:* June 24th, 2013

* Version 1.5.1
    + *Release:* June 22nd, 2013
    + Fix a bug after signing APK file: if signing process was not OK then don't
      rename the original APK.

* Version 1.5
    + *Initialize:* June 17th, 2013
    + *Release:* June 18th, 2013
    + Add new tab "Key Tools" which let you obtain fingerprints from keystore
      files. They're needed when you work with Google APIs console for example.
    + Optimize code.

* Version 1.4.2
    + *Release:* Janunary 8th, 2013
    + Fixes issue #1, thanks to Leo Chien  :-)
    + Now the app works fine with JDK 1.7;

* Version 1.4.1
    + *Release:* June 19th, 2012
    + update URL of Google+ page;

* Version 1.4
    + *Release:* June 7th, 2012
    + add library TinyLaF (thanks to Hans Bickel);

* Version 1.3
    + *Release:* February 17th, 2012
    + remember JDK path;
    + fix JFileChooserEx with regex filename filter;

* Version 1.2
    + *Release:* February 16th, 2012
    + Add popup menu for all text components;

* Version 1.1.1
    + *Release:* February 16th, 2012
    + Fix: use save dialog instead of open dialog in panel keygen;

* Version 1.1
    + *Release:* February 16th, 2012
