# Top Laravel Interview Questions & Answers

> Click :star: if you like the project. Pull Request are highly appreciated.

### Table of Contents

| No. | Questions |
| --- | --------- |
|| **ARCHITECTURE** |
|| Request Lifecycle |
|| [What is Request-Response?](#what-is-request-response) |
|| Service Container Binding and Resolution |
|| [What are service containers?](#What-are-service-containers) |
|| [What is Binding?](#What-is-Binding) |
|| [Explain Binding A Singleton?](#Explain-Binding-A-Singleton) |
|| [Explain Binding Instances?](#Explain-Binding-Instances) |
|| [Explain Binding Primitives?](#Explain-Binding-Primitives) |
|| [Explain Contextual Binding and how does it work?](#Explain-Contextual-Binding-and-how-does-it-work) |
|| [What is Tagging?](#What-is-Tagging) |
|| [Explain Extending Bindings?](#Explain-Extending-Bindings) |
|| Service Providers |
|| [What are Service Providers?](#what-are-service-providers) |
|| Facades |
|| [What are Facades?](#what-are-facades) |
|| HTTP Verbs |
|| [What are HTTP Verbs?](#http-verbs) |
|| [What is the difference between GET and POST?](#What-is-the-difference-between-GET-and-POST) |
|| [Which is fast between GET and POST?](#Which-is-fast-between-GET-and-POST) |
|| **Artisan Console** |
|| Generating Commands |
|| [How to generate application key in laravel?](#How-to-generate-application-key-in-laravel) |
|| [List all make commands](#List-all-make-commands) |
|| [Command I/O](https://laravel.com/docs/8.x/artisan#defining-input-expectations)|
|| Registering Commands (https://laravel.com/docs/8.x/artisan#registering-commands) |
|| Executing Commands (https://laravel.com/docs/8.x/artisan#programmatically-executing-commands) |
|| **Caching** |
|| Drivers / Configuration (https://laravel.com/docs/8.x/cache#driver-prerequisites)|
|| Storing Items (https://laravel.com/docs/8.x/cache#storing-tagged-cache-items) |
|| Retrieving Items (https://laravel.com/docs/8.x/cache#accessing-tagged-cache-items)|
|| Cache Tags (https://laravel.com/docs/8.x/cache#cache-tags) |
|| Creating Custom Drivers (https://laravel.com/docs/8.x/cache#adding-custom-cache-drivers) |
|| **Collections** |
|| Creating (https://laravel.com/docs/8.x/collections#creating-collections) / Extending Collections (https://laravel.com/docs/8.x/collections#extending-collections) |
|| Collection Methods (https://laravel.com/docs/8.x/collections#available-methods) |
|| Higher-order Messages (https://laravel.com/docs/8.x/collections#higher-order-messages) |
|| **Controllers** |
|| [Define Implicit Controller](#what-is-the-difference-between-where-and-having) |
|| Defining Controllers (https://laravel.com/docs/8.x/controllers#defining-controllers) |
|| Controller Namespacing |
|| Single Action Controllers (https://laravel.com/docs/8.x/controllers#single-action-controllers) |
|| Middleware (https://laravel.com/docs/8.x/controllers#controller-middleware)|
|| Resource Controllers (https://laravel.com/docs/8.x/controllers#resource-controllers) |
|| Dependency Injection (https://laravel.com/docs/8.x/controllers#dependency-injection-and-controllers) |
|| Route Caching (https://laravel.com/docs/8.x/controllers#route-caching) |
|| **Database** |
|| Query Builder (https://laravel.com/docs/8.x/queries)|
|| Pagination (https://laravel.com/docs/8.x/pagination) |
||    [How to do Pagination in DB?](#how-to-do-pagination-in-db) |
|| Migrations (https://laravel.com/docs/8.x/migrations) |
|| [When are Migrations?](#what-are-migrations) |
|| Seeding (https://laravel.com/docs/8.x/seeding) |
|| [What are Seeders?](#what-are-seeders) |
|| **Eloquent ORM** |
|   | Conventions (https://laravel.com/docs/5.0/eloquent) |
|   | Relationships (https://laravel.com/docs/8.x/eloquent-relationships) |
|   | Eloquent Collections (https://laravel.com/docs/8.x/eloquent-collections) |
|   | Mutators / Accessors (https://laravel.com/docs/8.x/eloquent-mutators) |
|| [What are Accessors and Mutators in Eloquent and why should you use them?](#What-are-Accessors-and-Mutators-in-Eloquent-and-why-should-you-use-them) |
|   | API Resources (https://laravel.com/docs/8.x/eloquent-resources) |
|   | Serialization (https://laravel.com/docs/8.x/eloquent-serialization) |
|   | Scopes (https://laravel.com/docs/8.x/eloquent#global-scopes) |
|   | **Events** (https://laravel.com/docs/8.x/events) |
| | [What are Events?](#what-are-events) |
| | [What are Listeners (https://laravel.com/docs/8.x/events#defining-listeners)?](#what-are-listeners) |
|   | Registering Events  / Listeners (https://laravel.com/docs/8.x/events#registering-events-and-listeners) |
|   | Queued Listeners (https://laravel.com/docs/8.x/events#queued-event-listeners) |
|   | Dispatching Events (https://laravel.com/docs/8.x/events#dispatching-events) |
|   | Subscribing to Events (https://laravel.com/docs/8.x/events#event-subscribers) |
|   | **File Storage** (https://laravel.com/docs/8.x/filesystem) |
|   | Configuration / Drivers  (https://laravel.com/docs/8.x/filesystem#configuration) |
|   | Storing (https://laravel.com/docs/8.x/filesystem#storing-files) / Retrieving Files (https://laravel.com/docs/8.x/filesystem#retrieving-files) |
|   | Custom Filesystems (https://laravel.com/docs/8.x/filesystem#custom-filesystems) |
|   | **Frontend** |
|   | Blade Templating (https://laravel.com/docs/8.x/blade) |
|   | Localization (https://laravel.com/docs/8.x/localization) |
|   | Asset Compilation (https://laravel.com/docs/8.x/mix) |
|   | **Helper Methods** (https://laravel.com/docs/8.x/helpers) |
|   | Arrays / Objects (https://laravel.com/docs/8.x/helpers#arrays-and-objects-method-list) |
|   | Paths (https://laravel.com/docs/8.x/helpers#paths-method-list) |
|   | Strings (https://laravel.com/docs/8.x/helpers#strings-method-list) |
|   | URLs (https://laravel.com/docs/8.x/helpers#urls-method-list) |
|   | Misc (https://laravel.com/docs/8.x/helpers#miscellaneous-method-list) |
|   | **Logging** (https://laravel.com/docs/8.x/logging#introduction) |
|   | Configuration (https://laravel.com/docs/8.x/logging#configuration) |
|   | Writing to Specific Channels (https://laravel.com/docs/8.x/logging#configuring-the-channel-name) |
|   | Creating Custom Channels (https://laravel.com/docs/8.x/logging#advanced-monolog-channel-customization) |
|   | **Mail** (https://laravel.com/docs/8.x/mail#introduction) |
|   | Drivers (https://laravel.com/docs/8.x/mail#driver-prerequisites) / Configuration (https://laravel.com/docs/8.x/mail#configuration)  |
|   | Generating Mailables (https://laravel.com/docs/8.x/mail#generating-mailables) |
|   | Writing Mail (https://laravel.com/docs/8.x/mail#writing-mailables) |
|   | Sending Mail (https://laravel.com/docs/8.x/mail#sending-mail) |
|   | Markdown (https://laravel.com/docs/8.x/mail#markdown-mailables) |
|   | Local Development (https://laravel.com/docs/8.x/mail#mail-and-local-development) |
|   | **Middleware** |
|   | Defining / Registering Middleware (https://laravel.com/docs/8.x/middleware#registering-middleware) |
|   | Middleware Parameters (https://laravel.com/docs/8.x/middleware#middleware-parameters)|
|   | **Notifications** |
|   | Creating Notifications (https://laravel.com/docs/8.x/notifications#introduction) |
|   | Sending Notifications (https://laravel.com/docs/8.x/notifications#sending-notifications) |
|   | Mail Notifications (https://laravel.com/docs/8.x/notifications#mail-notifications) |
|   | Markdown (https://laravel.com/docs/8.x/notifications#markdown-mail-notifications) |
|   | Database Notifications (https://laravel.com/docs/8.x/notifications#database-notifications) |
|   | Broadcast Notifications (https://laravel.com/docs/8.x/notifications#broadcast-notifications) |
|   | SMS Notifications (https://laravel.com/docs/8.x/notifications#sms-notifications) |
|   | Slack Notifications (https://laravel.com/docs/8.x/notifications#slack-notifications) |
|   | Custom Channels (https://laravel.com/docs/8.x/notifications#custom-channels) |
|   | **PHP** |
|   | Version 7.1+ |
|   | Composer |
|   | Autoloading Standards |
|   | **Package Development** |
|   | Discovery (https://laravel.com/docs/8.x/packages#package-discovery) |
|   | Service Providers (https://laravel.com/docs/8.x/packages#service-providers) |
|   | Resources (https://laravel.com/docs/8.x/packages#resources) |
|   | Commands (https://laravel.com/docs/8.x/packages#commands) |
|   | Assets (https://laravel.com/docs/8.x/packages#public-assets) |
|   | Publishing File Groups (https://laravel.com/docs/8.x/packages#publishing-file-groups) |
|   | **Queues** |
|   | Drivers / Configurations (https://laravel.com/docs/8.x/queues#other-driver-prerequisites) |
|   | Creating / Dispatching Jobs (https://laravel.com/docs/8.x/queues#dispatching-jobs) |
|   | **Routing** |
|   | Redirects (https://laravel.com/docs/8.x/routing#basic-routing) |
|   | Route Parameters (https://laravel.com/docs/8.x/routing#route-parameters) |
|   | Named Routes (https://laravel.com/docs/8.x/routing#named-routes) |
|   | Route Groups (https://laravel.com/docs/8.x/routing#route-groups) |
|   | Route Model Binding (https://laravel.com/docs/8.x/routing#route-model-binding) |
|   | Rate Limiting (https://laravel.com/docs/8.x/routing#rate-limiting) |
|   | [What is Rate Limiting OR Throttle in Laravel?](#What-is-Rate-Limiting-OR-Throttle-in-Laravel) |
|   | **Security** |
|   | Authentication (https://laravel.com/docs/8.x/authentication#introduction) |
|   | Authorization (https://laravel.com/docs/8.x/authorization#introduction) |
|   | Encryption (https://laravel.com/docs/8.x/encryption) / Hashing (https://laravel.com/docs/8.x/hashing) |
|   | CSRF Protection (https://laravel.com/docs/8.x/csrf#csrf-introduction) |
|   | XSS Protection |
|   | **Sessions** (https://laravel.com/docs/8.x/session) |
|   | Configuration (https://laravel.com/docs/8.x/session#configuration) |
|   | Storing Data (https://laravel.com/docs/8.x/session#storing-data)|
|   | Retrieving Data (https://laravel.com/docs/8.x/session#retrieving-data)|
|   | Deleting Data (https://laravel.com/docs/8.x/session#deleting-data) |
|   | Flash Data (https://laravel.com/docs/8.x/session#flash-data) |
|   | Custom Drivers (https://laravel.com/docs/8.x/session#adding-custom-session-drivers) |
|   | **Task Scheduling** (https://laravel.com/docs/8.x/scheduling#introduction) |
|   | Scheduling Artisan Commands (https://laravel.com/docs/8.x/scheduling#scheduling-artisan-commands) |
|   | Scheduling Queue Jobs (https://laravel.com/docs/8.x/scheduling#scheduling-queued-jobs)|
|   | Scheduling Shell Commands (https://laravel.com/docs/8.x/scheduling#scheduling-shell-commands) |
|   | Time Zones (https://laravel.com/docs/8.x/scheduling#timezones) |
|   | Preventing Task Overlaps (https://laravel.com/docs/8.x/scheduling#preventing-task-overlaps) |
|   | Maintenance Mode (https://laravel.com/docs/8.x/scheduling#maintenance-mode) |
|   | **Testing** |
|   | Creating (https://laravel.com/docs/8.x/testing#creating-tests) / Running Tests (https://laravel.com/docs/8.x/testing#running-tests) |
|   | HTTP Tests (https://laravel.com/docs/8.x/http-tests) |
|   | Session / Authentication (https://laravel.com/docs/8.x/http-tests#session-and-authentication) |
|   | Testing File Uploads (https://laravel.com/docs/8.x/http-tests#testing-file-uploads) |
|   | Available Assertions (https://laravel.com/docs/8.x/http-tests#available-assertions) |
|   | Browser Tests / Dusk |
|   | Data Factories |
|   | Fakes / Mocking (https://laravel.com/docs/8.x/mocking) |
|   | **URL Generation** (https://laravel.com/docs/8.x/urls#introduction) |
|   | Named Routes (https://laravel.com/docs/8.x/urls#urls-for-named-routes) |
|   | Controller Actions (https://laravel.com/docs/8.x/urls#urls-for-controller-actions) |
|   | Default Values (https://laravel.com/docs/8.x/urls#default-values)|
|   | **Validation** (https://laravel.com/docs/8.x/validation) |
|   | Form Requests (https://laravel.com/docs/8.x/validation#form-request-validation) |
|   | Manually Creating Validators (https://laravel.com/docs/8.x/validation#manually-creating-validators) |
|   | Error Messages (https://laravel.com/docs/8.x/validation#working-with-error-messages) |
|   | Validation Rules (https://laravel.com/docs/8.x/validation#available-validation-rules)|
|   | Custom Validation Rules (https://laravel.com/docs/8.x/validation#custom-validation-rules) |
|   | **Views** (https://laravel.com/docs/8.x/views#creating-and-rendering-views) |
|   | Creating Views (https://laravel.com/docs/8.x/views#creating-and-rendering-views) |
|   | Passing Data to Views (https://laravel.com/docs/8.x/views#passing-data-to-views) |
|   | View Composer (https://laravel.com/docs/8.x/views#view-composers) |
|   | **Websockets** (https://laravel.com/docs/8.x/broadcasting) |
|   | Broadcasting Events (https://laravel.com/docs/8.x/broadcasting#broadcasting-events) |
|   | Receiving Events |
|   | Broadcasting Channels () |
|   | Presence Channels (https://laravel.com/docs/8.x/broadcasting#presence-channels) |
|   | Client Events (https://laravel.com/docs/8.x/broadcasting#client-events) |
| | [What is Repository Pattern?](#what-is-repository-pattern) |
| | [What is Symfony?](#what-is-symfony) |
| | [What are Triggers?](#What-are-Triggers) |
| | [What are Procedures](#What-are-Procedures) |
| | [What are Laravel Traits?](#what-are-laravel-traits) |
| | [What are Bundles in Laravel?](#what-are-Bundles-in-Laravel) |
|| [In which folder robot.txt is placed?](#what-is-the-difference-between-where-and-having) |
|| [What is APP_KEY used for?](#What-is-APP_KEY-used-for) |
|| [What directories that need to be writable laravel installation?](#What-directories-that-need-to-be-writable-laravel-installation?) |
|| [What is Kept in vendor directory of Laravel?](#What-is-Kept-in-vendor-directory-of-Laravel) |
|| [What is the use of dd() function?](#what-is-the-difference-between-where-and-having) |
|| [What does "composer dump-autoload" do?](#What-does-composer-dump-autoload-do) |
|| [What is IOC (Inversion of Control)?](#what-is-the-difference-between-where-and-having) |
|| [What is the use of the bootstrap directory?](#What-is-the-use-of-the-bootstrap-directory) |
|| [What is Serialization in Laravel?](#What-is-Serialization-in-Laravel) |
|| [What is faker in Laravel?](#What-is-faker-in-Laravel) |
|| [What is Response in Laravel?](#What-is-Response-in-Laravel) |
|| [What is Response Macros in Laravel?](#What-is-Response-Macros-in-Laravel) |
|| [What is Lazy vs Eager Loading in Laravel?](#What-is-Lazy-vs-Eager-Loading-in-Laravel) |
|| [What is the make Method?](#What-is-the-make-Method) |
|| [What are the difference between insert() and insertGetId() in laravel?](#What-are-the-difference-between-insert-and-insertGetId-in-laravel) |
|| [Talk about Laravel Vapor Compatibility](#Talk-about-Laravel-Vapor-Compatibility) |
|| [What is Semantic Versioning?](#What-is-Semantic-Versioning) |
|| [What is LTS version of Laravel?](#What-is-LTS-version-of-Laravel) |
| | [What is Lumen?](#what-is-lumen) |
| | [What are Laravel contracts?](#what-are-contracts) |
|| [Directory structure of Laravel](#Directory-structure-of-Laravel) |
|| [Explain Laravel framework Architecture](#Explain-Laravel-framework-Architecture) |
|| [What is Monolog library in Laravel?](#What-is-Monolog-library-in-Laravel) |
|| [What is ORM?](#What-is-ORM) |
|   | **CONCEPTS** |
|| [Explain active record concept in Laravel](#what-is-the-difference-between-where-and-having) |
|| [What is Laravel API rate limit?](#what-is-the-difference-between-where-and-having) |
|| [What is Serialization in Laravel?](#what-is-the-difference-between-where-and-having) |
|| [What are Response Macros in Laravel?](#what-is-the-difference-between-where-and-having) |
|| [What is Method Spoofing in Laravel?](#what-is-the-difference-between-where-and-having) |
|| [What are Closures in Laravel?](#what-is-the-difference-between-where-and-having) |
|| [What are Closures in Laravel?](#What-are-Closures-in-Laravel) |
|| [How to create constants in laravel?](#what-is-the-difference-between-where-and-having) |
| | [What are factories?](#what-are-factories) |
|   | **ARTISAN CONSOLE** |
|| [What is tinker in laravel?](#What-is-tinker-in-laravel) |
|| [What is a REPL?](#What-is-a-REPL) |
| | [List some artisan commands](#list-some-artisan-commands) |
|   | **CACHING** |
| | [What is Caching?](#what-is-caching) |
| | [What is Redis?](#what-is-redis) |
| | [What is Memcache?](#what-is-memcache) |
| | [What is Route caching?](#what-is-route-caching) |
|| [Does Laravel support caching?](#what-is-the-difference-between-where-and-having) |
|| [How to clear cache in Laravel?](#How-to-clear-cache-in-Laravel) |
|   | **COLLECTIONS** |
|| [What are lazy collections?](#What-are-lazy-collections) |
|   | **DATABASE** |
|| [What is Query Builder?](#what-is-query-builder)
|| [What is ORM?](#what-is-orm) |
| | [How to achieve multiple DB hosts?](#How-to-achieve-multiple-DB-hosts)
| | [What are Default ports for MySQL Email etc?](#what-are-Default-ports-for-MySQL-Email-etc) |
| | [Explain Joins](#Explain-Joins) |
| | [Explain Unions](#Explain-Unions) |
| | [How mongodb is better than relational databases?](#How-mongodb-is-better-than-relational-databases) |
| | [What is  mongodb?](#What-is-mongodb) |
| | [Select highest and nth highest salary from DB](#Select-highest-and-nth-highest-salary-from-DB) |
| | [Write a join](#Write-a-join) |
| | [Write a union](#Write-a-union) |
| | [Write a complex query?](#Write-a-complex-query) |
|| [Name databases supported by Laravel](#what-is-the-difference-between-where-and-having) |
|| [Define Laravel guard](#what-is-the-difference-between-where-and-having) |
| | [What are Aggregate methods in query builder?](#what-are-aggregate-methods-in-query-builder) |
|   | **ELOQUENT** |
| | [What is Eloquent?](#what-is-eloquent) |
|| [Write CRUD in Laravel Eloquent?](#Write-CRUD-in-Laravel-Eloquent) |
|| [What are Eloquent collections?](#What-are-Eloquent-collections) |
|| [Output a raw query using eloquent/query builder ](#Output-a-raw-query-using-eloquent-or-query-builder) |
|| [How to create multiple where clause in eloquent?](#How-to-create-multiple-where-clause-in-eloquent) |
|| [What is the purpose of the Eloquent cursor() method in Laravel?](#what-is-the-difference-between-where-and-having) |
|| [List types of relationships available in Laravel Eloquent?](#what-is-the-difference-between-where-and-having) |
| | [Write CRUD in Laravel Eloquent](#Write-CRUD-in-Laravel-Eloquent) |
|| [Talk about Eloquent Subquery Enhancements?](#Talk-about-Eloquent-Subquery-Enhancements) |
|| [How can we create a record in Laravel using eloquent?](#How-can-we-create-a-record-in-Laravel-using-eloquent) |
|| [List types of relationships available in Laravel Eloquent?](#List-types-of-relationships-available-in-Laravel-Eloquent) |
|   | **FRONT END** |
|| [What does yield mean in PHP?](#what-is-the-difference-between-where-and-having) |
|| [How to extend a layout file in laravel view?](#How-to-extend-a-layout-file-in-laravel-view) |
|| [How do you use yield()?](#How-do-you-use-yield()) |
|| [How to redirect form controller to view file in laravel?](#How-to-redirect-form-controller-to-view-file-in-laravel) |
|   | **CONTROLLERS** |
|  | [What is Controller?](#what-is-controller) |
|   | **HELPER METHOD** |
|| [Helper Functions](#Helper-Functions) |
|| [How to create custom helper functions](#How-to-create-custom-helper-functions) |
|| [Laravel String Helper functions?](#Laravel-String-Helper-functions) |
|| [Laravel Array Helper functions?](#Laravel-Array-Helper-functions) |
|   | **DATABASE** |
| | [What is a Model?](#what-is-a-model) |
| | [What are Advanced Eloquent and Query Builder?](#what-are-advanced-eloquent-and-query-builder) |
| | [How to connect Laravel with other SQL databases?](#How-to-connect-Laravel-with-other-SQL-databases) |
| | [How to connect Laravel with non-SQL databases?](#How-to-connect-Laravel-with-non-SQL-databases) |
|| [List out databases that laravel supports?](#List-out-databases-that-laravel-supports) |
|| [How to use custom table in Laravel Model?](#How-to-use-custom-table-in-Laravel-Model) |
|| [What is Fillable Attribute in a Laravel Model?](#What-is-Fillable-Attribute-in-a-Laravel-Model) |
|| [What is Guarded Attribute in a Laravel Model?](#What-is-Guarded-Attribute-in-a-Laravel-Model) |
| | [How to get the data from more than 3 table without using a join?](#how-to-get-the-data-from-more-than-3-table-without-using-a-join) |
|| [What are active records?](#What-are-active-records) |
|| [What are the difference between soft delete & delete in Laravel?](#What-are-the-difference-between-soft-delete-&-delete-in-Laravel) |
|| [Please write some additional where Clauses in Laravel?](#Please-write-some-additional-where-Clauses-in-Laravel) |
|| [Write CRUD in Laravel Query Builder?](#Write-CRUD-in-Laravel-Query-Builder) |
|| [What is the difference between where and having?](#what-is-the-difference-between-where-and-having) |
|| [Name aggregates methods of query builder](#what-is-the-difference-between-where-and-having) |
|| [What is eager loading in Laravel?](#What-is-eager-loading-in-Laravel) |
|| [Which ORM are being used by laravel?](#Which-ORM-are-being-used-by-laravel) |
|   | **LOGGING** |
| | [What is Query log?](#what-is-query-log) |
|| [How do I log an error?](#How-do-I-log-an-error) |
|   | **MAIL** |
| | [How to setup Emails?](#how-to-setup-emails) |
|| [How to configure a mail-in Laravel?](#what-is-the-difference-between-where-and-having) |
|   | **MIDDLEWARE** |
|  | [What is Middleware?](#what-is-middleware) |
|| [How to register a middleware in Laravel?](#what-is-the-difference-between-where-and-having) |
|| [How to assign multiple middleware to Laravel route ?](#what-is-the-difference-between-where-and-having) |
|| [What are Jobs and Middleware?](#What-are-Jobs-and-Middleware) |
|   | **NOTIFICATION** |
|   | **PHP** |
|| [What does a $$$ mean in PHP? ](#what-is-the-difference-between-where-and-having) |
|| [What does PHP compact function do?](#what-is-the-difference-between-where-and-having) |
|| [How to check installed extensions in CLI and web for PHP?](#How-to-check-installed-extensions-in-CLI-and-web-for-PHP) |
|| [What does PHP compact function do?](#What-does-PHP-compact-function-do) |
| | [What are some new features of PHP X?](#how-to-combine-multiple-inline-style-objects) |
| | [What is Difference between PHP 5 and 4?](#What-is-Difference-between-PHP-5-and-4) |
|| [Explain require and require once difference](#Explain-require-and-require-once-difference) |
|| [Explain include and require diffrence](#Explain-include-and-require-diffrence) |
| | [What are Cookies?](#what-are-cookies) |
| | [Explain CURL and SOAP?](#Explain-CURL-and-SOAP) |
| | [Explain 4 basics of OOP](#Explain-4-basics-of-OOP) |
| | [What is diference between abstract class and interface?](#What-is-diference-between-abstract-class-and-interface) |
|| [Merge 2 arrays with duplicate](#Merge-2-arrays-with-duplicate) |
|| [Find the count of vowel and consonants](#Find-the-count-of-vowel-and-consonants) |
| | [What is Abstract class?](#what-is-Abstract-class) |
|   | **PACKAGE DEVELOPMENT** |
| | [What is Package development?](#what-is-package-development) |
|   | **QUEUES** |
| | [What are Queues?](#what-are-queues) |
| | [What are Jobs?](#what-are-jobs)
|   | **ROUTING** |
|  | [What is Routing?](#what-is-routing) |
|  | [How many types of routes are there?](#how-many-types-of-routes-are-there) |
|  | [What is web php?](#what-is-web-php) |
|  | [What is api php?](#what-is-api-php) |
|  | [What is channels php?](#what-is-channels-php) |
|  | [What is console-php?](#what-is-console-php) |
|| [Explain API.PHP route](#Explain-API.PHP-route) |
|| [How to exclude a route with parameters from CSRF verification?](#How-to-exclude-a-route-with-parameters-from-CSRF-verification) |
|| [How to get current route name?](#How-to-get-current-route-name) |
| | [What is Reverse routing?](#what-is-reverse-routing) | 
| | [What are Named routes?](#what-are-named-routes) |
|   | **SECURITY** |
|| [How can we protect site from SQL Injections?](#what-is-the-difference-between-where-and-having) |
| | [What is CSRF and JWT token?](#what-is-CSRF-and-JWT-token) |
| | [What are SQL Injections?](#What-are-SQL-Injections) |
| | [What is csrf token and xss attack?](#What-is-csrf-token-and-xss-attack) |
| | [What is Authentication using Passport CSRF XSRF?](#What-is-Authentication-using-Passport-CSRF-XSRF) |
|| [What is CSRF token?](#What-is-CSRF-token) |
|   | **SESSION** |
| | [What are Sessions?](#what-are-sessions) |
| | [What is default session time?](#What-is-default-session-time)
|| [Explain Difference between session and cookies?](#Explain-Difference-between-session-and-cookies)
|| [What is the default session timeout duration?](#What-is-the-default-session-timeout-duration) |
|   | **TASK SCHEDULING** |
|   | **TESTING** |
| | [What is Unit testing?](#what-is-unit-testing) |
| | [What is Test Driven Development?](#what-is-test-driven-development) |
|   | **URL GENERATION** |
|| [What is Request Lifecycle?](#what-is-the-difference-between-where-and-having) |
||   | **VALIDATION** |
| | [What are Validations and custom validations?](#what-are-validators) |
|   | **VIEWS** |
|  | [What are Views?](#what-are-views) |
|   | **WEB SOCKETS** |
|| [What is broadcasting in laravel?](#what-is-the-difference-between-where-and-having) |
|| [What is Pusher in Laravel?](#what-is-the-difference-between-where-and-having) |
|   | **ECOSYSTEM** |
|| [What is Vapor?](#what-is-the-difference-between-where-and-having) |
|| [What is Forge?](#what-is-the-difference-between-where-and-having) |
|| [What is Envoyer?](#what-is-the-difference-between-where-and-having) |
|| [What is Horizon?](#what-is-the-difference-between-where-and-having) |
|| [What is Nova?](#what-is-the-difference-between-where-and-having) |
|| [What is Echo?](#what-is-the-difference-between-where-and-having) |
|| [What is Lumen?](#what-is-the-difference-between-where-and-having) |
|| [What is Homestead?](#what-is-the-difference-between-where-and-having) |
|| [What is Spark?](#what-is-the-difference-between-where-and-having) |
|| [What is Valet?](#what-is-the-difference-between-where-and-having) |
|| [What is Mix?](#what-is-the-difference-between-where-and-having) |
|| [What is Cashier?](#what-is-the-difference-between-where-and-having) |
|| [What is Dusk?](#what-is-the-difference-between-where-and-having) |
|| [What is Passport?](#what-is-the-difference-between-where-and-having) |
|| [What is Scout?](#what-is-the-difference-between-where-and-having) |
|| [What is Socialite?](#what-is-the-difference-between-where-and-having) |
|| [What is Telescope?](#what-is-the-difference-between-where-and-having) |
|| [What is Tinker?](#what-is-the-difference-between-where-and-having) |
|| [What is Laravel Elixir?](#what-is-the-difference-between-where-and-having) |
|| [What is Laravel Mix?](#what-is-the-difference-between-where-and-having) |
|| [What is Laravel Elixir?](#What-is-Laravel--Elixir) |
|| [What is Laravel Mix?](#What-is-Laravel-Mix) |
|| [What do you mean by Laravel Dusk?](#What-do-you-mean-by-Laravel-Dusk) |
|| [Explain Laravel echo](#Explain-Laravel-echo) |
|| [What is Laravel Forge?](#What-is-Laravel-Forge) |
|   | **SETUP** |
|| [What is Homebrew?](#what-is-the-difference-between-where-and-having) |
|| [What is Valet?](#what-is-the-difference-between-where-and-having) |
|| [What is Laravel Homestead?](#what-is-the-difference-between-where-and-having) |
|| [What is Docker?](#what-is-the-difference-between-where-and-having) |
|| [How to launch Vagrant Box?](#what-is-the-difference-between-where-and-having) |
| | [What are System requirements for Laravel?](#what-are-system-requirements-for-laravel) |
|   | **WHATS NEW?** |
|| [What was new in Laravel 4?](#what-is-the-difference-between-where-and-having) |
|| [What was new in Laravel 5?](#what-is-the-difference-between-where-and-having) |
|| [What was new in Laravel 6?](#what-is-the-difference-between-where-and-having) |
|| [What was new in Laravel 7?](#what-is-the-difference-between-where-and-having) |
|| [What is new in Laravel 8?](#what-is-the-difference-between-where-and-having) |
|   | **DESIGN PATTERNS** |
|| [What is an Observer?](#What-is-an-Observer) |
|| [What are Laravel facades?](#What-are-Laravel-facades) |
|| [What is an Observer?](#what-is-the-difference-between-where-and-having) |
| | [What are design patterns?](#What-are-design-patterns) |
| | [What is MVC Framework?](#What-is-MVC-Framework) |
|| [What is Dependency injection in Laravel?](#what-is-dependency-injection) |
| | [What is Singelton design pattern?](#what-is-singelton-design-pattern) |
|   | **How To** |
|| [How to get current Url in Laravel?](#what-is-the-difference-between-where-and-having) |
|| [How will you check table is exists or in the database?](#what-is-the-difference-between-where-and-having) |
|| [How do I perform dependency injection in Laravel?](#what-is-the-difference-between-where-and-having) |
|| [How will you register service provider?](#what-is-the-difference-between-where-and-having) |
|| [How can you reduce memory usage in Laravel?](#what-is-the-difference-between-where-and-having) |
|| [How to assign a variable value for all view file?](#How-to-assign-a-variable-value-for-all-view-file) |
|| [How to make a constant and use globally?](#How-to-make-a-constant-and-use-globally) |
|| [How to check current installed version of Laravel?](#How-to-check-current-installed-version-of-Laravel) |
|| [How to share data with views?](#How-to-share-data-with-views) |
|| [How to generate a request in Laravel?](#How-to-generate-a-request-in-Laravel) |
|| [How to use GROUP_CONCAT() with JOIN in Laravel?](#How-to-use-GROUP_CONCAT()-with-JOIN-in-Laravel) |
|| [How to extend login expire time in Auth?](#How-to-extend-login-expire-time-in-Auth) |
|| [How to check column is exists or not in a table using Laravel?](#How-to-check-column-is-exists-or-not-in-a-tabl-using-Laravel) |
|| [How we can upload files in laravel?](#How-we-can-upload-files-in-laravel) |
|| [How to create real time sitemap.xml file in Laravel?](#How-to-create-real-time-sitemap.xml-file-in-Laravel) |
|| [How to use skip() and take() in Laravel Query?](#How-to-use-skip()-and-take()-in-Laravel-Query) |
|| [How to use multiple 'OR' condition in Laravel Query?](#How-to-use-multiple-'OR'-condition-in-Laravel-Query) |
|| [How to make a constant and use globally?](#How-to-make-a-constant-and-use-globally) |
|| [How to remove /public from URL in laravel?](#How-to-remove-public-from-URL-in-laravel) |
|| [How will you explain homestead in Laravel?](#How-will-you-explain-homestead-in-Laravel) |
|| [How can we get the user's IP address in Laravel?](#How-can-we-get-the-user's-IP-address-in-Laravel) |
|| [How will you create a helper file in Laravel?](#How-will-you-create-a-helper-file-in-Laravel) |
|| [How can we get the user's IP address in Laravel?](#give-a-simple-example-of-jest-test-case) |
|| [How to get Logged in user info in Laravel?](#How-to-get-Logged-in-user-info-in-Laravel) |
|| [How do you register a Service Provider?](#How-do-you-register-a-Service-Provider) |
|| [How to enable maintenance mode in Laravel?](#How-to-enable-maintenance-mode-in-Laravel) |
|| [How to install Laravel via composer?](#How-to-install-Laravel-via-composer) |
|| [How to do Web scraping?](#How-to-do-Web-scraping) |
| | [How to create hooks in Laravel?](#How-to-create-hooks-in-Laravel) |
|| [How can you display HTML with Blade in Laravel?](#How-can-you-display-HTML-with-Blade-in-Laravel) |
|| [How to enable maintenance mode in Laravel 5?](#what-is-the-difference-between-where-and-having) |
|| [How to install laravel via composer?](#How-to-install-laravel-via-composer) |
|| [How to create an API?](#how-to-create-an-api) |
| | [How to call static methods?](#How-to-call-static-methods) |
|| [How to get current environment in Laravel?](#How-to-get-current-environment-in-Laravel) |
|| [How to use custom table in Laravel Model?](#How-to-use-custom-table-in-Laravel-Model) |
|| [How to check current Laravel version using CLI?](#How-to-check-current-Laravel-version-using-CLI) |
|| [How to rollback last migration?](#How-to-rollback-last-migration) |
|| [How to check Ajax request in Laravel?](#How-to-check-Ajax-request-in-Laravel) |
|| [How to check if value is sent in request?](#How-to-check-if-value-is-sent-in-request) |
|   | **OTHERS** |
| | [What is the difference among various php versions?](#What-is-the-difference-among-various-php-versions) |
| | [What is the difference among various mysql versions?](#What-is-the-difference-among-various-mysql-versions) |
| | [What is the difference among various Laravel versions?](#What-is-the-difference-among-various-Laravel-versions) |
| | [In MySql we use many types of engines which one is faster and why?](#In-MySql-we-use-many-types-of-engines-which-one-is-faster-and-why) |
| | [What are some new feaatures of Laravel X?](#What-are-some-new-feaatures-of-Laravel-X) |
|| [What is the purpose of using dd() function in laravel?](#What-is-the-purpose-of-using-dd()-function-in-laravel) |
|| [Exceptions are handled by which class in Laravel?](#Exceptions-are-handled-by-which-class-in-Laravel) |
|| [Talk about Laravel User Interface (UI)](#talk-about-Laravel-User-Interface-(UI)) |
|| [What are improved Authorization Responses?](#What-are-improved-Authorization-Responses) |
|| [What are policies classes?](#What-are-policies-classes) |
|| [What is namespace in Laravel?](#What-is-namespace-in-Laravel) |
|| [State the difference between CodeIgniter and Laravel.](#State-the-difference-between-CodeIgniter-and-Laravel) |
|| [Define hashing in Laravel](#Define-hashing-in-Laravel) |
|| [What is Localization?](#What-is-Localization) |
|| [Explain the concept of encryption and decryption in Laravel.](#Explain-the-concept-of-encryption-and-decryption-in-Laravel) |
|| [I just have installed a fresh version of Laravel 5, and I have the white screen of death. What’s wrong?](#I-just-have-installed-a-fresh-version-of-Laravel-5-and-I-have-the-white-screen-of-death-What’s-wrong) |
|| [What are common HTTP error codes?](#what-is-the-difference-between-where-and-having) |
|| [Differentiate between delete() and softDeletes()?](#what-is-the-difference-between-where-and-having) |
|| [List different where Clauses available Laravel?](#what-is-the-difference-between-where-and-having) |
|| [What are Deferred Providers in laravel?](#what-is-the-difference-between-where-and-having) |
|| [What getFacadeAccessor method does?](#what-is-the-difference-between-where-and-having) |
|| [What are Macros in Laravel?](#what-is-the-difference-between-where-and-having) |
|   | **COMPOSER** |
| | [What is Composer?](#what-is-composer) |
|   | **Packages** |
| | [What are Popular composer packages?](#what-are-Popular-composer-packages) |
| | [What are Default packages: Cashier,Envoy,Passport,Scout,Socialite,Horizon?](#default-packages) |
|| [What is ACL in laravel?](#What-is-ACL-in-laravel) |
|   | **What Is** |
| | [Which is Error management?](#which-is-error-management) |
|| [What are Payments and cashier?](#what-are-payments-and-cashier) |
| | [What are Laravel Scout search and Algolia?](#what-are-laravel-scout-search-and-algolia) |
| | [What is Socialite and Auth?](#what-is-socialite-auth) |
| | [What is Single Page Application in Laravel?](#What--Single-Page-Application-in-Laravel) |
| | [What are Microservices in Laravel?](#What-are-Microservices-in-Laravel) |
| | [What is Service Oriented Architecture in Laravel?](#what-is-soa) |
|   | **Why** |
|| [Why prefer Laravel over other frameworks?](#Why-prefer-Laravel-over-other-frameworks) |
|   | **Current Versions** |
| | [What is Current version of PHP, MySQL, Laravel, MongoDB etc?](#what-is-current-version-of-PHP-MySQL-Laravel-MongoDB-etc) |
|   | **General Questions** |
| | [Describe design architecture of an app?](#Describe-design-architecture-of-an-app) |
|| [Explain an apps DB architecture ?](#Explain-an-apps-DB-architecture) |
|| [Explain AWS Services](#Explain-AWS-Services) |
| | [What is Vue-js?](#what-is-vue-js) |
| | [What is Horizontal scaling?](#What-is-Horizontal-scaling) |
| | [What is Vertical scaling?](#What-is-Vertical-scaling) |

1. ### What is Routing?
  When a user enters a URL, it gets send to a routes folder. web.php route is for web requests while api.php route is for API requests.

Below is an example get route from `routes/web.php`. You can call website.com/foo and it will bring the result.

  ```
  Route::get('foo', function () {
      return 'Hello World';
  });
  ```
 **[⬆ Back to Top](#table-of-contents)**
    
2. ### How many types of routes are there?

There are four types of routes,

    A. web.php 
    
    B. api.php
    
    C. console.php
    
    D. broadcast.php

  **[⬆ Back to Top](#table-of-contents)**
    
3. ### What is web php?

    web.php used for web routes. Like example.com/test
    
    ```
    Route::get('/test', function () {
        $path = storage_path() . "/app/json/options/docs.json";
        return view('skin/dev-wireframe', array('menu' => json_decode(file_get_contents($path), true)));
    });
    ```
    
    
  **[⬆ Back to Top](#table-of-contents)**
    
4. ### What is api php?

    The place where we write API route for mobile and API usage. Like http://localhost:8080/api/test
    ```
    Route::get('/test', function () {
        $path = storage_path() . "/app/json/options/docs.json";
        return view('skin/dev-wireframe', array('menu' => json_decode(file_get_contents($path), true)));
    });
    ```
     **[⬆ Back to Top](#table-of-contents)**
     
5. ### What is channels php?

    It is used for broadcasting

 **[⬆ Back to Top](#table-of-contents)**

6. ### What is console php?

    Used to give a name to console routes.

  **[⬆ Back to Top](#table-of-contents)**
   
    
7. ### What is Controller?

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
    
8. ### What are Views?

  Views is the fornt end of Laravel. Stored in `resources/views`.

    ```
    <html>
        <body>
            <h1>Hello, {{ $name }}</h1>
        </body>
    </html>
    ```


   **[⬆ Back to Top](#table-of-contents)**
    
9. ### 	What is a Model?
    A model is where you write the database logic. Stored in `/app`

    <?php

    namespace App;

    use Illuminate\Database\Eloquent\Model;

    class Flight extends Model
    {
        //
    }

   **[⬆ Back to Top](#table-of-contents)**
    
10. ### What is Request-Response?

    When we type a URL, a request is sent to the server. The server goes from /public to bootstrap folder from which is goes to the routes file. The route files sends it the right controller/view.


   **[⬆ Back to Top](#table-of-contents)**
    
11. ### What are Migrations?

    Migrations help us keep SQL tables in code. When we have to setup the DB, we just run the migration.


   **[⬆ Back to Top](#table-of-contents)**
    
12. ### What are Service Providers?

    Service providers are responsible for booting and configuration (binding all resources.)
    
   **[⬆ Back to Top](#table-of-contents)**
    
13. ### What is Middleware?

    Middleware acts as a bridge between a request and a response. It is a type of filtering mechanism.


   **[⬆ Back to Top](#table-of-contents)**
    
14. ### What is ORM?

    Object oriented and Model based way of DB query


   **[⬆ Back to Top](#table-of-contents)**
    
15. ### What is Eloquent?

    The ORM wrapper Laravel uses is called Eloquent. Every table has a model associated with it.
    
   **[⬆ Back to Top](#table-of-contents)**
    
16. ### What is Query Builder?

   A database wrapper that makes it easy to access DB.

   **[⬆ Back to Top](#table-of-contents)**
    
17. ### What are Facades?

    Facades are used to hide implementation details and complexities from end user making him/her feel like interacting with a black box.

   **[⬆ Back to Top](#table-of-contents)**
    
18. ### What is Repository Pattern?

    Repository pattern is used to create templates where implementation details are left to be implemented in child classes. It helps with further expansion of code and avoid bottlenecks in class updation.

   **[⬆ Back to Top](#table-of-contents)**
    
19. ### What is Authentication using Passport?
    
    Passport provides a better way to create API.

   **[⬆ Back to Top](#table-of-contents)**
    
20. ### What Unit testing?
    Testing every function

   **[⬆ Back to Top](#table-of-contents)**
    
21. ### What is Caching?

    Configured using `config/cache.php`. Used for database caching. Popular ways Redis and Memcache.

   **[⬆ Back to Top](#table-of-contents)**
    
22. ### What is Unit Testing?

    Writing a test for every unit (function or class) you write.

   **[⬆ Back to Top](#table-of-contents)**
   
23. ### How to setup Emails?

    Using PHP's `mail()` function and Laravel's `sendmail()` function. You can custoimize it using templates.

  **[⬆ Back to Top](#table-of-contents)**
  
  
24. ### What are Queues?

    Queue is a line of jobs to be proccessed. You can create multiple queues which is multiple lines of jobs
    
   **[⬆ Back to Top](#table-of-contents)**
    
25. ### What are Jobs?

    Job is a task being performed in the background.

   **[⬆ Back to Top](#table-of-contents)**
   
   
26. ### How to setup Emails?

   Use Laravel's sendmail() function and create a mail template.

   **[⬆ Back to Top](#table-of-contents)**
    
27. ### What are Advanced Eloquent and Query Builder?

    Complex eloquent queries are called advanced eloquent. Query builder is wrapper for database queries.

   **[⬆ Back to Top](#table-of-contents)**
    
28. ### Which is Error management?

   Error handling is managing `exception` in a Laravel application.

   **[⬆ Back to Top](#table-of-contents)**
    
29. ### How to create an API?

  Use api.php. Link will be x.com/api/slug

   **[⬆ Back to Top](#table-of-contents)**
    
30. ### What are Events?

   You get notified when an action is triggered.

   **[⬆ Back to Top](#table-of-contents)**
    
31. ### What are Listeners?

    Which listen to the events.

   **[⬆ Back to Top](#table-of-contents)**
    
32. ### What are Payments and cashier?

    Payment processing is difficult. Cashier is a package which makes it easy. Its installed using composer.

   **[⬆ Back to Top](#table-of-contents)**
    
33. ### What is Test Driven Development?

    Test is written first and then the function is written.

   **[⬆ Back to Top](#table-of-contents)**
    
34. ### What is Package development?

    Laravel uses composer which gets packages. You can develop your own package and submit.

   **[⬆ Back to Top](#table-of-contents)**
    
35. ### What are Laravel Scout search and Algolia?

   https://laravel.com/docs/5.8/scout

   **[⬆ Back to Top](#table-of-contents)**
    
36. ### Socialie and Auth?

    Socialite is Social login for Laravel.
    Auth is Laravel's authentication.

   **[⬆ Back to Top](#table-of-contents)**
    
37. ### What is Vue-js?

    In easy way to do SPA where you can change state.

   **[⬆ Back to Top](#table-of-contents)**
    
38. ### How to connect Laravel with other SQL databases?

    Go to config/database.php

   **[⬆ Back to Top](#table-of-contents)**
    
39. ### How to connect Laravel with non-SQL databases?

   Add the entry to config/database.php

   **[⬆ Back to Top](#table-of-contents)**
    
40. ### What is Lumen?

    Lumen is the lightweight version of Laravel used usually for making microservices.

   **[⬆ Back to Top](#table-of-contents)**
    
41. ### What is Redis?
    
    Key-value database making query faster.

   **[⬆ Back to Top](#table-of-contents)**
    
42. ### What is Memcache?

    Key-value database making query faster.


   **[⬆ Back to Top](#table-of-contents)**
    
43. ### What is Horizontal scaling?

    By adding more servers we scale horizontally.

   **[⬆ Back to Top](#table-of-contents)**
    
44. ###	What is Vertical scaling?

    By increasing the size of the same server we scale vertically.

   **[⬆ Back to Top](#table-of-contents)**
    
45. ### What is Single Page Application in Laravel?

    There is single URL. The assets are loaded once and only content keeps changing using JSON request. Its not great for SEO but there are workarounds to create virtual URL.

   **[⬆ Back to Top](#table-of-contents)**
    
46. ### What are Microservices in Laravel?

    There are many services which are similar sized. Each performs exactly one function and they talk to each other.

   **[⬆ Back to Top](#table-of-contents)**
    
47. ### What is CSRF and JWT token?
    CSRF and JWT tokens are used to make sure the action is performed by the user. If there is no token, someone can give a link to user to click or hide it behind some action and him do what the hacker wants.
    A JWT token is hidden in the request while CSRF token is not.

   **[⬆ Back to Top](#table-of-contents)**
    
48. ### What is Service Oriented Architecture in Laravel?

    There are many services which are similar sized. Each performs exactly one function and they talk to each other. 

   **[⬆ Back to Top](#table-of-contents)**
    
49. ### What are Validations and custom validations?

    Validations are used to make sure input is of the kind function wanted. Custom validators are custom made valiators.

   **[⬆ Back to Top](#table-of-contents)**
    
50. ### What is Composer?
   
    Composer is PHP's package manager.

   **[⬆ Back to Top](#table-of-contents)**
    
51. ### What is Symfony?
    Symfony is a framework Laravel is inspired from.

   **[⬆ Back to Top](#table-of-contents)**
    
52. ### What is Route caching?

    Caching of routes to make going to routes faster. Command: `php artisan route:cache`

   **[⬆ Back to Top](#table-of-contents)**
    
53. ### What are Default packages?
    Cashier, Envoy, Passport, Scout, Socialite, Horizon etc

   **[⬆ Back to Top](#table-of-contents)**
    
54. ### What are Named routes?

    You can give route a name using a parameter.

   **[⬆ Back to Top](#table-of-contents)**
    
55. ### What is Dependency injection in Laravel?

    Laravel injects dependencies as function parameters.
    Read more: https://medium.com/a-young-devoloper/how-laravel-injects-our-dependencies-14e1b1a044e


   **[⬆ Back to Top](#table-of-contents)**
    
56. ### What are Laravel contracts?

   They provide insstructions to interact with a facade. 

    https://laravel.com/docs/7.x/contracts

   **[⬆ Back to Top](#table-of-contents)**
    
57. ### What is Query log?

   You can enable logging queries and Laravel will record the queries which were run.

   **[⬆ Back to Top](#table-of-contents)**
    
58. ### What are Laravel Traits?

    They solve diamond problem which is when you have to inherit from two classes.

   **[⬆ Back to Top](#table-of-contents)**
    
59. ### What are Bundles in Laravel?

    Used for grouping stuff like route groups (CRUD in one line.)

   **[⬆ Back to Top](#table-of-contents)**
    
60. ### What are System requirements for Laravel?

    PHP version, MySQL, PHP packages mentioned on Laravel.com, apache server

   **[⬆ Back to Top](#table-of-contents)**
    
61.	### What are Aggregate methods in query builder?

    Max, min, sum etc
   ```
   $price = DB::table('orders')->max('price');
   ```
   
   **[⬆ Back to Top](#table-of-contents)**
  
    
62.	### What is Singelton design pattern?

    A single object of a class is created throughout the lifecycle.

   **[⬆ Back to Top](#table-of-contents)**
    
63.	### What is Reverse routing?

   To generate the process of generating the URL which leads to a route. Its used in MVC apps. You can use it using named routes in laravel.
   
   **[⬆ Back to Top](#table-of-contents)**
    
64.	### What are Popular composer packages?

    Guzzle

   **[⬆ Back to Top](#table-of-contents)**
    
65.	### How to get the data from more than 3 table without using a join ?

    Answer: Subquery, union.


   **[⬆ Back to Top](#table-of-contents)**
    
66.	### List some artisan commands

    ```
    php artisan list
    php artisan make:migrate
    php artisan make:controller
    php artisan make:model
    php artisan config:clear
    php artisan serve
    ```

   **[⬆ Back to Top](#table-of-contents)**
    
67.	### What are Sessions?

    Session is data related to a specific user.

   **[⬆ Back to Top](#table-of-contents)**
    
68.	### What are Cookies?

    Cookies is generalized data.

   **[⬆ Back to Top](#table-of-contents)**
    
69.	### What is Current version of PHP MySQL Laravel MongoDB etc?

    PHP: PHP 7.4
    MySQL: 7
    Laravel: 6
    MongoDB: 4

   **[⬆ Back to Top](#table-of-contents)**
    
70.	### Describe design architecture of an app?

    There are three layers
    1. Presentation layer: Front end
    2. Business layer: Backend and logic
    3. Data layer: Model and database 
  
   **[⬆ Back to Top](#table-of-contents)**
    
71.	### What are SQL Injections?

    Its a hacking trick used to complete a SQL query by filling a form content and placing query parts inside the form.

   **[⬆ Back to Top](#table-of-contents)**
    
72.	### How to call static methods?

    Using `::` before function name instead of `->`.

   **[⬆ Back to Top](#table-of-contents)**
    
73.	### How to achieve multiple DB hosts?

    Define the new DB in env or config/database.php and use it.
    
   **[⬆ Back to Top](#table-of-contents)**
    
74.	### What is Abstract class?

    A class which is just a template i.e has no defination but just declaration.

   **[⬆ Back to Top](#table-of-contents)**
    
75.	### What are Default ports for MySQL, Email, etc?

    http: 80
    MYSQL: 3306
    Email: 587

   **[⬆ Back to Top](#table-of-contents)**
    
76.	### Explain Joins

    There are 4 types of joins,
    1. Inner Join
    2. Outer Join
    3. Left Join
    4. Right Join

   **[⬆ Back to Top](#table-of-contents)**
    
77.	### Explain Unions

    Union vertically joins tables together i.e the records are added into the same columns.

   **[⬆ Back to Top](#table-of-contents)**
    
78.	### How mongodb is better than relational databases?

    It is faster and it stores data in JSON form so you can enter multiple types of data without being dependent on the data being consistent in type.

   **[⬆ Back to Top](#table-of-contents)**
    
79.	### What is mongodb?

   It is a NO SQL key value based database.
   
   **[⬆ Back to Top](#table-of-contents)**
    
80.	### What is default session time?

   2 hours.

   **[⬆ Back to Top](#table-of-contents)**
    
81.	### How to create hooks in Laravel?
    
    https://stackoverflow.com/questions/36226021/hooks-in-laravel-5

   **[⬆ Back to Top](#table-of-contents)**
    
82.	### What is csrf token and xss attack?

   CSRF and JWT tokens are used to make sure the action is performed by the user. If there is no token, someone can give a link to user to click or hide it behind some action and him do what the hacker wants.


   **[⬆ Back to Top](#table-of-contents)**
    
83.	### Select highest and nth highest salary from DB
    
    ```
    SELECT name, salary 
    FROM #Employee e1
    WHERE N-1 = (SELECT COUNT(DISTINCT salary) FROM #Employee e2
    WHERE e2.salary > e1.salary)
    ```
    https://javarevisited.blogspot.com/2016/01/4-ways-to-find-nth-highest-salary-in.html

   **[⬆ Back to Top](#table-of-contents)**
    
84.	### Write the 4 joins
    
    1. Inner join
    2. Outer join
    3. Left join
    4. Right join

   **[⬆ Back to Top](#table-of-contents)**
    
85. ### Write a union

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
    
86. ### Write a complex query?

   Like a 3 tables joined.

   **[⬆ Back to Top](#table-of-contents)**
    
87. ### Explain an apps DB architecture 
   
   Uber's DB arcitecture.

   **[⬆ Back to Top](#table-of-contents)**
    
88. ### What is Difference between PHP 5 and 4?

    PHP 5 has OOP.

   **[⬆ Back to Top](#table-of-contents)**
    
89. ### What is the difference among various php versions?

    PHP 4: No OOP
    PHP 5: OOP
    PHP 7: Faster speed

   **[⬆ Back to Top](#table-of-contents)**
    
90. ### What is the difference among various Laravel versions?

    Directory structure

   **[⬆ Back to Top](#table-of-contents)**
    
91. ### How to add AWS plugin in PHP?

    Using AWS SDK.

   **[⬆ Back to Top](#table-of-contents)**
    
92. ### What are design patterns?

    They are well known solutions to common problems every developer faces.

   **[⬆ Back to Top](#table-of-contents)**
    
93. ### What is the difference between GET and POST

    GET is used for retriving data
    POST is used to perform a change i.e action

   **[⬆ Back to Top](#table-of-contents)**
    
94. ### Which is fast between GET and POST?

    GET is used for retriving data
    POST is used to perform a change i.e action
    
95. ### Explain 4 basics of OOP

    Inheritance
    Polymorphism
    Encapsulation
    Abstraction

   **[⬆ Back to Top](#table-of-contents)**
    
96. ### What is diference between abstract class and interface?

   https://javapapers.com/core-java/abstract-and-interface-core-java-2/difference-between-a-java-interface-and-a-java-abstract-class/

   **[⬆ Back to Top](#table-of-contents)**
    
97. ### What is MVC Framework?

    It provides separation of concerns by separating the code into 3 parts,
    1. Model: Database logic
    2. View: Frontend logic
    3. Controller: Backend logic

   **[⬆ Back to Top](#table-of-contents)**
    
98. ### Create a project with CRUD, one algorithm logic and insert data in db for testing.

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
99. ### In MySql we use many types of engines which one is faster and why?

    There are two main types of engines,
    1.InnoDB
    2.MyISAM
    InnoDB is faster.

   **[⬆ Back to Top](#table-of-contents)**
    
100. ### What are Triggers?

    `DB::unprepared()` is used for it.
    
    ```
    php artisan make:migration create_trigger    
    ```

   **[⬆ Back to Top](#table-of-contents)**
    
101. ### What are Procedures

    Stored procedures are SQL code in tables. It is called and executed inside tables.

   **[⬆ Back to Top](#table-of-contents)**
    
102. ### What are some new feaatures of Laravel X?

   https://medium.com/@samwatsonets/difference-between-laravel-6-0-and-its-previous-versions-efb2829d0f55

   **[⬆ Back to Top](#table-of-contents)**
    
103. ### What are some new features of PHP X?

    PHP 7.4 brings,
    1. 
    2.

   **[⬆ Back to Top](#table-of-contents)**
    
104. ### Explain Difference between session and cookies?

  Cookies is data sent with every request. It is usually generalized for all.
  Session is data related to a specific user.

   **[⬆ Back to Top](#table-of-contents)**
    
105. ### Merge 2 arrays with duplicate

    ```
    array_unique(array_merge($array1,$array2), SORT_REGULAR);

    ```

   **[⬆ Back to Top](#table-of-contents)**
    
106. ### Find the count of vowel and consonants

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
    
107. ### Explain AWS Services

    AWS has 20 main categories and 150 sub-categories of items. For hosting, EC2 is a well known server type.

   **[⬆ Back to Top](#table-of-contents)**
    
108. ### How to do Web scraping?

    Composer has built in packages for it. They may get stopped due to IP usage (no of connections

   **[⬆ Back to Top](#table-of-contents)**
    
109. ### Explain require and require once difference

    In require, you can use require multiple times for the same file. It will add the file multiple times while require_once will only require it once.


   **[⬆ Back to Top](#table-of-contents)**
   
110. ### Explain include and require diffrence

    In include() the script will run even if the file is not found while in require it will stop if file required is not found.

   **[⬆ Back to Top](#table-of-contents)**
    
111. ### Directory structure of Laravel

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
    
112. ### How to install Laravel via composer?

    ```
    composer create-project --prefer-dist laravel/laravel blog "5.8.*"
    ```

   **[⬆ Back to Top](#table-of-contents)**
    
113. ### Which ORM are being used by laravel?

    Eloquent

   **[⬆ Back to Top](#table-of-contents)**
   
114. ### List types of relationships available in Laravel Eloquent?

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
    
115. ### How to enable maintenance mode in Laravel?

    ```
    php artisan down
    ```

   **[⬆ Back to Top](#table-of-contents)**
    
116. ### What is the purpose of using dd() function in laravel?

    dd() is dump and die. It prints the variable/array and exits the script.

   **[⬆ Back to Top](#table-of-contents)**
    
117. ### How do you register a Service Provider?
    
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
    
119. ### Explain Laravel framework Architecture

   **[⬆ Back to Top](#table-of-contents)**
    
120. ### Helper Functions
    
    Common function which you can use in many classes are stored in helper functions.

   **[⬆ Back to Top](#table-of-contents)**
    
121. ### What is Fillable Attribute in a Laravel Model?

   Which can be mass assigned.


   **[⬆ Back to Top](#table-of-contents)**
    
122. ### What is Guarded Attribute in a Laravel Model?

    Which can't be mass assigned.

   **[⬆ Back to Top](#table-of-contents)**
    
123. ### What are Closures in Laravel?

    a closure gives you access to an outer function's scope from an inner function

   **[⬆ Back to Top](#table-of-contents)**
    
124. ### How to get Logged in user info in Laravel?

    ```
    $user = auth()->user();
    print_r($user);
    ```

   **[⬆ Back to Top](#table-of-contents)**
    
125. ### What is Laravel Elixir?

   Used for compiling JS.

   **[⬆ Back to Top](#table-of-contents)**
    
126. ### What is Laravel Mix?

    Used for compiling JS.

   **[⬆ Back to Top](#table-of-contents)**
    
127. ### How can you display HTML with Blade in Laravel?

     {!! $text !!}

   **[⬆ Back to Top](#table-of-contents)**
    
128. ### How to install laravel via composer ?

     composer create-project laravel/laravel name

   **[⬆ Back to Top](#table-of-contents)**
    
129. ### List out databases that laravel supports?

     Laravel supports four database systems: MySQL, Postgres, SQLite, and SQL Server.

   **[⬆ Back to Top](#table-of-contents)**
    
130. ### How to use custom table in Laravel Model?

    By mentoning the name of the table in `$table` variable

   **[⬆ Back to Top](#table-of-contents)**
    
131. ### How To Use Select Query In Laravel? Eloquent and QB?

    QB: $users = DB::table('users')->select('name', 'email as user_email')->get();
    Eloquent: $users = User::all();
    
132. ### What are Accessors and Mutators in Eloquent and why should you use them?

    https://laravel.com/docs/4.2/eloquent#accessors-and-mutators

   **[⬆ Back to Top](#table-of-contents)**
    
133. ### How do I log an error?

    https://laravel.com/docs/5.2/errors

   **[⬆ Back to Top](#table-of-contents)**
    
134. ### What is Monolog library in Laravel?

    Helps with logging.

   **[⬆ Back to Top](#table-of-contents)**
    
135. ### Exceptions are handled by which class in Laravel?

     App\Exceptions\Handler class.

   **[⬆ Back to Top](#table-of-contents)**
    
136. ### What is Serialization in Laravel?

    https://laravel.com/docs/5.8/eloquent-serialization

   **[⬆ Back to Top](#table-of-contents)**
    
137. ### What is Response in Laravel?

    When we make a request , we get a responsse.

   **[⬆ Back to Top](#table-of-contents)**
    
138. ### What is Response Macros in Laravel?

    https://laravel.com/docs/5.8/responses#response-macros


   **[⬆ Back to Top](#table-of-contents)**
    
139. ### What is Rate Limiting OR Throttle in Laravel?

    https://www.cloudways.com/blog/laravel-and-api-rate-limiting/


   **[⬆ Back to Top](#table-of-contents)**
    
140. ### What is Lazy vs Eager Loading in Laravel?

    https://laravel.com/docs/5.8/eloquent-relationships

   **[⬆ Back to Top](#table-of-contents)**
    
141. ### How to get current environment in Laravel?

    https://stackoverflow.com/questions/14935846/laravel-4-how-can-i-get-the-environment-value

   **[⬆ Back to Top](#table-of-contents)**
    
142. ### How to use custom table in Laravel Model ?

    $table=""

   **[⬆ Back to Top](#table-of-contents)**
    
143. ### What is Binding?

    https://stackoverflow.com/questions/49348681/what-is-a-usage-and-purpose-of-laravels-binding


   **[⬆ Back to Top](#table-of-contents)**
    
144. ### Explain Binding A Singleton?

    https://stackoverflow.com/questions/25229064/laravel-difference-appbind-and-appsingleton

   **[⬆ Back to Top](#table-of-contents)**
    
145. ### Explain Binding Instances?

    https://stackoverflow.com/questions/40767040/how-laravels-container-binding-mechanisms-differ


   **[⬆ Back to Top](#table-of-contents)**
    
146. ### Explain Binding Primitives?

    https://stackoverflow.com/questions/40767040/how-laravels-container-binding-mechanisms-differ

   **[⬆ Back to Top](#table-of-contents)**
    
147. ### Explain Contextual Binding and how does it work?

    https://stackoverflow.com/questions/40767040/how-laravels-container-binding-mechanisms-differ


   **[⬆ Back to Top](#table-of-contents)**
    
148. ### What is Tagging?

    Giving your binding a name.

   **[⬆ Back to Top](#table-of-contents)**
    
149. ### Explain Extending Bindings?

        https://stackoverflow.com/questions/40767040/how-laravels-container-binding-mechanisms-differ


   **[⬆ Back to Top](#table-of-contents)**
    
150. ### What is the make Method?

    Makes controller, view, route, group and other items in artisan.

   **[⬆ Back to Top](#table-of-contents)**
    
151. ### How to clear cache in Laravel?

    php artisan cache:cleaer

   **[⬆ Back to Top](#table-of-contents)**
    
152. ### What is CSRF token?

     Protects against cross site attack


   **[⬆ Back to Top](#table-of-contents)**
    
153. ### How will you explain homestead in Laravel?

    Virtual box for vagrant

   **[⬆ Back to Top](#table-of-contents)**
    
154. ### How can we get the user's IP address in Laravel?

    Request::ip();

   **[⬆ Back to Top](#table-of-contents)**
    
155. ### How will you create a helper file in Laravel?

    https://tutsforweb.com/creating-helpers-laravel/

   **[⬆ Back to Top](#table-of-contents)**
    
156. ### How can we create a record in Laravel using eloquent?
        
        ```
        $flight = new Flight;

        $flight->name = $request->name;

        $flight->save();
        ```

   **[⬆ Back to Top](#table-of-contents)**
    

157. ### How can we get the user's IP address in Laravel?

   ```
   Request::ip();
   ```

   **[⬆ Back to Top](#table-of-contents)**
    
158. ### What is faker in Laravel?

   
     Used to generate dummy data


   **[⬆ Back to Top](#table-of-contents)**
    
159. ### What are active records?

    A design pattern which masks SQL queries to make database CRUD operations easy.

   **[⬆ Back to Top](#table-of-contents)**
    
160. ### What are the difference between insert() and insertGetId() in laravel?

    insert() only inserts
    insertGetId() inserts and returns id of last added item

   **[⬆ Back to Top](#table-of-contents)**
    
161. ### Talk about Laravel Vapor Compatibility

    https://vapor.laravel.com/


   **[⬆ Back to Top](#table-of-contents)**
    
162. ### What is Semantic Versioning?

    Major version . Minor version . Bug fix


   **[⬆ Back to Top](#table-of-contents)**
    
163. ### What are Jobs and Middleware?

    Jobs:
    Middleware:

   **[⬆ Back to Top](#table-of-contents)**
    
164. ### Talk about Laravel User Interface (UI)

    It uses Blade Templating Engine

   **[⬆ Back to Top](#table-of-contents)**
    
165. ### Talk about Eloquent Subquery Enhancements?

    https://laravel-news.com/eloquent-subquery-enhancements

   **[⬆ Back to Top](#table-of-contents)**
    
166. ### What are improved Authorization Responses?

    https://fullstackworld.com/post/what-is-new-to-laravel-6

   **[⬆ Back to Top](#table-of-contents)**
    
167. ### What are lazy collections?

    https://laravel.com/docs/6.x/collections#lazy-collection-introduction

   **[⬆ Back to Top](#table-of-contents)**
    
168. ### How to make a constant and use globally?

    https://medium.com/@panjeh/laravel-define-global-constants-config-php-file-5d6a9900bb6e

   **[⬆ Back to Top](#table-of-contents)**
    
169. ### How to remove /public from URL in laravel?


     Rename server.php in your Laravel root folder to index.php
     Copy the .htaccess file from /public directory to your Laravel root folder.


   **[⬆ Back to Top](#table-of-contents)**
    
170. ### What are the difference between soft delete & delete in Laravel?


     https://blog.hashvel.com/posts/eloquent-orm-soft-delete-permanent-delete-in-laravel/


   **[⬆ Back to Top](#table-of-contents)**
    
171. ### How we can upload files in laravel?

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
    
172. ### Why are Redux state functions c166. ### How to create real time sitemap.xml file in Laravel?

    Make a controller to loop through all pages and list them. Make a route to it.

   **[⬆ Back to Top](#table-of-contents)**
    
173. ### How to use skip() and take() in Laravel Query?

    https://www.bestinterviewquestion.com/question/how-to-use-skip-take-in-laravel-query-kcle83908l2

   **[⬆ Back to Top](#table-of-contents)**
    
174. ### What is tinker in laravel?

    Tinker is command line code functionality where you can write Laravel code in CLI.

   **[⬆ Back to Top](#table-of-contents)**
    
175. ### What is a REPL?

    https://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop

   **[⬆ Back to Top](#table-of-contents)**
    
176. ### How to use multiple 'OR' condition in Laravel Query?
    
    Use it as an array in a single or function.

   **[⬆ Back to Top](#table-of-contents)**
    
177. ### Please write some additional where Clauses in Laravel?
    
    Use it as an array inside where function.

   **[⬆ Back to Top](#table-of-contents)**
    
178. ### How to check column is exists or not in a table using Laravel?

    SELECT that column and chekc if result is not null

   **[⬆ Back to Top](#table-of-contents)**
    
179. ### What is eager loading in Laravel?
   
    https://medium.com/@sdkcodes/laravel-eloquent-eager-loading-9596b15e8b5d

   **[⬆ Back to Top](#table-of-contents)**
    
180. ### How to generate application key in laravel?

  php artisan key:generate

   **[⬆ Back to Top](#table-of-contents)**
    
181. ### What is LTS version of Laravel?

    LTS version is a version where the support is longer i.e it gets longer fixes and support and is a stable version.

   **[⬆ Back to Top](#table-of-contents)**
    
182. ### How to use GROUP_CONCAT() with JOIN in Laravel?

    https://www.bestinterviewquestion.com/question/how-to-use-group-concat-with-join-in-laravel-cht1n5023bz

   **[⬆ Back to Top](#table-of-contents)**
    
183. ### How to extend login expire time in Auth?

    Change the minutes in config\session.php file.

   **[⬆ Back to Top](#table-of-contents)**
    
184. ### How to extend a layout file in laravel view?

    @extends('name.app')

   **[⬆ Back to Top](#table-of-contents)**
    
185. ### How do you use yield()?

     @yield('navigation')

   **[⬆ Back to Top](#table-of-contents)**
    
186. ### What is ACL in laravel?

    Package that manages user permissions


   **[⬆ Back to Top](#table-of-contents)**
    
187. ### How to check Ajax request in Laravel?

    https://stackoverflow.com/questions/29231587/laravel-check-if-ajax-request

   **[⬆ Back to Top](#table-of-contents)**
    
188. ### How to check if value is sent in request?

    dd($Request)

   **[⬆ Back to Top](#table-of-contents)**
    
189. ### Laravel String Helper functions?

    https://laravel.com/docs/5.8/helpers

   **[⬆ Back to Top](#table-of-contents)**
    
190. ### Laravel Array Helper functions?

    https://laravel.com/docs/5.8/helpers


   **[⬆ Back to Top](#table-of-contents)**
    
191. ### How to exclude a route with parameters from CSRF verification?

    https://stackoverflow.com/questions/48062083/laravel-5-4-exclude-a-route-with-parameters-from-csrf-verification
    

   **[⬆ Back to Top](#table-of-contents)**
    
192. ### What are policies classes?

    https://laravel.com/docs/5.7/authorization#policy-methods

   **[⬆ Back to Top](#table-of-contents)**
    
193. ### How to rollback last migration?

    Run migration rollback. If you want to rollback more than one steps, give the steps count.

   **[⬆ Back to Top](#table-of-contents)**
    
194. ### What do you mean by Laravel Dusk?

    https://laravel.com/docs/5.8/dusk

   **[⬆ Back to Top](#table-of-contents)**
    
195. ### Explain Laravel echo

    Used with broadcasting and sockets.


   **[⬆ Back to Top](#table-of-contents)**
    
196. ### What is namespace in Laravel?

    Identifies a code block and treats it separate fropm the rest so same name confusions don't occur.

   **[⬆ Back to Top](#table-of-contents)**
    
197. ### What is Laravel Forge?

   Laravel managed cloud hosting

   **[⬆ Back to Top](#table-of-contents)**
    
198. ### State the difference between CodeIgniter and Laravel.

    CodeIgniter is an older framework and Laravel is a much advanced framework.

   **[⬆ Back to Top](#table-of-contents)**
    
199. ### What is an Observer?

    https://codebriefly.com/brief-understanding-on-laravel-observers/

   **[⬆ Back to Top](#table-of-contents)**
    
200. ### What is the use of the bootstrap directory?

   Laravel starts from there.

   **[⬆ Back to Top](#table-of-contents)**
    
201. ### What is the default session timeout duration?

  120 minutes

   **[⬆ Back to Top](#table-of-contents)**
    
202. ### Explain API.PHP route

   It is used for creating API. Its url is /api/slug

   **[⬆ Back to Top](#table-of-contents)**
    
203. ### Define hashing in Laravel

   https://laravel.com/docs/5.7/hashing

   **[⬆ Back to Top](#table-of-contents)**
    
204. ### What is Localization?

   https://medium.com/@nedsoft/laravel-localization-made-simple-8ee4a34731e7

   **[⬆ Back to Top](#table-of-contents)**
    
205. ### How to share data with views?

   Pass it from the routes. To add for all views: https://laravel.com/docs/5.7/views#sharing-data-with-all-views

   **[⬆ Back to Top](#table-of-contents)**
    
206. ### How to generate a request in Laravel?

   Enter a route. It will go to the routes file to match the route and return a response.

   **[⬆ Back to Top](#table-of-contents)**
    
207. ### I just have installed a fresh version of Laravel 5, and I have the white screen of death. What’s wrong?

    You might see the white screen of death because of not enough permissions in folders. Try changing permissions of `/public`, `/vendor`, `/storage` folders.

   **[⬆ Back to Top](#table-of-contents)**
    
208. ### How to assign a variable value for all view file?

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
    
209. ### How to make a constant and use globally?

Create it in the .env file

210. ### How to check current installed version of Laravel?

    See `composer.json` file.

   **[⬆ Back to Top](#table-of-contents)**
    
211. ### What does "composer dump-autoload" do?

It just regenerates the list of all classes that need to be included in the project (autoload_classmap.php).

   **[⬆ Back to Top](#table-of-contents)**
    
212. ### What is Kept in vendor directory of Laravel?

   Laravel dependencies. Their code.
   

   **[⬆ Back to Top](#table-of-contents)**
    
213. ### What does PHP compact function do?

   Convert variables to array.


   **[⬆ Back to Top](#table-of-contents)**
   
214. ### What are Laravel facades?

   ...


   **[⬆ Back to Top](#table-of-contents)**
   
215. ### What directories that need to be writable laravel installation?

   /public
   /bootstrap/cache
   /vendor


   **[⬆ Back to Top](#table-of-contents)**

216. ### How to check current Laravel version using CLI?

   php artisan --version


   **[⬆ Back to Top](#table-of-contents)**
   
217. ### Why prefer Laravel over other frameworks?

   https://blog.vanila.io/why-laravel-is-best-php-framework-98a2784d76dc?gi=a81f8fa92a65

   **[⬆ Back to Top](#table-of-contents)**
   
218. ### What are service containers?

Service container is like a container where we define how the dependency should be resolved. We have to register the dependencies into the service container during the initialization of the framework and the best place to do it is the service provider.

   **[⬆ Back to Top](#table-of-contents)**
   
   
 219. ### Write CRUD in Laravel Eloquent

   CREATE:
   
         $flight = new Flight;
   
   READ:
   
    $flights = App\Flight::all();
    foreach ($flights as $flight) {
        echo $flight->name;
    }
   
   UPDATE:
   
        $flight = new Flight;

        $flight->name = $request->name;

        $flight->save();
        
   DELETE:
   
   $flight->delete();
   

   **[⬆ Back to Top](#table-of-contents)**
   
 220. ### Write CRUD in Laravel Query Builder

   CREATE:
     ```
     DB::table('users')->insert(
          ['email' => 'john@example.com', 'votes' => 0]
     );
     ```
   
   READ: 
     ```
     $users = DB::table('users')->get();
     ```
   
   UPDATE:
      ```
      DB::table('users')
            ->where('id', 1)
            ->update(['votes' => 1]);
      ```      
            
   DELETE:
      ```
      DB::table('users')->where('votes', '>', 100)->delete();
      ```
   source: https://laravel.com/docs/5.8/queries
   
   **[⬆ Back to Top](#table-of-contents)**

 221. ###  What are Eloquent collections?

   A way to get all of the data of a one or more models which might be required.

   **[⬆ Back to Top](#table-of-contents)**

 222. ### Build a to-do application with Laravel backend and a frontend framework  

   --

   **[⬆ Back to Top](#table-of-contents)**
   
 223. ### What are the day to day tasks of a Laravel developer?
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

 224. ### Output a raw query using eloquent or query builder. 

   Two ways,
   1. Turn the DB logs on and check the last query run in it.
   2. add ->ToSQL() function after the query.
   
   **[⬆ Back to Top](#table-of-contents)**

 225. ### How to create custom helper functions?

   Create a helper.php file anywhere and place the functions in it
   
   Add its location in the composer.json `files` area.
   
   Run composer dump autoload
   
   Answer here: https://stackoverflow.com/questions/28290332/best-practices-for-custom-helpers-in-laravel-5
   
   **[⬆ Back to Top](#table-of-contents)**
   
 226. ### How to check installed extensions in CLI and web for PHP?

   ```
   web: run phpinfo() function
   
   cli: php -m
   
   ```
   **[⬆ Back to Top](#table-of-contents)**
   
 227. ### How to create multiple where clause in eloquent?

   Use a single where clause and give the parameters as array
   ```
     $query->where([
      ['column_1', '=', 'value_1'],
      ['column_2', '<>', 'value_2'],
      [COLUMN, OPERATOR, VALUE],
      ...
     ])
   ```
 228. ### How to clear all cache?
 
 There are 4 cache in Laravel. Clear them all.
 
     php artisan key:generate
     
     php artisan config:cache
     
     php artisan cache:clear
     
     php artisan view:clear
     
     php artisan route:clear
     
 **[⬆ Back to Top](#table-of-contents)**
 
 
  229. ### What is the difference between where and having?
  Where is used for rows, having is used for columns.
 

 230. ### How can we protect site from SQL Injections?
 
We can protect site from SQL injections by sanitizing inputs. Whenever you have to enter string, use PHP function mysqli_real_escape_string().

For XSS protection i.e when you have to enter string in HTML use htmlspecialchars.

You should always try to use use prepared statements.
     
 **[⬆ Back to Top](#table-of-contents)**
 
 
  231. ### List all make commands

  make:cast            Create a new custom Eloquent cast class
  
  make:channel         Create a new channel class
  
  make:command         Create a new Artisan command
  
  make:component       Create a new view component class
  
  make:controller      Create a new controller class
  
  make:event           Create a new event class
  
  make:exception       Create a new custom exception class
  
  make:factory         Create a new model factory
  
  make:job             Create a new job class
  
  make:listener        Create a new event listener class
  
  make:mail            Create a new email class
  
  make:middleware      Create a new middleware class
  
  make:migration       Create a new migration file
  
  make:model           Create a new Eloquent model class
  
  make:notification    Create a new notification class
  
  make:observer        Create a new observer class
  
  make:policy          Create a new policy class
  
  make:provider        Create a new service provider class
  
  make:request         Create a new form request class
  
  make:resource        Create a new resource
  
  make:rule            Create a new validation rule
  
  make:seeder          Create a new seeder class
  
  make:test            Create a new test class

  232. ### What Are HTTP Verbs?
  POST, GET, PUT, PATCH, and DELETE etc
  
  233. ### How to do Pagination in DB?
$users = DB::table('users')->paginate(15);

 
  234. ### What is ORM?
Object–relational mapping is used to use Object oriented way to use database.


