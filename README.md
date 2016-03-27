# PiUseGitHub
# To 'get' things from YOUR github...
# First change directories:
	cd /home/pi/git/dragon

# Initialize a 'git' directory:
	git init
	
# Then 'pull' from your github:
	git pull https://github.com/ocros03/Dragon.git

# Browse to the directory in the 'File Manager'

# Right click on Dragon.py and choose Python2

OR

# To push things to your github after making changes to your file...
# Make sure you're in the correct directory:
	cd /home/pi/git/dragon

# If you want to add new files that were't there already...
	git add --all

# 'Commit' your changes:
	git commit -m "comment goes here" dragon.py
	(-m means message and dragon is the name of the file you changed...you can use -a to push all files in directory) 

# Make a remote repository called 'ori' that points to github
	git remote add ori https://github.com/ocros03/Dragon.git
	git remote -v
	git push ori

# Enter your username:
	ocros03

# Enter your password:
	Orionthehunter03
