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
|52 | [What are Laravel Traits?](#what-are-traits) |
|53 | [What are Bundles in Laravel?](#what-are-Bundles-in-Laravel) |
|54 | [What are System requirements for Laravel?](#system-requirements) |
|55 | [What are Aggregate methods in query builder?](#how-error-boundaries-handled-in-react-v15) |
|56 | [What is Singelton design pattern?](#what-are-the-recommended-ways-for-static-type-checking) |
|57 | [What is Reverse routing?](#what-is-the-use-of-react-dom-package) | 
|58 | [What are Popular composer packages?](#what-is-the-purpose-of-render-method-of-react-dom) |
|59 | [How to get the data from more than 3 table without use join ? Answer: Subquery, union.](#what-is-reactdomserver) |
|60 | [List some artisan commands](#how-to-use-innerhtml-in-react) |
|61 | [What are Sessisons?](#how-to-use-styles-in-react) |
|62 | [What are Cookies?](#how-events-are-different-in-react) |
|63 | [What is Current version of PHP, MySQL, Laravel, MongoDB etc?](#what-will-happen-if-you-use-setstate-in-constructor) |
|64 | [Describe design architecture of an app?](#what-is-the-impact-of-indexes-as-keys) |
|65 | [What are SQL Injections?](#is-it-good-to-use-setstate-in-componentwillmount-method) |
|66 | [How to call static methods?](#what-will-happen-if-you-use-props-in-initial-state) |
|67 | [How to achieve multiple DB hosts?](#how-do-you-conditionally-render-components)
|68 | [What is Abstract class?](#why-we-need-to-be-careful-when-spreading-props-on-dom-elements) |
|69 | [What are Default ports for MySQL, Email, etc?](#how-you-use-decorators-in-react) |
|70 | [Explain Joins](#how-do-you-memoize-a-component) |
|71 | [Explain Unions](#how-you-implement-server-side-rendering-or-ssr) |
|72 | [How mongodb is better than relational databases?](#how-to-enable-production-mode-in-react) |
|73 | [What is  mongodb?](#what-is-cra-and-its-benefits) |
|74 | [What is default session time?](#what-is-the-lifecycle-methods-order-in-mounting) |
|75 | [How to create hooks in Laravel?](#what-are-the-lifecycle-methods-going-to-be-deprecated-in-react-v16) |
|76 | [What is csrf token and xss attack?](#what-is-the-purpose-of-getderivedstatefromprops-lifecycle-method) |
|77 | [Select highest/nth highest salary from DB](#what-is-the-purpose-of-getsnapshotbeforeupdate-lifecycle-method) |
|78 | [Write a join](#do-hooks-replace-render-props-and-higher-order-components) |
|79 | [Write a union](#what-is-the-recommended-way-for-naming-components) |
|80 | [Write a complex query?](#what-is-the-recommended-ordering-of-methods-in-component-class) |
|81 | [What is a switching component?](#what-is-a-switching-component) |
|82 | [What is Difference between PHP 5 and 4?](#why-we-need-to-pass-a-function-to-setstate) |
|83 | [What is the difference among various php versions?](#what-is-strict-mode-in-react) |
|84 | [What is the difference among various mysql versions?](#what-are-react-mixins) |
|85 | [What is the difference among various Laravel versions?](#why-is-ismounted-an-anti-pattern-and-what-is-the-proper-solution) |
|86 | [How to add AWS plugin in PHP?](#what-are-the-pointer-events-supported-in-react) |
|87 | [What are design patterns?](#why-should-component-names-start-with-capital-letter) |
|88 | [What is the difference between GET and POST](#are-custom-dom-attributes-supported-in-react-v16) |
|89 | [Which is fast between GET and POST?](#what-is-the-difference-between-constructor-and-getinitialstate) |
|90 | [Explain 4 basics of OOP](#can-you-force-a-component-to-re-render-without-calling-setstate) |
|91 | [What is diference between abstract class and interface?](#what-is-the-difference-between-super-and-superprops-in-react-using-es6-classes) |
|92 | [What is MVC Framework?](#how-to-loop-inside-jsx) |
|93 | [Create a project with CRUD, one algorithm logic and insert data in db for testing.](#how-do-you-access-props-in-attribute-quotes) |
|94 | [Explain CURL and SOAP?](#what-is-react-proptype-array-with-shape) |
|95 | [In MySql we use many types of engines which one is faster and why?](#how-to-conditionally-apply-class-attributes) |
|96 | [What are Triggers?](#what-is-the-difference-between-react-and-reactdom) |
|97 | [What are Procedures](#why-reactdom-is-separated-from-react) |
|98 | [What are some new feaatures of Laravel X?](#how-to-use-react-label-element) |
|99 | [What are some new features of PHP X?](#how-to-combine-multiple-inline-style-objects) |
|100| [Explain Difference between session and cookies?](#how-to-re-render-the-view-when-the-browser-is-resized)
|101| [Merge 2 arrays with duplicate](#what-is-the-difference-between-setstate-and-replacestate-methods) |
|102| [Find the count of vowel and consonants](#how-to-listen-to-state-changes) |
|103| [Explain AWS Services](#what-is-the-recommended-approach-of-removing-an-array-element-in-react-state) |
|104| [How to do Web scraping?](#is-it-possible-to-use-react-without-rendering-html) |
|105| [Explain require and require once difference](#how-to-pretty-print-json-with-react) |
|106| [Explain include and require diffrence](#why-you-cant-update-props-in-react) |
|107| [Directory structure of Laravel](#how-to-focus-an-input-element-on-page-load) |
|108| [How to install Laravel via composer?](#what-are-the-possible-ways-of-updating-objects-in-state) |
|109| [Which ORM are being used by laravel?](#why-function-is-preferred-over-object-for-setstate) |
|110| [List types of relationships available in Laravel Eloquent?](#how-can-we-find-the-version-of-react-at-runtime-in-the-browser) |
|111| [How to enable maintenance mode in Laravel?](#what-are-the-approaches-to-include-polyfills-in-your-create-react-app) |
|112| [What is the purpose of using dd() function in laravel?](#how-to-use-https-instead-of-http-in-create-react-app) |
|113| [How do you register a Service Provider?](#how-to-avoid-using-relative-path-imports-in-create-react-app) |
|114| [How to add Google Analytics for react-router?](#how-to-add-google-analytics-for-react-router) |
|115| [Helper Functions](#how-to-update-a-component-every-second) |
|116| [What is Fillable Attribute in a Laravel Model?](#how-do-you-apply-vendor-prefixes-to-inline-styles-in-react) |
|117| [What is Guarded Attribute in a Laravel Model?](#how-to-import-and-export-components-using-react-and-es6) |
|118| [What are Closures in Laravel?](#why-react-component-names-must-begin-with-a-capital-letter) |
|119| [How to get Logged in user info in Laravel?](#why-is-a-component-constructor-called-only-once) |
|120| [What is Laravel Elixir?](#how-to-define-constants-in-react) |
|121| [What is Laravel Mix?](#how-to-programmatically-trigger-click-event-in-react) |
|122| [How can you display HTML with Blade in Laravel?](#is-it-possible-to-use-asyncawait-in-plain-react) |
|123| [List out databases that laravel supports?](#what-are-the-common-folder-structures-for-react) |
|124| [How to use custom table in Laravel Model?](#what-are-the-popular-packages-for-animation) |
|125| [How To Use Select Query In Laravel? Eloquent and QB?](#what-is-the-benefit-of-styles-modules) |
|126| [What are Accessors and Mutators in Eloquent and why should you use them?](#what-are-the-popular-react-specific-linters) |
|127| [How do I log an error?](#how-to-make-ajax-call-and-in-which-component-lifecycle-methods-should-i-make-an-ajax-call) |
|128| [What is Monolog library in Laravel?](#what-are-render-props) |
|129| [Exceptions are handled by which class in Laravel?](#what-is-react-router) |
|130| [What is Serialization in Laravel?](#how-react-router-is-different-from-history-library) |
|131| [What is Response in Laravel?](#what-are-the-router-components-of-react-router-v4) |
|132| [What is Response Macros in Laravel?](#what-is-the-purpose-of-push-and-replace-methods-of-history) |
|133| [What is Rate Limiting OR Throttle in Laravel?](#how-do-you-programmatically-navigate-using-react-router-v4) |
|134| [What is Lazy vs Eager Loading in Laravel?](#how-to-get-query-parameters-in-react-router-v4) |
|135| [How to get current environment in Laravel?](#why-you-get-router-may-have-only-one-child-element-warning) |
|136| [How to use custom table in Laravel Model ?](#how-to-pass-params-to-historypush-method-in-react-router-v4) |
|137| [What is Binding?](#how-to-implement-default-or-notfound-page) |
|138| [Explain Binding A Singleton?](#how-to-get-history-on-react-router-v4) |
|139| [Explain Binding Instances?](#how-to-perform-automatic-redirect-after-login) |
|140| [Explain Binding Primitives?](#what-is-react-intl) |
|141| [Explain Contextual Binding and how does it work?](#what-are-the-main-features-of-react-intl) |
|142| [What is Tagging?](#what-are-the-two-ways-of-formatting-in-react-intl) |
|143| [Explain Extending Bindings?](#how-to-use-formattedmessage-as-placeholder-using-react-intl) |
|144| [What is the make Method?](#how-to-access-current-locale-with-react-intl) |
|145| [How to clear cache in Laravel?](#how-to-format-date-using-react-intl) |
|146| [What is CSRF token?](#what-is-shallow-renderer-in-react-testing) |
|147| [How will you explain homestead in Laravel?](#what-is-testrenderer-package-in-react) |
|148| [How can we get the user's IP address in Laravel?](#what-is-the-purpose-of-reacttestutils-package) |
|149| [How will you create a helper file in Laravel?](#what-is-jest) |
|150| [How can we create a record in Laravel using eloquent?](#what-are-the-advantages-of-jest-over-jasmine) |
|151| [How can we get the user's IP address in Laravel?](#give-a-simple-example-of-jest-test-case) |
|152| [What is faker in Laravel?](#what-is-flux) |
|153| [What are active records?](#what-is-redux) |
|154| [What are the difference between insert() and insertGetId() in laravel?](#what-are-the-core-principles-of-redux) |
|155| [Talk about Laravel Vapor Compatibility](#what-are-the-downsides-of-redux-compared-to-flux) |
|156| [What is Semantic Versioning?](#what-is-the-difference-between-mapstatetoprops-and-mapdispatchtoprops) |
|157| [What are Jobs and Middleware?](#can-i-dispatch-an-action-in-reducer) |
|158| [Talk about Laravel User Interface (UI)](#how-to-access-redux-store-outside-a-component) |
|159| [Talk about Eloquent Subquery Enhancements?](#what-are-the-drawbacks-of-mvw-pattern) |
|160| [What are improved Authorization Responses?](#are-there-any-similarities-between-redux-and-rxjs) |
|161| [What are lazy collections?](#how-to-dispatch-an-action-on-load) |
|162| [How to make a constant and use globally?](#how-to-use-connect-from-react-redux) |
|163| [How to remove /public from URL in laravel?](#how-to-reset-state-in-redux) |
|164| [What are the difference between soft delete & delete in Laravel?](#whats-the-purpose-of-at-symbol-in-the-redux-connect-decorator) |
|165| [How we can upload files in laravel?](#what-is-the-difference-between-react-context-and-react-redux) |
|166| [How to create real time sitemap.xml file in Laravel?](#why-are-redux-state-functions-called-reducers) |
|167| [How to use skip() and take() in Laravel Query?](#how-to-make-ajax-request-in-redux) |
|168| [What is tinker in laravel?](#should-i-keep-all-components-state-in-redux-store) |
|169| [What is a REPL?](#what-is-the-proper-way-to-access-redux-store) |
|170| [How to use multiple 'OR' condition in Laravel Query?](#what-is-the-difference-between-component-and-container-in-react-redux) |
|171| [Please write some additional where Clauses in Laravel?](#what-is-the-purpose-of-the-constants-in-redux) |
|172| [How to check column is exists or not in a table using Laravel?](#what-are-the-different-ways-to-write-mapdispatchtoprops) |
|173| [What is eager loading in Laravel?](#what-is-the-use-of-the-ownprops-parameter-in-mapstatetoprops-and-mapdispatchtoprops) |
|174| [How to generate application key in laravel?](#how-to-structure-redux-top-level-directories) |
|175| [What is LTS version of Laravel?](#what-is-redux-saga) |
|176| [How to use GROUP_CONCAT() with JOIN in Laravel?](#what-is-the-mental-model-of-redux-saga) |
|177| [How to extend login expire time in Auth?](#what-are-the-differences-between-call-and-put-in-redux-saga) |
|178| [How to extend a layout file in laravel view?](#what-is-redux-thunk) |
|179| [How do you use yield()?](#what-are-the-differences-between-redux-saga-and-redux-thunk) |
|180| [How to redirect form controller to view file in laravel?](#what-is-redux-devtools) |
|181| [How to get current route name?](#what-are-the-features-of-redux-devtools) |
|182| [What is ACL in laravel?](#what-are-redux-selectors-and-why-to-use-them) |
|183| [How to check Ajax request in Laravel?](#what-is-redux-form) |
|184| [How to check if value is sent in request?](#what-are-the-main-features-of-redux-form) |
|185| [Laravel String Helper functions?](#how-to-add-multiple-middlewares-to-redux) |
|186| [Laravel Array Helper functions?](#how-to-set-initial-state-in-redux) |
|187| [How to exclude a route with parameters from CSRF verification?](#how-relay-is-different-from-redux) |
|188| [What are policies classes?](#what-is-the-difference-between-react-native-and-react) |
|189| [How to rollback last migration?](#how-to-test-react-native-apps) |
|190| [What do you mean by Laravel Dusk?](#how-to-do-logging-in-react-native) |
|191| [Explain Laravel echo](#how-to-debug-your-react-native) |
|192| [What is namespace in Laravel?](#what-is-reselect-and-how-it-works) |
|193| [What is Laravel Forge?](#what-is-flow) |
|194| [State the difference between CodeIgniter and Laravel.](#what-is-the-difference-between-flow-and-proptypes) |
|195| [What is an Observer?](#how-to-use-font-awesome-icons-in-react) |
|196| [What is the use of the bootstrap directory?](#what-is-react-dev-tools) |
|197| [What is the default session timeout duration?](#why-is-devtools-not-loading-in-chrome-for-local-files) |
|198| [Explain API.PHP route](#how-to-use-polymer-in-react) |
|199| [Define hashing in Laravel](#what-are-the-advantages-of-react-over-vuejs) |
|200| [What is Localization?](#what-is-the-difference-between-react-and-angular) |
|201| [Explain the concept of encryption and decryption in Laravel.](#why-react-tab-is-not-showing-up-in-devtools) |
|202| [How to share data with views?](#what-are-styled-components) |
|203| [How to generate a request in Laravel?](#give-an-example-of-styled-components) |
|204| [I just have installed a fresh version of Laravel 5, and I have the white screen of death. What’s wrong?](#what-is-relay) |
|205| [How to assign a variable value for all view file?](#how-to-use-typescript-in-create-react-app-application) |
|206| [How to make a constant and use globally?](#what-are-the-main-features-of-reselect-library) |
|207| [How to check current installed version of Laravel?](#give-an-example-of-reselect-usage) |
|208| [What does "composer dump-autoload" do?](#what-is-an-action-in-redux) |
|209| [What is Kept in vendor directory of Laravel?](#does-the-statics-object-work-with-es6-classes-in-react) |
|210| [What does PHP compact function do?](#can-redux-only-be-used-with-react) |
|210| [What is APP_KEY used for?](#can-redux-only-be-used-with-react) |
## Core Laravel


    
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

 ...

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
    
59.	### How to get the data from more than 3 table without use join ?

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
    
63.	### What is Current version of PHP, MySQL, Laravel, MongoDB etc?

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

    ...

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
    
    ...

   **[⬆ Back to Top](#table-of-contents)**
    
76.	### What is csrf token and xss attack?

   CSRF and JWT tokens are used to make sure the action is performed by the user. If there is no token, someone can give a link to user to click or hide it behind some action and him do what the hacker wants.


   **[⬆ Back to Top](#table-of-contents)**
    
77.	### Select highest/nth highest salary from DB

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
78.	### Write the 4 joins

...

   **[⬆ Back to Top](#table-of-contents)**
    
79. ### Write a union

...

   **[⬆ Back to Top](#table-of-contents)**
    
80. ### Write a complex query?


   Like a 3 tables joined.


   **[⬆ Back to Top](#table-of-contents)**
    
81. ### What is a switching component?


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

    ...

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

    ```

   **[⬆ Back to Top](#table-of-contents)**
    
92. ### What is MVC Framework?

    ...

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

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
97. ### What are Procedures

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
98. ### What are some new feaatures of Laravel X?

    ...

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

    ...


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

    ...

   **[⬆ Back to Top](#table-of-contents)**
   
110. ### List types of relationships available in Laravel Eloquent?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
111. ### How to enable maintenance mode in Laravel?

    ```
    php artisan down
    ```

   **[⬆ Back to Top](#table-of-contents)**
    
112. ### What is the purpose of using dd() function in laravel?

    ...

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
    
114. ### X

   **[⬆ Back to Top](#table-of-contents)**
    
115. ### Helper Functions
    
    Common function which you can use in many classes are stored in helper functions.

   **[⬆ Back to Top](#table-of-contents)**
    
116. ### What is Fillable Attribute in a Laravel Model?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
117. ### What is Guarded Attribute in a Laravel Model?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
118. ### What are Closures in Laravel?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
119. ### How to get Logged in user info in Laravel?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
120. ### What is Laravel Elixir?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
121. ### What is Laravel Mix?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
122. ### How can you display HTML with Blade in Laravel?

     ...

   **[⬆ Back to Top](#table-of-contents)**
    
123. ### What are the common folder structures for React?

     ...

   **[⬆ Back to Top](#table-of-contents)**
    
124. ### List out databases that laravel supports?


    ...

   **[⬆ Back to Top](#table-of-contents)**
    
124. ### How to use custom table in Laravel Model?

    By mentoning the name of the table in `$table` variable

   **[⬆ Back to Top](#table-of-contents)**
    
125. ### How To Use Select Query In Laravel? Eloquent and QB?

    ...
    
126. ### What are Accessors and Mutators in Eloquent and why should you use them?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
127. ### How do I log an error?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
128. ### What is Monolog library in Laravel?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
129. ### Exceptions are handled by which class in Laravel?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
130. ### What is Serialization in Laravel?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
131. ### What is Response in Laravel?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
132. ### What is Response Macros in Laravel?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
133. ### What is Rate Limiting OR Throttle in Laravel?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
134. ### What is Lazy vs Eager Loading in Laravel?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
135. ### How to get current environment in Laravel?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
136. ### How to use custom table in Laravel Model ?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
137. ### What is Binding?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
138. ### Explain Binding A Singleton?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
139. ### Explain Binding Instances?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
140. ### Explain Binding Primitives?


    ...

   **[⬆ Back to Top](#table-of-contents)**
    
141. ### Explain Contextual Binding and how does it work?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
142. ### What is Tagging?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
143. ### Explain Extending Bindings?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
144. ### What is the make Method?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
145. ### How to clear cache in Laravel?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
146. ### What is CSRF token?

     ...


   **[⬆ Back to Top](#table-of-contents)**
    
147. ### How will you explain homestead in Laravel?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
14. ### How can we get the user's IP address in Laravel?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
149. ### How will you create a helper file in Laravel?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
150. ### How can we create a record in Laravel using eloquent?

    ...


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

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
155. ### Talk about Laravel Vapor Compatibility

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
156. ### What is Semantic Versioning?

    Major version . Minor version . Bug fix


   **[⬆ Back to Top](#table-of-contents)**
    
157. ### What are Jobs and Middleware?

    ...

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


     ...


   **[⬆ Back to Top](#table-of-contents)**
    
164. ### What are the difference between soft delete & delete in Laravel?


     ...


   **[⬆ Back to Top](#table-of-contents)**
    
165. ### How we can upload files in laravel?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
166. ### Why are Redux state functions c166. ### How to create real time sitemap.xml file in Laravel?

    ...

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

...

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
    
198	Explain API.PHP route

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
    
203	How to generate a request in Laravel?

   Enter a route. It will go to the routes file to match the route and return a response.

   **[⬆ Back to Top](#table-of-contents)**
    
204. ### I just have installed a fresh version of Laravel 5, and I have the white screen of death. What’s wrong?

    You might see the white screen of death because of not enough permissions in folders. Try changing permissions of `/public`, `/vendor`, `/storage` folders.

   **[⬆ Back to Top](#table-of-contents)**
    
205. ### How to assign a variable value for all view file?

...

   **[⬆ Back to Top](#table-of-contents)**
    
206. ### How to make a constant and use globally?

..

207. ### How to check current installed version of Laravel?

...

   **[⬆ Back to Top](#table-of-contents)**
    
208. ### What does "composer dump-autoload" do?

..


   **[⬆ Back to Top](#table-of-contents)**
    
209. ### What is Kept in vendor directory of Laravel?

   Laravel dependencies. Their code.
   

   **[⬆ Back to Top](#table-of-contents)**
    
210. ### What does PHP compact function do?

   Convert variables to array.


   **[⬆ Back to Top](#table-of-contents)**
