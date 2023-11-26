# Laravel 8 project for managing expenses and income

Features:
- CRUDs for income/expenses and their categories
- Monthly reports by income/expenses and their categories

![Expense manager screenshot](https://laraveldaily.com/wp-content/uploads/2019/09/laravel-expenses-manager-reports.png)

![Expense manager screenshot currency](https://laraveldaily.com/wp-content/uploads/2019/09/laravel-expenses-manager-table.png)

## How to use

- Clone the repository with __git clone__
- Copy __.env.example__ file to __.env__ and edit database credentials there
- Run __composer install__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- That's it: launch the main URL and login with default credentials __admin@admin.com__ - __password__
