# notes

PS C:\Users\Noona\Documents\web_kehitysperusteet_23\Git_harjotus> git clone https://github.com/mattpe/git-intro.git
Cloning into 'git-intro'...
remote: Enumerating objects: 68, done.
remote: Counting objects: 100% (18/18), done.
remote: Compressing objects: 100% (13/13), done.
Receiving objects: 100% (68/68), 419.78 KiB | 5.45 MiB/s, done.
remote: Total 68 (delta 5), reused 17 (delta 4), pack-reused 50
Resolving deltas: 100% (30/30), done.
PS C:\Users\Noona\Documents\web_kehitysperusteet_23\Git_harjotus> git init  
Initialized empty Git repository in C:/Users/Noona/Documents/web_kehitysperusteet_23/Git_harjotus/.git/
PS C:\Users\Noona\Documents\web_kehitysperusteet_23\Git_harjotus> cd .\git-intro\.git\
PS C:\Users\Noona\Documents\web_kehitysperusteet_23\Git_harjotus\git-intro\.git> cd ..
PS C:\Users\Noona\Documents\web_kehitysperusteet_23\Git_harjotus\git-intro> git init
Reinitialized existing Git repository in C:/Users/Noona/Documents/web_kehitysperusteet_23/Git_harjotus/git-intro/.git/
PS C:\Users\Noona\Documents\web_kehitysperusteet_23\Git_harjotus\git-intro> git remote remove origin
PS C:\Users\Noona\Documents\web_kehitysperusteet_23\Git_harjotus\git-intro> git remotr add origin https://github.com/NoonaJessica/git_harjotus.git
git: 'remotr' is not a git command. See 'git --help'.

The most similar command is
remote
PS C:\Users\Noona\Documents\web_kehitysperusteet_23\Git_harjotus\git-intro> git remote add origin https://github.com/NoonaJessica/git_harjotus.git
PS C:\Users\Noona\Documents\web_kehitysperusteet_23\Git_harjotus\git-intro> git push -u origin main
Enumerating objects: 62, done.
Counting objects: 100% (62/62), done.
Delta compression using up to 8 threads
Compressing objects: 100% (34/34), done.
Writing objects: 100% (62/62), 417.91 KiB | 139.30 MiB/s, done.
Total 62 (delta 25), reused 61 (delta 25), pack-reused 0
remote: Resolving deltas: 100% (25/25), done.
To https://github.com/NoonaJessica/git_harjotus.git

- [new branch] main -> main
  branch 'main' set up to track 'origin/main'.
  PS C:\Users\Noona\Documents\web_kehitysperusteet_23\Git_harjotus\git-intro> git add notes.md
  fatal: pathspec 'notes.md' did not match any files
  PS C:\Users\Noona\Documents\web_kehitysperusteet_23\Git_harjotus\git-intro> git commit -m "lisätty notes"
  On branch main
  Your branch is up to date with 'origin/main'.

Untracked files:
(use "git add <file>..." to include in what will be committed)
notes.md

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\Noona\Documents\web_kehitysperusteet_23\Git_harjotus\git-intro> git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
add
PS C:\Users\Noona\Documents\web_kehitysperusteet_23\Git_harjotus\git-intro> git add notes.md
PS C:\Users\Noona\Documents\web_kehitysperusteet_23\Git_harjotus\git-intro> git commit -m " lisätty notes"
[main 1ed0008] lisätty notes
1 file changed, 0 insertions(+), 0 deletions(-)
create mode 100644 notes.md
PS C:\Users\Noona\Documents\web_kehitysperusteet_23\Git_harjotus\git-intro> git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 275 bytes | 275.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/NoonaJessica/git_harjotus.git
5327158..1ed0008 main -> main
PS C:\Users\Noona\Documents\web_kehitysperusteet_23\Git_harjotus\git-intro>
