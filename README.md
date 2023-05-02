<h1 align="center">Dating app UI/UX using React Native</h1></br>

<p align="center">
📱 This project is a react-native mobile application interface
</p>
<br>

![Banner](https://cdn.discordapp.com/attachments/1091185439815245874/1102924123207901255/Sans_titre.png)

## Stats

![](https://img.shields.io/tokei/lines/noe-gif/Dating-app-React-Native?color=orange&label=Total%20Lines&logo=kotlin&logoColor=white)
[![](https://img.shields.io/github/downloads/noe-gif/Dating-app-React-Native/total?color=orange&label=Total%20Downloads%20(GitHub)&logo=github&logoColor=white)](https://tooomm.github.io/github-release-stats/?username=noe-gif&repository=Dating-app-React-Native)
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fnoe-gif%2FDating-app-React-Native&count_bg=%239A3DC8&title_bg=%23555555&icon=tencentweibo.svg&icon_color=%23E7E7E7&title=Total+Visits&edge_flat=false)](https://hits.seeyoufarm.com)
[![Release](https://img.shields.io/github/v/release/noe-gif/Dating-app-React-Native?color=52be80&label=Release)](https://github.com/noe-gif/Dating-app-React-Native/releases)
![](https://img.shields.io/github/languages/count/noe-gif/Dating-app-React-Native?color=white&label=Languages)
![](https://img.shields.io/github/license/noe-gif/Dating-app-React-Native?color=red&label=License)
![](https://img.shields.io/badge/Minimum%20SDK-23%20(Marshmallow)-839192?logo=android&logoColor=white)
![](https://img.shields.io/badge/Target%20SDK-33%20(Android%2013)-566573?logo=android&logoColor=white)
[![Crowdin](https://badges.crowdin.net/inure/localized.svg)](https://crowdin.com/project/inure)

# MBTI matching dating app

User interface and experience

<p align="center">
<img src="assets/lv_0_20230502125528.gif" alt="androiddevnotes logo"></img>
</p>

## Getting Started

Follow these instructions to build and run the project

![Banner](https://cdn.discordapp.com/attachments/1091185439815245874/1102924123207901255/Sans_titre.png)

### Setup Flutter

A detailed guide for multiple platforms setup could be find [here](https://flutter.dev/docs/get-started/install/)

### Setup Project

- Clone this repository using `git clone https://github.com/CircuitVerse/mobile-app.git`.
- `cd` into `mobile_app`.
- `flutter pub get` to get all the dependencies.
- Generate files using Builder Runner (**required**) 
```
flutter pub run build_runner build --delete-conflicting-outputs
```
- Switch to mobile-app's git hooks (**optional but recommended**)
```
git config core.hooksPath .githooks/
# Make sure npm is installed to run the next command
npm install -g @commitlint/config-conventional @commitlint/cli
```
> Mobile App enforces [Conventional Commits specification](https://www.conventionalcommits.org/en/v1.0.0/), make sure to read and follow them.

## Project Structure

```bash
mobile-app/lib/
├── config/                         # configuration files like environment_config
├── enums/                          # enum files
|   └── view_state.dart             # defines view states i.e Idle, Busy, Error
|   └── auth_state.dart             # defines auth states i.e logged in using Google/FB/Github/Email
├── l10n/                           # localization files like intl_en.arb
├── locale/                         # AppLocalization & AppLocalizationDelegate
├── managers/
|   └── dialog_manager.dart         # show dialogs using dialog navigation key
├── models/                         # model classes
|   └── dialog_models.dart          # dialog request and response models
        ...
├── services/                       # services
|   ├── API/                        # API implementations
|   └── dialog_service.dart         # handles dialog
|   └── local_storage_service.dart  # handles local storage (shared prefs)
├── ui/                             # UI layer
|  ├── views/                       # views
|  |  └── base_view.dart
|  |  └── cv_landing_view.dart
|  |  └── startup_view.dart
|  └── components/                  # shared components
├── utils/                          # utilities such as api_utils routes.dart and styles.dart
├── viewmodels/                     # Viewmodels layer
├── app_theme.dart                  # Shared App Colors/border decorations etc.
├── constants.dart                  # App constants
├── locator.dart                    # dependency injection using get_it
├── main.dart                       # <3 of the app
```

## Download

[![](https://img.shields.io/badge/Play%20Store-ea4335?logo=googleplay)](https://play.google.com/store/apps/details?id=app.simple.inure)
[![](https://img.shields.io/badge/GitHub%20Releases-181717?logo=github)](https://github.com/Hamza417/Inure/releases/latest)
[![](https://img.shields.io/badge/F--Droid-1976D2?logo=fdroid)](https://f-droid.org/en/packages/app.simple.inure/)

## Buy (Full Version)

[![](https://img.shields.io/badge/Full%20Unlocker%20(GumRoad)-Purchase-23a094?logo=gumroad&logoColor=white)](https://hamza417.gumroad.com/l/inure_unlocker/)
[![](https://img.shields.io/badge/Full%20Unlocker%20(Play%20Store)-Purchase-ea4335?logo=googleplay)](https://play.google.com/store/apps/details?id=app.simple.inureunlocker)
[![](https://img.shields.io/badge/Full%20Unlocker%20(GitHub%20Sponsors)-Purchase-ffffff?logo=github)](https://github.com/sponsors/Hamza417/sponsorships?sponsor=Hamza417&tier_id=262253)

## Featured

- [Android Weekly Issue #465](https://androidweekly.net/issues/issue-465)
- ["Inure, a beautifully animated Android App Manager." - Android Dev Notes](https://twitter.com/androiddevnotes/status/1389111968670179340)
- [Top 5 Android Apps of the Week - NextPit](https://www.nextpit.com/apps-of-the-week-51-2021)
- [5 Super Useful OPENSOURCE Apps for Android - TechDoc](https://youtu.be/vlf0jEFHR74)
- [Best Android Apps - February 2023 - HowToMen](https://youtu.be/kOrnfQOz4rg?t=112)
- [5 Magnificent Open Source Android Apps To Download Right NOW! - Anubhav Roy](https://youtu.be/kvM9hGJJ2wA?t=357)
- [Top Android Apps! (May 2023) - Sam Beckman](https://youtu.be/g6pMQAFfd3Q?t=220)

## About

Inure is an Android application package manager irrespective of whether they're installed or not, it
can scan through any app's internal components and modify them on the go. It also packs a nice
looking Terminal Emulator, Usage Stats, Split/APK Installer and various other tools and many of them
are waiting to be implemented as well. On top of that, Inure's all functionalities been made to
work with both Root and Shizuku modes.

Inure's development was started as an independent learning project which later has become one of the
most ambitious and intuitive Android apps developed by a single person and is based 100% on custom
UI APIs developed to be used only in this app with its own native theme engine, crash handler, image
renderer and a beautiful animation framework. There's also an implementation for PC like mouse hover
effects and click interactions for tablet and PC users.

Along with it own UI perks, Inure also supports dynamic Material You colors with split accent and
theme color modes.

Currently, the app is in stable beta testing stage. You can join app's early beta testing
from [Play Store](https://play.google.com/store/apps/details?id=app.simple.inure) and
its [Telegram Group](https://t.me/inure_app_manager) for development related updates.

## Development Status

### High priority features

- [x] Add basic Shizuku support.
- [x] Apps Backup feature.
- [x] Dedicated app installer.
- [x] External APK information.
- [x] Proper analytics panel.
- [x] App directories panel.
- [x] APK browser for apps that are not yet installed.
- [x] Modify Shared Prefs of other apps _(root)_.
- [x] Add battery optimisation manager for all apps.
- [x] Boot manager for all apps.
- [x] Add option to disable trackers.
- [ ] Manage system wide default apps.

### Low priority features

- [x] Dedicated TextEditor.
- [x] ImageViewer scalable zoom support.
- [ ] APK data extraction.

## Screenshots

### App's Interface

| ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/00.png) | ![02](fastlane/metadata/android/en-US/images/phoneScreenshots/01.png) | ![03](fastlane/metadata/android/en-US/images/phoneScreenshots/04.png) | 
|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|
|                                 0x01                                  |                                 0x02                                  |                                 0x03                                  |

| ![04](fastlane/metadata/android/en-US/images/phoneScreenshots/06.jpg) | ![15](fastlane/metadata/android/en-US/images/phoneScreenshots/15.png) | ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/07.png) |
|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|
|                                 0x04                                  |                                 0x05                                  |                                 0x06                                  |  

| ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/05.jpg) | ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/08.jpg) | ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/02.jpg) |
|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|
|                                 0x07                                  |                                 0x08                                  |                                 0x09                                  | 

| ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/09.jpg) | ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/10.jpg) | ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/11.jpg) |
|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|
|                                 0x00                                  |                                 0x0A                                  |                                 0x0B                                  |

| ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/12.jpg) | ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/13.png) | ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/03.png) | 
|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|
|                                 0x0C                                  |                                 0x0D                                  |                                 0x0E                                  |

| ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/14.png) | ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/16.png) | ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/21.jpg) |
|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|
|                                 0x0F                                  |                                 0x11                                  |                                 0x12                                  | 

| ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/17.png) | ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/18.png) | ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/19.png) |
|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|
|                                 0x13                                  |                                 0x14                                  |                                 0x15                                  | 

| ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/20.png) | ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/22.jpg) | ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/21.png) |
|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|
|                                 0x16                                  |                                 0x17                                  |                                 0x18                                  |

| ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/23.png) | ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/24.png) | ![01](fastlane/metadata/android/en-US/images/phoneScreenshots/25.png) |
|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|
|                                 0x19                                  |                                 0x1A                                  |                                 0x1B                                  |

## Behind The Scenes

|             ![01](./assets/01.jpg)              |
|:-----------------------------------------------:|
|   Designing of interface skeletons for Inure    |

|        ![01](./assets/inure_music.png)        |
|:---------------------------------------------:|
| Audio Player interface design (later removed) |

|     ![01](./assets/inure_batch.png)     |
|:---------------------------------------:|
| Presentation design for Batch interface |

## Contribute

#### Developers

Inure's repo doesn't require any special setup, clone/fork the repo and run
in [Android Studio](https://developer.android.com/studio) and let the initial
setup finish automatically and you'll be good to go.

#### Not a developer?

You can take participation in app's translation on [Crowdin](https://crowdin.com/project/inure)
and watch Inure work in your language and make the app more user friendly to
everyone speaking your tongue... 😎😎

Alternatively, you can also edit/upload your locale's strings
from `app/src/main/res/values-locale-code` directory.

#### Want to show you were here?

You cannot do the above still wanna show your support? hit the star 🌟 and let me know you were here
and appreciate the project.. 😄

## License

**Inure App Manager** Copyright © 2022 - Hamza Rizwan

**Inure App Manager** is released as open source software under
the [GPL v3](https://opensource.org/licenses/gpl-3.0.html)
license, see the [LICENSE](./LICENSE) file in the project root for the full license text.


[tutorial]: assets/lv_0_20230502125528.gif
