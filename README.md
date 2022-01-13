
                  3-1 github Module Introduction

  1. Git SCM download = cmd ->git –version
  2. GitHub download
  
Source code management (SCM)

                  3-2 Install git, create GitHub repository

cd.. (folder path)

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin git@github.com:hamidhosen42/ProgrammingHero.git 

git push -u origin main

                    3-3 Introduction to Git init, git add, git commit

echo "# Programming-Hero" >> README.md

git init

git add .

git commit -m "first commit"

git branch -M main

git remote add origin git@github.com:hamidhosen42/ProgrammingHero.git 

git push -u origin main

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
