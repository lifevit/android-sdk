# LifeVit SDK for Android

LifeVit SDK is an Android library used to easily communicate with LifeVit's bluetooth wearables and devices.

## Installation

In your main project's gradle, add our maven repository url:

```
allprojects {
    repositories {
        [...]
        maven {
            url "https://raw.githubusercontent.com/lifevit/android-sdk/master"
        }
    }
}
```

Then you can add the library implementation to the gradle of any module that you want:

```
dependencies {
    [...]
    implementation 'es.lifevit:lifevit-sdk:2.1.0'
    [...]
}
```


## Usage

You have a complete documentation of the library and all its devices in:

https://developers.lifevit.es/


## Example project

You can download a sample project to check how to import and use the library, and test devices quickly:

https://github.com/lifevit/android-app

