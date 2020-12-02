Configure your local repository to push to the cPanel-hosted repository :

```
# untuk frontend
git remote add hosting ssh://developer@hilmy.website:64000/home/hilmyweb/repositories/hrms-frontend

# untuk backend
git remote add hosting ssh://developer@hilmy.website:64000/home/hilmyweb/repositories/hrms-backend

git push -u hosting master
```

Seed and migrations :

```
php artisan migrate:fresh --seed
```
