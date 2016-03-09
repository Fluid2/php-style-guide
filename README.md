# PHP Style Guide

This guide lays out the code style for contributing PHP code to any Fluid 2 projects. The aim is to ensure that all code produced is consistent and make it as easy as possible to become familiar with a project.

### Basic Rules

Where possible code format will follow the [PSR-2](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md) standard and autoloading will follow the [PSR-4](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-4-autoloader.md) standard, particularly the following rules:

- Class names MUST be declared in `StudlyCaps`.
- Class constants MUST be declared in all upper case with underscore separators.
- Method names MUST be declared in `camelCase`.

#### Exceptions

There are situations where it may not be appropriate to follow these standards. Several examples are listed below:

- Working with 3rd party software. CMS systems such as WordPress often have their own coding standards that contradict with PSR. In these situations the local standard should be followed. A copy of the WordPress PHP coding standards can be found [here](https://make.wordpress.org/core/handbook/best-practices/coding-standards/php/).
- Tests should be structured to be easily legible. Method names should be declared in `snake_case`.

Aside from these examples there may be other situations where it makes sense to deviate from PSR. The main rule of thumb to figure is that these should be situations where deviating from PSR makes a project easier to reason about.

## Laravel 5 Coding

Section coming soon.

## WordPress Coding

Section coming soon.
