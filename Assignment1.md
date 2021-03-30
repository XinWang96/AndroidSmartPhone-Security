# 1. Build an Android app that consists of 4 activities to demonstrate the usage of different types of app components

### MainActivity 
Create buttons to go to the other three activities

Show the current time in the UI, no need to continuously update the time


### Broadcast Activity
Create a broadcast receiver that listens to a customized action. You may use any string for your action, such as “com.example.homework”

When the intent is received, the receiver will show the current time and message embedded in the intent

You may use a text view to show the message or a toast text

Create the UI to send the broadcast intent and show the message sent to the receiver

### Service Activity
Create a service that can report the current time in the format HH:mm

You may bind to the service and retrieve the time from the service, or let the service continuously update a text view

Create the UI to start and stop the service

### Content Provider Activity 
Create a content provider for contacts, including id, name, phone

Create UI to insert contacts and clear contacts

To show contacts, use a listview or a table

# 2.Build the APK and upload the solution as a single zip file
In Android Studio, click the Build in the menu, and then select build APK.

After the build is finished successfully, a notification will pop up in the lower right corner. Click the notification and you will be redirected to the folder where the built APK is.

Rename your APK file to contain your name

Zip your source codes (the whole project is fine) and the APK file and upload to canvas
