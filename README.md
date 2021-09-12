# ECE 1778 Track-A-Mole Project

<p align="center">
  <img src="pictures/mole.png" width="350" title="App logo">
</p>

The purpose of this Android application is to allow users to record and keep track of their moles. The application also uses OpenCV, an open source library for computer vision, to auto-generate some properties of the mole like it's size and whether or not it is symmetric. 

## User Guide

Users first have to create an account after which they can login to the application. This application uses a Firebase backend for user registration as well as for storing images.
<p align="center">
  <img src="pictures/loginscreen.png" width="350" title="Login screen">
  <img src="pictures/registrationscreen.png" width="350" title="Registration screen">
</p>

Users can take a picture by selecting the "Take Picture" button. The application asks for additional information about the mole. Some of these properties are auto-generated. 
<p align="center">
  <img src="pictures/homepage.png" width="350" title="Home screen">
  <img src="pictures/newmole.png" width="350" title="Enter a new mole screen">
</p>

You can also view previous roles that have been recorded. Select the mole you wish to view. Each entry can be selected individually, or you can choose to a view a timelapse to see how the mole may have changed over time. 

<p align="center">
  <img src="pictures/viewHistory_1.png" width="350" title="Select mole to view screen">
  <img src="pictures/viewHistory_2.png" width="350" title="Select entry to view screen">
</p>

A physician code can also be entered that allows users to share their recorded moles with a physician who also uses the application. 

<p align="center">
  <img src="pictures/addphysician.png" width="350" title="Login screen">
</p>

## Installation

After you clone the repo, open the folder using Android Studio. 
Run the application. You can also plug in your device to test out the application. 
