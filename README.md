# Laravel 8 project for managing expenses and income

Features:
- CRUDs for income/expenses and their categories (An)
- Searching by id, date, amount, description, categories (Bao)
- Filtering by month, year (Huy)
- Export PDF, Excel (Duy)
- Sign in (Đạt)
- Sign up (Đạt)
- Log out (Huy)
- Reset password via email verification (Duy)
- Sorting by id, date, categories, description (Bao)

![Expense manager screenshot](https://laraveldaily.com/wp-content/uploads/2019/09/laravel-expenses-manager-reports.png)

![Expense manager screenshot currency](https://laraveldaily.com/wp-content/uploads/2019/09/laravel-expenses-manager-table.png)

## How to use

- Clone the repository with __git clone__
- Change directory to budget-buddy
- Run __cp .env.example .env__
- Run __composer update__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- That's it: launch the main URL and login with default credentials  username: admin@admin.com - password:password
