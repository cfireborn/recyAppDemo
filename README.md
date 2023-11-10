# SuperHero Recycling App

A proof-of-concept / minimum viable product for a daily engagement app incorporating edTech elements and real-world rewards to motivate users to live sustainably

A chunk of intellectual property to support the circularity brand [SuperHero Recycling](https://superherorecycling.com/help).

# App Demo

![App Demo 8-26](AppDemo.gif)

App Demo 8/26/2022 (v0.030)

This project was created with [Xcode 13](https://developer.apple.com/documentation/xcode-release-notes/xcode-13-release-notes). Download it [here](https://developer.apple.com/xcode/resources/)

## Installation Instructions

Set up git ([tutorial here](https://bytes.usc.edu/cs104/labs/lab0-github/)) and clone the repo, then open it in Xcode. 

With the project opened in Xcode, you can build the project by choosing a built-in simulator and pressing "run" or Command+R: 
![BuildDemo](BuildDemo.gif)

## Testing (GOD MODE page easter egg)

You can get to the GOD MODE page with testing buttons (Changing streak values, knowledge points, setting up simulated score submissions, etc) by pressing an invisible button on the Benefits page 7 times in a row, just at the crown of the logo.

![GodMode Hack](GodModeHack.gif)

## Preparing For App Store Submission

Take screenshots of the simulator.

It is best practice to hide the status bar, which you can do by:
1. Open Info.plist.
2. Add row with key View controller-based status bar appearance and value NO if not present.
3. Add row with key Status bar is initially hidden with value YES if not present.
4. Save and run the project.

[[Source]](https://gist.github.com/remarkablemark/95f4d09feebd92ac876103fef9be6114)

Use an online screenshot generator such as [progressier.com](https://progressier.com/pwa-screenshots-generator) to prettify the screenshots (6.5"). The raw .SCREENSHOTS file is on the drive in [~/app/Screenshots for app store/Screenshots v1.0/6.5"](https://drive.google.com/drive/folders/15D790oLvh5BNpsdfzCcOp_mttlTJltWZ) if you need to import it back into progressier for work (seriously this is an awesome free service).

 This one is also good at time of writing (for iPhone 8 Plus sizes 5.5"): [studio.app-mockup.com](https://studio.app-mockup.com/). Ask me for my login if you want to get the old ones

![Screenshots for 6.5 1"](iPhone12Screenshots1.png)
![Screenshots for 6.5 2"](iPhone12Screenshots2.png)
![Screenshots for 5.5 1"](iPhone8PlusScreenshots1.png)
![Screenshots for 5.5 2"](iPhone8PlusScreenshots2.png)

The interface for the latter (studio app mockup) is a little tricky.

App metadata for App Store submission can be found [here](https://developer.apple.com/app-store/review/guidelines/)

## Learn More

To learn Xcode, check out the [documentation](https://developer.apple.com/documentation/xcode). I highly recommend tutorials by [raywenderlich](https://www.youtube.com/watch?v=27TFuaOpUsE), and this tutorial on [Scroll Views](https://www.youtube.com/watch?v=Zvfhhud3MAc)

### Branching

See [gitflow](https://datasift.github.io/gitflow/IntroducingGitFlow.html) for best practices used in this project.

# Developer Orientation

![Color Palette import](ColorPaletteImport.gif)

If you have questions about stuff from the video, don't hesitate to give me a call - you've got my number.

## Intellectual Property

Developed by Rabid Prototyping Games Studio - Charlie Feuerborn  

Source code owned by SH Recycling Corp.  

All Rights Reserved  