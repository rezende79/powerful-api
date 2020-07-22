# Powerful _and simple_ API

A Simple API project using [Symfony Framework 5](https://symfony.com/what-is-symfony) and [API Platform](https://symfony.com/projects/apiplatform) bundle.

## :star: Requisites

Write a simple API (using at least Symfony 4.2) for showing a list of users, and creating a new user.

The goal is to be able to swap out the data source for users without having to touch any of the code that uses the data source and returns the response and also provide documentation for consuming the API.

+ _(plus)_ Added a [Unique](https://symfony.com/doc/current/reference/constraints/Unique.html) constraint for 'email' field
+ _(plus)_ Added a [NotBlank](https://symfony.com/doc/current/reference/constraints/NotBlank.html) constraint for 'first name' and 'last name' fields.

## :muscle: Try it out 

Play with this API here: [https://api.rezehnde.com/](https://api.rezehnde.com/)

## :triangular_ruler: Built With 

* [Symfony 5](https://symfony.com/what-is-symfony) - PHP Framework
* [Composer](https://getcomposer.org/) - A Dependency Manager for PHP
* [API Platform](https://api-platform.com/) - Framework to build modern API-driven projects

## :trophy: Authors 

* **Marcos Rezende** - *Initial work* - [Software Engineer](https://github.com/rezehnde)

### :mag: Backlog 

* Implement a authentication method to consume the API
* Include Unit Tests
* CI/CD implemente using Git on a Shared Host with cPanel
