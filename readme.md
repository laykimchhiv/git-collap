#check branch
```bash
git branch
```

#change branch
```bash
git fetch origin
gti checkout <branch-name>
```


#create new branch
```bash
git add .
git commit -m "message"
git branch <branch-name>
gti checkout <branch-name>
```

#to work with local branch
```bash
#create new branch
git branch <branch-name>
gti checkout <branch-name>

#when finish code in new branch
git add.
git commit -m "message"

 #switch from new branch to main branch
 git checkout main

 #merge new branch to mian branch
 git merge <new branch>

