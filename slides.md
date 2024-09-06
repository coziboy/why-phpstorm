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

<v-click>Features:</v-click>
<br>
<v-click>- Intelligent code editor with advanced code completion and error prevention</v-click>
<br>
<v-click>- Powerful debugging and profiling tools for PHP applications</v-click>
<br>
<v-click>- Seamless integration with version control systems like Git</v-click>
<br>
<v-click>- Smart code navigation and refactoring capabilities</v-click>
<br>
<v-click>- Extensive support for HTML, CSS, and JavaScript development</v-click>
<br>
<v-click>- Database tools for efficient SQL editing and management</v-click>

---
layout: cover
background: https://cover.sli.dev
---

# Favorite Features

---

# Code Completion

PhpStorm is renowned for its zero-configuration code completion, which is powered by the IntelliJ platform. It provides code completion suggestions as you type, based on the context of your code.

<v-click>Some of the code completion features include:</v-click>

<v-click>
````md magic-move
```php
// Start typing a class name
use Carbon\Carbon; // PHPStorm will suggest 'Carbon\Carbon'
```

```php {4-8}
// Start typing a class name
use Carbon\Carbon; // PHPStorm will suggest 'Carbon\Carbon'

// Inside a function
function getCurrentDate() {
    // Start typing the Carbon class method
    return Carbon::now(); // PHPStorm will suggest 'now()' as you type
}
```

```php
// Inside a class
class User {
    private $name;
}
```

```php {5-8}
// Inside a class
class User {
    private $name;
    
    // Start typing the constructor method
    public function __construct($name) {
        $this->name = $name; // PHPStorm will suggest '$name' as you type
    }
}
```

```php {10-13}
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
</v-click>
---

# Deep Code Understanding and Refactoring

PhpStorm provides deep code understanding and refactoring capabilities, which help you maintain your codebase with ease.

<v-click>Some of the refactoring features include:</v-click>
<br>
<v-click>- Rename refactoring</v-click>
<br>
<v-click>- Move refactoring</v-click>
<br>
<v-click>- Extract method refactoring</v-click>
<br>
<v-click>- Safe delete refactoring</v-click>

---

# Database Tools

PhpStorm comes with a set of database tools that allow you to work with databases directly from the IDE. You can view and edit database schemas, run queries, and manage database connections without leaving the IDE.

<v-click>Some of the database tools features include:</v-click>
<br>
<v-click>- Database navigator</v-click>
<br>
<v-click>- SQL editor</v-click>
<br>
<v-click>- Database console</v-click>
<br>
<v-click>- Data editor</v-click>

---
layout: cover
background: https://cover.sli.dev
---

# Most Favorite Extensions

---

# Laravel IDEA

The Laravel Idea plugin in PHPStorm is a specialized plugin designed to enhance the development experience for Laravel projects within PHPStorm. It offers a variety of features that streamline and simplify Laravel development by providing intelligent code assistance

<v-click>Some of the features of Laravel IDEA include:</v-click>
<br>
<v-click>- Eloquent model support: Code completion, navigation, and refactoring for Eloquent models</v-click>
<br>
<v-click>- Laravel-specific code generation: Generates Laravel-specific code snippets</v-click>
<br>
<v-click>- Navigation to Laravel-specific files: Navigate to Laravel-specific files with ease</v-click>

---

# PEST Plugin

The Pest plugin in PHPStorm is designed to support the Pest testing framework, which is a testing library for PHP that emphasizes simplicity and a human-readable syntax. This plugin enhances the testing experience by integrating Pest’s features into the PHPStorm IDE.

<v-click>Some of the features of PEST Plugin include:</v-click>
<br>
<v-click>- Test execution: Allows you to run Pest tests directly from the PHPStorm interface</v-click>
<br>
<v-click>- Test results and reporting: Displays test results within the IDE</v-click>
<br>
<v-click>- Code completion: Provides code completion for Pest’s syntax</v-click>
<br>
<v-click>- Navigation: Simplifies navigating between test cases, test definitions, and the code being tested</v-click>

---

# Laravel Query

The Laravel Query plugin in PHPStorm is a tool specifically designed to assist with writing and managing complex Laravel Eloquent queries. This plugin enhances the development experience by providing features that make it easier to work with Laravel’s ORM (Object-Relational Mapping) system.

<v-click>Some of the features of Laravel Query include:</v-click>
<br>
<v-click>- Query Builder code completion: Provides code completion for Laravel Query Builder methods</v-click>
<br>
<v-click>- Query Builder navigation: Allows you to navigate between query builder methods and their definitions</v-click>
<br>
<v-click>- Query Builder refactoring: Provides refactoring capabilities for query builder methods</v-click>

---

# Bitbucket Pull Requests

Bitbucket Pull Requests is a PhpStorm plugin that provides support for Bitbucket pull requests. It enhances the Bitbucket pull request experience by providing code completion, navigation, and refactoring capabilities for Bitbucket pull requests.

<v-click>Some of the features of Bitbucket Pull Requests include:</v-click>
<br>
<v-click>- Review pull requests directly from the IDE</v-click>
<br>
<v-click>- Comment on pull requests</v-click>
<br>
<v-click>- Create new pull requests</v-click>
<br>
<v-click>- Approve, decline, or merge pull requests</v-click>

---

# Laravel Tinker

The Laravel Tinker plugin in PHPStorm is designed to enhance the experience of using Laravel’s Tinker, a powerful REPL (Read-Eval-Print Loop) for interacting with your Laravel application from the command line. Tinker allows developers to run PHP code within the context of the Laravel application, making it useful for testing, debugging, and performing quick tasks.

<v-click>Some of the features of Laravel Tinker include:</v-click>
<br>
<v-click>- Tinker console: Provides an interactive console within the PHPStorm interface</v-click>
<br>
<v-click>- Code completion: Offers code completion for Laravel-specific classes, methods, and variables</v-click>
<br>
<v-click>- History navigation: Allows you to navigate through previous commands and results in the Tinker console</v-click>

---

# Conclusion

PhpStorm is a powerful IDE that offers a wide range of features to enhance your PHP development experience. From intelligent code completion and refactoring to database tools and Laravel-specific plugins, PhpStorm provides everything you need to write, test, and maintain PHP applications with ease.

---
layout: end
---

# Thank You!

Any Questions?

<PoweredBySlidev mt-10 />
