1. Composer install
2. Create database and set data connection in config/db.php file
3. Run below commands

```   
yii migrate --migrationPath=@mdm/admin/migrations
yii migrate --migrationPath=@yii/rbac/migrations
```
    
