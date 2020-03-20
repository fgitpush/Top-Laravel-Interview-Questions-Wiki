# Laravel Interview Questions & Answers

> Click :star: if you like the project. Pull Request are highly appreciated.

### Table of Contents

| No. | Questions |
| --- | --------- |
|1  | [What is Routing?](#what-is-routing) |
|2  | [How many types of routes are there?](#how-many-types-of-routes-are-there) |
|3  | [What is web php?](#what-is-web-php) |
|4  | [What is api php?](#what-is-api-php) |
|5  | [What is channels php?](#what-is-channels-php) |
|6  | [What is console-php?](#what-is-console-php) |
|2  | [What is Controller?](#what-is-controller) |
|3  | [What are Views?](#what-are-views) |
|4  | [What is a Model?](#what-is-a-model) |
|5  | [What is Request-Response?](#what-is-request-response) |
|6  | [When are Migrations?](#what-are-migrations) |
|7  | [What are Seeders?](#what-are-seeders) |
|8  | [What are Service Providers?](#what-are-service-providers) |
|9  | [What is Middleware?](#what-is-middleware) |
|10 | [What is ORM?](#what-is-orm) |
|11 | [What is Eloquent?](#what-is-eloquent) |
|12 | [What is Query Builder?](#what-is-query-builder)
|13 | [What are Facades?](#what-are-facades) |
|14 | [What is Repository Pattern?](#what-is-repository-pattern) |
|15 | [What is Authentication using Passport CSRF XSRF?](#What-is-Authentication-using-Passport-CSRF-XSRF) |
|16 | [What is Unit testing?](#what-is-unit-testing) |
|17 | [What is Caching?](#what-is-caching) |
|18 | [How to setup Emails?](#how-to-setup-emails) |
|19 | [What are Queues?](#what-are-queues) |
|20 | [What are Jobs?](#what-are-jobs)
|21 | [What are Advanced Eloquent and Query Builder?](#what-are-advanced-eloquent-and-query-builder) |
|22 | [Which is Error management?](#which-is-error-management) |
|23 | [How to create an API?](#how-to-create-an-api) |
|24 | [What are Events?](#what-are-events) |
|25 | [What are Listeners?](#what-are-listeners) |
|26 | [What are Payments and cashier?](#what-are-payments-and-cashier) |
|27 | [What is Test Driven Development?](#what-is-test-driven-development) |
|28 | [What is Package development?](#what-is-package-development) |
|29 | [What are Laravel Scout search and Algolia?](#what-are-laravel-scout-search-and-algolia) |
|30 | [What is Socialite and Auth?](#what-is-socialite-auth) |
|31 | [What is Vue-js?](#what-is-vue-js) |
|32 | [How to connect Laravel with other SQL databases?](#How-to-connect-Laravel-with-other-SQL-databases) |
|33 | [How to connect Laravel with non-SQL databases?](#How-to-connect-Laravel-with-non-SQL-databases) |
|34 | [What is Lumen?](#what-is-lumen) |
|35 | [What is Redis?](#what-is-redis) |
|36 | [What is Memcache?](#what-is-memcache) |
|37 | [What is Horizontal scaling?](#What-is-Horizontal-scaling) |
|38 | [What is Vertical scaling?](#What-is-Vertical-scaling) |
|39 | [What is Single Page Application in Laravel?](#What--Single-Page-Application-in-Laravel) |
|40 | [What are Microservices in Laravel?](#What-are-Microservices-in-Laravel) |
|41 | [What is CSRF and JWT token?](#what-is-CSRF-and-JWT-token) |
|42 | [What is Service Oriented Architecture in Laravel?](#what-is-soa) |
|43 | [What are Validations and custom validations?](#what-are-validators) |
|44 | [What is Composer?](#what-is-composer) |
|45 | [What is Symfony?](#what-is-symfony) |
|46 | [What is Route caching?](#what-is-route-caching) |
|47 | [What are Default packages: Cashier,Envoy,Passport,Scout,Socialite,Horizon?](#default-packages) |
|48 | [What are Named routes?](#what-are-named-routes) |
|49 | [What is Dependency injection in Laravel?](#what-is-dependency-injection) |
|50 | [What are Laravel contracts?](#what-are-contracts) |
|51 | [What is Query log?](#what-is-query-log) |
|52 | [What are Laravel Traits?](#what-are-laravel-traits) |
|53 | [What are Bundles in Laravel?](#what-are-Bundles-in-Laravel) |
|54 | [What are System requirements for Laravel?](#what-are-system-requirements-for-laravel) |
|55 | [What are Aggregate methods in query builder?](#what-are-aggregate-methods-in-query-builder) |
|56 | [What is Singelton design pattern?](#what-is-singelton-design-pattern) |
|57 | [What is Reverse routing?](#what-is-reverse-routing) | 
|58 | [What are Popular composer packages?](#what-are-Popular-composer-packages) |
|59 | [How to get the data from more than 3 table without using a join?](#how-to-get-the-data-from-more-than-3-table-without-using-a-join) |
|60 | [List some artisan commands](#list-some-artisan-commands) |
|61 | [What are Sessions?](#what-are-sessions) |
|62 | [What are Cookies?](#what-are-cookies) |
|63 | [What is Current version of PHP, MySQL, Laravel, MongoDB etc?](#what-is-current-version-of-PHP-MySQL-Laravel-MongoDB-etc) |
|64 | [Describe design architecture of an app?](#Describe-design-architecture-of-an-app) |
|65 | [What are SQL Injections?](#What-are-SQL-Injections) |
|66 | [How to call static methods?](#How-to-call-static-methods) |
|67 | [How to achieve multiple DB hosts?](#How-to-achieve-multiple-DB-hosts)
|68 | [What is Abstract class?](#what-is-Abstract-class) |
|69 | [What are Default ports for MySQL Email etc?](#what-are-Default-ports-for-MySQL-Email-etc) |
|70 | [Explain Joins](#Explain-Joins) |
|71 | [Explain Unions](#Explain-Unions) |
|72 | [How mongodb is better than relational databases?](#How-mongodb-is-better-than-relational-databases) |
|73 | [What is  mongodb?](#What-is-mongodb) |
|74 | [What is default session time?](#What-is-default-session-time)
|75 | [How to create hooks in Laravel?](#How-to-create-hooks-in-Laravel) |
|76 | [What is csrf token and xss attack?](#What-is-csrf-token-and-xss-attack) |
|77 | [Select highest and nth highest salary from DB](#Select-highest-and-nth-highest-salary-from-DB) |
|78 | [Write a join](#Write-a-join) |
|79 | [Write a union](#Write-a-union) |
|80 | [Write a complex query?](#Write-a-complex-query) |
|81 | [Explain an apps DB architecture ?](#Explain-an-apps-DB-architecture) |
|82 | [What is Difference between PHP 5 and 4?](#What-is-Difference-between-PHP-5-and-4) |
|83 | [What is the difference among various php versions?](#What-is-the-difference-among-various-php-versions) |
|84 | [What is the difference among various mysql versions?](#What-is-the-difference-among-various-mysql-versions) |
|85 | [What is the difference among various Laravel versions?](#What-is-the-difference-among-various-Laravel-versions) |
|86 | [How to add AWS plugin in PHP?](#How-to-add-AWS-plugin-in-PHP) |
|87 | [What are design patterns?](#What-are-design-patterns) |
|88 | [What is the difference between GET and POST](#What-is-the-difference-between-GET-and-POST) |
|89 | [Which is fast between GET and POST?](#Which-is-fast-between-GET-and-POST) |
|90 | [Explain 4 basics of OOP](#Explain-4-basics-of-OOP) |
|91 | [What is diference between abstract class and interface?](#What-is-diference-between-abstract-class-and-interface) |
|92 | [What is MVC Framework?](#What-is-MVC-Framework) |
|93 | [Write CRUD in Laravel Eloquent](#Write-CRUD-in-Laravel-Eloquent) |
|94 | [Explain CURL and SOAP?](#Explain-CURL-and-SOAP) |
|95 | [In MySql we use many types of engines which one is faster and why?](#In-MySql-we-use-many-types-of-engines-which-one-is-faster-and-why) |
|96 | [What are Triggers?](#What-are-Triggers) |
|97 | [What are Procedures](#What-are-Procedures) |
|98 | [What are some new feaatures of Laravel X?](#What-are-some-new-feaatures-of-Laravel-X) |
|99 | [What are some new features of PHP X?](#how-to-combine-multiple-inline-style-objects) |
|100| [Explain Difference between session and cookies?](#Explain-Difference-between-session-and-cookies)
|101| [Merge 2 arrays with duplicate](#Merge-2-arrays-with-duplicate) |
|102| [Find the count of vowel and consonants](#Find-the-count-of-vowel-and-consonants) |
|103| [Explain AWS Services](#Explain-AWS-Services) |
|104| [How to do Web scraping?](#How-to-do-Web-scraping) |
|105| [Explain require and require once difference](#Explain-require-and-require-once-difference) |
|106| [Explain include and require diffrence](#Explain-include-and-require-diffrence) |
|107| [Directory structure of Laravel](#Directory-structure-of-Laravel) |
|108| [How to install Laravel via composer?](#How-to-install-Laravel-via-composer) |
|109| [Which ORM are being used by laravel?](#Which-ORM-are-being-used-by-laravel) |
|110| [List types of relationships available in Laravel Eloquent?](#List-types-of-relationships-available-in-Laravel-Eloquent) |
|111| [How to enable maintenance mode in Laravel?](#How-to-enable-maintenance-mode-in-Laravel) |
|112| [What is the purpose of using dd() function in laravel?](#What-is-the-purpose-of-using-dd()-function-in-laravel) |
|113| [How do you register a Service Provider?](#How-do-you-register-a-Service-Provider) |
|114| [Explain Laravel framework Architecture](#Explain-Laravel-framework-Architecture) |
|115| [Helper Functions](#Helper-Functions) |
|116| [What is Fillable Attribute in a Laravel Model?](#What-is-Fillable-Attribute-in-a-Laravel-Model) |
|117| [What is Guarded Attribute in a Laravel Model?](#What-is-Guarded-Attribute-in-a-Laravel-Model) |
|118| [What are Closures in Laravel?](#What-are-Closures-in-Laravel) |
|119| [How to get Logged in user info in Laravel?](#How-to-get-Logged-in-user-info-in-Laravel) |
|120| [What is Laravel Elixir?](#What-is-Laravel--Elixir) |
|121| [What is Laravel Mix?](#What-is-Laravel-Mix) |
|122| [How can you display HTML with Blade in Laravel?](#How-can-you-display-HTML-with-Blade-in-Laravel) |
|123| [List out databases that laravel supports?](#List-out-databases-that-laravel-supports) |
|124| [How to use custom table in Laravel Model?](#How-to-use-custom-table-in-Laravel-Model) |
|125| [How To Use Select Query In Laravel? Eloquent and QB?](#How-To-Use-Select-Query-In-Laravel-Eloquent-and-QB) |
|126| [What are Accessors and Mutators in Eloquent and why should you use them?](#What-are-Accessors-and-Mutators-in-Eloquent-and-why-should-you-use-them) |
|127| [How do I log an error?](#How-do-I-log-an-error) |
|128| [What is Monolog library in Laravel?](#What-is-Monolog-library-in-Laravel) |
|129| [Exceptions are handled by which class in Laravel?](#Exceptions-are-handled-by-which-class-in-Laravel) |
|130| [What is Serialization in Laravel?](#What-is-Serialization-in-Laravel) |
|131| [What is Response in Laravel?](#What-is-Response-in-Laravel) |
|132| [What is Response Macros in Laravel?](#What-is-Response-Macros-in-Laravel) |
|133| [What is Rate Limiting OR Throttle in Laravel?](#What-is-Rate-Limiting-OR-Throttle-in-Laravel) |
|134| [What is Lazy vs Eager Loading in Laravel?](#What-is-Lazy-vs-Eager-Loading-in-Laravel) |
|135| [How to get current environment in Laravel?](#How-to-get-current-environment-in-Laravel) |
|136| [How to use custom table in Laravel Model?](#How-to-use-custom-table-in-Laravel-Model) |
|137| [What is Binding?](#What-is-Binding) |
|138| [Explain Binding A Singleton?](#Explain-Binding-A-Singleton) |
|139| [Explain Binding Instances?](#Explain-Binding-Instances) |
|140| [Explain Binding Primitives?](#Explain-Binding-Primitives) |
|141| [Explain Contextual Binding and how does it work?](#Explain-Contextual-Binding-and-how-does-it-work) |
|142| [What is Tagging?](#What-is-Tagging) |
|143| [Explain Extending Bindings?](#Explain-Extending-Bindings) |
|144| [What is the make Method?](#What-is-the-make-Method) |
|145| [How to clear cache in Laravel?](#How-to-clear-cache-in-Laravel) |
|146| [What is CSRF token?](#What-is-CSRF-token) |
|147| [How will you explain homestead in Laravel?](#How-will-you-explain-homestead-in-Laravel) |
|148| [How can we get the user's IP address in Laravel?](#How-can-we-get-the-user's-IP-address-in-Laravel) |
|149| [How will you create a helper file in Laravel?](#How-will-you-create-a-helper-file-in-Laravel) |
|150| [How can we create a record in Laravel using eloquent?](#How-can-we-create-a-record-in-Laravel-using-eloquent) |
|151| [How can we get the user's IP address in Laravel?](#give-a-simple-example-of-jest-test-case) |
|152| [What is faker in Laravel?](#What-is-faker-in-Laravel) |
|153| [What are active records?](#What-are-active-records) |
|154| [What are the difference between insert() and insertGetId() in laravel?](#What-are-the-difference-between-insert-and-insertGetId-in-laravel) |
|155| [Talk about Laravel Vapor Compatibility](#Talk-about-Laravel-Vapor-Compatibility) |
|156| [What is Semantic Versioning?](#What-is-Semantic-Versioning) |
|157| [What are Jobs and Middleware?](#What-are-Jobs-and-Middleware) |
|158| [Talk about Laravel User Interface (UI)](#talk-about-Laravel-User-Interface-(UI)) |
|159| [Talk about Eloquent Subquery Enhancements?](#Talk-about-Eloquent-Subquery-Enhancements) |
|160| [What are improved Authorization Responses?](#What-are-improved-Authorization-Responses) |
|161| [What are lazy collections?](#What-are-lazy-collections) |
|162| [How to make a constant and use globally?](#How-to-make-a-constant-and-use-globally) |
|163| [How to remove /public from URL in laravel?](#How-to-remove-public-from-URL-in-laravel) |
|164| [What are the difference between soft delete & delete in Laravel?](#What-are-the-difference-between-soft-delete-&-delete-in-Laravel) |
|165| [How we can upload files in laravel?](#How-we-can-upload-files-in-laravel) |
|166| [How to create real time sitemap.xml file in Laravel?](#How-to-create-real-time-sitemap.xml-file-in-Laravel) |
|167| [How to use skip() and take() in Laravel Query?](#How-to-use-skip()-and-take()-in-Laravel-Query) |
|168| [What is tinker in laravel?](#What-is-tinker-in-laravel) |
|169| [What is a REPL?](#What-is-a-REPL) |
|170| [How to use multiple 'OR' condition in Laravel Query?](#How-to-use-multiple-'OR'-condition-in-Laravel-Query) |
|171| [Please write some additional where Clauses in Laravel?](#Please-write-some-additional-where-Clauses-in-Laravel) |
|172| [How to check column is exists or not in a table using Laravel?](#How-to-check-column-is-exists-or-not-in-a-tabl-using-Laravel) |
|173| [What is eager loading in Laravel?](#What-is-eager-loading-in-Laravel) |
|174| [How to generate application key in laravel?](#How-to-generate-application-key-in-laravel) |
|175| [What is LTS version of Laravel?](#What-is-LTS-version-of-Laravel) |
|176| [How to use GROUP_CONCAT() with JOIN in Laravel?](#How-to-use-GROUP_CONCAT()-with-JOIN-in-Laravel) |
|177| [How to extend login expire time in Auth?](#How-to-extend-login-expire-time-in-Auth) |
|178| [How to extend a layout file in laravel view?](#How-to-extend-a-layout-file-in-laravel-view) |
|179| [How do you use yield()?](#How-do-you-use-yield()) |
|180| [How to redirect form controller to view file in laravel?](#How-to-redirect-form-controller-to-view-file-in-laravel) |
|181| [How to get current route name?](#How-to-get-current-route-name) |
|182| [What is ACL in laravel?](#What-is-ACL-in-laravel) |
|183| [How to check Ajax request in Laravel?](#How-to-check-Ajax-request-in-Laravel) |
|184| [How to check if value is sent in request?](#How-to-check-if-value-is-sent-in-request) |
|185| [Laravel String Helper functions?](#Laravel-String-Helper-functions) |
|186| [Laravel Array Helper functions?](#Laravel-Array-Helper-functions) |
|187| [How to exclude a route with parameters from CSRF verification?](#How-to-exclude-a-route-with-parameters-from-CSRF-verification) |
|188| [What are policies classes?](#What-are-policies-classes) |
|189| [How to rollback last migration?](#How-to-rollback-last-migration) |
|190| [What do you mean by Laravel Dusk?](#What-do-you-mean-by-Laravel-Dusk) |
|191| [Explain Laravel echo](#Explain-Laravel-echo) |
|192| [What is namespace in Laravel?](#What-is-namespace-in-Laravel) |
|193| [What is Laravel Forge?](#What-is-Laravel-Forge) |
|194| [State the difference between CodeIgniter and Laravel.](#State-the-difference-between-CodeIgniter-and-Laravel) |
|195| [What is an Observer?](#What-is-an-Observer) |
|196| [What is the use of the bootstrap directory?](#What-is-the-use-of-the-bootstrap-directory) |
|197| [What is the default session timeout duration?](#What-is-the-default-session-timeout-duration) |
|198| [Explain API.PHP route](#Explain-API.PHP-route) |
|199| [Define hashing in Laravel](#Define-hashing-in-Laravel) |
|200| [What is Localization?](#What-is-Localization) |
|201| [Explain the concept of encryption and decryption in Laravel.](#Explain-the-concept-of-encryption-and-decryption-in-Laravel) |
|202| [How to share data with views?](#How-to-share-data-with-views) |
|203| [How to generate a request in Laravel?](#How-to-generate-a-request-in-Laravel) |
|204| [I just have installed a fresh version of Laravel 5, and I have the white screen of death. What’s wrong?](#I-just-have-installed-a-fresh-version-of-Laravel-5-and-I-have-the-white-screen-of-death-What’s-wrong) |
|205| [How to assign a variable value for all view file?](#How-to-assign-a-variable-value-for-all-view-file) |
|206| [How to make a constant and use globally?](#How-to-make-a-constant-and-use-globally) |
|207| [How to check current installed version of Laravel?](#How-to-check-current-installed-version-of-Laravel) |
|208| [What does "composer dump-autoload" do?](#What-does-composer-dump-autoload-do) |
|209| [What is Kept in vendor directory of Laravel?](#What-is-Kept-in-vendor-directory-of-Laravel) |
|210| [What does PHP compact function do?](#What-does-PHP-compact-function-do) |
|210| [What is APP_KEY used for?](#What-is-APP_KEY-used-for) |
|211| [How to install laravel via composer?](#How-to-install-laravel-via-composer) |
|212| [How to install laravel via composer?](#How-to-install-laravel-via-composer) |
|213| [How to install laravel via composer?](#How-to-install-laravel-via-composer) |
|214| [How to install laravel via composer?](#How-to-install-laravel-via-composer) |
|215| [How to install laravel via composer?](#How-to-install-laravel-via-composer) |
|216| [How to install laravel via composer?](#How-to-install-laravel-via-composer) |
|217| [How to install laravel via composer?](#How-to-install-laravel-via-composer) |
|218| [How to install laravel via composer?](#How-to-install-laravel-via-composer) |
|219| [How to install laravel via composer?](#How-to-install-laravel-via-composer) |
|220| [Output a raw query using eloquent/query builder ](#Output-a-raw-query-using-eloquent-or-query-builder) |
|221| [How to create custom helper functions](#How-to-create-custom-helper-functions) |
|222| [How to check installed extensions in CLI and web for PHP?](#How-to-check-installed-extensions-in-CLI-and-web-for-PHP) |
 
 
1. ### What is Routing?

  When a user enters a URL, it gets send to a routes file. Laravel contains a routes.php file where it matches it with the right controller/view.

Below is an example route from `routes/web.php`. You can can call site.exension/foo and it will bring the result.

```
Route::get('foo', function () {
    return 'Hello World';
});
```
   **[⬆ Back to Top](#types-of-routes)**
    
2. ### How many types of routes are there?

There are four types of routes in routes.php file,

    A. web.php 
    
    B. api.php
    
    C. console.php
    
    D. broadcast.php

   **[⬆ Back to Top](#what-is-web-php)**
    
5. ### What is web php?

web.php used for web routes. Like example.com/test

    ```
    Route::get('/test', function () {
        $path = storage_path() . "/app/json/options/docs.json";
        return view('skin/dev-wireframe', array('menu' => json_decode(file_get_contents($path), true)));
    });
    ```
    
    
   **[⬆ Back to Top](#types-of-routes)**
    
6. ### What is api php?

    The place where we write API route for mobile and API usage. Like http://localhost:8080/api/test
    ```
    Route::get('/test', function () {
        $path = storage_path() . "/app/json/options/docs.json";
        return view('skin/dev-wireframe', array('menu' => json_decode(file_get_contents($path), true)));
    });
    ```
    
7. ### What is channels php?

    ...

 **[⬆ Back to Top](#what-is-api-php)**

8. ### What is console php?

    Update here.

   **[⬆ Back to Top](#what-is-api-php)**
   
    
6. ### What is Controller?

    Controller is the place where we write the logic of the program. Placed in app/Http/Conrollers

    ```
    <?php namespace App\Http\Controllers;

    use App\Http\Controllers\Controller;

    class UserController extends Controller {

        /**
         * Show the profile for the given user.
         *
         * @param  int  $id
         * @return Response
         */
        public function showProfile($id)
        {
            return view('user.profile', ['user' => User::findOrFail($id)]);
        }

    }
    ```


   **[⬆ Back to Top](#table-of-contents)**
    
3. ### What are Views?

  Views is the fornt end of Laravel. Stored in `resources/views`.

    ```
    <html>
        <body>
            <h1>Hello, {{ $name }}</h1>
        </body>
    </html>
    ```


   **[⬆ Back to Top](#table-of-contents)**
    
4. ### 	What is a Model?
    A model is where you write the database logic. Stored in `/app`

    <?php

    namespace App;

    use Illuminate\Database\Eloquent\Model;

    class Flight extends Model
    {
        //
    }

   **[⬆ Back to Top](#table-of-contents)**
    
5. ### What is Request-Response?

    When we type a URL, a request is sent to the server. The server goes from /public to bootstrap folder from which is goes to the routes file. The route files sends it the right controller/view.


   **[⬆ Back to Top](#table-of-contents)**
    
6. ### What are Migrations?

    Migrations help us keep SQL tables in code. When we have to setup the DB, we just run the migration.


   **[⬆ Back to Top](#table-of-contents)**
    
7. ### What are Service Providers?

    Service providers are responsible for booting and configuration (binding all resources.)
    
   **[⬆ Back to Top](#table-of-contents)**
    
8. ### What is Middleware?

    Middleware checks for authentication.


   **[⬆ Back to Top](#table-of-contents)**
    
9. ### What is ORM?

    Object oriented and Model based way of DB query


   **[⬆ Back to Top](#table-of-contents)**
    
10. ### What is Eloquent?

    The ORM wrapper Laravel uses is called Eloquent. Every table has a model associated with it.
    
   **[⬆ Back to Top](#table-of-contents)**
    
11. ### What is Query Builder?

   A database wrapper that makes it easy to access DB.

   **[⬆ Back to Top](#table-of-contents)**
    
12. ### What are Facades?

    Facades are used to hide implementation details and complexities from end user making him/her feel like interacting with a black box.

   **[⬆ Back to Top](#table-of-contents)**
    
13. ### What is Repository Pattern?

    Repository pattern is used to create templates where implementation details are left to be implemented in child classes. It helps with further expansion of code and avoid bottlenecks in class updation.

   **[⬆ Back to Top](#table-of-contents)**
    
14. ### What is Authentication using Passport?
    
    Passport provides a better way to create API.

   **[⬆ Back to Top](#table-of-contents)**
    
15. ### What Unit testing?
    Testing every function

   **[⬆ Back to Top](#table-of-contents)**
    
16. ### What is Caching?

    Configured using `config/cache.php`. Used for database caching. Popular ways Redis and Memcache.

   **[⬆ Back to Top](#table-of-contents)**
    
17. ### What is Unit Testing?

    Writing a test for every unit (function or class) you write.

   **[⬆ Back to Top](#table-of-contents)**
   
18. ### How to setup Emails?

    Using PHP's `mail()` function amnd Laravel's `sendmail()` function. You can custoimize it using templates.

  **[⬆ Back to Top](#table-of-contents)**
  
18. ### What are Queues?

    Queue is a line of jobs to be proccessed. You can create multiple queues which is multiple lines of jobs
   **[⬆ Back to Top](#table-of-contents)**
    
19. ### What are Jobs?

    Job is a task being performed in the background.

   **[⬆ Back to Top](#table-of-contents)**
   
   
19. ### How to setup Emails?

   Use Laravel's sendmail() function and create a mail template.

   **[⬆ Back to Top](#table-of-contents)**
    
20. ### What are Advanced Eloquent and Query Builder?

    Complex eloquent queries are called advanced eloquent. Query builder is wrapper for database queries.

   **[⬆ Back to Top](#table-of-contents)**
    
21. ### Which is Error management?

   Error handling is managing `exception` in a Laravel application.

   **[⬆ Back to Top](#table-of-contents)**
    
22. ### How to create an API?

  Use api.php. Link will be x.com/api/slug

   **[⬆ Back to Top](#table-of-contents)**
    
23. ### What are Events?

   You get notified when an action is triggered.

   **[⬆ Back to Top](#table-of-contents)**
    
24. ### What are Listeners?

    Which listen to the events.

   **[⬆ Back to Top](#table-of-contents)**
    
25. ### What are Payments and cashier?

    Payment processing is difficult. Cashier is a package which makes it easy. Its installed using composer.

   **[⬆ Back to Top](#table-of-contents)**
    
26. ### What is Test Driven Development?

    Test is written first and then the function is written.

   **[⬆ Back to Top](#table-of-contents)**
    
27. ### What is Package development?

    Larvel uses composer which gets packages. You can develop your own package and submit.

   **[⬆ Back to Top](#table-of-contents)**
    
28. ### What are Laravel Scout search and Algolia?

   https://laravel.com/docs/5.8/scout

   **[⬆ Back to Top](#table-of-contents)**
    
29. ### Socialie and Auth?

    Socialite is Social login for Laravel.
    Auth is Laravel's authentication.

   **[⬆ Back to Top](#table-of-contents)**
    
30. ### What is Vue-js?

    In easy way to do SPA where you can change state.

   **[⬆ Back to Top](#table-of-contents)**
    
31. ### How to connect Laravel with other SQL databases?

    Go to config/database.php

   **[⬆ Back to Top](#table-of-contents)**
    
32. ### How to connect Laravel with non-SQL databases?

   Add the entry to config/database.php

   **[⬆ Back to Top](#table-of-contents)**
    
33. ### What is Lumen?

    Lumen is the lightweight version of Laravel used usually for making microservices.

   **[⬆ Back to Top](#table-of-contents)**
    
34. ### What is Redis?
    
    Key-value database making query faster.

   **[⬆ Back to Top](#table-of-contents)**
    
35. ### What is Memcache?

    Key-value database making query faster.


   **[⬆ Back to Top](#table-of-contents)**
    
36. ### What is Horizontal scaling?

    By adding more servers we scale horizontally.

   **[⬆ Back to Top](#table-of-contents)**
    
37. ###	What is Vertical scaling?

    By increasing the size of the same server we scale vertically.

   **[⬆ Back to Top](#table-of-contents)**
    
38. ### What is Single Page Application in Laravel?

    There is single URL. The assets are loaded once and only content keeps changing using JSON request. Its not great for SEO but there are workarounds to create virtual URL.

   **[⬆ Back to Top](#table-of-contents)**
    
40. ### What are Microservices in Laravel?

    There are many services which are similar sized. Each performs exactly one function and they talk to each other.

   **[⬆ Back to Top](#table-of-contents)**
    
41. ### What is CSRF and JWT token?
    CSRF and JWT tokens are used to make sure the action is performed by the user. If there is no token, someone can give a link to user to click or hide it behind some action and him do what the hacker wants.

   **[⬆ Back to Top](#table-of-contents)**
    
42. ### What is Service Oriented Architecture in Laravel?

    There are many services which are similar sized. Each performs exactly one function and they talk to each other. 

   **[⬆ Back to Top](#table-of-contents)**
    
43. ### What are Validations and custom validations?

    Validations are used to make sure input is of the kind function wanted. Custom validators are custom made valiators.

   **[⬆ Back to Top](#table-of-contents)**
    
44. ### What is Composer?
   
    Composer is PHP's package manager.

   **[⬆ Back to Top](#table-of-contents)**
    
45. ### What is Symfony?
    Symfony is a framework Laravel is inspired from.

   **[⬆ Back to Top](#table-of-contents)**
    
46. ### What is Route caching?

    Caching of routes to make going to routes faster. Command: `php artisan route:cache`

   **[⬆ Back to Top](#table-of-contents)**
    
47. ### What are Default packages?
    Cashier, Envoy, Passport, Scout, Socialite, Horizon etc

   **[⬆ Back to Top](#table-of-contents)**
    
48. ### What are Named routes?

    You can give route a name using a parameter.

   **[⬆ Back to Top](#table-of-contents)**
    
49. ### What is Dependency injection in Laravel?

    Laravel injects dependencies as function parameters.
    Read more: https://medium.com/a-young-devoloper/how-laravel-injects-our-dependencies-14e1b1a044e


   **[⬆ Back to Top](#table-of-contents)**
    
50. ### What are Laravel contracts?

    https://laravel.com/docs/7.x/contracts

   **[⬆ Back to Top](#table-of-contents)**
    
51. ### What is Query log?

   You can enable logging queries and Laravel will record the queries which were run.

   **[⬆ Back to Top](#table-of-contents)**
    
52. ### What are Laravel Traits?

    They solve diamond problem which is when you have to inherit from two classes.

   **[⬆ Back to Top](#table-of-contents)**
    
53. ### What are Bundles in Laravel?

    Used for grouping stuff like route groups (CRUD in one line.)

   **[⬆ Back to Top](#table-of-contents)**
    
54. ### What are System requirements for Laravel?

    PHP version, MySQL, PHP packages mentioned on Laravel.com, apache server

   **[⬆ Back to Top](#table-of-contents)**
    
55.	### What are Aggregate methods in query builder?

    Max, min, sum etc
   ```
   $price = DB::table('orders')->max('price');
   ```
   
   **[⬆ Back to Top](#table-of-contents)**
  
    
56.	### What is Singelton design pattern?

    A single object of a class is created throughout the lifecycle.

   **[⬆ Back to Top](#table-of-contents)**
    
57.	### What is Reverse routing?

   To generate the process of generating the URL which leads to a route. Its used in MVC apps. You can use it using named routes in laravel.
   
   **[⬆ Back to Top](#table-of-contents)**
    
58.	### What are Popular composer packages?

    Guzzle

   **[⬆ Back to Top](#table-of-contents)**
    
59.	### How to get the data from more than 3 table without using a join ?

    Answer: Subquery, union.


   **[⬆ Back to Top](#table-of-contents)**
    
60.	### List some artisan commands

    ```
    php artisan list
    php artisan make:migrate
    php artisan make:controller
    php artisan make:model
    php artisan config:clear
    php artisan serve
    ```

   **[⬆ Back to Top](#table-of-contents)**
    
61.	### What are Sessisons?

    Session is data related to a specific user.

   **[⬆ Back to Top](#table-of-contents)**
    
62.	### What are Cookies?

    Cookies is generalized data.

   **[⬆ Back to Top](#table-of-contents)**
    
63.	### What is Current version of PHP MySQL Laravel MongoDB etc?

    PHP: PHP 7.4
    MySQL: 7
    Laravel: 6
    MongoDB: 4

   **[⬆ Back to Top](#table-of-contents)**
    
64.	### Describe design architecture of an app?

    There are three layers
    1. Presentation layer: Front end
    2. Business layer: Backend and logic
    3. Data layer: Model and database 
  
   **[⬆ Back to Top](#table-of-contents)**
    
65.	### What are SQL Injections?

    Its a hacking trick used to complete a SQL query by filling a form content and placing query parts inside the form.

   **[⬆ Back to Top](#table-of-contents)**
    
66.	### How to call static methods?

    Using `::` before function name instead of `->`.

   **[⬆ Back to Top](#table-of-contents)**
    
67.	### How to achieve multiple DB hosts?

    Define the new DB in env or config/database.php and use it.
    
   **[⬆ Back to Top](#table-of-contents)**
    
68.	### What is Abstract class?

    A class which is just a template i.e has no defination but just declaration.

   **[⬆ Back to Top](#table-of-contents)**
    
69.	### What are Default ports for MySQL, Email, etc?

    http: 80
    MYSQL: 3306
    Email: 587

   **[⬆ Back to Top](#table-of-contents)**
    
70.	### Explain Joins

    There are 4 types of joins,
    1. Inner Join
    2. Outer Join
    3. Left Join
    4. Right Join

   **[⬆ Back to Top](#table-of-contents)**
    
71.	### Explain Unions

    Union horizontally joins tables together i.e the records are added into the same columns.

   **[⬆ Back to Top](#table-of-contents)**
    
72.	### How mongodb is better than relational databases?

    It is faster and it stores data in JSON form so you can enter multiple types of data without being dependent on the data being consistent in type.

   **[⬆ Back to Top](#table-of-contents)**
    
73.	### What is mongodb?

   It is a NO SQL key value based database.
   
   **[⬆ Back to Top](#table-of-contents)**
    
74.	### What is default session time?

   1 hour.

   **[⬆ Back to Top](#table-of-contents)**
    
75.	### How to create hooks in Laravel?
    
    https://stackoverflow.com/questions/36226021/hooks-in-laravel-5

   **[⬆ Back to Top](#table-of-contents)**
    
76.	### What is csrf token and xss attack?

   CSRF and JWT tokens are used to make sure the action is performed by the user. If there is no token, someone can give a link to user to click or hide it behind some action and him do what the hacker wants.


   **[⬆ Back to Top](#table-of-contents)**
    
77.	### Select highest and nth highest salary from DB
    
    ```
    SELECT name, salary 
    FROM #Employee e1
    WHERE N-1 = (SELECT COUNT(DISTINCT salary) FROM #Employee e2
    WHERE e2.salary > e1.salary)
    ```
    https://javarevisited.blogspot.com/2016/01/4-ways-to-find-nth-highest-salary-in.html

   **[⬆ Back to Top](#table-of-contents)**
    
78.	### Write the 4 joins
    
    1. Inner join
    2. Outer join
    3. Left join
    4. Right join

   **[⬆ Back to Top](#table-of-contents)**
    
79. ### Write a union

    ```
    SELECT expression1, expression2, ... expression_n
    FROM tables
    [WHERE conditions]
    UNION [DISTINCT]
    SELECT expression1, expression2, ... expression_n
    FROM tables
    [WHERE conditions];
    ```

   **[⬆ Back to Top](#table-of-contents)**
    
80. ### Write a complex query?

   Like a 3 tables joined.

   **[⬆ Back to Top](#table-of-contents)**
    
81. ### Explain an apps DB architecture 
   
   ...

   **[⬆ Back to Top](#table-of-contents)**
    
82. ### What is Difference between PHP 5 and 4?

    PHP 5 has OOP.

   **[⬆ Back to Top](#table-of-contents)**
    
83. ### What is the difference among various php versions?

    PHP 4: No OOP
    PHP 5: OOP
    PHP 7: Faster speed

   **[⬆ Back to Top](#table-of-contents)**
    
85. ### What is the difference among various Laravel versions?

    Directory structure

   **[⬆ Back to Top](#table-of-contents)**
    
86. ### How to add AWS plugin in PHP?

    Using AWS SDK.

   **[⬆ Back to Top](#table-of-contents)**
    
87. ### What are design patterns?

    They are well known solutions to common problems every developer faces.

   **[⬆ Back to Top](#table-of-contents)**
    
88. ### What is the difference between GET and POST

    GET is used for retriving data
    POST is used to perform a change i.e action

   **[⬆ Back to Top](#table-of-contents)**
    
89. ### Which is fast between GET and POST?

    GET is used for retriving data
    POST is used to perform a change i.e action
    
90. ### Explain 4 basics of OOP

    Inheritance
    Polymorphism
    Encapsulation
    Abstraction


   **[⬆ Back to Top](#table-of-contents)**
    
91. ### What is diference between abstract class and interface?

   https://javapapers.com/core-java/abstract-and-interface-core-java-2/difference-between-a-java-interface-and-a-java-abstract-class/

   **[⬆ Back to Top](#table-of-contents)**
    
92. ### What is MVC Framework?

    It provides separation of concerns by separating the code into 3 parts,
    1. Model: Database logic
    2. View: Frontend logic
    3. Controller: Backend logic

   **[⬆ Back to Top](#table-of-contents)**
    
93. ### Create a project with CRUD, one algorithm logic and insert data in db for testing.

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
95. ### In MySql we use many types of engines which one is faster and why?

    There are two main types of engines,
    1.InnoDB
    2.MyISAM
    InnoDB is faster.

   **[⬆ Back to Top](#table-of-contents)**
    
96. ### What are Triggers?

    `DB::unprepared()` is used for it.
    
    ```
    php artisan make:migration create_trigger    
    ```

   **[⬆ Back to Top](#table-of-contents)**
    
97. ### What are Procedures

    Stored procedures are SQL code in tables. It is called and executed inside tables.

   **[⬆ Back to Top](#table-of-contents)**
    
98. ### What are some new feaatures of Laravel X?

   https://medium.com/@samwatsonets/difference-between-laravel-6-0-and-its-previous-versions-efb2829d0f55

   **[⬆ Back to Top](#table-of-contents)**
    
99. ### What are some new features of PHP X?

    PHP 7.4 brings,
    1. 
    2.

   **[⬆ Back to Top](#table-of-contents)**
    
100. ### Explain Difference between session and cookies?

  Cookies is data sent with every request. It is usually generalized for all.
  Session is data related to a specific user.

   **[⬆ Back to Top](#table-of-contents)**
    
101. ### Merge 2 arrays with duplicate

    ```
    array_unique(array_merge($array1,$array2), SORT_REGULAR);

    ```

   **[⬆ Back to Top](#table-of-contents)**
    
102. ### Find the count of vowel and consonants

    $str="Find the count of vowel and consonants"
    $i=0; $vowel=0; $const=0;
    foreach ($char in $str)
    {
        if(($char==" ") || ($i==0))
            {
               if(($str[$i+1]==a) || ($str[$i+1]==e) || ($str[$i+1]==i) || ($str[$i+1]==o) || ($str[$i+1]==u))
               $vowel++;
               else
               $const++;
            }
            $i++;
    }

   **[⬆ Back to Top](#table-of-contents)**
    
103. ### Explain AWS Services

    AWS has 20 main categories and 150 sub-categories of items. For hosting, EC2 is a well known server type.

   **[⬆ Back to Top](#table-of-contents)**
    
104. ### How to do Web scraping?

    Composer has built in packages for it. They may get stopped due to IP usage (no of connections

   **[⬆ Back to Top](#table-of-contents)**
    
105. ### Explain require and require once difference

    In require, you can use require multiple times for the same file. It will add the file multiple times while require_once will only require it once.


   **[⬆ Back to Top](#table-of-contents)**
   
106. ### Explain include and require diffrence

    In include() the script will run even if the file is not found while in require it will stop if file required is not found.

   **[⬆ Back to Top](#table-of-contents)**
    
107. ### Directory structure of Laravel

    ```
    /bootsrtrap
    /public
    /routes
    /resources
    /config
    /app
    .env
    ```
    etc

   **[⬆ Back to Top](#table-of-contents)**
    
108. ### How to install Laravel via composer?

    ```
    composer create-project --prefer-dist laravel/laravel blog "5.8.*"
    ```

   **[⬆ Back to Top](#table-of-contents)**
    
109. ### Which ORM are being used by laravel?

    Eloquent

   **[⬆ Back to Top](#table-of-contents)**
   
110. ### List types of relationships available in Laravel Eloquent?

    One To One
    One To Many
    One To Many (Inverse)
    Many To Many
    Has Many Through
    Polymorphic Relationships
    One To One
    One To Many
    Many To Many
    Custom Polymorphic Types

   **[⬆ Back to Top](#table-of-contents)**
    
111. ### How to enable maintenance mode in Laravel?

    ```
    php artisan down
    ```

   **[⬆ Back to Top](#table-of-contents)**
    
112. ### What is the purpose of using dd() function in laravel?

    dd() is dump and die. It prints the variable/array and exits the script.

   **[⬆ Back to Top](#table-of-contents)**
    
113. ### How do you register a Service Provider?
    
    Inside `config/app.php`
    ```
    'providers' => [
  
        /*
         * Laravel Framework Service Providers...
         */
        Illuminate\Auth\AuthServiceProvider::class,
        Illuminate\Broadcasting\BroadcastServiceProvider::class,
        ...
    ```

   **[⬆ Back to Top](#table-of-contents)**
    
114. ### Explain Laravel framework Architecture

   **[⬆ Back to Top](#table-of-contents)**
    
115. ### Helper Functions
    
    Common function which you can use in many classes are stored in helper functions.

   **[⬆ Back to Top](#table-of-contents)**
    
116. ### What is Fillable Attribute in a Laravel Model?

   Which can be mass assigned.


   **[⬆ Back to Top](#table-of-contents)**
    
117. ### What is Guarded Attribute in a Laravel Model?

    Which can't be mass assigned.

   **[⬆ Back to Top](#table-of-contents)**
    
118. ### What are Closures in Laravel?

    a closure gives you access to an outer function's scope from an inner function

   **[⬆ Back to Top](#table-of-contents)**
    
119. ### How to get Logged in user info in Laravel?

    ```
    $user = auth()->user();
    print_r($user);
    ```

   **[⬆ Back to Top](#table-of-contents)**
    
120. ### What is Laravel Elixir?

   Used for compiling JS.

   **[⬆ Back to Top](#table-of-contents)**
    
121. ### What is Laravel Mix?

    Used for compiling JS.

   **[⬆ Back to Top](#table-of-contents)**
    
122. ### How can you display HTML with Blade in Laravel?

     {!! $text !!}

   **[⬆ Back to Top](#table-of-contents)**
    
123. ### How to install laravel via composer ?

     ...

   **[⬆ Back to Top](#table-of-contents)**
    
124. ### List out databases that laravel supports?

     Laravel supports four database systems: MySQL, Postgres, SQLite, and SQL Server.

   **[⬆ Back to Top](#table-of-contents)**
    
124. ### How to use custom table in Laravel Model?

    By mentoning the name of the table in `$table` variable

   **[⬆ Back to Top](#table-of-contents)**
    
125. ### How To Use Select Query In Laravel? Eloquent and QB?

    QB: $users = DB::table('users')->select('name', 'email as user_email')->get();
    Eloquent: $users = User::all();
    
126. ### What are Accessors and Mutators in Eloquent and why should you use them?

    https://laravel.com/docs/4.2/eloquent#accessors-and-mutators

   **[⬆ Back to Top](#table-of-contents)**
    
127. ### How do I log an error?

    https://laravel.com/docs/5.2/errors

   **[⬆ Back to Top](#table-of-contents)**
    
128. ### What is Monolog library in Laravel?

    Helps with logging.

   **[⬆ Back to Top](#table-of-contents)**
    
129. ### Exceptions are handled by which class in Laravel?

     App\Exceptions\Handler class.

   **[⬆ Back to Top](#table-of-contents)**
    
130. ### What is Serialization in Laravel?

    https://laravel.com/docs/5.8/eloquent-serialization

   **[⬆ Back to Top](#table-of-contents)**
    
131. ### What is Response in Laravel?

    When we make a request , we get a responsse.

   **[⬆ Back to Top](#table-of-contents)**
    
132. ### What is Response Macros in Laravel?

    https://laravel.com/docs/5.8/responses#response-macros


   **[⬆ Back to Top](#table-of-contents)**
    
133. ### What is Rate Limiting OR Throttle in Laravel?

    https://www.cloudways.com/blog/laravel-and-api-rate-limiting/


   **[⬆ Back to Top](#table-of-contents)**
    
134. ### What is Lazy vs Eager Loading in Laravel?

    https://laravel.com/docs/5.8/eloquent-relationships

   **[⬆ Back to Top](#table-of-contents)**
    
135. ### How to get current environment in Laravel?

    https://stackoverflow.com/questions/14935846/laravel-4-how-can-i-get-the-environment-value

   **[⬆ Back to Top](#table-of-contents)**
    
136. ### How to use custom table in Laravel Model ?

    $table=""

   **[⬆ Back to Top](#table-of-contents)**
    
137. ### What is Binding?

    https://stackoverflow.com/questions/49348681/what-is-a-usage-and-purpose-of-laravels-binding


   **[⬆ Back to Top](#table-of-contents)**
    
138. ### Explain Binding A Singleton?

    https://stackoverflow.com/questions/25229064/laravel-difference-appbind-and-appsingleton

   **[⬆ Back to Top](#table-of-contents)**
    
139. ### Explain Binding Instances?

    https://stackoverflow.com/questions/40767040/how-laravels-container-binding-mechanisms-differ


   **[⬆ Back to Top](#table-of-contents)**
    
140. ### Explain Binding Primitives?

    https://stackoverflow.com/questions/40767040/how-laravels-container-binding-mechanisms-differ

   **[⬆ Back to Top](#table-of-contents)**
    
141. ### Explain Contextual Binding and how does it work?

    https://stackoverflow.com/questions/40767040/how-laravels-container-binding-mechanisms-differ


   **[⬆ Back to Top](#table-of-contents)**
    
142. ### What is Tagging?

    https://laravel-news.com/how-to-add-tagging-to-your-laravel-app


   **[⬆ Back to Top](#table-of-contents)**
    
143. ### Explain Extending Bindings?

        https://stackoverflow.com/questions/40767040/how-laravels-container-binding-mechanisms-differ


   **[⬆ Back to Top](#table-of-contents)**
    
144. ### What is the make Method?

    Makes controller, view, route, group and other items in artisan.

   **[⬆ Back to Top](#table-of-contents)**
    
145. ### How to clear cache in Laravel?

    php artisan cache:cleaer

   **[⬆ Back to Top](#table-of-contents)**
    
146. ### What is CSRF token?

     Protects against cross site attack


   **[⬆ Back to Top](#table-of-contents)**
    
147. ### How will you explain homestead in Laravel?

    Virtual box for vagrant

   **[⬆ Back to Top](#table-of-contents)**
    
148. ### How can we get the user's IP address in Laravel?

    Request::ip();

   **[⬆ Back to Top](#table-of-contents)**
    
149. ### How will you create a helper file in Laravel?

    https://tutsforweb.com/creating-helpers-laravel/

   **[⬆ Back to Top](#table-of-contents)**
    
150. ### How can we create a record in Laravel using eloquent?

        $flight = new Flight;

        $flight->name = $request->name;

        $flight->save();


   **[⬆ Back to Top](#table-of-contents)**
    

151. ### How can we get the user's IP address in Laravel?

   ```
   Request::ip();
   ```

   **[⬆ Back to Top](#table-of-contents)**
    
152. ### What is faker in Laravel?

   
     Used to generate dummy data


   **[⬆ Back to Top](#table-of-contents)**
    
153. ### What are active records?

    A design pattern which masks SQL queries to make database CRUD operations easy.

   **[⬆ Back to Top](#table-of-contents)**
    
154. ### What are the difference between insert() and insertGetId() in laravel?

    insert() only inserts
    insertGetId() inserts and returns id of last added item

   **[⬆ Back to Top](#table-of-contents)**
    
155. ### Talk about Laravel Vapor Compatibility

    https://vapor.laravel.com/


   **[⬆ Back to Top](#table-of-contents)**
    
156. ### What is Semantic Versioning?

    Major version . Minor version . Bug fix


   **[⬆ Back to Top](#table-of-contents)**
    
157. ### What are Jobs and Middleware?

    Jobs:
    Middleware:

   **[⬆ Back to Top](#table-of-contents)**
    
158. ### Talk about Laravel User Interface (UI)

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
159. ### Talk about Eloquent Subquery Enhancements?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
160. ### What are improved Authorization Responses?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
161. ### What are lazy collections?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
162. ### How to make a constant and use globally?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
163. ### How to remove /public from URL in laravel?


     Rename server.php in your Laravel root folder to index.php
     Copy the .htaccess file from /public directory to your Laravel root folder.


   **[⬆ Back to Top](#table-of-contents)**
    
164. ### What are the difference between soft delete & delete in Laravel?


     ...


   **[⬆ Back to Top](#table-of-contents)**
    
165. ### How we can upload files in laravel?

    Using `Form` class.
    ```
    <html>
       <body>
          <?php
             echo Form::open(array('url' => '/uploadfile','files'=>'true'));
             echo 'Select the file to upload.';
             echo Form::file('image');
             echo Form::submit('Upload File');
             echo Form::close();
          ?>
       </body>
    </html>
    ```
    
   **[⬆ Back to Top](#table-of-contents)**
    
166. ### Why are Redux state functions c166. ### How to create real time sitemap.xml file in Laravel?

    Make a controller to loop through all pages and list them. Make a route to it.

   **[⬆ Back to Top](#table-of-contents)**
    
167. ### How to use skip() and take() in Laravel Query?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
168. ### What is tinker in laravel?

    Tinker is command line code functionality where you can write Laravel code in CLI.

   **[⬆ Back to Top](#table-of-contents)**
    
169. ### What is a REPL?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
170. ### How to use multiple 'OR' condition in Laravel Query?
    ...

   **[⬆ Back to Top](#table-of-contents)**
    
171. ### Please write some additional where Clauses in Laravel?
    
    ...

   **[⬆ Back to Top](#table-of-contents)**
    
172. ### How to check column is exists or not in a table using Laravel?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
173. ### What is eager loading in Laravel?
   
    ...

   **[⬆ Back to Top](#table-of-contents)**
    
174. ### How to generate application key in laravel?

  ...

   **[⬆ Back to Top](#table-of-contents)**
    
175. ### What is LTS version of Laravel?

    LTS version is a version where the support is longer i.e it gets longer fixes and support and is a stable version.

   **[⬆ Back to Top](#table-of-contents)**
    
176. ### How to use GROUP_CONCAT() with JOIN in Laravel?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
177. ### How to extend login expire time in Auth?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
178. ### How to extend a layout file in laravel view?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
179. ### How do you use yield()?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
182. ### What is ACL in laravel?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
183. ### How to check Ajax request in Laravel?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
184. ### How to check if value is sent in request?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
185. ### Laravel String Helper functions?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
186. ### Laravel Array Helper functions?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
187. ### How to exclude a route with parameters from CSRF verification?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
188. ### What are policies classes?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
189. ### How to rollback last migration?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
190. ### What do you mean by Laravel Dusk?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
191. ### Explain Laravel echo

    Used with broadcasting and sockets.


   **[⬆ Back to Top](#table-of-contents)**
    
192. ### What is namespace in Laravel?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
193. ### What is Laravel Forge?

...

   **[⬆ Back to Top](#table-of-contents)**
    
194. ### State the difference between CodeIgniter and Laravel.

    CodeIgniter is an older framework and Laravel is a much advanced framework.

   **[⬆ Back to Top](#table-of-contents)**
    
195. ### What is an Observer?

...

   **[⬆ Back to Top](#table-of-contents)**
    
196. ### What is the use of the bootstrap directory?

...


   **[⬆ Back to Top](#table-of-contents)**
    
197. ### What is the default session timeout duration?


...

   **[⬆ Back to Top](#table-of-contents)**
    
198. ### Explain API.PHP route

...


   **[⬆ Back to Top](#table-of-contents)**
    
199. ### Define hashing in Laravel

...

   **[⬆ Back to Top](#table-of-contents)**
    
200. ### What is Localization?
...

   **[⬆ Back to Top](#table-of-contents)**
    
202. ### How to share data with views?

...

   **[⬆ Back to Top](#table-of-contents)**
    
203. ### How to generate a request in Laravel?

   Enter a route. It will go to the routes file to match the route and return a response.

   **[⬆ Back to Top](#table-of-contents)**
    
204. ### I just have installed a fresh version of Laravel 5, and I have the white screen of death. What’s wrong?

    You might see the white screen of death because of not enough permissions in folders. Try changing permissions of `/public`, `/vendor`, `/storage` folders.

   **[⬆ Back to Top](#table-of-contents)**
    
205. ### How to assign a variable value for all view file?

    ```
            public function __construct() {       

                $this->middleware(function ($request, $next) {              

                    $name = session()->get('businessinfo.name');  // get value from session

                    View::share('user_name', $name);                   // set value for all View

                    View::share('user_email', session()->get('businessinfo.email'));            

                    return $next($request);

                });

                 }


         
    ```

   **[⬆ Back to Top](#table-of-contents)**
    
206. ### How to make a constant and use globally?

Create it in the .env file

207. ### How to check current installed version of Laravel?

    See `composer.json` file.

   **[⬆ Back to Top](#table-of-contents)**
    
208. ### What does "composer dump-autoload" do?

It just regenerates the list of all classes that need to be included in the project (autoload_classmap.php).

   **[⬆ Back to Top](#table-of-contents)**
    
209. ### What is Kept in vendor directory of Laravel?

   Laravel dependencies. Their code.
   

   **[⬆ Back to Top](#table-of-contents)**
    
210. ### What does PHP compact function do?

   Convert variables to array.


   **[⬆ Back to Top](#table-of-contents)**
   
211. ### What are Laravel facades?

   ...


   **[⬆ Back to Top](#table-of-contents)**
   
212. ### What directories that need to be writable laravel installation?

   /public
   /bootstrap/cache
   /vendor


   **[⬆ Back to Top](#table-of-contents)**

213. ### How to check current Laravel version using CLI?

   php artisan --version


   **[⬆ Back to Top](#table-of-contents)**
   
214. ### Why prefer Laravel over other frameworks?

   --


   **[⬆ Back to Top](#table-of-contents)**
   
215. ### What are service containers?

   --


   **[⬆ Back to Top](#table-of-contents)**
   
   
   
 216. ### Write CRUD in Laravel Eloquent

   --

   **[⬆ Back to Top](#table-of-contents)**
   
 217. ### Write CRUD in Laravel Query Builder

   --

   **[⬆ Back to Top](#table-of-contents)**

 219. ### Write CRUD in Laravel Query Builder

   --

   **[⬆ Back to Top](#table-of-contents)**

 220. ### Build a to-do application with Laravel backend and a frontend framework  


   --

   **[⬆ Back to Top](#table-of-contents)**
   
 221. ### What are the day to day tasks of a Laravel developer?
1. Creating APIs
2. Write queries using Eloquent
3. Write helper functions
4. Installing required extensions for setting up Laravel
5. Setting up docker
6. Setting up homestead
7. Vue
8. Writing complex queries using eloquent
9. Using design patterns to build scaleable solutions
10. Tweak blade template.
11. Create SPA
12. Seed data into the database
   --

   **[⬆ Back to Top](#table-of-contents)**

 220. ### Output a raw query using eloquent or query builder. 

   Two ways,
   1. Turn the DB logs on and check the last query run in it.
   2. add ->ToSQL() function after the query.
   
   **[⬆ Back to Top](#table-of-contents)**

 220. ### How to create custom helper functions?

   Create a helper.php file anywhere and place the functions in it
   
   Add its location in the composer.json `files` area.
   
   Run composer dump autoload
   
   Answer here: https://stackoverflow.com/questions/28290332/best-practices-for-custom-helpers-in-laravel-5
   
   **[⬆ Back to Top](#table-of-contents)**
   
 221. ### How to check installed extensions in CLI and web for PHP?

   web: run phpinfo() function
   cli: php -m
      
   **[⬆ Back to Top](#table-of-contents)**
