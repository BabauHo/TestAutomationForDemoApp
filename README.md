# TestAutomationForDemoApp
Automatic test script made by Robotframework 

Follow the requirement below to set up your environment on Windows.

Requirement
1. Python 2.7
2. Fiddler 4
3. Android Studio or you can just download Android platform tool (adb)
3. Appium 1.6.1
4. Robotframework 3
  by "pip install robotframework"
5. Robotframework AppiumLibrary 1.4.6 
  by "pip install robotframework-appiumlibrary"


How it work?

1. Copy "CustomRules.js" to ${your_Fiddler_path}/Scripts/ then overwrite it.
2. Make sure that your android device is connected to your computer and adb commands are workable.
3. Launch Appium server and start it.
4. Launch Fiddler and disabling the capture mode.
5. Let your android device be connected to your Fiddler proxy server. 
6. Use the following command "robot in2wowdemo.txt" to start the test script.


