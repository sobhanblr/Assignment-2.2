# Assignment-2.2
Acadgild Android Assignment 2.2

Android Assignment 2.2

Problem Statement
Change the launcher icon and app name.

Expected Output

Changed app name and icon should be reflected in the AVD.

Project has been linked through git repository AVD Emulator Configuration Nexus 6 API 25 - Android 7.1.1 (Target) Screen Shot of Output is attached in repository Source Code of the Android App is uploaded in repository


APP NAME & ICON HAS BEEN CHANGED

Problem Solution
a. Edited AndroidManifest.xml in android Studio and following changes has been made

<application <!-- CHANGE THE ic_launcher to the name you selected in step 3 shown above --> 

android:icon="@drawable/ic_launcher" 
<!-- CHANGE THIS TO GIVE A NEW NAME TO THE APP --> 
android:label="NEW APP NAME" > .... 
</application>

b. Alternatively instead of hard coding the app name, an entry has been created for it in the strings.xml. e.g.

<string name="app_name">NEW APP NAME</string>

c. and passed it to the android:label="" attribute show above:

android:label="@string/app_name"


APP SOURCE CODE & SCREEN SHOTS ENCLOSED
