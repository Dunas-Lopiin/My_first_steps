https://github.com/Dunas-Lopiin/My_first_steps 

oinil@LAPTOP-JM4GAN0A MINGW64 ~/Desktop/My_first_steps (main)
$ git remote add origin git@github.com:Dunas-Lopiin/My_first_steps.git

oinil@LAPTOP-JM4GAN0A MINGW64 ~/Desktop/My_first_steps (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 298 bytes | 74.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:Dunas-Lopiin/My_first_steps.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

oinil@LAPTOP-JM4GAN0A MINGW64 ~/Desktop/My_first_steps (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ola_mundo.txt
nothing added to commit but untracked files present (use "git add" to track)

oinil@LAPTOP-JM4GAN0A MINGW64 ~/Desktop/My_first_steps (main)
$ git add .

oinil@LAPTOP-JM4GAN0A MINGW64 ~/Desktop/My_first_steps (main)
$ git commit -m "commit com o olá mundo nele"
[main 96e75e6] commit com o olá mundo nele
 1 file changed, 3 insertions(+)
 create mode 100644 ola_mundo.txt

oinil@LAPTOP-JM4GAN0A MINGW64 ~/Desktop/My_first_steps (main)
$ git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 390 bytes | 130.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:Dunas-Lopiin/My_first_steps.git
   e77ea1a..96e75e6  main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

serei_ignorado.txt