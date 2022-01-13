### github-push-command

                    Module 3-Git, source control,GitHub and hosting

3-1 github Module Introduction
  1. Git SCM download = cmd ->git –version
  2. GitHub download
Source code management (SCM)
3-2 Install git, create GitHub repository
cd.. (folder path)
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:hamidhosen42/ProgrammingHero.git git push -u origin main
3-3 Introduction to Git init, git add, git commit
echo "# Programming-Hero" >> README.md
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:hamidhosen42/ProgrammingHero.git git push -u origin main
if : git@github.com: Permission denied (publickey).
1. git remote rm origin
2. git remote add origin https://github.com/hamidhosen42/simple_portfolio.git
3-4 Set origin, Git push, git pull, and repo overview
If author identity unknown:
git config –global user.email “mdhamidhosen8444@gmail.com”
git config –global user.name “hamidhosen42”
3-5 Send small incremental changes to github
1. git add .
2. git commit -m "first commit"
3. git push
or -> if problem
4. git push origin main –f
3-6 Host simple website in gitHub using gh-pages
Setting -> page= main->save
3-7 Common github related issues faced by new developer
3-8 [advanced] Create git branch, merge branches
Commend link: https://github.com/joshnh/Git-Commands
List branches (the asterisk denotes the
git branch current branch)
git branch -a List all branches (local and remote)
git branch [branch name] Create a new branch
git branch -d [branch name] Delete a branch
git push origin --delete [branch name] Delete a remote branch
git checkout -b [branch name] Create a new branch and switch to it
git checkout -b [branch name] Clone a remote branch and switch to it origin/[branch name]
git branch - m [old branch name] [new Rename a local branch branch name]
git checkout [branch name] Switch to a branch
git checkout - Switch to the branch last checked out
git checkout -- [file-name.txt] Discard changes to a file
git merge [branch name] Merge a branch into the active branch
git merge [source branch] [target Merge a branch into a target branch branch]
git stash Stash changes in a dirty working directory
git stash clear Remove all stashed entries
Main Branch to push another Branch:-> git branch
1. git branch
2. git branch image-add = git branch branch_name
3. git branch
4. git checkout image-add = git checkout
branch_name ->html or other file code adit
5. git add .
6. git commit -m"added paragraph"
7. git push
8. git push --set-upstream origin image-add
Branch to main Branch Change: ->marge
1. git branch
2. git checkout main
3. git merge image-add = git merge branch_name
or
4. git push origin main –f
3-9 [advanced ] git pull, toggle branch, merge conflict
Branch create:
1. git branch
2. 2.1-git branch image-add = git branch branch_name or 2.1-git checkout -b add-blog
3. 2.1-git branch
4. 2.1-git checkout image-add = git checkout
branch_name ->html or other file code adit
5. 2.1-git add .
6. 2.1-git commit -m"added paragraph"
7. 2.1-git push
8. 2.1-git push --set-upstream origin image-add
9. 2.2- git commit -m"added paragraph"
10. 2.2- git status
11. 2.2-git add .
12. 2.2- git commit -m"hamid"
13. 2.2- git push
14. 2.2- git push --set-upstream origin image-add
Branch to main Branch Change: -> merge conflict
1. git branch
2. git checkout main
3. git merge image-add = git merge branch_name
or
4. git push origin main –f
3-10 GitHub module overall summary
