# HAT Starter app for Android
[View HAT Android's documentation][1] | [Open a new issue on Github][2]

A simple application showcasing how you can work with the `HAT` in a
mobile app, including log in and sign up. The purpose of the app is to showcase
log in, registration and simple read/write operations. Also you can use it to
build on it your own application
​
## Getting Started
​
You can start by either downloading the project or cloning it.
​
## Prerequisites
```
Android Studio 3.5.0
Kotlin 1.3.50
```
## Configuration
You can change the configuration with your application details.
```
object AppConfig {
    val applicationId = "testhatapp" // your application ID.
    val namespace = "testhatapp" // application's namespace.
    val scope = "testing" // the scope where to store the sample's data.
    val authBaseUrl = "https://hatters.hubofallthings.com" // your base Url for the HAT's look up
    val signupBaseUrl = "https://hatters.hubofallthings.com" // your base Url for the HAT's validations
}
```

## License
Copyright (C) 2019 Dataswift Ltd

This Source Code Form is subject to the terms of the Mozilla Public
License, v. 2.0. If a copy of the MPL was not distributed with this
file, You can obtain one at http://mozilla.org/MPL/2.0/

[1]: https://developers.hubofallthings.com/guides/android-guide
[2]: https://github.com/Hub-of-all-Things/hat-starter-app-android/issues
