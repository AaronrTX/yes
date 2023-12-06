# seeddemo
Project 1 - Seed Health App

java classes are HelperClass LoginActivity ProfileActivity ProfileEditActivity SignupActivity

for xml files that are drawable (res - drawable) baseline_email_24.xml baseline_lock_24.xml baseline_person_24.xml baseline_person_pin_24.xml ic_angry_farmer.jpg ic_default_profile.jpeg ic_launcher_background.xml ic_launcher_foreguround.xml lavender_border.xml white_background.xml

for xml files that are layout (res-layout) activity_login.xml activity_profile.xml activity_profile_edit.xml activity_signup.xml

for xml files that are colors (res - values) colors.xml

Add firebase to the project

Inside Android Studio Go To Tools - Firebase - Realtime Database

//It will open up your brower to add database Go to add project - then keep continuing - Make sure to click connect at the end

//Go back to android studio

Click on 'Add the Firebase Database SDK to your app'

Click add realtime database

//Go back to your browser where you have firebase console open

Go to build (on the left side) - Realtime Database - create Database - Next - Click on test mode - enable

To run, if you get an error of something in drawable requires new version of comileSdk = 34

Go to Gradie Scripts - build.gradle.kts (Module :app) Go to compileSdk and change it from 33 to 34 Save and sync it


//Files that i have updated is 
colors.xml
ProfileEditActivity
SignupActivity
activity_profile_edit.xml
