# Week 1 - Day 2 - Working with Git, Github and the Terminal!


## Terminal Basics:
- pwd for file location in terminal
- ls for all folders and files in terminal
- ls -a for all hidden files with a . Before files. -a is called a flag
- ls -l for all files with all details
- pwd and ls useful
- ls -al for all everything
- cd for change directory. Like cd Documents
- ls gives details, pwd gives location


## Navigation:
- cd after folder always returns to home directory ~
- cd “take me back to home”
- Can only have a single file in every folder. 2 files in 2 folders aren’t the same even if copied
- . Current directory
- .. Parent directory 1 level above 
- Dots come after folder 
- Zoom cd .. to go to parent directory
- Documents cd . Stays in the same directory
- Documents cd Zoom > Goes too Zoom
- Need to use dots with cd always
- Go back to folder you were originally use ‘cd -‘ if you accidentally jumped out of folder. Can do that after folder.
- DO NOT TYPE IN FOLDERS LETTER BY LETTER. TYPE START OF FOLDER THAN PRESS TAB KEY, THEN TAB AGAIN TO SELECT RIGHT FOLDER, THEN ENTER TO SELECT CORRECT FILE. 
- TAB SUPER USEFUL FOR GOING TO EXACT DOCUMENT DIRECTORY
- Otherwise just use ls and select the folder (slower)


## Create/Modify files:
- mkdir my_documentary to create a new directory with the name my_documentary.
- NEVER USE SPACES FOR FILENAMES FROM NOW ON. IT CREATES SEPARATE THINGS!
- Use ls to see if new folder my_documentary has been created
- snake_case or snakeCase or Kebab-case (not great) for naming files
- touch my_file.txt > to create the txt file
- open my_file.txt will open text editing file on laptop. Can open up any type of file! Html/doc/ppt
- open . Will open up exact current directory in GUI (Useful if extremely lost!) Makes moving/copying files much easier!
- mv my_file.txt (use tab) .. > move my file.txt to parent directory
- Cd .. to parent directory now has file. Only when you change directory. .. is a navigation to any other folder
- mv my_file my_other_file to move directory 
- Delete stuff is danger zone. rm > remove stuff
- rm my_file.txt deletes it forever > no way of returning it PERMANENTLY! DOESN’T SAY ARE YOU SURE. RM IS A NUCLEAR AND PERMANENT THING SO BE VERY CAREFUL.
- Cannot delete a directory which could delete multiple things. rm - r to everything inside directory. 
- ‘rm -r my_directory’ to delete everything in it


# WARNING:
- ‘rm - rf ‘> DO NOT USE 3 TO 4 MONTHS IN CAREER!!!!! WILL NUKE HOME DIRECTORY UNTIL MACBOOK IS DESTROYED. TICKING BOMB!!! ALWAYS HAVE AN INSTRUCTOR PRESENT!!!


## Accessibility:
- hIstory command gives last 10,000 commands
- Can also use up and down arrow to check previous commands
- To clear terminal either type clear or press control and l.