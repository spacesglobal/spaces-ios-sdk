# Spaces SDK for iOS
This library allows you to integrate Spaces into your iOS app.

Learn more about the provided samples, documentation, integrating the SDK into your app, accessing source code, and more at https://developers.spacesnet.com/docs/ios

## Features
* Login
* Sharing
* Graph API

## Usage
Spaces SDKs are broken up into separate modules as shown above. To ensure the most optimized use of space only install the modules that you intend to use. To get started, see the Installation section below.

Any Spaces SDK initialization must occur only in the main process of the app. Use of Spaces SDK in processes other than the main process is not supported and will likely cause problems.

## Installation
Spaces SDKs are published to Maven as independent modules. To utilize a feature listed above include the appropriate dependency (or dependencies) listed below in your app/build.gradle file.
