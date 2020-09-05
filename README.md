# First Tutorial
This is your first tutorial for building an iOS app.
## IDE Setup
Download and install the Xcode IDE via the App Store:
https://apps.apple.com/us/app/xcode/id497799835?mt=12
> When you try to open Xcode, you may be prompted to "Install Additional Components" If that is the case, click "Install"

## Creating a new project
When you first open Xcode, you will see the menu below:

<img src="https://github.com/SiGMobileUIUC/HelloWorldiOS/blob/master/Resources/Images/XcodeOpen.png" width="400">

From here, you should select `Create a new Xcode Project`. Next, a dropdown menu will appear, allowing you to choose what kind of app you want. For now, let's choose `Single View Application`

<img src="https://github.com/SiGMobileUIUC/HelloWorldiOS/blob/master/Resources/Images/SelectAppType.png" width="400">

Next, we'll be given options for how we want this app to be configured. Set up your configuration to match this one:

<img src="https://github.com/SiGMobileUIUC/HelloWorldiOS/blob/master/Resources/Images/AppConfig.png" width="400">

[OPTIONAL] This is what each field is for:
* Product name: The name of your app. This will be the name users see
* Team: If you are working with/for an Apple Developer, this dropdown will "sign" this app with their information, allowing it to be published to the app store
* Organization name: This identifies who is working on this app for the app store
* Organization identifier: A unique identifier for each app posted to the app store. This is typically also where users can get more information about the app. Notice that it is in reverse www notation. For example, acm.illinois.edu is edu.illinois.acm in this scenario
* Language: If for some reason you *really* want to work in Objective-C, this option allows you to do so. Keep in mind these tutorials are for Swift
* User Interface: Apple recently released SwiftUI in 2019. Since then, you've been able to choose between the old way of building user interfaces (storyboards) and the new way (SwiftUI). Our tutorials are for SwiftUI, but many older apps still use storboards
* Use Core Data/Use CloudKit: This allows your app to store data in a local (or cloud-based) database for users.
* Include Unit Tests: Basically CS126 in a nutshell
* Include UI Tests: Unit tests for the UI. This allows you to ensure users can press buttons and that elements are visible for all devices

Finally, you'll be prompted with where to save your project. Obviously, this is up to you. Also during this step, there's a checkbox to initialize a git repository. If you know how git works, it is recommended you enable it. If not, ask someone! (or look at the tutorial) Git is a fantastic tool.

## Setting up your workspace
When you first open up your project, Xcode should look something like this:

<img src="https://github.com/SiGMobileUIUC/HelloWorldiOS/blob/master/Resources/Images/MainView.png" width="400">
