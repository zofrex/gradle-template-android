# Android Gradle Project Template

A minimal barebones template for starting a new Android application using the new build tool.

## What

A Gradle-based Android project configured to use the latest versions of the build tools. The project is configured as a single-project build, using the latest conventions for filesystem layout.

## Why

The projects generated by Android Studio have a bit more cruft and are more complicated than I usually need for a simple app. I wanted to create a template from which I could start new projects, and figured it might be helpful for other people too.

## How

You can quickly get started by [downloading this project as a zipfile](https://github.com/zofrex/gradle-template-android/archive/master.zip). You can use it as a basis for a new project, and it comes ready to be imported into Android Studio (should work in 0.4.\* and 0.5.\*).

This is all under the ISC license, which should give you enough freedom to use this as you wish - as a starting point, copy-pasting bits from it, or merely a reference.

## Beginner's Guide

As your first steps, change the package and app name in the manifest. Next you'll probably want to create a java package in src/main/java, and create an Activity class. Any resources your app needs can be put in src/main/res. Lastly you might want to change or add some dependencies in build.gradle.

## See also

If you want Robolectric support, [there's a project template for that, too](https://github.com/zofrex/gradle-template-android-robolectric).
