Configure your local repository to push to the cPanel-hosted repository :

```
git remote add hosting ssh://hilmyweb@hilmy.website:64000/home/hilmyweb/repositories/hrms-{frontend|backend}
git push -u hosting master
```
