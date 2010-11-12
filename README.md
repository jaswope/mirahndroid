# Mirahndroid

This project (tentatively called Mirahndroid) generates an Android app that's ready for you to write in Mirah.

## Getting Started

Before you use it, you'll need to install all of the things that you'd need to compile an Android app--the JDK and the Android SDK. Obviously, you'll need mirah as well, and mirahc will have to be in your path.

## Usage

Create an app using `mirahndroid create` (use `mirahndroid help create` to see the params).

You can compile your app by running `ant debug` in the root of your app.

Install the and then install it by running `adb install -r bin/YourAppName-debug.apk`