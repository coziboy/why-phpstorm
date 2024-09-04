---
theme: seriph
background: https://cover.sli.dev
title: Why PhpStorm?
class: text-center
transition: slide-left
mdc: true
---

# Why PhpStorm?

By: Andreas Asatera Sandi Nofa

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

---

# What is PhpStorm?

PhpStorm is an IDE that actually ‘gets’ your code. It provides on-the-fly error prevention, best autocompletion & code refactoring, zero configuration debugging, and an extended HTML, CSS, and JavaScript editor.

Features:

- Intelligent code editor with advanced code completion and error prevention
- Powerful debugging and profiling tools for PHP applications
- Seamless integration with version control systems like Git
- Smart code navigation and refactoring capabilities
- Extensive support for HTML, CSS, and JavaScript development
- Database tools for efficient SQL editing and management

---
layout: cover
background: https://cover.sli.dev
---

# Favorite Features

---

# Code Completion

PhpStorm is renowned for its zero-configuration code completion, which is powered by the IntelliJ platform. It provides code completion suggestions as you type, based on the context of your code.

Some of the code completion features include:

````md magic-move
```php {*|1-2|4-8}
// Start typing a class name
use Carbon\Carbon; // PHPStorm will suggest 'Carbon\Carbon'

// Inside a function
function getCurrentDate() {
    // Start typing the Carbon class method
    return Carbon::now(); // PHPStorm will suggest 'now()' as you type
}
```

```php {*|5-8|10-13}
// Inside a class
class User {
    private $name;
    
    // Start typing the constructor method
    public function __construct($name) {
        $this->name = $name; // PHPStorm will suggest '$name' as you type
    }
    
    // Start typing a method name
    public function getName() {
        return $this->name; // PHPStorm will suggest '$this->name' as you type
    }
}
```
````
---

# Deep Code Understanding and Refactoring

PhpStorm provides deep code understanding and refactoring capabilities, which help you maintain your codebase with ease. Some of the refactoring features include:

- Rename refactoring
- Move refactoring
- Extract method refactoring
- Safe delete refactoring

---

# Database Tools

PhpStorm comes with a set of database tools that allow you to work with databases directly from the IDE. You can view and edit database schemas, run queries, and manage database connections without leaving the IDE.

Some of the database tools features include:

- Database navigator
- SQL editor
- Database console
- Data editor

---
layout: cover
background: https://cover.sli.dev
---

# Most Favorite Extensions

---

# Laravel IDEA

The Laravel Idea plugin in PHPStorm is a specialized plugin designed to enhance the development experience for Laravel projects within PHPStorm. It offers a variety of features that streamline and simplify Laravel development by providing intelligent code assistance

Some of the features of Laravel IDEA include:

- Eloquent model support: Provides code completion, navigation, and refactoring for Eloquent models
- Laravel-specific code generation: Generates Laravel-specific code snippets, such as routes, controllers, and views
- Navigation to Laravel-specific files: Allows you to navigate to Laravel-specific files, such as routes, controllers, and views, with ease

---

# PEST Plugin

The Pest plugin in PHPStorm is designed to support the Pest testing framework, which is a testing library for PHP that emphasizes simplicity and a human-readable syntax. This plugin enhances the testing experience by integrating Pest’s features into the PHPStorm IDE.

Some of the features of PEST Plugin include:

- Test execution: Allows you to run Pest tests directly from the PHPStorm interface. You can execute individual tests, test files, or entire test suites with ease.
- Test results and reporting: Displays test results within the IDE, showing which tests passed, failed, or were skipped. It provides detailed output and error messages to help you debug failed tests.
- Code completion: Provides code completion for Pest’s syntax, including assertions, test functions, and custom test methods, making it easier to write and maintain tests.
- Navigation: Simplifies navigating between test cases, test definitions, and the code being tested. You can quickly jump from a test to the corresponding code or vice versa.

---

# Laravel Query

The Laravel Query plugin in PHPStorm is a tool specifically designed to assist with writing and managing complex Laravel Eloquent queries. This plugin enhances the development experience by providing features that make it easier to work with Laravel’s ORM (Object-Relational Mapping) system.

Some of the features of Laravel Query include:

- Query Builder code completion: Provides code completion for Laravel Query Builder methods, making it easier to write complex queries.
- Query Builder navigation: Allows you to navigate between query builder methods and their definitions, helping you understand how queries are constructed.
- Query Builder refactoring: Provides refactoring capabilities for query builder methods, allowing you to rename, move, or extract query builder code with ease.

---

# Bitbucket Pull Requests

Bitbucket Pull Requests is a PhpStorm plugin that provides support for Bitbucket pull requests. It enhances the Bitbucket pull request experience by providing code completion, navigation, and refactoring capabilities for Bitbucket pull requests.

Some of the features of Bitbucket Pull Requests include:

- Review pull requests directly from the IDE
- Comment on pull requests
- Create new pull requests
- Approve, decline, or merge pull requests

---

# Laravel Tinker

The Laravel Tinker plugin in PHPStorm is designed to enhance the experience of using Laravel’s Tinker, a powerful REPL (Read-Eval-Print Loop) for interacting with your Laravel application from the command line. Tinker allows developers to run PHP code within the context of the Laravel application, making it useful for testing, debugging, and performing quick tasks.

Some of the features of Laravel Tinker include:

- Tinker console: Provides an interactive console within the PHPStorm interface, allowing you to run PHP code and interact with your Laravel application.
- Code completion: Offers code completion for Laravel-specific classes, methods, and variables, making it easier to write and execute code in the Tinker console.
- History navigation: Allows you to navigate through previous commands and results in the Tinker console, making it easier to review and reuse code snippets.

---

# Conclusion

PhpStorm is a powerful IDE that offers a wide range of features to enhance your PHP development experience. From intelligent code completion and refactoring to database tools and Laravel-specific plugins, PhpStorm provides everything you need to write, test, and maintain PHP applications with ease.

---
layout: end
---

# Thank You!

Any Questions?

<PoweredBySlidev mt-10 />
