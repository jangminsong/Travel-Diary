# Wander Snap
Final Project for Mobile SoftWare Engineering Class. 3 of my classmates and I created the Travel Diary on Android Studio using Kotlin

## Overview
We made a travel diary which the app contains the following features: 
  * Login/Sign Up
  * Feed
  * Add Post/Photo
  * Map
  * Buttom Navigation Bar

The Application can be ran by opening the file with latest version of Android Studio

## Main File Structures
* `/app/src/main/java/hu/ait/traveldiary` - main file
  * `/ui/screen`
    * `/add/AddEntryScreen` - screen that can add the post which all the informations will be saved on Google Firebase
    * `/feed` 
      * `/FeedScreen.kt` - feed screen that the posts created will appear
      * `/PostCard.kt` - details of the post when the detail button is clicked
    * `/login/LoginScreen.kt`- login/sign up screen which all the informations will be saved on Google Firebase
    * `/map/MapScreen.kt` - map screen where all the places visited will be appeared on google map with icons and when the icon is clicked, the picture that was taken pops up.
  *`BottomBarScreen.kt` - buttom bar which screens can be easily changed by clicking the icons

## Collaborators - @github username
* Ashley Liang   - @ashleyliangg
* Mustafa Sameen - @ssameen
* Sabine Mejia   - @sabine-mejia

