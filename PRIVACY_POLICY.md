## The Best Part Privacy Policy

Thanks for checking out The Best Part!

This app is solely developed by Sean Driscoll.

The Best Part does not collect or share any personal information. All data created by the user is stored on your device only, and can be erased by clearing the app's data or uninstalling.

All song data displayed by The Best Part comes directly from Spotify and is never modified or stored locally.

The only data this app stores are the timestamps created by the user.

### Explanation of permissions requested in the app

The list of permissions required by the app:

```
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />

<uses-permission android:name="android.permission.INTERNET" />

<uses-permission android:name="android.permission.BLUETOOTH" />

<uses-permission android:name="android.permission.FOREGROUND_SERVICE" />
```

<br/>

| Permission | Why it is required |
| :---: | --- |
| `android.permission.READ_EXTERNAL_STORAGE` | The only sensitive permission that the app requests. This is required for the app to interact with Spotify. |
| `android.permission.INTERNET` | Required to authenticate user's Spotify account. |
| `android.permission.BLUETOOTH` | Required to allow Bluetooth devices to control playback. |
| `android.permission.FOREGROUND_SERVICE` | Enables the app to create foreground services that will listen for media buttons while the app is not in focus. |

 <hr style="border:1px solid gray">

If you find any issues with my implementation, or have any questions regarding how the app handles data, please send me an email and I will do my best to help.

Sean Driscoll  
seandriscolldev@gmail.com
