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
