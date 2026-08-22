# Awesome CakePHP with stars

> A curated list of CakePHP plugins, resources, and tools.

[CakePHP](https://cakephp.org/) is a rapid development PHP framework that uses well-known design patterns like MVC and ORM. It provides a robust foundation for building web applications with conventions over configuration.

If you are looking for previous CakePHP resources please visit:

* the [CakePHP 2.x version](https://github.com/FriendsOfCake/awesome-cakephp/tree/cake2) ⭐ 937 | 🐛 1 | 📅 2026-08-21 of this awesome list
* the [CakePHP 3.x version](https://github.com/FriendsOfCake/awesome-cakephp/tree/cake3) ⭐ 937 | 🐛 1 | 📅 2026-08-21 of this awesome list
* the [CakePHP 4.x version](https://github.com/FriendsOfCake/awesome-cakephp/tree/cake4) ⭐ 937 | 🐛 1 | 📅 2026-08-21 of this awesome list
* this wiki with a [list of not-yet upgraded plugins](https://github.com/FriendsOfCake/awesome-cakephp/wiki#plugins-not-yet-upgraded-from-2x-to-3x) ⭐ 937 | 🐛 1 | 📅 2026-08-21

Additional lists you might find useful:

* [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness) ⭐ 33,617 | 🐛 60 | 🌐 Ruby | 📅 2024-06-02
* [Awesome PHP](https://github.com/ziadoz/awesome-php) ⭐ 32,666 | 🐛 86 | 📅 2026-07-13
* [CakePHP Plugins](https://plugins.cakephp.org)

> For those wondering; this list differs from plugins.cakephp.org by supporting
> plugin subparts (instead of only the whole plugin/repo), more granular
> grouping and the primary focus on task-specific functionality.

## Contents

* [Plugins](#plugins)
  * [AI Tools](#ai-tools)
  * [Architecture](#architecture)
  * [Asset Management](#asset-management)
  * [Auditing / Logging](#auditing--logging)
  * [Authentication and Authorization](#authentication-and-authorization)
  * [Caching](#caching)
  * [Code Analysis](#code-analysis)
  * [Console](#console)
  * [Debugging](#debugging)
  * [Email](#email)
  * [File Manipulation](#file-manipulation)
  * [Filtering and Validation](#filtering-and-validation)
  * [Geolocation](#geolocation)
  * [I18n](#i18n)
  * [Imagery](#imagery)
  * [Libs](#libs)
  * [Markup](#markup)
  * [Migration](#migration)
  * [Miscellaneous](#miscellaneous)
  * [Navigation](#navigation)
  * [Notifications and Real-time Communication](#notifications-and-real-time-communication)
  * [ORM / Database / Datamapping](#orm--database--datamapping)
  * [PDF](#pdf)
  * [Queue](#queue)
  * [REST and API](#rest-and-api)
  * [Search](#search)
  * [Security](#security)
  * [SEO](#seo)
  * [Skeleton](#skeleton)
  * [Social](#social)
  * [Templating](#templating)
  * [Testing](#testing)
  * [Third Party APIs](#third-party-apis)
* [Software](#software)
  * [Development Environment](#development-environment)
  * [Web Applications](#web-applications)
  * [CMS and applications built on CakePHP](#cms-and-applications-built-on-cakephp)
  * [Demo](#demo)
* [Resources](#resources)
  * [Help](#help)
  * [CakePHP Websites](#cakephp-websites)
  * [CakePHP Books and Articles](#cakephp-books-and-articles)
  * [CakePHP Videos](#cakephp-videos)
  * [CakePHP Tutorials](#cakephp-tutorials)
  * [CakePHP Reading and Listening](#cakephp-reading-and-listening)
  * [CakePHP Internals Reading](#cakephp-internals-reading)
* [Conferences](#conferences)

## Plugins

### AI Tools

*Plugins and libraries for integrating artificial intelligence and machine learning tools.*

* [Synapse plugin](https://github.com/josbeir/cakephp-synapse) ⭐ 9 | 🐛 0 | 🌐 PHP | 📅 2026-08-08 - Expose your application functionality via MCP, with built-in tools and documentation search to help you discover and interact with your app's capabilities.
* [Crustum/OpenRouter plugin](https://github.com/crustum/cakephp-open-router) ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2026-07-25 - Integration with OpenRouter service for unified LLM access, supporting multiple AI models with chat completions, streaming, tool calling, and web search.

### Architecture

* [Burzum/CakeServiceLayer plugin](https://github.com/burzum/cakephp-service-layer) ⭐ 68 | 🐛 0 | 🌐 PHP | 📅 2026-01-04 - Service layer and domain/business model implementation.

### Asset Management

*Managing, compressing and minifying website assets.*

* [AssetCompress plugin](https://github.com/markstory/asset_compress) ⭐ 368 | 🐛 30 | 🌐 PHP | 📅 2025-11-20 - A complete asset manager for CakePHP.
* [AssetMix plugin](https://github.com/ishanvyas22/asset-mix) ⭐ 33 | 🐛 1 | 🌐 PHP | 📅 2024-09-24 - Provides integration with [Laravel Mix](https://laravel-mix.com) asset compilation.
* [CakeVite plugin](https://github.com/josbeir/cakephp-vite) ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2026-03-08 - A fully-featured [Vite](https://vite.dev/) plugin (spiritual successor of [brandcom/cakephp-vite](https://github.com/brandcom/cakephp-vite) ⭐ 23 | 🐛 6 | 🌐 PHP | 📅 2026-01-25).

### Auditing / Logging

*Tracking changes and events in your app.*

* [Muffin/Footprint plugin](https://github.com/UseMuffin/Footprint) ⭐ 95 | 🐛 0 | 🌐 PHP | 📅 2026-04-22 - Plugin to allow passing currently logged in user to model layer.
* [Version plugin](https://github.com/josegonzalez/cakephp-version) ⭐ 49 | 🐛 7 | 🌐 PHP | 📅 2024-01-09 - A plugin that facilitates versioned database entities.
* [DatabaseLog plugin](https://github.com/dereuromark/CakePHP-DatabaseLog) ⭐ 44 | 🐛 0 | 🌐 PHP | 📅 2026-08-06 - Simple and stand-alone logging to database instead of files.
* [AuditStash plugin](https://github.com/dereuromark/cakephp-audit-stash) ⭐ 8 | 🐛 1 | 🌐 PHP | 📅 2026-06-28 - Flexible and rock solid audit log tracking.
* [Bouncer plugin](https://github.com/dereuromark/cakephp-bouncer) ⭐ 1 | 🐛 2 | 🌐 PHP | 📅 2026-07-22 - The pendant to AuditStash, allow moderation and approval of add/edit/delete actions before the actual change is applied.

### Authentication and Authorization

*Plugins and libraries for implementing authentication and authorization.*

* [CakeDC/Users plugin](https://github.com/CakeDC/users) ⭐ 523 | 🐛 48 | 🌐 PHP | 📅 2026-07-01 - Complete user management (admin panel, remember me, etc), Social login (FB, Twitter, LinkedIn, Google, Instagram), RBAC, API and more.

* [Tools:Passwordable](https://github.com/dereuromark/cakephp-tools) ⭐ 333 | 🐛 1 | 🌐 PHP | 📅 2026-08-02 - Containing [Passwordable behavior](https://dereuromark.github.io/cakephp-tools/behavior/passwordable) for a DRY approach on password hashing.

* [TinyAuth plugin](https://github.com/dereuromark/cakephp-tinyauth) ⭐ 131 | 🐛 1 | 🌐 PHP | 📅 2026-08-02 - Authentication and role-based (single/multi) authorization as very light-weight approach.

* [Authentication plugin](https://github.com/cakephp/authentication) ⭐ 118 | 🐛 2 | 🌐 PHP | 📅 2026-08-17 - Official CakePHP authentication middleware plugin.

* [Authorization plugin](https://github.com/cakephp/authorization) ⭐ 74 | 🐛 0 | 🌐 PHP | 📅 2026-08-17 - Official CakePHP authorization stack.

* [ADmad/SocialAuth plugin](https://github.com/ADmad/cakephp-social-auth) ⭐ 51 | 🐛 4 | 🌐 PHP | 📅 2026-01-06 - A plugin which allows you to authenticate using social providers like Facebook/Google/Twitter etc. using [SocialConnect/auth](https://github.com/SocialConnect/auth) ⭐ 564 | 🐛 37 | 🌐 PHP | 📅 2026-06-23 social sign on library.

* [TwoFactorAuth plugin](https://github.com/andrej-griniuk/cakephp-two-factor-auth) ⭐ 38 | 🐛 2 | 🌐 PHP | 📅 2026-05-07 - Allows two factor authentication using Google Authenticator or similar app to generate one-time codes. Based on [RobThree/TwoFactorAuth](https://github.com/RobThree/TwoFactorAuth) ⭐ 1,186 | 🐛 3 | 🌐 PHP | 📅 2026-01-05 library.

* [ApiTokenAuthenticator plugin](https://github.com/rrd108/api-token-authenticator) ⭐ 3 | 🐛 4 | 🌐 PHP | 📅 2025-11-26 - A simple token authentication plugin for CakePHP REST APIs.

* [CakeVerification plugin](https://github.com/salines/cakephp-verification) ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2026-07-12 - Two-factor verification supporting email OTP, email magic link, SMS OTP, and TOTP (Google Authenticator).

### Caching

*Storing data for faster retrieval.*

* [Cache plugin](https://github.com/dereuromark/cakephp-cache) ⭐ 33 | 🐛 2 | 🌐 PHP | 📅 2026-06-28 - For caching views (HTML, CSV, JSON, XML, ...) as static cache files.
* [CakeDC/CachedRouting plugin](https://github.com/CakeDC/cakephp-cached-routing) ⭐ 5 | 🐛 0 | 🌐 PHP | 📅 2025-06-23 - Provides a cached version of the RoutingMiddleware to improve the load time of routes.

### Code Analysis

*Analyzing, parsing and manipulation codebases.*

* [IdeHelper plugin](https://github.com/dereuromark/cakephp-ide-helper) ⭐ 189 | 🐛 4 | 🌐 PHP | 📅 2026-08-14 - Helps to make IDE support better by adding annotations to your existing code similar to what baking does to new code.
* [cakedc/cakephp-phpstan](https://github.com/CakeDC/cakephp-phpstan) ⭐ 43 | 🐛 0 | 🌐 PHP | 📅 2026-05-21 - A PHPStan extension to resolve CakePHP magic around getter return types for the static analyzer.
* [TestHelper plugin](https://github.com/dereuromark/cakephp-test-helper) ⭐ 6 | 🐛 1 | 🌐 PHP | 📅 2026-08-02 - Provides testing enhancements and TDD support as browser backend.
* [lordsimal/cakephp-psalm](https://github.com/LordSimal/cakephp-psalm) ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2025-11-21 - A Psalm extension to resolve CakePHP magic around getter return types for the static analyzer.
* [IdeHelperExtra plugin](https://github.com/dereuromark/cakephp-ide-helper-extra) ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2026-06-28 - Useful IdeHelper addons for other plugins or custom use cases.

### Console

*Command-line tools and improvements.*

* [SignalHandler plugin](https://github.com/skie/SignalHandler) ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2026-07-04 - Cross-platform signal handling for CakePHP console commands with zero external dependencies. Supports Linux (pcntl), Windows (native API).
* [Scheduling plugin](https://github.com/skie/cakephp-scheduling) ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2026-07-17 - The plugin provides task scheduling capabilities with sub-minute precision, allowing you to schedule tasks as frequently as every second, with single crontab entry point. It allows tasks monitoring.

### Debugging

*Debugging and local development.*

* [DebugKit plugin](https://github.com/cakephp/debug_kit) ⭐ 839 | 🐛 0 | 🌐 PHP | 📅 2026-08-17 - The de-facto standard for debugging.
* [Setup plugin](https://github.com/dereuromark/cakephp-setup) ⭐ 35 | 🐛 0 | 🌐 PHP | 📅 2026-08-02 - A lightweight setup plugin containing healthcheck(s), debugging and maintenance tools.
* [Execution order](https://github.com/dereuromark/executionorder) ⭐ 21 | 🐛 4 | 🌐 PHP | 📅 2024-11-07 - A demo app to display the execution order of files, methods and callbacks.
* [CakephpWhoops plugin](https://github.com/dereuromark/cakephp-whoops) ⭐ 14 | 🐛 1 | 🌐 PHP | 📅 2026-06-28 - PHP errors and exceptions for cool kids with [filp/whoops](https://github.com/filp/whoops) ⭐ 13,234 | 🐛 9 | 🌐 PHP | 📅 2026-08-16.
* [Sentry plugin](https://github.com/lordsimal/cakephp-sentry) ⭐ 12 | 🐛 1 | 🌐 PHP | 📅 2026-08-09 - A plugin to seamlessly integrate Sentry for errors and exceptions.
* [AssociationsDebugger plugin](https://github.com/zunnu/associations-debugger) ⭐ 11 | 🐛 1 | 🌐 JavaScript | 📅 2024-06-15 - A plugin that draws your model associations as diagram.

### Email

*Transports and tools for email handling.*

* [Queue plugin](https://github.com/dereuromark/cakephp-queue) ⭐ 308 | 🐛 0 | 🌐 PHP | 📅 2026-08-02 - A dependency-free queue-based mail solution using Mailer/Email class, allowing re-queue on (network) failure.
* [SendGrid plugin](https://github.com/sprintcube/cakephp-sendgrid) ⭐ 5 | 🐛 5 | 🌐 PHP | 📅 2025-01-10 - Email transport plugin for sending email via SendGrid API.
* [CakeSymfonyMailer plugin](https://github.com/josbeir/cakephp-symfony-mailer) ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2026-08-16 - Use Symfony Mailer as a CakePHP mail transport.

### File Manipulation

*Upload, storage, and file handling.*

* [Josegonzalez/Upload plugin](https://github.com/FriendsOfCake/cakephp-upload) ⭐ 545 | 🐛 10 | 🌐 PHP | 📅 2026-02-16 - A customisable plugin that uses [Flysystem](https://flysystem.thephpleague.com/) to write to multiple backends (Dropbox, FTP, S3, Local, etc.).
* [FileStorage plugin](https://github.com/dereuromark/cakephp-file-storage) ⭐ 10 | 🐛 1 | 🌐 PHP | 📅 2026-07-31 - Flexible file storage and upload plugin.

### Filtering and Validation

*Data sanitization and validation rules.*

* see Cake/Localized plugin below.
* see Tools plugin below.
* [RuleFlow plugin](https://github.com/skie/rule-flow) ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2025-06-13 - A plugin that seamlessly transforms server-side validation rules into client-side JSON Logic validation, providing automatic form validation without requiring separate client-side validation code.

### Geolocation

*Geocoding addresses and working with latitudes and longitudes.*

* [Geo plugin](https://github.com/dereuromark/cakephp-geo) ⭐ 51 | 🐛 0 | 🌐 PHP | 📅 2026-08-02 - Containing [Geocoder behavior](https://www.dereuromark.de/2012/06/12/geocoding-with-cakephp/) and [GoogleMaps helper](https://www.dereuromark.de/2010/12/21/googlemapsv3-cakephp-helper/).

### I18n

*I18n (Internationalization) and L10n (Localization).*

* [Cake/Localized plugin](https://github.com/cakephp/localized) ⭐ 212 | 🐛 4 | 🌐 PHP | 📅 2026-06-30 - Localized validation and ready-to-use translation PO files.
* [ADmad/I18n plugin](https://github.com/ADmad/cakephp-i18n) ⭐ 44 | 🐛 1 | 🌐 PHP | 📅 2026-06-28 - A plugin with I18n related tools.
* [Translate plugin](https://github.com/dereuromark/cakephp-translate) ⭐ 17 | 🐛 4 | 🌐 PHP | 📅 2026-07-09 - Translate your translations in the backend with ease.

### Imagery

*Image processing and manipulation libraries.*

* [ADmad/Glide plugin](https://github.com/ADmad/cakephp-glide) ⭐ 34 | 🐛 0 | 🌐 PHP | 📅 2025-03-21 - A plugin for using [Glide](https://glide.thephpleague.com/) image manipulation library.
* [QrCode plugin](https://github.com/dereuromark/cakephp-qrcode/) ⭐ 9 | 🐛 0 | 🌐 PHP | 📅 2026-06-28 - Easily render SVG/PNG QR Codes for your app.
* [file-storage-image-processor](https://github.com/php-collective/file-storage-image-processor) ⭐ 0 | 🐛 1 | 🌐 PHP | 📅 2026-04-29 as `intervention/image` wrapper through [FileStorage plugin](https://github.com/dereuromark/cakephp-file-storage) ⭐ 10 | 🐛 1 | 🌐 PHP | 📅 2026-07-31.

### Libs

*Useful libraries or tools that don't fit in any of the other categories.*

* [Rocketeer](https://github.com/rocketeers/rocketeer) ⚠️ Archived - PHP task runner and deployment package.
* [Composer Installers](https://github.com/composer/installers) ⭐ 1,441 | 🐛 26 | 🌐 PHP | 📅 2026-07-01 - A multi framework Composer library installer.
* [Chronos](https://github.com/cakephp/chronos) ⭐ 1,362 | 🐛 2 | 🌐 PHP | 📅 2026-08-17 - A simple standalone DateTime API extension (successor of Carbon).
* [Graphviz](https://github.com/alexandresalome/graphviz) ⭐ 73 | 🐛 3 | 🌐 PHP | 📅 2024-04-25 - A Graphviz library.
* [Composer](https://getcomposer.org/)/[Packagist](https://packagist.org/) - A package and dependency manager.

### Markup

*Syntax highlighting and markup processing.*

* [Markup plugin](https://github.com/dereuromark/cakephp-markup) ⭐ 3 | 🐛 0 | 🌐 PHP | 📅 2026-08-18 - Allows to use PHP or JS based syntax highlighting.

### Migration

*Plugins and resources around migration and upgrading.*

* [Migrations plugin](https://github.com/cakephp/migrations) ⭐ 134 | 🐛 6 | 🌐 PHP | 📅 2026-08-17 - (DB) Migration plugin.
* [Upgrade app](https://github.com/cakephp/upgrade) ⭐ 111 | 🐛 0 | 🌐 PHP | 📅 2026-08-10 - Official upgrade app for 3.x=>4.x and 4.x=>5.x.
* [Upgrade app (extended)](https://github.com/dereuromark/upgrade) ⭐ 23 | 🐛 1 | 🌐 PHP | 📅 2026-06-18 - An extended upgrade app for 3.x=>4.x and some 5.x snippets.
* [Upgrade/Migration Guide](https://book.cakephp.org/5/en/appendices.html) - Official migration guide.

### Miscellaneous

*Misc plugins and libraries.*

* [Tools plugin](https://github.com/dereuromark/cakephp-tools) ⭐ 333 | 🐛 1 | 🌐 PHP | 📅 2026-08-02 - Containing lots of useful helpers, behaviors, components, commands, helpers, libs and more.
* [Ajax plugin](https://github.com/dereuromark/cakephp-ajax) ⭐ 54 | 🐛 0 | 🌐 PHP | 📅 2026-06-28 - A plugin to ease handling AJAX requests.
* [Shim plugin](https://github.com/dereuromark/cakephp-shim) ⭐ 40 | 🐛 0 | 🌐 PHP | 📅 2026-08-17 - A plugin containing useful shims and improvements as basis for your application.
* [Setup:Maintenance](https://github.com/dereuromark/cakephp-setup/blob/master/docs/Maintenance/Maintenance.md) ⭐ 35 | 🐛 0 | 🌐 PHP | 📅 2026-08-02 - Maintenance shell to go into maintenance mode for all requests with optional IP whitelisting.
* [CakeDC/Enum plugin](https://github.com/CakeDC/enum) ⭐ 30 | 🐛 4 | 🌐 PHP | 📅 2026-07-06 - A plugin to add enumeration list support to your app.
* [CakeDto plugin](https://github.com/dereuromark/cakephp-dto) ⭐ 30 | 🐛 0 | 🌐 PHP | 📅 2026-06-28 - Quickly generate useful data transfer objects for your app (mutable/immutable), replacing messy arrays and leveraging your IDE through typehinting and autocomplete.
* [DatabaseBackup plugin](https://github.com/mirko-pagliai/cakephp-database-backup) ⭐ 24 | 🐛 4 | 🌐 PHP | 📅 2026-08-22 - A plugin to export, import and manage database backups. Currently, the plugin supports MySQL, PostgreSQL and SQLite databases.
* [CakeHtmx plugin](https://github.com/zunnu/cake-htmx) ⭐ 18 | 🐛 0 | 🌐 PHP | 📅 2025-12-03 - CakePHP integration for [htmx](https://htmx.org/).
* [Calendar plugin](https://github.com/dereuromark/cakephp-calendar) ⭐ 16 | 🐛 0 | 🌐 PHP | 📅 2026-06-28 - For generating basic calendars. Includes IcalView for ICS calendar file generation.
* [Flash plugin](https://github.com/dereuromark/cakephp-flash) ⭐ 12 | 🐛 0 | 🌐 PHP | 📅 2026-06-28 - More powerful flash messages for your application.
* [Inertia plugin](https://github.com/CakeDC/cakephp-inertia) ⭐ 12 | 🐛 1 | 🌐 Twig | 📅 2025-03-03 - Plugin for connecting a Vue 3 app and use an API interface using a middleware.
* [OPCache Preloader](https://github.com/cnizzardini/cakephp-preloader) ⭐ 12 | 🐛 0 | 🌐 PHP | 📅 2026-07-25 - An OPCache Preloader for CakePHP applications.
* [Feedback plugin](https://github.com/dereuromark/cakephp-feedback) ⭐ 7 | 🐛 2 | 🌐 PHP | 📅 2026-06-28 - Allow visitors to send quick and easy feedback incl. a screenshot via sidebar form.
* [Workflow plugin](https://github.com/dereuromark/cakephp-workflow) ⭐ 3 | 🐛 0 | 🌐 PHP | 📅 2026-06-28 - Batteries-included state machine plugin with PHP 8 attributes, YAML config, audit trails, and visual admin dashboard.
* [AttributeRegistry plugin](https://github.com/josbeir/cakephp-attribute-registry) ⚠️ Archived - A powerful CakePHP plugin for discovering, caching, and querying PHP 8 attributes across your application and plugins.

### Navigation

*Building navigation structures.*

* [Icings/Menu plugin](https://github.com/icings/menu) ⭐ 12 | 🐛 4 | 🌐 PHP | 📅 2024-06-19 - A [KnpMenu](https://github.com/KnpLabs/KnpMenu) ⭐ 1,394 | 🐛 22 | 🌐 PHP | 📅 2026-08-21 seasoned menu plugin for CakePHP.
* [Menu plugin](https://github.com/dereuromark/cakephp-menu) ⭐ 5 | 🐛 1 | 🌐 PHP | 📅 2026-08-08 - Composable menu builder and renderer for nested navigation, active-state matching, and breadcrumbs - and zero dependencies.

### Notifications and Real-time Communication

*Working with notification software.*

* [Mercure plugin](https://github.com/josbeir/cakephp-mercure) ⭐ 5 | 🐛 1 | 🌐 PHP | 📅 2026-02-25 - Push real-time updates to clients using the Mercure protocol.
* [Crustum/Notification plugin](https://github.com/crustum/notification) ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2026-07-25 - The Notification plugin provides support for sending notifications across a variety of delivery channels.
* [Crustum/Broadcasting plugin](https://github.com/crustum/broadcasting) ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2026-08-13 - The Broadcasting plugin provides real-time event broadcasting for CakePHP applications using WebSocket connections compatible with the Pusher protocol or Redis pub/sub.

### ORM / Database / Datamapping

*Plugins that implement object-relational mapping or data-mapping techniques.*

* [Muffin/Trash plugin](https://github.com/usemuffin/trash) ⭐ 85 | 🐛 4 | 🌐 PHP | 📅 2026-03-24 - Soft-delete behavior for CakePHP.
* [Duplicatable plugin](https://github.com/riesenia/cakephp-duplicatable) ⭐ 51 | 🐛 5 | 🌐 PHP | 📅 2024-08-07 - Behavior for duplicating entities including related data.
* [ADmad/Sequence plugin](https://github.com/ADmad/cakephp-sequence) ⭐ 45 | 🐛 0 | 🌐 PHP | 📅 2025-11-22 - Behavior for maintaining ordered list of records.
* [Itosho/EasyQuery plugin](https://github.com/itosho/easy-query) ⭐ 26 | 🐛 0 | 🌐 PHP | 📅 2024-03-07 - Behavior for easily generating some complicated queries like (bulk) insert/upsert etc.
* [Muffin/Orderly plugin](https://github.com/usemuffin/orderly) ⭐ 22 | 🐛 0 | 🌐 PHP | 📅 2026-01-06 - Allows setting default order for your tables.
* [Icings/Partitionable plugin](https://github.com/icings/partitionable) ⭐ 15 | 🐛 2 | 🌐 PHP | 📅 2024-07-03 - Partitionable associations allowing for basic limiting per group.
* [CakeDecimal plugin](https://github.com/dereuromark/cakephp-decimal) ⭐ 8 | 🐛 0 | 🌐 PHP | 📅 2026-06-28 - A value object approach on handling decimals.
* [Lampager/Cake plugin](https://github.com/lampager/lampager-cakephp) ⭐ 7 | 🐛 1 | 🌐 PHP | 📅 2025-08-24 - Rapid pagination without using OFFSET.
* [CakeUid](https://github.com/josbeir/cakephp-uid) ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2025-08-27 - A collection of UID field types for your Tables (UUIDV4, UUIDV6, UUIDV7, ULID).

### PDF

*Plugins and software for working with PDF files.*

* [CakePdf plugin](https://github.com/FriendsOfCake/CakePdf) ⭐ 372 | 🐛 2 | 🌐 PHP | 📅 2026-06-19 - A plugin around PDF generation.

### Queue

*Working with event and task queues.*

* [Queue plugin](https://github.com/dereuromark/cakephp-queue) ⭐ 308 | 🐛 0 | 🌐 PHP | 📅 2026-08-02 - A minimal and dependency-free queue solution.
* [Queue plugin](https://github.com/cakephp/queue) ⭐ 36 | 🐛 9 | 🌐 PHP | 📅 2026-08-20 - CakePHP core queue system for the [php-queue](https://php-enqueue.github.io) queue library.
* [QueueScheduler plugin](https://github.com/dereuromark/cakephp-queue-scheduler) ⭐ 7 | 🐛 1 | 🌐 PHP | 📅 2026-06-28 - A dependency-free crontab-like scheduler as DB driven solution and addon to Queue (dereuromark) plugin.
* [Cake/Enqueue plugin](https://github.com/CakeDC/cakephp-enqueue) ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2025-09-22 - Database-driven message queue integration using the Enqueue library for CakePHP Queue plugin.
* [Crustum/BatchQueue plugin](https://github.com/crustum/batch-queue) ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2026-07-25 - Unified system for managing batch job processing with parallel execution and sequential chains.
* [Crustum/Temporal plugin](https://github.com/crustum/cakephp-temporal) ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2025-12-21 - Workflow orchestration plugin for durable execution, reliable background jobs, and long-running processes with automatic retries.

### REST and API

*Plugins and web tools for developing REST-ful APIs.*

* [CRUD plugin](https://github.com/FriendsOfCake/crud) ⭐ 379 | 🐛 11 | 🌐 PHP | 📅 2026-01-13 - CakePHP Application development on steroids - rapid prototyping / scaffolding & production-ready code.
* [CakeDC/Api plugin](https://github.com/CakeDC/cakephp-api) ⭐ 61 | 🐛 8 | 🌐 PHP | 📅 2026-08-17 - All-in-one solution to provide a complete API. It includes versioning, renderers, CRUD, authentication, extensions (paginate, filter, HATEOAS), and much more.
* [SwaggerBake plugin](https://github.com/cnizzardini/cakephp-swagger-bake) ⭐ 60 | 🐛 1 | 🌐 PHP | 📅 2026-07-25 - This plugin automatically builds OpenAPI from your existing models and routes for display in Swagger and Redoc.
* [FractalTransformerView plugin](https://github.com/andrej-griniuk/cakephp-fractal-transformer-view) ⭐ 18 | 🐛 0 | 🌐 PHP | 📅 2023-12-11 - A plugin which allows using [Fractal transformers](https://fractal.thephpleague.com/transformers/) for your API output.
* [MixerApi](https://mixerapi.com) - Streamline development of modern RESTful APIs for your team's CakePHP project.

### Search

*Plugins and software for indexing and performing search queries on data.*

* [Search plugin](https://github.com/FriendsOfCake/search) ⭐ 171 | 🐛 0 | 🌐 PHP | 📅 2026-05-11 - Provides easy searching/filtering for paginated views using PRG pattern.
* [Cake/Elasticsearch plugin](https://github.com/cakephp/elastic-search) ⭐ 86 | 🐛 1 | 🌐 PHP | 📅 2026-08-17 - Alternative ORM using [Elasticsearch](https://www.elastic.co/) as its backend.
* [PlumSearch plugin](https://github.com/skie/plum_search) ⭐ 19 | 🐛 0 | 🌐 PHP | 📅 2026-08-13 - Implements custom, flexible and extendable search strategies. Implements PRG pattern.
* [Tags plugin](https://github.com/dereuromark/cakephp-tags) ⭐ 17 | 🐛 1 | 🌐 PHP | 📅 2026-06-28 - For tagging and finding tagged records.
* [CakeDC/SearchFilter plugin](https://github.com/CakeDC/search-filter) ⭐ 3 | 🐛 0 | 🌐 PHP | 📅 2026-07-01 - Powerful and flexible solution for implementing advanced search functionality. Provides a robust set of tools for creating dynamic, user-friendly search interfaces with minimal effort.

### Security

*Plugins and information around security, preventing vulnerabilities and protection against XSS and alike.*

* [Muffin/Throttle plugin](https://github.com/usemuffin/throttle) ⭐ 62 | 🐛 0 | 🌐 PHP | 📅 2023-09-23 - A plugin for rate limiting (API) requests.
* [Muffin/Obfuscate plugin](https://github.com/usemuffin/obfuscate) ⭐ 36 | 🐛 0 | 🌐 PHP | 📅 2023-09-27 - Primary key obfuscation/shortening using UUIDs, HashIds, Optimus, Tiny and/or custom obfuscation strategies.
* [Recaptcha plugin](https://github.com/ctlabvn/Recaptcha) ⭐ 20 | 🐛 0 | 🌐 PHP | 📅 2025-01-28 - Simple, lightweight Google Recaptcha v2.
* [Expose plugin](https://github.com/dereuromark/cakephp-expose) ⭐ 9 | 🐛 0 | 🌐 PHP | 📅 2026-06-29 - Expose entities through additional UUIDs instead of their AIID primary keys to obfuscate those IDs and data associated with these numerically ordered values.
* [Captcha plugin](https://github.com/dereuromark/cakephp-captcha) ⭐ 8 | 🐛 0 | 🌐 PHP | 📅 2026-07-02 - Simple, unobtrusive and extendable captcha solution providing by default an image based math captcha.

### SEO

*Search Engine Optimization.*

* [Tools:Slugged](https://github.com/dereuromark/cakephp-tools) ⭐ 333 | 🐛 1 | 🌐 PHP | 📅 2026-08-02 - Containing Slugged behavior to auto-generate URL-compatible slugs from titles.
* [Muffin/Slug plugin](https://github.com/UseMuffin/Slug) ⭐ 38 | 🐛 5 | 🌐 PHP | 📅 2024-10-29 - A plugin for generating slugs and finding records by slug. Uses a pluggable architecture which allows using your own slug generator class.

### Skeleton

*Plugins and repositories around app skeletons.*

* [App template](https://github.com/cakephp/app) ⭐ 385 | 🐛 6 | 🌐 PHP | 📅 2026-08-05 - An empty CakePHP project for use with composer.
* [BS flavored App template](https://github.com/dereuromark/cakephp-app) ⭐ 4 | 🐛 0 | 🌐 PHP | 📅 2026-05-02 - An empty CakePHP project with BS5 and FontAwesome out of the box.

### Social

*Plugins around social features.*

* [Ratings plugin](https://github.com/dereuromark/cakephp-ratings) ⭐ 9 | 🐛 1 | 🌐 PHP | 📅 2026-06-28 - Allows users to rate records and displays ratings.
* [Favorites plugin](https://github.com/dereuromark/cakephp-favorites) ⭐ 3 | 🐛 0 | 🌐 PHP | 📅 2026-06-28 - Allows users to star/like/favor records.
* [Comments plugin](https://github.com/dereuromark/cakephp-comments) ⭐ 2 | 🐛 1 | 🌐 PHP | 📅 2026-06-28 - Allows users to comment records, supporting different formats.

### Templating

*Template engines and view generation.*

* [BootstrapUI plugin](https://github.com/friendsofcake/bootstrap-ui) ⭐ 353 | 🐛 0 | 🌐 PHP | 📅 2026-07-11 - Bootstrap 4/5 integration.
* [Tools:Tree](https://github.com/dereuromark/cakephp-tools) ⭐ 333 | 🐛 1 | 🌐 PHP | 📅 2026-08-02 - Tree helper to work with Core Tree behavior and handle tree structure output.
* [CsvView plugin](https://github.com/FriendsOfCake/cakephp-csvview) ⭐ 177 | 🐛 2 | 🌐 PHP | 📅 2026-05-12 - A view class to easily generate CSV.
* [Bake plugin](https://github.com/cakephp/bake) ⭐ 112 | 🐛 0 | 🌐 PHP | 📅 2026-08-17 - Provides code generation functionality.
* [TwigView plugin](https://github.com/cakephp/twig-view) ⭐ 15 | 🐛 3 | 🌐 PHP | 📅 2026-06-30 - A plugin to use the Twig Templating Language for views.
* [Feed plugin](https://github.com/dereuromark/cakephp-feed) ⭐ 13 | 🐛 0 | 🌐 PHP | 📅 2026-06-28 - Containing an RssView class to easily generate (complex) RSS feeds.
* [Meta plugin](https://github.com/dereuromark/cakephp-meta) ⭐ 9 | 🐛 0 | 🌐 PHP | 📅 2026-06-28 - Makes handling meta tags and SEO-relevant HTML markup DRY and easy.
* [Templating](https://github.com/dereuromark/cakephp-templating) ⭐ 5 | 🐛 0 | 🌐 PHP | 📅 2026-06-28 - HTML snippets as value objects, (Font) icons, and templating topics.
* [LatteView plugin](https://github.com/josbeir/cakephp-latte-view) ⭐ 2 | 🐛 3 | 🌐 PHP | 📅 2026-04-06 - A plugin providing Latte template engine integration.
* [TailwindUi plugin](https://github.com/dereuromark/cakephp-tailwind-ui) ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2026-08-08 - Tailwind CSS / DaisyUI (or KTUI/Metronic) integration for form, pagination, flash, and breadcrumb helpers.
* [XlsView plugin](https://github.com/impronta48/cakephp-xlsview) ⭐ 1 | 🐛 2 | 🌐 PHP | 📅 2025-01-11 - A view class to easily generate XLS using PHPSpreadsheet.
* [TemplaterDefaults plugin](https://github.com/josbeir/cakephp-templater-defaults) ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2025-09-20 - Allows the use of default HTML attributes within CakePHP's string template system.

### Testing

*Plugins/Tools for testing codebases and generating test data.*

* [CakePHP CodeSniffer rules](https://github.com/cakephp/cakephp-codesniffer) ⭐ 232 | 🐛 5 | 🌐 PHP | 📅 2026-08-21 - The official CakePHP CS rules.
* [FriendsOfCake/Fixturize plugin](https://github.com/FriendsOfCake/fixturize) ⭐ 24 | 🐛 4 | 🌐 PHP | 📅 2024-08-09 - More efficient inserting fixtures when running test suites by decreasing amount of inserts (MySQL only).
* [CakephpFixtureFactories plugin](https://github.com/dereuromark/cakephp-fixture-factories) ⭐ 4 | 🐛 2 | 🌐 PHP | 📅 2026-05-28 - Create your fixtures dynamically on a test basis, accelerate the writing and maintenance of your tests.

### Third Party APIs

*Accessing third party APIs.*

## Software

*Software for creating a development environment.*

### Development Environment

*Software and tools for creating a sandboxed development environment.*

* [NetBeans](https://github.com/junichi11/cakephp3-netbeans) ⭐ 47 | 🐛 8 | 🌐 Java | 📅 2022-11-24 - This package provides support for CakePHP in NetBeans 8.1+.
* [Docker](https://github.com/stefanvangastel/docker-cakephp) ⭐ 30 | 🐛 0 | 🌐 Dockerfile | 📅 2019-11-09 - CakePHP in a Docker container environment.
* [CakePHP Docker](https://github.com/cnizzardini/cakephp-docker) ⭐ 29 | 🐛 4 | 🌐 PHP | 📅 2024-11-25 - A cakephp/app template for Docker.
* [CakePHP Vagrant Setup](https://github.com/cpierce/cakephp-vagrant-setup) ⭐ 5 | 🐛 0 | 🌐 Jinja | 📅 2022-03-31 - Tool for spinning up multiple CakePHP vanilla dev environments using Vagrant.
* [CakePHP Docker Setup](https://github.com/cpierce/cakephp-docker-setup) ⭐ 0 | 🐛 0 | 🌐 Smarty | 📅 2026-04-30 - Tool for spinning up multiple CakePHP vanilla dev environments using Docker.
* [DDEV](https://ddev.readthedocs.io/en/stable/) - Docker based local env.
* [Devilbox](https://devilbox.readthedocs.io/en/latest/) - A Docker development environment for (CakePHP) apps to be auto-setup including a lot of tools.
* [Galley](https://gitlab.com/amayer5125/galley) - A small Docker dev environment for CakePHP development which includes a simple command line utility.
* [Puppet](https://puppetlabs.com/) - A server automation framework and application.
* [Vagrant](https://developer.hashicorp.com/vagrant) - A portable development environment utility.

IDE specific compatibility information and tips can be found [here](https://github.com/dereuromark/cakephp-ide-helper/wiki#ide-support-and-tips) ⭐ 189 | 🐛 4 | 🌐 PHP | 📅 2026-08-14.

### Web Applications

* [Toolbox](https://toolbox.dereuromark.de) - Online toolbox with useful tools for modern CakePHP apps. Powers the awesome CI/linter.

### CMS and applications built on CakePHP

* [baserCMS](https://github.com/baserproject/basercms) ⭐ 193 | 🐛 94 | 🌐 PHP | 📅 2026-08-20 - This is a website development framework with RESTful APIs. Installable as a plugin for CakePHP.

### Demo

*Web-based (demo) applications and tools.*

* [RealWorld](https://github.com/gothinkster/cakephp-realworld-example-app) ⚠️ Archived - Example CakePHP codebase containing real world examples (CRUD, auth, advanced patterns and more) that adheres to the [RealWorld](https://github.com/gothinkster/realworld-example-apps) ⭐ 84,119 | 🐛 32 | 🌐 TypeScript | 📅 2026-08-13 spec and API.
* [Query examples](https://github.com/lorenzo/cakephp3-examples) ⭐ 56 | 🐛 0 | 🌐 PHP | 📅 2014-08-23 - Advanced query building examples.
* [Xeta](https://github.com/XetaIO/Xeta) ⭐ 50 | 🐛 4 | 🌐 PHP | 📅 2017-04-25 - A resource to help people starting with CakePHP.
* [Vue.js demo app](https://github.com/ishanvyas22/cakephpvue-spa) ⭐ 46 | 🐛 2 | 🌐 PHP | 📅 2026-08-06 - A CakePHP + Vue.js single page application skeleton.
* [Bookmarkr](https://github.com/lorenzo/cakephp3-bookmarkr) ⚠️ Archived - A bookmarking application built with the CRUD plugin.
* [BlogMVC](https://github.com/Kareylo/BlogMVC-CakePHP3) ⭐ 8 | 🐛 0 | 🌐 PHP | 📅 2017-08-24 - A simple Blog example with CakePHP based on [BlogMVC Project](https://github.com/Grafikart/BlogMVC) ⚠️ Archived.
* [Fluentd + Grafana Loki demo application](https://github.com/ishanvyas22/cakephp-loki-demo) ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2026-08-03 - A demo application to send CakePHP Docker container logs to [Grafana Loki](https://grafana.com/) via [Fluentd](https://www.fluentd.org/).
* [TinyAuth demo](https://github.com/dereuromark/cakephp-tinyauth-demo) ⭐ 0 | 🐛 2 | 🌐 PHP | 📅 2026-07-29 - Full interactivate auth (TinyAuth incl. Authentication and Authorization core plugins) demo.
* [Sandbox](https://sandbox.dereuromark.de) - A sandbox CakePHP application with lots of demos and plugin showcasings.

## Resources

Various resources, such as books, websites and articles, for improving your CakePHP development skills and knowledge.

### Help

*Where to get help.*

* [Official CakePHP Forum](https://discourse.cakephp.org/) - This is for generic questions and alike.
* [stackoverflow.com/questions/tagged/cakephp](https://stackoverflow.com/questions/tagged/cakephp) - This is for specific questions, ideally along with some example code.

### CakePHP Websites

*Useful and current CakePHP-related websites and blogs.*

* [CakeDC](https://www.cakedc.com/articles) - Articles around CakePHP.
* [dereuromark.de](https://www.dereuromark.de) - An extensive CakePHP core dev blog.
* [josediazgonzalez.com](https://josediazgonzalez.com/) - A mainly CakePHP related core dev blog.
* [mark-story.com](https://mark-story.com) - CakePHP lead dev blog.

### CakePHP Books and Articles

*Fantastic CakePHP-related (e)books and other reading material.*

### CakePHP Videos

*Fantastic CakePHP-related videos.*

* [CakePHP](https://www.youtube.com/user/CakePHP) - Channel about CakePHP videos.

### CakePHP Tutorials

*Must-do tutorials.*

* [Official Content Management Tutorial](https://book.cakephp.org/5/en/tutorials-and-examples/cms/installation.html)

### CakePHP Reading and Listening

*Documentation and CakePHP-related reading and listening materials.*

* [CakePHP Cookbook(!)](https://book.cakephp.org/) - The official CakePHP documentation.

### CakePHP Internals Reading

*Reading materials related to the CakePHP internals and decisions.*

* [Top 10 (and more) core contributors](https://github.com/cakephp/cakephp/graphs/contributors) ⭐ 8,795 | 🐛 28 | 🌐 PHP | 📅 2026-08-22 - Give 'em a hand.

## Conferences

### Official

*International conference.*

* [cakefest.org](https://cakefest.org/) - Annual CakePHP Conference.

### MeetUps

*Regional meet-ups.*

* [CakePHP-DE](https://www.meetup.com/CakePHP-DE) - MeetUps in Germany.

## Footnotes

awesome-cakephp has been created by [dereuromark](https://github.com/dereuromark) and is currently maintained by him and the FriendsOfCake group. Thank you to all [contributors](https://github.com/FriendsOfCake/awesome-cakephp/graphs/contributors) ⭐ 937 | 🐛 1 | 📅 2026-08-21, too.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-22._
