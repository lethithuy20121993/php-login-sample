# Migrate from PHP to ASP.NET Project
- PHP 7.0.0

## Build and Run
### php Project
```bash
cd src/
```

using PHP built-in server to buid:
```bash
php -S localhost:8000
```

Test:
Access to: http://localhost:8000
(this link will show login1 page)

Test:
Access to:
- For login1 page (this page is migrated from login1 page of php project):
http://localhost:5278
 
- For login2 page (there is a little difference with the login1 page above):
http://localhost:5278/login2

Output:
login1 page(php-project):
![login1](outputs/login1-php.PNG)


signup page(php-project):
![signup](outputs/signup-php.PNG)