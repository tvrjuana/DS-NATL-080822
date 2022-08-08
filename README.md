Written Instructions to Connect to This Repository:

We will go through and follow these instructions together in a lecture during Week 1 - no rush!

FORK this repository, creating a copy on your own GitHub account

Then clone your fork down to your local computer

git clone https://github.com/[yourusername]/DS-NATL-080822.git
Add the /flatiron-school/ version as the upstream (to pull future changes)
git remote add upstream https://github.com/flatiron-school/DS-NATL-080822.git
You can make changes to the notebooks now! Remember to push your changes to your forked version of the repo (to put your local changes up online):
git add [filename]
git commit -m 'message here'
git push
Whenever you want to get updated notes:
Grab the changes from the upstream repo
git fetch upstream
Merge new changes onto your local repo
git merge upstream/main -m "meaningful message about what you're updating"