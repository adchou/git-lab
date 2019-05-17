Andrew Chou adchou
Answer 1: git version 2.20.1 (Apple Git-117)
Answer 2:credential.helper=osxkeychain
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
user.name=Andrew Chou
user.email=ac686115@ohio.edu
Answer 3:git manual shows up
Answer 4: On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	README.md
	answers.md

nothing added to commit but untracked files present (use "git add" to track)
MacBook-Pro-6:git-lab andrewchou$ 
Answer 5: On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	answers.md

MacBook-Pro-6:git-lab andrewchou$ 
Answer 6: On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md
	new file:   answers.md

MacBook-Pro-6:git-lab andrewchou$ 
Answer 7: On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")
Answer 8: commit f8b5dc56d25b31c3e7fdfc694838dcefd56429a4 (HEAD -> master)
Author: Andrew Chou <ac686115@ohio.edu>
Date:   Fri May 17 11:18:42 2019 -0400

    Initial commit
Answer 9: On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")
Answer 10: they were not added
Answer 11: recieved this error  ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/adchou/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
MacBook-Pro-6:git-lab andrewchou$ git pull
Answer 12: Yes the changes were recorded
Answer 13: .		..		.git		.gitignore	README.md
MacBook-Pro-6:git-lab-2 andrewchou$ 

