```
১. তোমার কম্পিউটারে একটা ফোল্ডার খুলবে এবং কমান্ডলাইন দিয়ে সেই ফোল্ডারে যাবে। 
২. যে যে এসাইনমেন্ট এর জন্য প্রাইভেট রিপোজিটরি কে পাবলিক করতে চাও আমাদের ওয়েবসাইট এ গিয়ে সেটা ওপেন করো। ওপেন করার লিংক তোমার github এর হোম পেইজে গেলে বামপাশে দেখতে পাবে। অথবা আমাদের ওয়েবসাইট এ এসাইনমেন্ট এ গিলে your submission এ গেলে লিংক দেখতে পাবে। এমনকি এসাইনমেন্ট সাবমিট করার লিংক এ ক্লিক করলেও দেখতে পাবে। সেই লিংক ওপেন করে .git ওয়ালা লিংক কপি নিয়ে নিয়ে এসে নিচের কমান্ড চালাও 
git clone --bare assignmentRepoURL
৪. cd করে কমান্ড লাইন দিয়ে নতুন যেটা ক্লোন করেছো সেই ফোল্ডার এর ভিতরে ঢুকো 
৫. তোমার গিটহাব একাউন্টে গিয়ে এ নতুন একটা পাবলিক রিপো খুলে সেটার .git ওয়ালা লিংক কপি করে নিয়ে এসে নিচের মতো করে বসাও 
git push --mirror publicRepoURL 
```

```
যদি কোন github থেকে কোড clone করার পর নতুন repository তে রাখতে চাই তাহলে 
1. git remote -v
2. git remote set-url (যে নতুন repository তে রাখবো তার লিংক)
```



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
