# Windows Subsystem for Android:tm: Developers

Windows Subsystem for Android enables your Windows 11 device to run Android applications that are available in the Amazon Appstore.

## What is this repository for?

|:bug: [File a developer bug](https://github.com/microsoft/WSA/issues/new?assignees=&labels=triage-needed%2Cbug&template=bug_report.yml) | :gear: [Submit a feature request](https://github.com/microsoft/WSA/issues/new?assignees=&labels=triage-needed%2Cfeature-request&template=feature_request.yml) | :books: [Report a documentation issue](https://github.com/microsoft/WSA/issues/new?assignees=&labels=Issue-Docs%2CTriage-Needed&template=documentation_issue.yml) | :speaking_head: [Discuss with the community](https://github.com/microsoft/WSA/discussions)|
|:--:|:--:|:--:|:--:|
|Report **developer** issues with apps and features on Windows Subsystem for Android. | Submit a **developer** feature request for the Windows Subsystem for Android | Report issues with our developer documentation | Discuss Windows Subsystem for Android with other developers

> This repository is not for end-user related issues for apps or the Amazon Appstore. Use the Windows Feedback Hub for end-user related issues.

## Repository Interaction

Your best method of filing bugs and feature requests directly with the subsystem team is through issues! Please follow the **[contributing best practices](CONTRIBUTING.md)**. Before filing an issue, please ensure it hasn't already been answered in our [Frequently Asked Questions](https://github.com/microsoft/WSA/discussions/51), an existing issue, or [developer documentation](https://docs.microsoft.com/windows/android/wsa)

### File an Issue

![Bugs](https://img.shields.io/github/issues/microsoft/wsa/bug?label=Bugs) ![Feature Requests](https://img.shields.io/github/issues/microsoft/wsa/feature-request?color=blue&label=Feature%20Requests)

You can file a bug, feature request or documentation issue under **[Issues](https://github.com/microsoft/WSA/issues)**. Please avoid filing duplicates of open/closed items. If you're filing a bug, always include the version number of Windows Subsystem for Android in the **version number** field of the issue.

#### Milestones (build number)

**[Milestones](https://github.com/microsoft/WSA/milestones?direction=asc&sort=title&state=open)** are used by the Microsoft team to track what subsystem version a bug or feature request is targeting. You can find your version number in the Windows Subsystem for Android **Settings app**, under the **About** section.

|[Previous Milestones](https://github.com/microsoft/WSA/milestones?state=closed) | [Current Milestones](https://github.com/microsoft/WSA/milestones?direction=asc&sort=title&state=open) | [Future Release](https://github.com/microsoft/WSA/milestone/8)
|:--:|:--:|:--:|
All previous builds of the subsystem and past bugs/feature requests can be found here | The current builds of the subsystem. This is where **current bugs** will be found. This includes the generally available build, as well as the preview builds of the subsystem. | Future build(s) of the subsystem. All **feature requests** will be associated with this milestone.

### Discuss the Subsystem and FAQ

For **developer discussions** around Windows Subsystem for Android, please use **[Discussions](https://github.com/microsoft/WSA/discussions)**.
 The internal Microsoft team will post [Announcements](https://github.com/microsoft/WSA/discussions/categories/announcements) here upon new releases and major updates relevant to developers. You can find the [Frequently Asked Questions (FAQ)](https://github.com/microsoft/WSA/discussions/51) here as well.

For all general **(non-developer)** subsystem questions, please visit [Microsoft Answers](https://learn.microsoft.com/en-us/answers/topics/windows-subsystem-for-android.html). For all Amazon Appstore or app-specific questions, please visit [Amazon's developer page](https://developer.amazon.com/apps-and-games/appstore-on-windows-11).

## Roadmap

Here's a snippet of what's currently :white_check_mark: available or :x: unavailable and what we have on our radar for the :fast_forward:future:

Current Features| Future Roadmap |
|:--|:--|
:x: Android Widgets <br> :white_check_mark: Certain Audio Codecs <br> :white_check_mark: Camera (front + back)	<br> :white_check_mark: ClearKey DRM or MPEG-DASH content <br> :white_check_mark: CTS/VTS <br> :x: Direct Bluetooth access (and BLE) <br> :white_check_mark: Ethernet <br> :x: File Backup/restore <br> :x: File transfer <br> :white_check_mark: Freeform window management <br> :white_check_mark: Gamepad <br> :x: Hardware DRM <br> :white_check_mark: Location + GPS <br> :white_check_mark: Microphone <br> :white_check_mark: Multi-monitor/secondary display <br> :white_check_mark: Picture-in-picture <br> :white_check_mark: Print <br> :x: Quick tiles <br> :white_check_mark: Software DRM (Widevine L3 support) <br> :white_check_mark: Touch/Multitouch <br> :x: USB <br> :white_check_mark: Certain Video Decoders and Encoders <br> :white_check_mark: WebView <br> :white_check_mark: Wi-Fi <br> :white_check_mark: Window orientation <br> :white_check_mark: Android 13 | :fast_forward: File transfer <br> :fast_forward: Shortcuts <br> :fast_forward: Local network access by default

## Publishing your app for Windows

To publish your app for Windows Subsystem for Android to the Microsoft Store, you must submit it to the Amazon Appstore. Please visit **[Amazon's portal for the Amazon Appstore on Windows 11](https://developer.amazon.com/apps-and-games/appstore-on-windows-11)**.

## Get Early Access to Builds

1. You can get early access to new features on Windows Subsystem for Android, the Amazon Appstore **and Windows 11** by joining the **[Windows Insider Program!](https://insider.windows.com/getting-started)**

2. The Windows Subsystem for Android [Preview Program](https://learn.microsoft.com/en-us/windows/android/wsa/preview-program) allows you to receive early-preview builds of **just** the Windows Subsystem for Android and Amazon Appstore. All you have to do is sign up with your MSA (the email you use in the Microsoft Store). **[Sign up now!](https://forms.office.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbRxmldwLByptEu0fsWe3hlg1UNjYyVlFWV0UwTFk4U1dUQktOMzIyWFE4Qy4u)**

## Documentation

- [Developer Docs](https://docs.microsoft.com/windows/android/wsa) - Microsoft developer documentation covering a wide range of topics related to the subsystem and app-development.
  - [Input and window management for your app](https://docs.microsoft.com/windows/android/wsa#input-compatibility-considerations-for-windows-devices) - Information on how to handle keyboard/mouse input and window management.
  - [Test and debug your app](https://docs.microsoft.com/windows/android/wsa#test-and-debug) - Learn about connecting to the subsystem using adb and installing/debugging your app.
- [Consumer Docs](https://support.microsoft.com/windows/abed2335-81bf-490a-92e5-fe01b66e5c48) - Microsoft documentation on the end-user experience with the subystem.

## Code of Conduct  

This project has adopted the [Microsoft Open Source Code of Conduct][oss-conduct-code].

[oss-conduct-code]: CODE_OF_CONDUCT.md

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow Microsoft’s Trademark & Brand Guidelines. Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship. Any use of third-party trademarks or logos are subject to those third-party’s policies.

*Android is a trademark of Google LLC. Amazon and all related marks are trademarks of Amazon.com, Inc., or its affiliates.*
