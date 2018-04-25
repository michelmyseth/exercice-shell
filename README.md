#exercice-shell
# exercice-shell

/home/MadBoy/.babunrc:36: unmatched "
{ Documents } master » ls                                                                                                                                        /c/Users/MadBoy/Documents
desktop.ini  FeedbackHub  formation_coder  Ma musique  Mes images  Mes vidéos  Test Report
{ Documents } master » cd formation_coder                                                                                                                        /c/Users/MadBoy/Documents
{ formation_coder } master » ls                                                                                                                  /c/Users/MadBoy/Documents/formation_coder
html-base  Jaime_le_shell
{ formation_coder } master » cd jaime_le_shell                                                                                                   /c/Users/MadBoy/Documents/formation_coder
{ jaime_le_shell } master » ls                                                                                                    /c/Users/MadBoy/Documents/formation_coder/jaime_le_shell
le_shell_cest_trop_cool!  README.md  test2  test3  test4  test6
{ jaime_le_shell } master » echo                                                                                                  /c/Users/MadBoy/Documents/formation_coder/jaime_le_shell

{ jaime_le_shell } master » echo "# exercice-shell">> READ.md                                                                     /c/Users/MadBoy/Documents/formation_coder/jaime_le_shell
{ jaime_le_shell } master » git init                                                                                              /c/Users/MadBoy/Documents/formation_coder/jaime_le_shell
Reinitialized existing Git repository in /cygdrive/c/Users/MadBoy/Documents/formation_coder/jaime_le_shell/.git/
{ jaime_le_shell } master » git status                                                                                            /c/Users/MadBoy/Documents/formation_coder/jaime_le_shell
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

        READ.md

nothing added to commit but untracked files present (use "git add" to track)
{ jaime_le_shell } master » echo "# exercice-shell">> README.md                                                                   /c/Users/MadBoy/Documents/formation_coder/jaime_le_shell
{ jaime_le_shell } master » git init                                                                                              /c/Users/MadBoy/Documents/formation_coder/jaime_le_shell
Reinitialized existing Git repository in /cygdrive/c/Users/MadBoy/Documents/formation_coder/jaime_le_shell/.git/
{ jaime_le_shell } master » git status                                                                                            /c/Users/MadBoy/Documents/formation_coder/jaime_le_shell
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        READ.md

no changes added to commit (use "git add" and/or "git commit -a")
{ jaime_le_shell } master » git add README.md                                                                                     /c/Users/MadBoy/Documents/formation_coder/jaime_le_shell
{ jaime_le_shell } master » git commit -m "premier exercice shell"                                                                /c/Users/MadBoy/Documents/formation_coder/jaime_le_shell
[master a0d7e06] premier exercice shell
 1 file changed, 1 insertion(+)
{ jaime_le_shell } master » git remote add origin https://github.com/michelmyseth/exercice-shell.bit                              /c/Users/MadBoy/Documents/formation_coder/jaime_le_shell
fatal: remote origin already exists.
{ jaime_le_shell } master  » git push -u origin master # exercice-shell
