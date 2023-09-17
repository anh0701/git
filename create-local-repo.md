# create folder/project in local before create repo in github
1. Problem
- create folder/project in computer
- after create new repo 
2. Resolve
- step 1: git init
- step 2: git remote add origin  URL-REPO
- step 2: git remote -v => to check
- step 3: git checkout -b main => switch to branch main
- step 4: git pull origin main
- step 5: git add .
- step 6: git commit -m "..{messgae}.."
- step 7: git push origin main 