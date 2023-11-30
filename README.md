-: Todo Project :-

Project Important Command List : 

composer create-project laravel/laravel todo<br />
composer require laravel/ui:* <br />
php artisan ui react --auth <br />
php artisan migrate <br />
npm install && npm run dev<br />

php artisan migrate:rollback --step=1<br />
php artisan make:migration add_status_to_users_table --table=users<br />
php artisan make:migration create_todo_table<br />

php artisan event:list<br />
php artisan make:event TodoAlert<br />
php artisan make:listener SendTodoAlert --event=TodoAlert<br />

