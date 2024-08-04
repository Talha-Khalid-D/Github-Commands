# <h1>GitHub Commands : Basics to Advanced</h1>
These are all the commands and Comments that you need to know about github to use it properly for personal as well as for open source projects


<h3>•	ls :</h3>
<p>is used to show all files in the directory</p>
<h3>•	mkdir :</h3>
<p>is used to make a new directory in the local system</p>
<h3>•	cd:</h3>
<p>is used to change the directory means if we are outside the folder and give command cd projects then we will move from outside the projects folder to inside projects folder</p>
<h3>•	.git:</h3>
<p>is repository file that git provides us inside which all the history of commits is saved.</p>
<h3>•	git init:</h3>
<p>is used to initialize the git repository which is empty at first</p>
<h3>•	ls -a :</h3>
<p>is used to show all the hidden files in a repository .git is also a hidden file and can be shown using this command.</p>
<h3>•	touch file-name:</h3>
<p>is used to create a file inside a local repository.</p>
<h3>•	git status:</h3>
<p>is used to get status of the repository means is all the files inside the repository are committed</p>
<h3>•	git add . :</h3>
<p>is used to add all the files of the current directory</p>
<h3>•	git add file-name :</h3>
<p>is used to add only that file to the current directory</p>
<h3>•	git commit -m “msg about commit” :</h3>
<p>is used to stage means upload/save all the history of the files added</p>
<h3>•	cat file-name :</h3>
<p>is used to show all the data inside that file</p>
<h3>•	git status :</h3>
<p>there are four stages : untracked ,modified , changed , unchanged</p>
<h3>•	git restore — staged file-name :</h3>
<p>is used to un-stage the file we have stage recently</p>
<h3>•	git log :</h3>
<p>is used to see the history of all the commits that we have made</p>
<h3>•	rm -rf file-name :</h3>
<p>is used to delete a file through command line from local repository</p>
<h3>•	git reset commit hash-link (get it from history of commits):</h3>
<p>is used to delete a particular commit if we want to</p>
<h3>•	git stash :</h3>
<p>means back staging some files that are not commited yet (means saving a file for commit in future if we want to commit it)</p>
<h3>•	git stash pop :</h3>
<p>is used to bring the file from back stage state to stage state</p>
<h3>•	git stash clear : </h3>
<p>is used to delete the stash files</p>
<h3>•	vi file-name :</h3>
<p>is used to view the file through command line</p>
<h3>•	git remote add origin url :</h3>
<p>is used to attach the url and our local repository
here , remote means we are working with some url</p>
add means adding some url</p>
<p>origin is the url name (that can be anything) but in general it should be origin if you are working on personal project</p>
<h3>•	git remote -v :</h3>
<p>is used to check all the urls that are attached with our folder</p>
<h3>•	git push url-name branch-name :</h3>
<p>is used to push all the files from local repository to our remote repository</p>
<h3>•	now what are branches :</h3>
<p>these are the copies of our files and is made if more than one person are working on same projects and commit made in one branch not effects or added to other branch unless we want to do that.</p>
<h3>•	Use of branches :</h3>
<p>these are used when we are working on a bug or error and don’t want to make the change in main branch(file) or when many people or collaborating on a single project.</p>
<h3>•	git branch name:</h3>
<p>is used to make a new branch</p>
<h3>•	git checkout branch-name :</h3>
<p>is used to switch from one branch to other</p>
<h3>•	git merge branch-name :</h3>
<p>is used to merge one branch to another</p>
<h3>•	git remote -v:</h3>
<p>is used to open the repository through command line</p>
<h3>•	Fork :</h3>
<p>is used to take someone else repository to your own account</p>
<h3>•	upstream url :</h3>
<p>is the url of that repository that you have forked to your account. command : (git remote add upstream upstream-url)</p>
<h3>•	Pull request:</h3>
<p>means we want to merge to branches than we need to submit a pull request if we don’t have the main branch access. Also never make a single pull request for many more commits.</p>
<h3>•	git fetch —all —prune :</h3>
<p>is used to fetch all the commits made to the forked repository to your fork, here prune means deleted commits too.</p>
<h3>•	git reset —hard upstream/main:</h3>
<p>is used to apply these fetched commits changes to our main branch of fork origin</p>
<h3>•	Other way to do the same above thing is :</h3>
<p>git pull upstream main : do the same fetching thing</p>
<h3>•	git rebase -i commit-hash-link:</h3>
<p>is used to pick all the a commit and squash any commit we want , squash means which ever commit I have picked just merge all the squash-selected commits to it.</p>
<h3>•	‘ :x ‘</h3>
<p>used to create a new message for the commits</p>
<h3>•	merge conflicts :</h3>
<p>means changes made at same line in merge requests than git will be confused about which change we want to keep.
To resolve this do manually and keep which line you want we can keep both if we want to.</p>

