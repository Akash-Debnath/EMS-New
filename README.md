### Repository URL of Old Version of EMS is here - 

https://github.com/Akash-Debnath/EMS-Old-Version)



<hr>
## Project Setup:

### 1. Clone the repo to htdocs or www folder

```
git clone gslgit@192.168.10.63:/home/gslgit/ems2.1.git
```

### 2. go to the directory 
```
cd ems2.1
```

### 3. Install Composer
```
composer install
```

### 3.1 Composer update
```
composer update
```

### 3.2 Spatie Install
```
 composer require spatie/laravel-permission
```


### 4. Create .env File
```
copy .env.example as .env
```

### 5. Generate Key
```
php artisan key:generate
```

### 6. Enable Permission (for Linux User)

```
sudo chmod -R 777 storage
```

## 7. Database Section

```
Create db ems_v2
```

```
import ems_v2.sql stored in ems2.1 project directory 
```

# Great ! Done! 

## 8. From Browser
```html
http://localhost/ems2.1/public
```

### 10. User credentials for login
```html

body: 
    username: CEO.
    or,Email :anis.rahman@genusys.us
    password: 12345678
```


