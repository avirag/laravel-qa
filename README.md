Command list
```
php artisan make:auth
php artisan migrate

php artisan make:model Question --migration
php artisan migrate

php artisan make:factory QuestionFactory

php artisan tinker
>>> factory(App\User::class, 3)->create();

php artisan migrate:fresh --seed

php artisan make:controller QuestionsController --resource --model=Question

php artisan vendor:publish --tag=laravel-pagination

php artisan make:request AskQuestionRequest
```
Debug
```
$ composer require barryvdh/laravel-debugbar --dev

\DB::enableQueryLog();
dd(\DB::getQueryLog());
```
