### Debugging WebViews

Install TrustWallet app from [TrustWallet](https://trustwalletapp.com) ([latest release](https://s3-us-east-2.amazonaws.com/trustandroidapk/builds/latest_release.apk)) to a device.

##### Enable developer options and debugging on the device.
On Android 4.1 and lower, the Developer options screen is available by default. On Android 4.2 and higher, you must enable this screen as follows:
1. Open the Settings app.
2. (Only on Android 8.0 or higher) Select System.
3. Scroll to the bottom and select About phone.
4. Scroll to the bottom and tap Build number 7 times.
5. Return to the previous screen to find Developer options near the bottom.
At the top of the Developer options screen, toggle the options to on.
Next, you should scroll down a little and enable USB debugging. This allows Android Studio and other SDK tools to recognize your device when connected via USB, so you can use the debugger and other tools.

On a development computer, install [android comand line tools](https://developer.android.com/studio/#downloads).
Connect the device to the computer. Go to the Chrome browser and open chrome://inspect/#devices and select your device, page and tap by inspect.
