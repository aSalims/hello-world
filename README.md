# hello-world
Hello-World repository
Arwa Salim begining to learn git, gitHub and R in pursuit of becoming a data scientist
- Made a local directory on my computer (helloword_repo)
- Initialised a git in there
- Had to "view hidden folders" to see the .git folder initialization created
- used "git remote add origin https://github.com/aSalims/hello-world" which points to the test repo I just made on git hub
- used "git pull origin master" which caused the README.md file in the remote github repo to show up in my local repo
- now editing README.md
- will try and push this to remote repo using "git push origin master"
  -- the above command seemed to work - git bash said 'everything up to date' but the updated readme did not show up on git hub!
- git status:
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

- what needs to be done is first you have to git add the file you've made changes in, so "git add README.md"
$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   README.md
