# Complete SCSS  

This repository provides a detailed guide to SCSS (Sassy CSS), a CSS preprocessor that enhances the power and elegance of CSS with variables, nesting, mixins, inheritance, and more. SCSS is widely used for building scalable and maintainable stylesheets.

---

## **Table of Contents**
1. [Introduction](#introduction)
2. [SCSS Basics](#scss-basics)
3. [Variables](#variables)
4. [Nesting](#nesting)
5. [Partials and Import](#partials-and-import)
6. [Mixins](#mixins)
7. [Inheritance](#inheritance)
8. [Functions](#functions)
9. [Operators](#operators)
10. [Conditionals and Loops](#conditionals-and-loops)
11. [Best Practices](#best-practices)

---

## **Introduction**
SCSS (Sassy CSS) is an extension of CSS that adds powerful features like variables, mixins, and functions. SCSS files have the `.scss` extension and compile into regular CSS.

---

## **SCSS Basics**
SCSS allows you to write modular, reusable, and readable stylesheets.  
Example:
```scss
$primary-color: #3498db;

body {
  font-family: Arial, sans-serif;
  background-color: $primary-color;
}


1. Variables
    -> Variables in SCSS store reusable values, such as colors, fonts, or sizes.

2. Nesting
    -> Nesting in SCSS makes it easy to write hierarchical styles similar to HTML structure.


3. Partials and Import
    -> Partials are SCSS files prefixed with an underscore (_) and used for modular styles. Use @import to include them.
  Example:
    _variables.scss
    _header.scss

4. Mixins
    -> Mixins allow reusable blocks of styles with optional arguments.

5. Inheritance
    -> Inheritance enables sharing styles between selectors using @extend.

6. Functions
    -> Functions in SCSS return a value based on calculations or operations.

7. Operators
    -> SCSS supports mathematical and logical operators.

8. Conditionals and Loops
    -> SCSS provides @if, @else, and loops like @for, @each, and @while for dynamic styles.