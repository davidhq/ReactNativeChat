# React Native demo

Based on a workshop at [Reactive 2015 conference](https://reactive2015.com) in Bratislava given by [STRV](http://www.strv.com), uses [Firebase](https://www.firebase.com) as a backend.
You can also check the [original repo](https://github.com/strvcom/React-Meetup) and here is an interesting tool they used while giving a workhop: [Live Coding](https://github.com/frantic/live-coding).

Totally unrelated: [Silicon Valley Insights - STRV](http://www.strv.com/silicon-valley-insights).

## Screen

![Screen](http://f.cl.ly/items/323P3l323P2k252c3L1y/chat.png)

## Instructions

Install XCode, Node.js 4.0+ and npm, then

    npm install -g react-native-cli
    brew install watchman
    brew install flow

and:

    git clone git@github.com:davidhq/ReactNativeChat.git
    cd ReactNativeChat
    npm install
    open ios/Chat.xcodeproj

Select iPhone 6 or 6S (not 6 Plus) to get normal sized emulator.

Press Run icon on the toolbar.

Press `⌘D` in the emulator and *Enable Live Reloading*

Open the project in SublimeText and edit files in app folder, as you save, the emulator will update.

## Starting a fresh project

How to start a project:

    react-native init AwesomeProject

Note: if you add some npm module, it might be neccessary to close *React Packager* terminal window (it will reopen on run)...

## Debugging

`⌘D` in emulator, then select *Enable Chrome Debugging*

Use

    console.log("something")


And observe the value in Chrome Dev Tools console...

And also install [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en)

## Android

    brew install android-sdk
    cd ReactNativeChat
    react-native run-android

## Resources

Play with copy/pasting code from [Component docs](http://facebook.github.io/react-native/docs/getting-started.html) (select in left sidebar).


