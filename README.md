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
```

---

## **Variables**

Variables in SCSS store reusable values, such as colors, fonts, or sizes.
Example:

```scss
$font-stack: Helvetica, sans-serif;
$main-color: #333;

body {
  font: 100% $font-stack;
  color: $main-color;
}
```

---

Nesting
Nesting in SCSS makes it easy to write hierarchical styles similar to HTML structure.
Example:

```scss
nav {
  ul {
    margin: 0;
    padding: 0;
    list-style: none;
  }

  li {
    display: inline-block;
    margin-right: 10px;
  }
}
```
---
