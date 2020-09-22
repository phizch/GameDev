# How to use GitHub and Git in general

## How to sync your fork's master branch
```
git fetch upstream
git reset --hard upstream/master
git push --force
```
This will avoid "1 commit ahead" that a pull would produce.  
Note : It will also delete any changes you've made on your local master branch.  
It will leave any branches you've made unchanged.
