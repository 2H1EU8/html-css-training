# HTML and CSS Training Repository

Welcome to the HTML and CSS training repository! This repository is designed to help you learn the fundamentals of HTML and CSS through practical exercises and examples.

## Table of Contents

1.  [Introduction](#introduction)
2.  [Exercises](#exercises)
3.  [Timeline](#timeline)
4.  [Resources](#resources)

## Introduction

This training covers the basics of HTML for structuring web content and CSS for styling it. You'll learn how to create well-structured and visually appealing web pages.

## Getting Started

To get started, follow these steps:

1.  Clone this repository to your local machine:
    ```bash
    git clone <repository-url>
    ```
2.  Navigate to the repository directory:
    ```bash
    cd html-css-training
    ```
3.  Switch between branch to watch all my examples and practices about HTML/CSS

## Exercises

The exercises are located in each branch have prefix `example/*` or `practice/*` in the name. Each exercise focuses on a specific aspect of HTML or CSS.

- **Exercise 1: Basic HTML Structure**
  - Create a basic HTML document with a header, paragraph, and list.
- **Exercise 2: CSS Styling & Layout**
  - Apply CSS styles to the HTML elements to change their appearance.
  - Use CSS to create a simple page layout with a header, sidebar, and main content area.

## Timeline

- July 8 -> July 10 (3days)

## Resources

Here are some useful resources for learning HTML and CSS:

- [Training Plan](https://docs.google.com/document/d/1yn6m0kTYpayTPiZRiltiKUn9YjRjqoxLKAzceoRBpdE/edit?tab=t.0)
- [CSS - web.dev](https://web.dev/learn/css/)
- [HTML Design and Build a Website](/)

# CSS Selectors Training Notes

This is a quick guide to CSS selectors, based on [this article](https://web.dev/learn/css/selectors).

## Basic Selectors

- **Universal Selector (`*`)**: Selects all elements. Use sparingly!
- **Type Selectors (e.g., `p`, `h1`, `div`)**: Selects all elements of a specific type.
- **Class Selectors (e.g., `.my-class`)**: Selects all elements with a specific class. Super useful!
- **ID Selectors (e.g., `#my-id`)**: Selects the element with a specific ID. IDs should be unique!
- **Attribute Selectors (e.g., `[type="text"]`)**: Selects elements with a specific attribute or attribute value.

## Combinators

- **Descendant Combinator (e.g., `div p`)**: Selects all `<p>` elements that are descendants of `<div>` elements.
- **Child Combinator (e.g., `div > p`)**: Selects all `<p>` elements that are direct children of `<div>` elements.
- **Adjacent Sibling Combinator (e.g., `h1 + p`)**: Selects the first `<p>` element that immediately follows an `<h1>` element.
- **General Sibling Combinator (e.g., `h1 ~ p`)**: Selects all `<p>` elements that follow an `<h1>` element (not necessarily immediately).

## Pseudo-classes and Pseudo-elements

- **Pseudo-classes (e.g., `:hover`, `:focus`, `:nth-child()`)**: Selects elements based on their state or position in the document tree.
- **Pseudo-elements (e.g., `::before`, `::after`)**: Creates virtual elements within an element.

## Specificity

Remember that CSS rules have different levels of specificity. ID selectors are more specific than class selectors, which are more specific than type selectors. Inline styles are the _most_ specific. Use the dev tools to debug specificity issues!

## Example

Check out `index.html` and `style.css` for a practical demonstration of these selectors.
