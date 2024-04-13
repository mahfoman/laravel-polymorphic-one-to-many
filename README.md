## Laravel polymorphic one to many relationship Demo with posts, comments and videos table

This is simple one controller and three models demo project. Here eloquent ORM morphTo and morphMany relationships are used.

Three migration files are also created for posts, comments and videos table inside migration folder. Although videos migration file
is not used.

## Here following are not used

- html forms
- validations
- Resource routes

Laravel 10.43.0 on php 8.1.0 is used for this demo project

## How to use

- Clone or download the project
- composer install
- copying .env from .env.example [ cp .env.example .env ]
- creating a mysql database and update the name in .env file
- Setting APP_KEY value in .env by - php artisan key:generate
- seeding data [ php artisan migrate ]
- running the project [php artisan serve]
- browsing to http://localhost:8000/posts to see the output


## License
Feel free to use and re-use any way you want.

---

## You can check more tutorials and posts in my site [LaravelCodeSnippet.com](https://laravelcodesnippets.com)

## Most viewed Links in Laravelcodesnippets.com

- [Building mini ecommerce in Laravel](https://laravelcodesnippets.com/communities/projects/topics/mini-ecommerce/posts/113)
- [Building mini issue trackcer with vue3 spa, authentication and authorization in Laravel](https://laravelcodesnippets.com/communities/projects/topics/mini-issue-tracker/posts/159)

## Available for freelance work
Feel free to reach me at [mahfoozurrahman.com](https://www.mahfoozurrahman.com)
