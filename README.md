WebViewMarker
=============

This library provides text selection support for Android WebView. The core logic is the same as [BTAndroidWebViewSelection](https://github.com/btate/BTAndroidWebViewSelection).

## Features
- More modular (not inherit webview)
- Not depend quick action lib (for actionbar support)
- Mimic ICS native text selection handlers
- Smart tap selection for CJK characters

## Supported Android Versions
Tested on API 8-21 (Android 2.2-5.0.1).

## How to use
See `samples/demos` directory.

##How to add to Gradle
Add the following to your build file:
dependencies {
    //other dependencies also go here
    compile 'com.github.naoak:WebViewMarker:v0.1.3'
}
repositories {
    //other repositories
    maven { url "https://jitpack.io" }
}
Then just sync Gradle with the project

## Included Libraries
This project uses the following libraries.
- [rangy](https://github.com/timdown/rangy) by Tim Down
- [drag and drop](https://blahti.wordpress.com/2011/01/17/moving-views-part-2/) library by Bill Lahti

## License
MIT License.
