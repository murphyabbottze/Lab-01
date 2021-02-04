<<<<<<< HEAD
# github-workflow assignment

## DUE: 21 Jan 2021

## Instructions:
***NOTE:***This assignment has a dual purpose. 1. To test the Git workflow procedures for completing assignments this semester and 2. To ensure you have Android Studio installed correctly.

### TODO:
1. Fork the github-workflow repository into your Github account.
1. Install Android Studio for your OS. If you have issues, please post questions on Slack.
2. Create a simple "Hello World" Android application.
3. Using the Android Virtual Device, create a virtual device.
4. Start the virtual device and run the Application.
5. Make the project managed under Git.
6. Add YOUR repository as a remote for your Android project.
7. Pull from the remote to sync.
8. Commit and Push your android code.
9. Verify files were uploaded to your GitHub account.
 
 ***Note:*** Any issues you have with either the GitHub steps or Java questions should be asked publically in Slack. If you have a question, chances are someone else does also. If you see someone has posted a question on Slack and you know the answer, please chime in and answer. This might seem rough at the beginning, but I promise it will get easier.
 
 ## Challenge: Create an SSH key and set up Github to use it (SSH rather than HTTPS). ##
 This will remove you having to enter your username/password for every push.
=======
# Lab-01
Instructions for Inclass Lab 01

## Problem
This lab will have you creating a simple countdown timer. Android comes with a built-in class for constructing **CountDownTimers**.

## Purpose
This lab will introduce some basic features that are not present in a basic HelloWorld project, such as TableLayout, TextView items, Buttons, and OnClickListeners. Use of the **values** resource files will also be demonstrated.  

## Steps
* Open Android Studio and create a basic project. Name the project whatever you like, **SimpleTimer** is a good candidate. Choose **API 23: Android 6.0 (Marshmallow)**. Next choose just an **Empty Activity**.
* Edit the **MainActivity.java** file to implement the **OnClickListener** interface. Implement the required methods. (NOTE: This can easily be done by clicking Code -> Implement then choose the method for OnClickListner)
* Create a subclass of **CountDownTimer**. This will be a public class **inside** of ActivityMain class. This class class does not allow for default constructor. You will need to implement a constructor (and call the super constructor) that takes in two arguments **CountDownTimer(long millisInFuture, long countDownInterval)**. (NOTE: This can easily done by clicking Code -> Generate -> Constructor). You will also need to implement a couple of methods. This can be accomplished in the same fashion as the privious step.
* Fill in methods with code provided in java.txt. Fix any errors that may occur, ie variable names are different.
* Replace all of the XML inside of res/layout/activity_main.xml with code from the view.xml file in the lab repository.
* Create a virtual device (or use a real device if you are able) to run the lab on. This virtual device will need to have API 23 or greater.
* AFter you have code running on a device properly, refactor "hard coded" strings to be read from res/values/strings.xml
* Share, commit, and push lab to your GitHub account
>>>>>>> ba5658729c29ae892edb839e29de9d613c72f804
