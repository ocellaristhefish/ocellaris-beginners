Readme for getting started on git
1. Install git - `brew install git`
2. check version - `git --version`
3. Set your name and email for your git repository - `git config --global user.name <My Name>`, `git config --global user.email <myemail>`
4. Create your repository on your local box - `mkdir my-repo`, `cd my-repo`, `git init`

5. Add a new file to your repository
$ vim readme.txt
6. Get git status of your newly added file
$ git status
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	readme.txt

nothing added to commit but untracked files present (use "git add" to track)
7. Add file you just created to the files you would like to commit 
$ git add readme.txt
$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   readme.txt
8. Finally, commit the changes to repository’s history with a short description of the updates
$ git commit -m readme.txt 
[master (root-commit) 376298b] readme.txt
 1 file changed, 6 insertions(+)
 create mode 100644 readme.txt
$ git status
On branch master
nothing to commit, working directory clean



