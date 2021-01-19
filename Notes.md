# Project Set-up
## Create project
> composer create-project laravel/laravel LavarelAnswer

> npm install 

* run the app
> php artisan serve

## File structure

> app folder: core logic
  > Exceptions : Handle exceptions on the code

  > Http: handles all the http logic

    > Controllers
        > Auth controller
    > Middleware > logic between route and controller: good for authentication
    > User.php > model that manten the user models

 > Resources: keep the views

 > Routes: Show all the routes registered: php artisan route:list

### Models
### Views
### Controllers

## Laravel Blade : Templating Engine
* Laravel blade: gets display to the user.
* Combine html and php together.
* {{run php inside}}
* {{!! run php inside but does not scape the content !!}}



