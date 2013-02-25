# Nooku Chrome App

Sample that shows how to use the [webview tag](http://developer.chrome.com/trunk/apps/app_external.html#webview) to create a native looking app for your Nooku powered projects.

![Nooku Chrome App](https://raw.github.com/nooku/nooku-chrome-app/master/screenshots/1280x800.png)

The app's main window contains a `<webview>` that is sized to fit (via the `width` and `height` attributes) and contains an hardcoded URL to our demo installation of Nooku Server at [http://demo.nooku.org/administrator](http://demo.nooku.org/administrator).

`<webview>` is the preferred way for you to load web content into your app. It runs in a separate process and has its own storage, ensuring the security and reliability of your application.

## Requirements

* Tested on Chrome v25.0.1364.99

Tip: Checkout [Chromatic](http://mrgeckosmedia.com/applications/info/Chromatic), an easy way to install and update [Chromium](http://www.chromium.org/getting-involved/download-chromium).


## Installation

Simply install the app from the [Chrome App Store](https://chrome.google.com/webstore/detail/nooku/pbkhaabnfdganaandeonchcbjcbbohdd).

## Development

For more information, check the excellent [Create Your First App](http://developer.chrome.com/trunk/apps/first_app.html) tutorial and you'll be up and running in seconds.

## Credits

This App is built in just over a couple of minutes by hacking the [Browser sample](http://developer.chrome.com/apps/samples.html) provided by our friends at [Google Developers](http://developer.chrome.com/trunk/apps/about_apps.html).
