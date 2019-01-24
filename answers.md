Answer 1; git version 2.17.1
Answer 2; 
    user.name=Skylar Boggs 
    user.email=sb667617@ohio.edu
Answer 3;
    You get a list of common Git commands used in various situations. 
Answer 4;
    On branch master
    No commits yet
    Untracked files:
        (use "git add <file>..." to include in what will be committed)

         README.md
         answers.md

    nothing added to commit but untracked files present (use "git add" to track)
Answer 5;
    No commits yet

    Changes to be committed:
        (use "git rm --cached <file>..." to unstage)

             new file:   README.md

    Untracked files:
        (use "git add <file>..." to include in what will be committed)

            answers.md
Answer 6;
    No commits yet

    Changes to be committed:
        (use "git rm --cached <file>..." to unstage)

            new file:   README.md
            new file:   answers.md
Answer 7;
    On branch master
    nothing to commit, working tree clean
Answer 8;
    On branch master

    No commits yet

    Changes to be committed:
        (use "git rm --cached <file>..." to unstage)

            new file:   README.md
            new file:   answers.md

    sboggs@odd35:~/2400/git-lab$ git commit -m "Initial commit"
    [master (root-commit) 943296f] Initial commit
    2 files changed, 0 insertions(+), 0 deletions(-)
    create mode 100644 README.md
    create mode 100644 answers.md
    sboggs@odd35:~/2400/git-lab$ git status
    On branch master
    nothing to commit, working tree clean
    sboggs@odd35:~/2400/git-lab$ git log
    commit 943296f0b0fb58fba38c4bc11353f87d435406ee (HEAD -> master)
    Author: Skylar Boggs <sb667617@ohio.edu>
    Date:   Wed Jan 23 18:37:28 2019 -0500
Answer 9;
    On branch master
    Your branch is up to date with 'origin/master'.

    Changes not staged for commit:
    (use "git add <file>..." to update what will be committed)
    (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   answers.md

    no changes added to commit (use "git add" and/or "git commit -a")
Answer 10; 
    No the changes were not reflected in my local copy
Answer 11;
     ! [rejected]        master -> master (fetch first)
    error: failed to push some refs to 'https://github.com/SkylarBoggs/git-lab.git'
    hint: Updates were rejected because the remote contains work that you do
    hint: not have locally. This is usually caused by another repository pushing
    hint: to the same ref. You may want to first integrate the remote changes
    hint: (e.g., 'git pull ...') before pushing again.
    hint: See the 'Note about fast-forwards' in 'git push --help' for details.
Answer 12; 
    The changes I made online were reflected in my copy.
Answer 13;
    .  ..  .git  .gitignore  README.md


