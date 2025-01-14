# Class Companion iOS App

Website: [http://www.class-companion.com](http://www.class-companion.com)

Web app GitHub: [https://github.com/MysticalCabbage/class-companion](https://github.com/MysticalCabbage/class-companion)

This is a native iOS app for the teacher to use while teaching using Class Companion. The app syncs in real-time via Firebase with the web app for cross-platform communication.

## Table of Contents

1. [Features](#features)
1. [Team](#team)
1. [Mobile](#mobile)
1. [Installing Dependencies](#installing-dependencies)
1. [Technologies](#technologies)


## Features
 - Add/Remove students and classes
 - Record and track daily attendance
 - Add/remove students and classes
 - Arrange students into groups
 - Randomly and manually select students
 - Assign student behavior points
 

## Team

The Class Companion mobile iOS app is a solo project I completed inside of the larger team where we built [Class Companion](https://github.com/MysticalCabbage/class-companion). 

## Development

### Installing Dependencies

```
pod install
```
```
open class-companion.xcworkspace
```

If the project file is opened through Xcode, there could be potential issues with the Firebase library. It's necessary to open the .xcworkspace file instead of the .xcodeproj file. If there are any issues, follow the instructions on the Firebase site: [https://www.firebase.com/docs/ios/quickstart.html](https://www.firebase.com/docs/ios/quickstart.html)

## Technologies
 - Swift
 - Xcode
 - Firebase iOS Library
