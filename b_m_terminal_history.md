HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS
$ cd git_versionCtrl/

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl
$ mkdir branch_merge

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl
$ cd branch_merge/

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge
$ touch chapter1.txt chapter2.txt chapter3.txt

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge
$ touch min.sass contig.t.ds _DS.store app_data.tsx aws.dsi isbn_details.md READ.ME pub.med

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge
$ touch .gitignore

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge
$ code .gitignore

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge
$ plot_summary.md characters.md scenes.jpeg cover.png
bash: plot_summary.md: command not found

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge
$ touch plot_summary.md characters.md scenes.jpeg cover.png

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge
$ mkdir author_files

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge
$ mv plot_summary.md characters.md scenes.jpeg cover.png author_files/

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge
$ code READ.ME 

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge
$ code chapter1.txt chapter2.txt chapter3.txt 

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge
$ git init
Initialized empty Git repository in C:/Users/HP-PC/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge/.git/

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (master)
$ git add -a -m "Work start - Created 3 chapters of my new book called Whispers Beyond the Horizon. Added all relevant files and metadata files"
error: unknown switch `a'
usage: git add [<options>] [--] <pathspec>...

    -n, --[no-]dry-run    dry run
    -v, --[no-]verbose    be verbose

    -i, --[no-]interactive
                          interactive picking
    -p, --[no-]patch      select hunks interactively
    -e, --[no-]edit       edit current diff and apply
    -f, --[no-]force      allow adding otherwise ignored files
    -u, --[no-]update     update tracked files
    --[no-]renormalize    renormalize EOL of tracked files (implies -u)
    -N, --[no-]intent-to-add
                          record only the fact that the path will be added later
    -A, --[no-]all        add changes from all tracked and untracked files
    --[no-]ignore-removal ignore paths removed in the working tree (same as --no-all)
    --[no-]refresh        don't add, only refresh the index
    --[no-]ignore-errors  just skip files which cannot be added because of errors
    --[no-]ignore-missing check if - even missing - files are ignored in dry run
    --[no-]sparse         allow updating entries outside of the sparse-checkout cone
    --[no-]chmod (+|-)x   override the executable bit of the listed files
    --[no-]pathspec-from-file <file>
                          read pathspec from file
    --[no-]pathspec-file-nul
                          with --pathspec-from-file, pathspec elements are separated with NUL character


HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (master)
$ git add .

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   .gitignore
        new file:   READ.ME
        new file:   author_files/characters.md
        new file:   author_files/cover.png
        new file:   author_files/plot_summary.md
        new file:   author_files/scenes.jpeg
        new file:   aws.dsi
        new file:   chapter1.txt
        new file:   chapter2.txt
        new file:   chapter3.txt
        new file:   isbn_details.md


HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (master)
$ git rm --cached -r .
rm '.gitignore'
rm 'READ.ME'
rm 'author_files/characters.md'
rm 'author_files/cover.png'
rm 'author_files/plot_summary.md'
rm 'author_files/scenes.jpeg'
rm 'aws.dsi'
rm 'chapter1.txt'
rm 'chapter2.txt'
rm 'chapter3.txt'
rm 'isbn_details.md'

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (master)
$ git add .

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   .gitignore
        new file:   READ.ME
        new file:   aws.dsi
        new file:   chapter1.txt
        new file:   chapter2.txt
        new file:   chapter3.txt
        new file:   isbn_details.md


HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (master)
$ git commit -a -m "Start work - created 3 chapters of my new book called Whispers Beyond the Horizon. Added all relevant files and metadata files"
[master (root-commit) 3c52bf4] Start work - created 3 chapters of my new book called Whispers Beyond the Horizon. Added all relevant files and metadata files
 7 files changed, 57 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 READ.ME
 create mode 100644 aws.dsi
 create mode 100644 chapter1.txt
 create mode 100644 chapter2.txt
 create mode 100644 chapter3.txt
 create mode 100644 isbn_details.md

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (master)
$ git status
On branch master
nothing to commit, working tree clean

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (master)
$ git remote add origin https://github.com/sausdeveloperr/Whispers-Beyond-the-Horizon.git

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (master)
$ git branch -M main

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git push -u origin main
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (8/8), 2.16 KiB | 441.00 KiB/s, done.
Total 8 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/sausdeveloperr/Whispers-Beyond-the-Horizon.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git commit -a -m 'Add new key words to chapter 1 and 2 to spice things up'
[main f13dd8f] Add new key words to chapter 1 and 2 to spice things up
 2 files changed, 5 insertions(+), 5 deletions(-)

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git commit chapter3.txt -m 'Add new lines to continue chapter 3'
[main 991c3cf] Add new lines to continue chapter 3
 1 file changed, 4 insertions(+)

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git log
commit 991c3cf6953e13084087b9a298fef5dfadac716c (HEAD -> main)
Author: Lekan <salamiolamilekan8991@gmail.com>
Date:   Sat May 10 17:09:54 2025 +0100

    Add new lines to continue chapter 3

commit f13dd8fb80629c42275f37ba8bf9678cda3a6c02
Author: Lekan <salamiolamilekan8991@gmail.com>
Date:   Sat May 10 17:07:40 2025 +0100

    Add new key words to chapter 1 and 2 to spice things up

commit 3c52bf447d7b220bfe1b3bc82a7be328f19d018c (origin/main)
Author: Lekan <salamiolamilekan8991@gmail.com>
Date:   Sat May 10 16:44:03 2025 +0100

    Start work - created 3 chapters of my new book called Whispers Beyond the Horizon. Added all relevant files and metadata f

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git push
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 4 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 999 bytes | 111.00 KiB/s, done.
Total 7 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (4/4), completed with 3 local objects.
To https://github.com/sausdeveloperr/Whispers-Beyond-the-Horizon.git
   3c52bf4..991c3cf  main -> main

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git commit isbn_details.md aws.dsi -m "Add ISBN metadata and AWS config details"
[main a9c5ed8] Add ISBN metadata and AWS config details
 2 files changed, 18 insertions(+)

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git log
commit a9c5ed847c1bf349194ddca727e3f470071e7177 (HEAD -> main)
Author: Lekan <salamiolamilekan8991@gmail.com>
Date:   Sat May 10 17:28:31 2025 +0100

    Add ISBN metadata and AWS config details

commit 991c3cf6953e13084087b9a298fef5dfadac716c (origin/main)
Author: Lekan <salamiolamilekan8991@gmail.com>
Date:   Sat May 10 17:09:54 2025 +0100

    Add new lines to continue chapter 3

commit f13dd8fb80629c42275f37ba8bf9678cda3a6c02
Author: Lekan <salamiolamilekan8991@gmail.com>
Date:   Sat May 10 17:07:40 2025 +0100

    Add new key words to chapter 1 and 2 to spice things up

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git commit chapter2.txt -m 'Add a new line to chapter 2 personally'
[main aea3d36] Add a new line to chapter 2 personally
 1 file changed, 2 insertions(+), 1 deletion(-)

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git push
Enumerating objects: 11, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 1.01 KiB | 114.00 KiB/s, done.
Total 7 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
To https://github.com/sausdeveloperr/Whispers-Beyond-the-Horizon.git
   991c3cf..aea3d36  main -> main

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git branch
* main

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git branch alien_theme

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git branch
  alien_theme
* main

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git checkout alien_theme
Switched to branch 'alien_theme'

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (alien_theme)
$ git branch
* alien_theme
  main

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (alien_theme)
$ git commit -a -m 'Create a new branch alien_theme to test out that theme'
[alien_theme 13a8ca8] Create a new branch alien_theme to test out that theme
 3 files changed, 21 insertions(+), 40 deletions(-)

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (alien_theme)
$ git commit -a -m 'Add said alien theme to each book chapter'
[alien_theme 5fff079] Add said alien theme to each book chapter
 3 files changed, 3 insertions(+), 3 deletions(-)

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (alien_theme)
$ git log
commit 5fff079121a5c913ffa870c40b83864aa7e0e882 (HEAD -> alien_theme)
Author: Lekan <salamiolamilekan8991@gmail.com>
Date:   Sat May 10 17:42:25 2025 +0100

    Add said alien theme to each book chapter

commit 13a8ca8e082b2074b78439d4583ee16b5acf658a
Author: Lekan <salamiolamilekan8991@gmail.com>
Date:   Sat May 10 17:40:07 2025 +0100

    Create a new branch alien_theme to test out that theme

commit aea3d366a6d3146323ef742601201b4c6d819754 (origin/main, main)
Author: Lekan <salamiolamilekan8991@gmail.com>
Date:   Sat May 10 17:30:38 2025 +0100

    Add a new line to chapter 2 personally

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (alien_theme)
$ git status
On branch alien_theme
nothing to commit, working tree clean

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (alien_theme)
$ git push -u origin alien_theme
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 4 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (10/10), 2.38 KiB | 203.00 KiB/s, done.
Total 10 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), done.
remote:
remote: Create a pull request for 'alien_theme' on GitHub by visiting:
remote:      https://github.com/sausdeveloperr/Whispers-Beyond-the-Horizon/pull/new/alien_theme
remote:
To https://github.com/sausdeveloperr/Whispers-Beyond-the-Horizon.git
 * [new branch]      alien_theme -> alien_theme
branch 'alien_theme' set up to track 'origin/alien_theme'.

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (alien_theme)
$ git branch
* alien_theme
  main

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (alien_theme)
$ touch chapter4.txt chapter5.txt

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (alien_theme)
$ code chapter4.txt chapter5.txt 

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (alien_theme)
$ git add chapter4.txt chapter5.txt

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (alien_theme)
$ git commit chapter4.txt chapter5.txt -m 'Add chapters 4 and 5 in the alien theme branch'
[alien_theme 955a23b] Add chapters 4 and 5 in the alien theme branch
 2 files changed, 36 insertions(+)
 create mode 100644 chapter4.txt
 create mode 100644 chapter5.txt

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (alien_theme)
$ git status
On branch alien_theme
Your branch is ahead of 'origin/alien_theme' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (alien_theme)
$ git log
commit 955a23b43625ec0426b5d4e671d7f7d485a5708f (HEAD -> alien_theme)
Author: Lekan <salamiolamilekan8991@gmail.com>
Date:   Sat May 10 18:08:50 2025 +0100

    Add chapters 4 and 5 in the alien theme branch

commit 5fff079121a5c913ffa870c40b83864aa7e0e882 (origin/alien_theme)
Author: Lekan <salamiolamilekan8991@gmail.com>
Date:   Sat May 10 17:42:25 2025 +0100

    Add said alien theme to each book chapter

commit 13a8ca8e082b2074b78439d4583ee16b5acf658a
Author: Lekan <salamiolamilekan8991@gmail.com>
Date:   Sat May 10 17:40:07 2025 +0100

    Create a new branch alien_theme to test out that theme

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (alien_theme)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.63 KiB | 835.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/sausdeveloperr/Whispers-Beyond-the-Horizon.git
   5fff079..955a23b  alien_theme -> alien_theme

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (alien_theme)
$ git branch
* alien_theme
  main

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (alien_theme)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git checkout alien_theme
Switched to branch 'alien_theme'
Your branch is up to date with 'origin/alien_theme'.

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (alien_theme)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git commit -a -m 'Do thesaurus works on all chapters'
[main 969afc8] Do thesaurus works on all chapters
 3 files changed, 5 insertions(+), 5 deletions(-)

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git push -u origin main
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 616 bytes | 205.00 KiB/s, done.
Total 5 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To https://github.com/sausdeveloperr/Whispers-Beyond-the-Horizon.git
   aea3d36..969afc8  main -> main
branch 'main' set up to track 'origin/main'.

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git commit -a -m 'Do more thesaurus works on all chapters'
[main 6e57a77] Do more thesaurus works on all chapters
 3 files changed, 3 insertions(+), 3 deletions(-)

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git push
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 591 bytes | 295.00 KiB/s, done.
Total 5 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To https://github.com/sausdeveloperr/Whispers-Beyond-the-Horizon.git
   969afc8..6e57a77  main -> main

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ merge alien_theme
bash: merge: command not found

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git merge alien_theme
Auto-merging chapter1.txt
CONFLICT (content): Merge conflict in chapter1.txt
Auto-merging chapter2.txt
CONFLICT (content): Merge conflict in chapter2.txt
Auto-merging chapter3.txt
CONFLICT (content): Merge conflict in chapter3.txt
Automatic merge failed; fix conflicts and then commit the result.

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main|MERGING)
$ git add .

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main|MERGING)
$ git commit -a -m "Merge alien to main - Resolved merge conflicts"
[main 6c53fa6] Merge alien to main - Resolved merge conflicts

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 339 bytes | 339.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/sausdeveloperr/Whispers-Beyond-the-Horizon.git
   6e57a77..6c53fa6  main -> main

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git branch
  alien_theme
* main

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ git checkout alien_theme
Switched to branch 'alien_theme'
Your branch is up to date with 'origin/alien_theme'.

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (alien_theme)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ touch b_m_terminal_history.md

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ code b_m_terminal_history.md

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ mkdir others

HP-PC@SWIFTWEBBER-ILM4KF7 MINGW64 ~/Documents/Salami Olamilekan/MERN/JS/git_versionCtrl/branch_merge (main)
$ mv aws.dsi min.sass config.t.ds pub.med app_data.tsx _DS.store others/