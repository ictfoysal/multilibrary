# MultiLibrary

[![Release](https://img.shields.io/github/v/release/ictfoysal/multilibrary)](https://github.com/ictfoysal/multilibrary/releases)
[![Build Status](https://img.shields.io/github/actions/workflow/status/ictfoysal/multilibrary/build.yml)](https://github.com/ictfoysal/multilibrary/actions)
[![License](https://img.shields.io/github/license/ictfoysal/multilibrary)](LICENSE)

MultiLibrary is a versatile and easy-to-use Android library that simplifies common tasks and accelerates application development. It provides a collection of reusable components and utilities designed to help developers write clean and efficient code with minimal effort.

## Features

- **Networking:** Simplified API calls and response handling.
- **Database Management:** Easy integration with SQLite and Room databases.
- **UI Components:** Pre-built customizable views and widgets.
- **Utilities:** Handy tools for common operations like image loading, caching, and more.
- **Compatibility:** Supports a wide range of Android versions and devices.

## Installation

MultiLibrary is available through [JitPack](https://jitpack.io/#ictfoysal/multilibrary/6.0). To include it in your project, follow these steps:

### Step 1: Add JitPack Repository

**For Gradle (Project-level `build.gradle`):**

# MultiLibrary

**MultiLibrary** is a versatile Android library designed to simplify various common tasks in Android development. This library provides a set of tools and utilities that can help streamline your app's development process.

## Getting Started

To include **MultiLibrary** in your Android project, follow these steps:

### Step 1: Add the JitPack Repository and Dependency

Add the following code to your app's `build.gradle` file:

```gradle
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        google()
        maven { url = uri("https://jitpack.io") }
        mavenCentral()
    }
}

dependencies {
    implementation ("com.github.ictfoysal:multilibrary:6.0")
}

# Use Slider Xml Like this


<com.library.foysaltech.smarteist.autoimageslider.SliderView
        android:id="@+id/imageSlider"
        android:layout_width="match_parent"
        android:layout_height="140dp"
        android:layout_below="@+id/toolbar"
        android:layout_marginStart="@dimen/_15sdp"
        android:layout_marginTop="@dimen/_10sdp"
        android:layout_marginEnd="@dimen/_15sdp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:sliderAnimationDuration="600"
        app:sliderAutoCycleDirection="back_and_forth"
        app:sliderAutoCycleEnabled="true"
        app:sliderIndicatorAnimationDuration="600"
        app:sliderIndicatorGravity="center_horizontal|bottom"
        app:sliderIndicatorMargin="15dp"
        app:sliderIndicatorOrientation="horizontal"
        app:sliderIndicatorPadding="3dp"
        app:sliderIndicatorRadius="2dp"
        app:sliderIndicatorUnselectedColor="#ECEFF4"
        app:sliderScrollTimeInSec="1"
        app:sliderStartAutoCycle="true" />

