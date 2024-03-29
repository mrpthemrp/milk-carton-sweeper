# Milk Carton Sweeper App :milk_glass:

This repository contains an Android App.  
:hotsprings: Java and Android Studio was used to program the app.

:warning: ***Please DO NOT FORK this repository/project!*** :warning:

This project is not intended to be open-source, feel free to use it as a reference but DO NOT FORK!  
If used as reference, please cite by providing link to project and author name \([see section below](#4-citation-format)\).

  
Watch a quick demo of the project through the link below!  
:vhs: **[Video Demo Link](https://youtu.be/UMjSen06EAM)**

## :bookmark_tabs: Table of Contents
1. [Project Description and Summary](#1-project-description-and-summary)
   1. [How To Play The Game](#book-how-to-play-the-game)
   2. [Project Takeaways](#sparkles-project-takeaways)
   3. [Project Shortcomings](#exclamation-project-shortcomings)
2. [Installation Guide](#2-installation-guide)
   1. [OS Requirements](#iphone-os-requirements)
   2. [Steps](#memo-steps)
3. [References](#3-references)
    1. [Images](#art-images)
4. [Citation Format](#4-citation-format)

## 1. Project Description and Summary

This project is the result of a introduction to Android Studio assignment for CMPT 276 ([Dr. Brian Fraser](https://opencoursehub.cs.sfu.ca/bfraser/grav-cms)).

This project runs an Android App that is similar to the idea behind [Mine Sweeper](https://en.wikipedia.org/wiki/Minesweeper_(video_game)), but instead of avoiding mines (or cartons in this case), the goal is to find all cartons with the lowest amount of moves. Cartons are placed pseudo-randomly.

**See [video demo](#milk-carton-sweeper-app-milk_glass) for more comprehensive walkthrough.**

### :book: How To Play The Game

1. Tap on any cell in the game grid to inspect it.
2. If there is a milk carton on that cell, then it will reveal itself.
    - If it is an empty cell, the vertical and horizontal columns of that cell will be scanned.
    - After the scan, a number will appear in the selected cell which tells the user how many milk cartons are nearby in either the cell's horizontal or vertical columns.
3. Continue tapping on different cells to find all the milk cartons!

*Note: Finding a milk carton in a cell will not count towards the scan number. Only selecting empty cells or already found cartons will count towards the total number of scans.*

### :sparkles: Project Takeaways

- Built my first ever Android App with Android studio
   - Wrote in HTML and XML for the first time.
   - Started to understand how to connect frontend UI with backend algorithms
- Learned how to do a loading screen that uses animations and a timer.
- Wrote a simple algorithm that checks if a cell has been selected or not.
- Wrote in a simple pseudo-random generator to place the cartons in the grid.
- First time using Shared Preferences to save game settings

### :exclamation: Project Shortcomings

- :lady_beetle: There are bugs in the game!  
Sometimes the cartons are not distributed properly depending on grid size and carton count. 
- Did not account for dark mode support.
- Not all String values are stored in the [values folder](/app/src/main/res/values).

## 2. Installation Guide
***This project was created for phones that run Android OS.**  
**Unfortunately there is no Apple equivalent available.***

### :iphone: OS Requirements
- **Android OS**
	- The app runs horizontally, so make sure the phone you are using is wide enough for a horizontal game.
	- Use on Tablets is NOT recommended. 
- **Minimum APK 21**
  - Any lower APKs have not been tested with this app and is NOT recommended.
- **Light Mode Support Only**
	- There is currently no support for dark mode with this app. Please use light mode when using the app. 

### :memo: Steps

1. Click into the **[milkCartonSweeper.apk file](/milkCartonSweeper.apk)**.
2. Click **'Download'** to download the file.
3. Navigate your phone's directory to **find the downloaded file**.
	- Check **'Internal storage'** and then the **'Downloads'** folder
4. **Click on the file to download**
5.  Pop-up will appear, **'Allow 3rd-party download'**
	- This **step will be different depending on the phone**
	- May need to toggle Settings in Files to allow download
6. Click **'Install'** and let the app download.
7. The app will now be ready to use!


## 3. References
All images used are not of my own work. The JPG files can be found in the **[drawable folder](/app/src/main/res/drawable)**.  

### :art: Images
- [Milk Carton Image Source](https://dribbble.com/shots/14312353-Kawaii-flavored-milk)
- [Peach Background Image Source](https://wallpaperforu.com/peach-aesthetic-wallpaper-pc/)
- [3D Render Background Image Source](https://unsplash.com/photos/SXigdcQPbd8)


## 4. Citation Format
Example of citing this project as a reference:
> Reference used for loading screen in Android Studio: https://github.com/mrpthemrp/milk-carton-sweeper/blob/master/app/src/main/res/layout/activity_welcome_screen.xml
> Date Accessed: January 2022  
> Developer: [Deborah Wang](https://github.com/mrpthemrp)

If using this project as a reference please copy and paste the following into your references/citations:
```diff
Reference for <code referenced>: <file/folder URL>
Date Accessed: <date accessed>
Developer: Deborah Wang (https://github.com/mrpthemrp)
```

---
Last Code Update Date: September 2022

Copyright October 2021, Deborah Wang
