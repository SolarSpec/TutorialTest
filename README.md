# SolarSpec Test Respository

This is a repository to test out commands learnt from the tutorials

## Usage

There are two ways to get the repository started:

1. This method automatically sets up everything for you and initialises the repository for you (no need to do `git init`)

   `$ git clone https://github.com/SolarSpec/TutorialTest.git`

   A new folder called TutorialTest will be created where the command was called. (Avoid using it in folders where you already run `git init`)

   After it has finished downloading all files, run:

   `$ cd TutorialTest`

   You will now be in the folder with all the work in the repository, and you should the `(main)` in your git bash

2. This method gives you more control of the folder name and is close to what we have been doing in the tutorials

   `$ git init`

   `$ git pull https://github.com/SolarSpec/TutorialTest.git`

After following one of the two methods above, we can then add files(Don't modify the README.md as it is being followed by everyone), create branches, and commit. To have a more indepth feel of git run the following commands

`$ git checkout -b <Your name>`

`$ echo > "<your name>.txt`

Modify the `<your name>.txt` however you like

`$ git add .`

`$ git commit -m "Adding <your name>'s branch"`

`$ git remote add origin https://github.com/SolarSpec/TutorialTest.git`

`$ git push -u origin <Your branch name>`

If you now visit https://github.com/SolarSpec/TutorialTest, you should see your branch under branches, and under https://github.com/SolarSpec/TutorialTest/network you should be able to see the position of your branch

If you want to see what others have added to their branches

` git pull`

This will update your files and branches

` git switch <branch you want to see>`

If you notice, your `<your name>.txt` should now be hidden, as it only exists in your branch, but the README.md should not, as it's on the main branch shared by everyone

Please do let me know if you run into any trouble

Once you are comfortable with this tutorial, I will upldoad a new one with merging, so that everyone can see your work, and so that you can collaborate with team mates in making scripts.
