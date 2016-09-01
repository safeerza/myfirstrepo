# GITHUB

### Github Overview

#####  GitHub:

- Is a cloud-based code hosting platform built on the GIT version control software.
- Provides version control.
- Supports distributed collaboration and content development while maintaining version control
- Provides access control and requires an account for access.

##### GitHub allows you to:

- Create repositories
- Create repository branches
- Create folders and contents
- Clone repositories / content
- Make content changes
- Commit changes
- Merge content - Specific branch being merged into the master branch.
- Push content - Push your locally stored branch to the origin on github.com.
- Rebase - Put your changes on top of another branch.
- Resolve version conflicts - Code conflicts arising during a ‘merge”.

### Important Concepts
#### Github Repositories
- A repository is usually used to organize a single project.
- Repositories can contain folders and files, images, videos, spreadsheets, and data sets – anything your project needs.
- Recommended: Include a README, or a file with information about your project.
- GitHub makes it easy to add one at the same time you create your new repository. It also offers other common options such as a license file.
- Master - The main code repository.

##### Github Branches
- Branching is the way to work on different versions of a repository at one time.
- By default your repository has one branch named master which is considered to be the definitive branch.
- Use branches to experiment and make edits before committing them to master.

##### Github Commits
- On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made.
- Commit messages capture the history of your changes, so other contributors can understand what you’ve done and why.

##### Pull Request
- When you have changes in a branch off of master, you can open a pull request.
Pull Requests are the heart of collaboration on GitHub.
- When you open a pull request, you’re proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches.
- The changes, additions, and subtractions are shown in green and red.
- As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.
*-------*

#### Sample Github Exercises and Screenshots

https://guides.github.com/activities/hello-world/

##### Topics
1.  Create a new repository
2.  Create a new branch
3.  Make and commit changes
4.  Make pull requests

*-------*

# GIT

##  Git Overview

#### Git:
- Is a version control system that has the ability to offer almost all of its features for use offline and without a central server.
- It is the brainchild of Linus Torvalds, with the first prototype written in  two-weeks in response to the “BitKeeper debacle” of 2005.
- Developers everywhere are using this  platform.
- It provides collaboration and “Distributed Version Control” functionality, usage flexibility, offline capabilities and tracking features for distributed software and content development projects


#### Key Concepts
- Branch - A deviation from the master code where you store a feature.
- Origin - The remote repository located on github.com.
- Request - Specific branch being merged into the master branch.
- Push - Push your locally stored branch to the origin on github.com.
- Rebase - Put your changes on top of another branch.
- Merge Conflict- Code conflicts arising during a ‘merge”.
- Master - The main code repository.

#### Common Commands
- git Init -  Initialize the n=index / create a new repository
- git Add -  Add a file to the index
- git Commit - Saving your code (commits the changes) to GIT with a message.
- git Push - The remote repository located on github.com.
- git Status - Specific branch being urged into the master branch.
- git Rebase - Put your changes on top of another branch.
- git Merge	 - Code conflicts arising during a ‘merge”.
- git Status - Shows you the status of files in your index versus your working directory. It will list out  files that are untracked, modified and staged.

###  Overview of Git Commands
###### (https://www.kernel.org/pub/software/scm/git/docs)

##### Basic Git Commands

##### git config
- Sets configuration values for things like your user name, email, and gpg key, your preferred diff algorithm, file formats to use, proxies, remotes and tons of other stuff.
- For a full list, see the git-con g docs
- http://www.kernel.org/pub/software/scm/git/docs/git-config.html

##### git init
- Initializes a git repository
- Creates the initial ‘.git’ directory in a new or existing project.
- http://www.kernel.org/pub/software/scm/git/docs/git-init.html

##### git clone
- Copies a Git repository from another place and adds the original location as a remote you can fetch from again and possibly push to if you have permission.
- http://www.kernel.org/pub/software/scm/git/docs/git-clone.html

##### git add
- Adds changes in files in your working directory to your index, or staging area.
- http://www.kernel.org/pub/software/scm/git/docs/git-add.html

##### git rm
- Removes files from your index and your working directory so they will stopped being tracked.
- http://www.kernel.org/pub/software/scm/git/docs/git-rm.html

##### git commit  
- Takes all of the changes staged in the index (that have been git add’ed), creates a new commit object pointing to it, and advances the branch to point to that new commit.
- http://www.kernel.org/pub/software/scm/git/docs/git-commit.html

##### git status
- Shows you the status of files in your index versus your working directory. It will list out files that are untracked (only in your working directory), modified (tracked but not yet updated in your index), and staged (added to your index and ready for committing).
- http://www.kernel.org/pub/software/scm/git/docs/git-status.html

##### git branch
- Lists existing branches, including remote branches if ‘-a’ is provided. Creates a new branch if a branch name is provided. Branches can also be created with ‘-b’ option to ‘git checkout’.
- http://www.kernel.org/pub/software/scm/git/docs/git-branch.html

##### git checkout
- Checks out a different branch – makes your working directory look like the tree of the commit that branch points to and updates your HEAD to point to this branch now, so your next commit will modify it.
- http://www.kernel.org/pub/software/scm/git/docs/git-checkout.html

##### git merge
- Merges one or more branches into your current branch and automatically creates a new commit if there are no con icts.
- http://www.kernel.org/pub/software/scm/git/docs/git-merge.html

##### git reset
- Resets your index and working directory to the state of your last commit, in the event that something screwed up and you just want to go back.
- http://www.kernel.org/pub/software/scm/git/docs/git-reset.html

##### git rebase
- An alternative to merge that rewrites your commit history to move commits since you branched off to apply to the current head instead. A bit dangerous as it discards existing commit objects.
- Manual Pages: http://www.kernel.org/pub/software/scm/git/docs/git-rebase.html

##### git stash
- Temporarily saves changes that you don’t want to commit immediately for later. Can re-apply the saved changes at any time.
- http://www.kernel.org/pub/software/scm/git/docs/git-stash.html

##### git tag
- Tags a specific commit with a simple, human readable handle that never moves.
- http://www.kernel.org/pub/software/scm/git/docs/git-tag.html

##### git fetch
- Fetches all the objects that a remote version of your repository has that you do not yet so you can merge them into yours or simply inspect them.
- http://www.kernel.org/pub/software/scm/git/docs/git-fetch.html

##### git pull
- Runs a ‘git fetch’ then a ‘git merge’.
- http://www.kernel.org/pub/software/scm/git/docs/git-pull.html

##### git push
- Pushes all the objects that you have that a remote version does not yet have to that repository and advances its branches.
- http://www.kernel.org/pub/software/scm/git/docs/git-push.html

##### git remote
- Lists all the remote versions of your repository, or can be used to add and delete them. Inspecting Repositories
- https://www.kernel.org/pub/software/scm/git/docs/git-remote.html

##### git log
- Shows a listing of commits on a branch or involving a specific file and optionally Manual Pages about what changed between it and its parents.
- https://www.kernel.org/pub/software/scm/git/docs/git-log.html

##### git show
- Shows information about a git object, normally used to view commit information.
- Manual Pages @: www.kernel.org/pub/software/scm/git/docs/git-show.html
http://www.kernel.org/pub/software/scm/git/docs/git-show.html

##### git ls-tree
- Shows a tree object, including the mode and name of each node and the SHA-1 value of the blob or tree that it points to. Can also be run recursively to see all subtrees as well.
- http://www.kernel.org/pub/software/scm/git/docs/git-ls-tree.html

##### git cat-file
- Used to view the type of an object if you only have the SHA-1 value, or used to redirect contents of files or view raw information about any object.
- http://www.kernel.org/pub/software/scm/git/docs/git-cat-file.html

##### git grep
- Filets you search through your trees of content for words and phrases without having to actually check them out.
- http://www.kernel.org/pub/software/scm/git/docs/git-grep.html

##### git diff
- Generates patch files or statistics of differences between paths or files in your git repository, or your index or your working directory.
- http://www.kernel.org/pub/software/scm/git/docs/git-diff.html

##### gitk
- Graphical Tcl/Tk based interface to a local Git repository.
- http://www.kernel.org/pub/software/scm/git/docs/gitk.html

### Other Git Tools
##### git archive
- Creates a tar or zip file of the contents of a single tree from your repository.
- Easiest way to export a snapshot of content from your repository.
- http://www.kernel.org/pub/software/scm/git/docs/git-archive.html

##### git gc
- Garbage collector for your repository. Packs all your loose objects for space and speed efficiency and optionally removes unreachable objects as well. Should be run occasionally on each of your repos.
- http://www.kernel.org/pub/software/scm/git/docs/git-gc.html

##### git fsck
- Does an integrity check of the Git “ filesystem”, identifying dangling pointers and corrupted objects.
- http://www.kernel.org/pub/software/scm/git/docs/git-fsck.html

##### git prune
- Removes objects that are no longer pointed to by any object in any reachable branch.
- http://www.kernel.org/pub/software/scm/git/docs/git-prune.html

##### git-daemon
- Runs a simple, unauthenticated wrapper on the git-upload-pack program, used to provide efficient, anonymous and unencrypted fetch access to a Git repository.
- http://www.kernel.org/pub/software/scm/git/docs/git-daemon.html



*-------*

###  References
- GitHub: https://guides.github.com/activities/hello-world/
- GitHub: repository overview:  http://www.dzone.com
- Git User’s Manual / Commands: https://kernel.org/pub/software/scm/git/docs/user-manual.html
- A Tutorial Introduction to Git:
 https://www.kernel.org/pub/software/scm/git/docs/tutorial.html
