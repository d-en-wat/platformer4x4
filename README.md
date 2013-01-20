# README for test platformer
This is a test of github for team 4x4s platformer game for CEN3031

# Steps to set up git

#Add the repository as a remote
git remote add origin git@github.com:murphyslaw480/platformer4x4.git

# Clone the Repository
git clone git://github.com/murphyslaw480/Platformer.git

#Create a Fork

#Reverting Changes
Suppose you make a change and realize you screwed something up.
You can revert a file back to its status in the last commit.
First make sure the file isn't staged:
git reset HEAD <filename>

Now revert the file to its previous state:
git checkout -- <filename>

Note: All work on that file since the last commit will be lost
