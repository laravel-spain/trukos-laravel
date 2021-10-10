# trukos-laravel

# Create a project 
```
composer create-project laravel/laravel nameproject
composer create-project laravel/laravel nameproject "6.*"
cd nameproject
php artisan serve
```

# Run a project 
```
php artisan serve
```


# Install Mysql
```
brew install mysql
brew services start mysql
mysql_secure_installation
mysql -u root -p
create database demo
```

# Create a Model
```
php artisan make:model students -a
```

/Users/marlonfalcon/Documents/php/bloglaravel/database/migrations/2021_10_10_200942_create_students_table.php
```
Schema::create('students', function (Blueprint $table) {
            $table->id();
            $table->string(column: 'name')->nullable();
            $table->boolean(column: 'active')->nullable();
            $table->timestamps();
        });
```
