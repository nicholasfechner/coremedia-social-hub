![Status: Active](https://documentation.coremedia.com/badges/badge_status_active.png "Status: Active")
![For CoreMedia CMS](https://documentation.coremedia.com/badges/badge_coremedia_cms.png "For CoreMedia CMS")

![CoreMedia Labs Logo](https://documentation.coremedia.com/badges/banner_coremedia_labs_wide.png "CoreMedia Labs Logo Title Text")


# CoreMedia Social Hub

The Social Hub allows to integrate various social networks into the CoreMedia Studio.
It provides a separate tab that shows different social network feeds and messages that have been
scheduled for publishing. 

The Social Hub is implemented as a Blueprint extension.

We usually only work on the latest CoreMedia version, so the latest version of the documentation and demo content 
may be on the latest version branch.

### Documentation & Tutorial

https://github.com/CoreMedia/coremedia-social-hub/tree/master/documentation

### Demo Content

To enable the Social Hub, some settings have to be created on a global or site specific level.
A global example configuration can be found here:

https://github.com/CoreMedia/coremedia-social-hub/tree/master/test-data

### Issue Tracker

https://github.com/CoreMedia/coremedia-social-hub/issues

### Installation

- From the project's root folder, clone this repository as submodule into the extensions folder. Make sure to use the branch name that matches your workspace version. 
```
git submodule add  -b 1907.1 https://github.com/CoreMedia/coremedia-studio-hub modules/extensions/coremedia-social-hub
```

- Use the extension tool in the root folder of the project to link the modules into your workspace.
 ```
mvn -f workspace-configuration/extensions com.coremedia.maven:extensions-maven-plugin:LATEST:sync -Denable=coremedia-social-hub
```


For the IDEA import:
- Ignore folder ".remote-package"
- Disable "Settings > Compiler > Clear output directory on rebuild" to ensure the Studio development roundtrip

### Open Issues

Please check the issues section of the project:
https://github.com/CoreMedia/coremedia-social-hub/issues


