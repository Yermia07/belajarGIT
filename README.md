Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GiT
…
Yersolid@Clays-MacBook-Pro ~ % cd belajarGIT
Yersolid@Clays-MacBook-Pro belajarGIT % git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'
Yersolid@Clays-MacBook-Pro belajarGIT % touch Tugas-Git.txt
Yersolid@Clays-MacBook-Pro belajarGIT % ls
README.md	Tugas-Git.txt
Yersolid@Clays-MacBook-Pro belajarGIT % nano Tugas-Git.txt
Yersolid@Clays-MacBook-Pro belajarGIT % nano Tugas-Git.txt
Yersolid@Clays-MacBook-Pro belajarGIT % nano Tugas-Git.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git add .
Yersolid@Clays-MacBook-Pro belajarGIT % git commit -m "Menambahkan isi ke file Tugas-Git.txt"
[Tugas-git 4b4688a] Menambahkan isi ke file Tugas-Git.txt
 Committer: Yersolid <Yersolid@Clays-MacBook-Pro.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 3 insertions(+)
 create mode 100644 Tugas-Git.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git config --global user.name "Yermia Turangan"
Yersolid@Clays-MacBook-Pro belajarGIT % git config --global user.email "yermiaturangan07@gmail.com"
Yersolid@Clays-MacBook-Pro belajarGIT % git log
commit 4b4688a5cd6841f96bd1a6514bb548d56b9f4235 (HEAD -> Tugas-git)
Author: Yersolid <Yersolid@Clays-MacBook-Pro.local>
Date:   Mon Mar 11 15:55:48 2024 +0800

    Menambahkan isi ke file Tugas-Git.txt

commit 5bf1fadef9d49bf2c784a4d10ea8ff2efeefaea6 (origin/main, origin/HEAD, main)
Author: Yermia07 <118597873+Yermia07@users.noreply.github.com>
Date:   Mon Mar 11 15:40:43 2024 +0800

    Update README.md

commit 7de662a3f37e10ff60c306cfc77b914888d0252f
Author: Yermia07 <118597873+Yermia07@users.noreply.github.com>
Date:   Mon Mar 11 15:40:01 2024 +0800

    Initial commit
Yersolid@Clays-MacBook-Pro belajarGIT % git config --global --edit
hint: Waiting for your editor to close the file... 
zsh: suspended  git config --global --edit
Yersolid@Clays-MacBook-Pro belajarGIT % git config --global --edit
hint: Waiting for your editor to close the file... error: There was a problem with the editor 'vi'.
Yersolid@Clays-MacBook-Pro belajarGIT % git config --global --edit
hint: Waiting for your editor to close the file... 
zsh: suspended  git config --global --edit
Yersolid@Clays-MacBook-Pro belajarGIT % git log
commit 4b4688a5cd6841f96bd1a6514bb548d56b9f4235 (HEAD -> Tugas-git)
Author: Yersolid <Yersolid@Clays-MacBook-Pro.local>
Date:   Mon Mar 11 15:55:48 2024 +0800

    Menambahkan isi ke file Tugas-Git.txt

commit 5bf1fadef9d49bf2c784a4d10ea8ff2efeefaea6 (origin/main, origin/HEAD, main)
Author: Yermia07 <118597873+Yermia07@users.noreply.github.com>
Date:   Mon Mar 11 15:40:43 2024 +0800

    Update README.md

commit 7de662a3f37e10ff60c306cfc77b914888d0252f
Author: Yermia07 <118597873+Yermia07@users.noreply.github.com>
Date:   Mon Mar 11 15:40:01 2024 +0800

    Initial commit
Yersolid@Clays-MacBook-Pro belajarGIT % git branch
* Tugas-git
  main
Yersolid@Clays-MacBook-Pro belajarGIT % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
Yersolid@Clays-MacBook-Pro belajarGIT % git merge Tugas-git
Updating 5bf1fad..4b4688a
Fast-forward
 Tugas-Git.txt | 3 +++
 1 file changed, 3 insertions(+)
 create mode 100644 Tugas-Git.txt
Yersolid@Clays-MacBook-Pro belajarGIT % ls
README.md	Tugas-Git.txt
Yersolid@Clays-MacBook-Pro belajarGIT % nano Tugas-Git.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git remote -v
origin	https://github.com/Yermia07/belajarGIT.git (fetch)
origin	https://github.com/Yermia07/belajarGIT.git (push)
Yersolid@Clays-MacBook-Pro belajarGIT % git push -u origin main
Username for 'https://github.com': Yermia07
Password for 'https://Yermia07@github.com': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 428 bytes | 428.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Yermia07/belajarGIT.git
   5bf1fad..4b4688a  main -> main
branch 'main' set up to track 'origin/main'.
Yersolid@Clays-MacBook-Pro belajarGIT % git branch
  Tugas-git
* main
Yersolid@Clays-MacBook-Pro belajarGIT % git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'
Yersolid@Clays-MacBook-Pro belajarGIT % git branch
  Tugas-git
* Tugas-html
  main
Yersolid@Clays-MacBook-Pro belajarGIT % touch Tugas-HTML.txt
Yersolid@Clays-MacBook-Pro belajarGIT % ls
README.md	Tugas-Git.txt	Tugas-HTML.txt
Yersolid@Clays-MacBook-Pro belajarGIT % nano Tugas-HTML.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
Yersolid@Clays-MacBook-Pro belajarGIT % git branch
  Tugas-git
  Tugas-html
* main
Yersolid@Clays-MacBook-Pro belajarGIT % git merge Tugas-html
Already up to date.
Yersolid@Clays-MacBook-Pro belajarGIT % git checkout Tugas-html
Switched to branch 'Tugas-html'
Yersolid@Clays-MacBook-Pro belajarGIT % ls   
README.md	Tugas-Git.txt	Tugas-HTML.txt
Yersolid@Clays-MacBook-Pro belajarGIT % nano Tugas-HTML.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git add .
Yersolid@Clays-MacBook-Pro belajarGIT % git commit -m "Menambahkan isi file Tugas-HTML.txt"
[Tugas-html 1ce73fc] Menambahkan isi file Tugas-HTML.txt
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-HTML.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git branch
  Tugas-git
* Tugas-html
  main
Yersolid@Clays-MacBook-Pro belajarGIT % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
Yersolid@Clays-MacBook-Pro belajarGIT % git merge Tugas-html
Updating 4b4688a..1ce73fc
Fast-forward
 Tugas-HTML.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-HTML.txt
Yersolid@Clays-MacBook-Pro belajarGIT % gut push -u origin main
zsh: command not found: gut
Yersolid@Clays-MacBook-Pro belajarGIT % git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 416 bytes | 416.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Yermia07/belajarGIT.git
   4b4688a..1ce73fc  main -> main
branch 'main' set up to track 'origin/main'.
Yersolid@Clays-MacBook-Pro belajarGIT % git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'
Yersolid@Clays-MacBook-Pro belajarGIT % git branch
* Tugas-css
  Tugas-git
  Tugas-html
  main
Yersolid@Clays-MacBook-Pro belajarGIT % touch Tugas-CSS.txt
Yersolid@Clays-MacBook-Pro belajarGIT % ls
README.md	Tugas-CSS.txt	Tugas-Git.txt	Tugas-HTML.txt
Yersolid@Clays-MacBook-Pro belajarGIT % nano Tugas-CSS.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git add Tugas-CSS.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git commit -m "Menambahkan isi file Tugas-CSS.txt"
[Tugas-css e76563b] Menambahkan isi file Tugas-CSS.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-CSS.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git branch 
* Tugas-css
  Tugas-git
  Tugas-html
  main
Yersolid@Clays-MacBook-Pro belajarGIT % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
Yersolid@Clays-MacBook-Pro belajarGIT % git branch
  Tugas-css
  Tugas-git
  Tugas-html
* main
Yersolid@Clays-MacBook-Pro belajarGIT % git merge Tugas-css
Updating 1ce73fc..e76563b
Fast-forward
 Tugas-CSS.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-CSS.txt
Yersolid@Clays-MacBook-Pro belajarGIT % ls
README.md	Tugas-CSS.txt	Tugas-Git.txt	Tugas-HTML.txt
Yersolid@Clays-MacBook-Pro belajarGIT % nano Tugas-CSS.txt
Yersolid@Clays-MacBook-Pro belajarGIT % nano README.md
Yersolid@Clays-MacBook-Pro belajarGIT % git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'
Yersolid@Clays-MacBook-Pro belajarGIT % git branch
  Tugas-css
  Tugas-git
  Tugas-html
* Tugas-js
  main
Yersolid@Clays-MacBook-Pro belajarGIT % touch Tugas-JS.txt 
Yersolid@Clays-MacBook-Pro belajarGIT % ls
README.md	Tugas-CSS.txt	Tugas-Git.txt	Tugas-HTML.txt	Tugas-JS.txt
Yersolid@Clays-MacBook-Pro belajarGIT % nano Tugas-JS.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git add Tugas-JS.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git commit -m "menambahkan isi file Tugas-JS.txt"
[Tugas-js 24ef3e6] menambahkan isi file Tugas-JS.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-JS.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)
Yersolid@Clays-MacBook-Pro belajarGIT % git merge Tugas-js 
Updating e76563b..24ef3e6
Fast-forward
 Tugas-JS.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-JS.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git push -u origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 672 bytes | 672.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Yermia07/belajarGIT.git
   1ce73fc..24ef3e6  main -> main
branch 'main' set up to track 'origin/main'.
Yersolid@Clays-MacBook-Pro belajarGIT % git checkout -b Tugas-midProject 
Switched to a new branch 'Tugas-midProject'
Yersolid@Clays-MacBook-Pro belajarGIT % git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
* Tugas-midProject
  main
Yersolid@Clays-MacBook-Pro belajarGIT % touch Tugas-MidProject.txt
Yersolid@Clays-MacBook-Pro belajarGIT % nano Tugas-MidProject.txt
Yersolid@Clays-MacBook-Pro belajarGIT % ls
README.md		Tugas-Git.txt		Tugas-JS.txt
Tugas-CSS.txt		Tugas-HTML.txt		Tugas-MidProject.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git add Tugas-MidProject.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git commit -m "Menambahkan isi file TUgas-MidProject.txt"
[Tugas-midProject fe25ff5] Menambahkan isi file TUgas-MidProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
Yersolid@Clays-MacBook-Pro belajarGIT % git push -u origin main
branch 'main' set up to track 'origin/main'.
Everything up-to-date
Yersolid@Clays-MacBook-Pro belajarGIT % git merge Tugas-midProject
Updating 24ef3e6..fe25ff5
Fast-forward
 Tugas-MidProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git push -u origin main   
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 351 bytes | 351.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Yermia07/belajarGIT.git
   24ef3e6..fe25ff5  main -> main
branch 'main' set up to track 'origin/main'.
Yersolid@Clays-MacBook-Pro belajarGIT % git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'
Yersolid@Clays-MacBook-Pro belajarGIT % git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
* Tugas-php
  main
Yersolid@Clays-MacBook-Pro belajarGIT % touch Tugas-PHP.txt 
Yersolid@Clays-MacBook-Pro belajarGIT % nano Tugas-PHP.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git add Tugas-PHP.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git commit -m "Menambahkan isi file Tugas-PHP.txt
dquote> "                    
[Tugas-php 170fd87] Menambahkan isi file Tugas-PHP.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-PHP.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
Yersolid@Clays-MacBook-Pro belajarGIT % git merge Tugas-php
Updating fe25ff5..170fd87
Fast-forward
 Tugas-PHP.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-PHP.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 345 bytes | 345.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Yermia07/belajarGIT.git
   fe25ff5..170fd87  main -> main
branch 'main' set up to track 'origin/main'.
Yersolid@Clays-MacBook-Pro belajarGIT % git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'
Yersolid@Clays-MacBook-Pro belajarGIT % touch Tugas-FinalProject.txt
Yersolid@Clays-MacBook-Pro belajarGIT % nano Tugas-FinalProject.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git add Tugas-FinalProject.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git commit -m "Menambahkan isi file Tugas-FinalProject.txt"
[Tugas-finalProject 54f8006] Menambahkan isi file Tugas-FinalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
Yersolid@Clays-MacBook-Pro belajarGIT % git merge Tugas-finalProject
Updating 170fd87..54f8006
Fast-forward
 Tugas-FinalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt
Yersolid@Clays-MacBook-Pro belajarGIT % git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 350 bytes | 350.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Yermia07/belajarGIT.git
   170fd87..54f8006  main -> main
branch 'main' set up to track 'origin/main'.
Yersolid@Clays-MacBook-Pro belajarGIT % ls   
README.md		Tugas-Git.txt		Tugas-MidProject.txt
Tugas-CSS.txt		Tugas-HTML.txt		Tugas-PHP.txt
Tugas-FinalProject.txt	Tugas-JS.txt

