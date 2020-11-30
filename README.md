# homework1
Code Refactor Homework 1

## Why I did this homework

The objective of this homework is to improve accessibility on an existing site. Accessibility is defined as a product, designed to make it easier for those with disabilities to use. To do this, I had to refactor the HTML and CSS file provided without changing what it does.

## What I learned

Some of the reasons accessibility is important is

* It helps people with disabilities and screen readers understand and navigate through the web.
* It improves inclusion on the web. Making it not only easier for people with disabilities but also older people and those with slower internet connections
* It will improve the placement of sites on search engines.

 A way to improve accessibility is to use semantic tags. Semantics make it easier to understand the purpose of a tag and will make your codes more organized. 

## HTML refactors

* Changed `<div class=”content”>` to `<header>`.
* Changed `<div>` in `<header>` to `<nav>`.
* Changed `<div class="hero"></div>` to `<figure>` and removed class.
* Changed `<div class=”content”>` to `<main>`.
* Changed `<div>` in `<main>` to ``<section>`.
* Changed class in `<sections>` within `<main>` to “content”.
* Added missing `<id>` to `<img>` on line 34.
* Added alt to images in `<main>`.
* Changed `<div class=”benefits”>` to `<aside>`.
* Changed `<div>` within `<aside>` to `<section>`.
* Changed `<section>` class to benefit on all.
* Added alt to images in `<aside>`.
* Changed `<div class=”footer”>` to `<footer>`.

## CSS refactors

* Added comments to label each section and selectors.
* Consolidating repeating sections that gave the same styling to multiple tags.
* Removed unnecessary class selectors.

## Link to Live URL

https://cloud126.github.io/homework1/

## Link to GitHub URL

https://github.com/Cloud126/test

## Screenshot

![Alt text](images/Screenshot-1 "Screenshot-1")

![Alt text](images/Screenshot-2 "Screenshot-1")

## License

MIT License

Copyright (c) [2020] [Maurino Federico Hernandez]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.