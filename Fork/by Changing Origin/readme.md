*If you can't fork because GitHub's interface doesn't work? Make a new archive.repo, clone the desired Fork, and change it's origin to your archive.repo.

https://www.google.com/search?q=git+change+origin

https://kodekloud.com/blog/change-remote-origin-in-git/

```
newOrigin=my.git.net/aForkedRepo
git remote -v
git remote set-url command $newOrigin
```
