# anota-GIT


Initialized empty Git repository in C:/Users/danie/OneDrive/Área de Trabalho/Nova pasta (2)/lc-challenges-python/code/.git/
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git add .\README.md
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git status
On branch master

No commits yet

Changes to be committed:
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)  
        modified:   README.md

PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git diff
diff --git a/README.md b/README.md
index e17ec72..8ecf780 100644
--- a/README.md
+++ b/README.md
@@ -1,5 +1,4 @@
 # curso digital-git


-# gravando mudanças no repositório
-
+# salvando modificações no git
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git add .\README.md
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git diff
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code>
fwd-i-search: _


PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git diff --staged
diff --git a/README.md b/README.md
new file mode 100644
index 0000000..8ecf780
--- /dev/null
+++ b/README.md
@@ -0,0 +1,4 @@
+# curso digital-git
+
+
+# salvando modificações no git
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git commit -m "add new title"
[master (root-commit) 49e4742] add new title
 1 file changed, 4 insertions(+)
 create mode 100644 README.md
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git diff
diff --git a/README.md b/README.md
index 8ecf780..99ff6e2 100644
--- a/README.md
+++ b/README.md
@@ -1,4 +1,4 @@
-# curso digital-git
+# curso Digital: git

+## salvando alterações no git

-# salvando modificações no git
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git add .\README.md
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-ch -m "add new title"
[master 4e12f2f] add new title  
 1 file changed, 2 insertions(+), 2 deletions(-)
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git log   
commit 4e12f2f0fa76176d70a263bfa8b84f39dc054224 (HEAD -> master)

Author: Bowie <starsnanda2@gmail.com>
Date:   Sat Nov 4 08:01:25 2023 -0300

    add new title

commit 49e474241f6dfec97722786ac2c4b690527599c1
Author: Bowie <starsnanda2@gmail.com>
Date:   Sat Nov 4 07:57:42 2023 -0300

    add new title
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-pythqn\code>
 ion
    + FullyQualifiedErrorId :
   CommandNotFoundException

PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git restore .\README.md
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git add .\README.md
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code>          git add .\README.md
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git commit -m "add new command"
[master 9d13db8] add new command
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git remote
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git push origin master
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git remote origin
error: unknown subcommand: `origin'
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename [--[no-]progress] <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand 

PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git push origin master
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> master

PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git fetch
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> master

PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git branch testing
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git log --oneline --decorate
9d13db8 (HEAD -> master, testing) add new command
4e12f2f add new title
49e4742 add new title
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> q
dlet, função, arquivo
de script ou programa operável. Verifique a grafia do nome ou, se um
caminho tiver sido incluído, veja se o caminho está correto e tente
novamente.
No linha:1 caractere:1
+ q
+ ~
    + CategoryInfo          : ObjectNotFound: (q:String) [], CommandNot
   FoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git checkout testing
Switched to branch 'testing'
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git log --oneline --decorate
9d13db8 (HEAD -> testing, master) add new command

4e12f2f add new title
49e4742 add new title
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-git checkout master         
Switched to branch 'master'
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git branch
* master
  testing
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code> git branch testing
fatal: a branch named 'testing' already exists
PS C:\Users\danie\OneDrive\Área de Trabalho\Nova pasta (2)\lc-challenges-python\code>
