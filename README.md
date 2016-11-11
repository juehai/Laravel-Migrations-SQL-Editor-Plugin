# Laravel Migrations Plugin for SQLEditor

Exports [Laravel database migrations](https://laravel.com/docs/5.3/migrations#modifying-columns).

### Outputs
```php
Schema::create(<dbname>, ...);
Schema::drop(<dbname>, ...);
```

### Not implemented
1.	`change();`
2. `renameColumn();`
3. `dropColumn;`
4. custom index names
