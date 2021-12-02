# Andersen1
First Andersen HomeWork

My Steps:

git init

git add *

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/ExSaw/Andersen1.git

git remote set-url origin https://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@github.com/ExSaw/Andersen1

git push -u origin main

git branch Dev

git checkout Dev

git add *

git commit -m "first Dev branch commit"

git add *

git commit -m "added RU locales"

git status

git push -u origin Dev

git add *

git commit -m "added second textView"

git push -u origin Dev

git status

//simulating hotfix

git checkout -b hotfix

git status

git add *

git commit -m "fixed AndroidManifest"

git push -u origin hotfix

git checkout main

git merge hotfix

git branch -d hotfix

//git push origin --delete hotfix

git add *

git status

git push -u origin main

//Dev is depricated now! Solving this problem...

git checkout dev

git merge main //dev is now up to date

git status

git add *

git commit -m "sync with main"

git push -u origin Dev

git checkout main

git merge Dev
