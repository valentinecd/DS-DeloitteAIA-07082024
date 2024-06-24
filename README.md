# DS-DeloitteAIA-07082024
Course repo for Deloitte AI Academy beginning 08 July 2024


# Instructions to Connect to this Repository:
We will be going through this workflow several times during the first week of class - no rush!

1. FORK this repository, creating a copy on your own GitHub account

2. Then clone **your fork** down to your local computer

```
git clone https://github.com/[your-username]/DS-DeloitteAIA-07082024
```

3. Add the ```/flatiron-school/``` version as the upstream (to pull future changes)  
```
 git remote add upstream https://github.com/flatiron-school/DS-DeloitteAIA-07082024
```

4. You can make changes to the notebooks now! Remember to push your changes to your forked version of the repo (to put your local changes up online):
```
git add [filename]
git commit -m 'message here'
git push
```
**Whenever you want to get updated notes:**

5. Grab the changes from the upstream repo
 ```
git fetch upstream
```  
6. Merge new changes onto your local repo
```
git merge upstream/main -m "meaningful message about what you're updating"

NOTE: A 'meaningful message' describes briefly the changes that the commit makes to the code.
