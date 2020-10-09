# Installation Instruction

1. Connect your phone to your computer and enable developer mode (for iPhone, enable developer mode by  
   connecting an iPhone while Xcode is running on a Mac) 
2. Install yarn, node, and git if not installed \
  *yarn: https://classic.yarnpkg.com/en/docs/install/#windows-stable \
  *node: https://nodejs.org/en/download/ 
  
  2.1 yarn and node.js can also be installed on Mac/Linux through the homebrew command brew install yarn \
  
 
  *Check if these are installed
  ![CheckTools](https://github.com/annguyen2790/firebase-reactnative/blob/master/Tools.PNG)
  
  
3. Install expo client using the following command line: npm install --global expo-cli
4. Clone or fork this repo to your computer
5. Install expo local server using : yarn add expo in the directory that contains app.js \
5.1 Install firebase using yarn add firebase 
6. Go to src/firebase/config.js and enter API keys info (This is where we connect react native to firebase)
7. Go back to directory that contain app.js and run the command: expo start
8. A screen will appear on the broswer that looks like this: \
    ![ScrrenExample](https://github.com/annguyen2790/firebase-reactnative/blob/master/screenEx.PNG)
    
9. Click on Run Android/emulator, or any other option of your devices, etc.
10. On your device, a home screen like this should appear
    ![HomeScreen](https://github.com/annguyen2790/firebase-reactnative/blob/master/Screenshot_20200920-020003.jpg)

# WhatIsThis_Backend

###Version Control
For the course of this project, the branching strategy will involve using [git flow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow).

This means we will use a master branch for releases and a develop branch to work off of for integrating features. See link above for a more detailed explanation. Whenever a new feature is to be implemented, a feature branch will be created. It's highly recommended that you check out the link above as it will give you a better understanding of what this branching strategy is. This will align with our Rally tickets. The format for creating a new branch is as follows:

*TicketNumber*/*type*-*name*
See an example below

If the rally ticket number is TA111 and it's title is "Implement login feature" it is a feature, then the branch will be named as follows
    TA111/feature-implement-login-feature

If the rally ticket is TA111 "Fix login bug" for a bug fix it will look like 
    TA111/bug-fix-login-bug

Remember, everytime you wish to create a new feature, branch off of develop. This will help to avoid merge conflicts, make it easier to code review changes, amongst many other benefits.

If there is any confusion, see the link above, or talk to the team leader.

If you need a refresher on git, there is a good cheatsheet [here](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet).