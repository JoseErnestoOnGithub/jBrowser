jBrowser
=============

<p align="center">
  <img src="https://raw.githubusercontent.com/JoseErnestoOnGithub/curly-potato/main/Dtafalonso-Android-Lollipop-Browser.512.png" />
</p>

jBrowser is a mod of Split Browser that is a minimalistic, ultra-lightweight and open-source web browser for desktop, based on [WebKit](https://webkit.org/) (provided by [Playwright](https://playwright.dev/)), [Ultralight](https://ultralig.ht/) and a native [webview](https://webview.dev/) (WebKit on macOS, WebKitGTK on Linux, Microsoft Edge WebView2 on Windows), with split screen functionality. It was originally made with [Qt](https://www.qt.io/), but now it uses Qt (browser), Python (launcher) and HTML, CSS, JavaScript (documentation).


Every variant of jBrowser (WebKit, Ultralight and native WebView) uses less than 100 MB (it will increase to 1 GB significantly, if many tabs are open) of RAM to show the homepage, which is much less than Chrome, Firefox, Edge, etc. This causes the browser to run as fast as possible. My PC currently has 8 GB of RAM. Also, jBrowser allows you to show webpages side-by-side as tiles by dragging &amp; dropping tabs.

See the RAM usage of all 3 variants showing the DuckDuckGo home page:

![Original Split Browser RAM usage](https://i.imgur.com/LbHUr1N.png)

Currently, jBrowser is in the alpha stage. Other features like bookmarks, history, extensions, adblock and advanced settings are not implemented.

## Download

You'll need to compile the binaries manually using Qt 5.14, MSVC 2017 and qmake.

## Build

jBrowser is being developed on Windows 11 using Qt 5.14, MSVC 2017 and qmake. Still, it also runs on Linux and macOS, provided that you have downloaded the latest [WebKitGTK](https://webkitgtk.org/), [Ultralight SDK](https://github.com/ultralight-ux/Ultralight#eyes-getting-the-latest-sdk) or [Playwright WebKit binaries](https://github.com/microsoft/playwright) for your platform. Extract them to folders: `../ultralight` and `../webkit` relative to `splitbrowser`, open this project in Qt Creator, set the engine in `splitbrowser.pro` and run it.

jBrowser is currently untested on Linux & macOS, as i do not have a Linux or macOS development environment set up yet.


## Contribute

This is a fork. You won't be able to contribute in this repository.

## License

jBrowser is developed in the Public Domain.

Ultralight &copy; 2022 Ultralight Inc. under [Ultralight Free License Agreement](https://github.com/ultralight-ux/Ultralight/blob/master/license/LICENSE.txt).

Playwright &copy; 2022 Microsoft Corporation under Apache 2.0 License.

Webview &copy; 2022 Serge Zaitsev et. al. under MIT license.

Copyright &copy; 2010-2023 Freepik Company S.L. All rights reserved.

&copy; 2023 IconArchive.com

## Copyright?

jBrowser is currently ineligible for copyright, meaning that copyright cannot be applied to the browser. This forces me to develop the mod in the Public Domain, with no signs of copyright eligibility.
