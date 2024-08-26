## LearnX: Privacy policy

Welcome to the LearnX app for Android!

This is an closed source Android app developed by Azezn Studio.

As an avid Android user myself, I take privacy very seriously.
I know how frustrating it is when apps collect your data without your knowledge.

### Data collected by the app

The app collects information about your device like name and os version for logging history which is sent to the server. All data (app preferences (like theme) and alarms) created by the you (the user) is stored locally in your device only, and can be simply erased by clearing the app's data or uninstalling it. There is Notification Data that is stored in  Firebase which allows to send notification etc.


| Permission | Why it is required |
| :---: | --- |
| `android.permission.ACCESS_NETWORK_STATE` | This is a must permission for the app work properly. If not allowed the app won't work. It is used to fetch data like Exams, Profile, Fees etc |
| `android.permission.INTERNET` | It is used to check the internet connection |
| `android.permission.ACCESS_NOTIFICATION_POLICY` | Allows the app to change the Do Not Disturb settings of the device to make sure that an notification rings. It is an optional permission. If not granted, the app will respect the DND settings of your device and cannot recieve notifications |
| `android.permission.FOREGROUND_SERVICE` | Required to the show notification and then proccess the information |
| `android.permission.WAKE_LOCK`| Required to the show notification. Automatically granted by the system; cannot be revoked by user. |

 <hr style="border:1px solid gray">

If you find any security vulnerability that has been inadvertently caused by me, or have any question regarding how the app protectes your privacy, please send me an email or post a discussion on GitHub, and I will surely try to fix it/help you.

Yours sincerely,  
Rayyan Zahid  
Rahim Yar Khan, Pakistan.  
azezn786@gmail.com
