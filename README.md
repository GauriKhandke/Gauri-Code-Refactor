
# UW Bootcamp Homework 1 - HTML CSS Code Refactor

  

## Goal

* Goal of this project is to refactor existing code to make it more accessible.

* Website should follow web accessibility standards for search Engine Optimization.

  

## Motivation

Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

  

#### Code Refactoring :

* Code Refactoring is the process of clarifying and simplifying the design of existing code, without changing its behavior.

* Refactoring is intended to improve the design, structure, and/or implementation of the software (its non-functional attributes), while preserving its functionality.

* Refactoring improves code readability and reduces complexity. These can improve the source code's maintainability and create a simpler, cleaner, or more expressive internal architecture or object model to improve extensibility and performance.

  

#### Semantic HTML :

* Semantic HTML or semantic markup is HTML that introduces meaning to the web page rather than just presentation.

* Semantic HTML refers to syntax that makes the HTML more comprehensible by better defining the different sections and layout of web pages. It makes web pages more informative and adaptable, allowing browsers and search engines to better interpret content.

* Semantically correct HTML helps search engines, screen readers, and other user devices determine the significance and context of web content.

* Semantic HTML tags are self descriptive. For example `<article>` tag itself describes that it is article.

* Non-semantic elements such as `<div>` or `<span>` tells nothing about its content.

	##### HTML Semantic tags used:
	* `<header>` :   Specifies a header for a document or section.
	* `<main>` : Specifies the main content of a document.
	* `<article>` : Article is used to wrap autonomous content on a page. It can be moved from one page & put on some another page.
	* `<section>` : Wraps logical groups of related content.
	* `<figure>` : Used to mark up photos, code blocks, diagrams, charts, illustrations, and other graphical content.
	* `<aside>` : An additional content, unimportant for understanding an article, but related to the article.
	* `<footer>` : Defines a footer for a document or section.

  

## Features :

1. Webpage meets accessibility standards.
2. Followed semantic HTML structure by replacing`<div>` with respective tags that are more meaningful viz. `<header>` , `<nav>` , `<main>` , `<section>`, `<aside>`, `<article>`, `<footer>`, `<figure>`. 
3. Structure of HTML elements follow logical structure independent of styling and positioning.
4. Added `alt` attribute for images so that when image fails to load, alternate text can be shown.
5. Added comments before each element to make `html` code more descriptive.
6. Ensured that all links are working correctly.
7. Aligned HTML and CSS with proper indentation for better readability.
8. Consolidated CSS selectors having same attributes.
9. Consolidated CSS using shorthand property. 
10. Added comments before each selectors in CSS.

## Deployed Website: 

* https://github.com/GauriKhandke/gauri-code-refactor