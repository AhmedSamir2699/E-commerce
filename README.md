## Ecommerce(laravel+vue)

![Signup Page](https://user-images.githubusercontent.com/34624785/90558102-cf296b00-e19b-11ea-943b-60b2846f7fe5.png)
![Login Page](https://user-images.githubusercontent.com/34624785/90558086-c6d13000-e19b-11ea-8540-89d88d252e3f.png)
![Start Page](https://user-images.githubusercontent.com/34624785/90558116-d51f4c00-e19b-11ea-91b1-c94bbd864f1b.png)
![Product Page](https://user-images.githubusercontent.com/34624785/90558151-e1a3a480-e19b-11ea-8af6-16326730af98.png)
![Cart Page](https://user-images.githubusercontent.com/34624785/90558152-e1a3a480-e19b-11ea-8415-6c83ebd0e658.png)

## Installation

1. Clone the repo and `cd` into it
1. `composer install`
1. Rename or copy `.env.example` file to `.env`
1. `php artisan key:generate`
1. Set your database credentials in your `.env` file
1. Set your Stripe credentials in your `.env` file. Specifically `STRIPE_KEY` and `STRIPE_SECRET`
1. Set your `APP_URL` in your `.env` file. This is needed for Voyager to correctly resolve asset URLs.
1. `php artisan ecommerce:install`. This will migrate the database and run any seeders necessary
1. Set `ADMIN_PASSWORD` in your `.env` file if you want to specify an admin password. If not, the default password is 'password'
1. `npm install`
1. `npm run dev`
1. `php artisan serve` or use Laravel Valet or Laravel Homestead
1. Visit `localhost:8000` in your browser
1. Visit `/admin` if you want to access the Voyager admin backend. Admin User/Password: `admin@admin.com/password`. Admin Web User/Password: `adminweb@adminweb.com/password`


