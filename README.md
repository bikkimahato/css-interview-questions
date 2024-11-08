# CSS Interview Questions Repository
Welcome to the CSS Interview Questions Repository! This repository is a curated collection of CSS interview questions categorized by difficulty: Easy, Medium, and Hard. Whether you're just starting out or looking to master advanced CSS techniques, this repository will help you enhance your skills.

## Introduction

Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in HTML or XML. Mastery of CSS is essential for creating visually appealing web pages and applications. This repository aims to provide a comprehensive set of questions to help you practice and improve your CSS skills.

## Why CSS?

- **Essential for Web Design**: CSS is crucial for creating visually compelling and responsive web designs.
- **Customizable**: Allows for extensive customization of web pages, making them more user-friendly and attractive.
- **Widely Used**: CSS is a fundamental technology in web development, used across virtually all websites.

## Question Categories

### Easy

These questions cover basic CSS concepts, properties, and selectors. Ideal for beginners who are just getting started with CSS.

### Medium

These questions delve into more complex topics such as layout techniques (Flexbox, Grid), pseudo-classes, and responsive design.

### Hard

These questions are designed for advanced users and cover topics like animations, transitions, advanced selectors, and performance optimization.

## Contributing

We welcome contributions from the community! If you have a question or improvement that you think should be included, please follow these steps:

1. Fork the repository.
2. Create a new branch for your contribution.
3. Add your question or improvement in the appropriate category folder (`easy`, `medium`, `hard`).
4. Submit a pull request with a detailed description of your changes.

---

Happy coding! If you find this repository helpful, please give it a star ⭐ and share it with others.

---

### Table of Contents
### Level : Easy
| No. | Questions |
| --- | --------- |
| 1   | [What is CSS?](#1-what-is-css) |
| 2   | [How do you apply CSS to a web page?](#2-how-do-you-apply-css-to-a-web-page) |
| 3   | [What is the difference between class and ID selectors in CSS?](#3-what-is-the-difference-between-class-and-id-selectors-in-css) |
| 4   | [How can you include CSS in a web page?](#4-how-can-you-include-css-in-a-web-page) |
| 5   | [What is the box model in CSS?](#5-what-is-the-box-model-in-css) |
| 6   | [Explain the difference between margin and padding.](#6-explain-the-difference-between-margin-and-padding) |
| 7   | [What is the purpose of the `z-index` in CSS?](#7-what-is-the-purpose-of-the-z-index-in-css) |
| 8   | [How do you center a block element horizontally?](#8-how-do-you-center-a-block-element-horizontally) |
| 9   | [What are pseudo-classes in CSS?](#9-what-are-pseudo-classes-in-css) |
| 10  | [What are pseudo-elements in CSS?](#10-what-are-pseudo-elements-in-css) |
| 11  | [How can you make a list not display bullet points?](#11-how-can-you-make-a-list-not-display-bullet-points) |
| 12  | [What is the difference between `inline` and `block` elements?](#12-what-is-the-difference-between-inline-and-block-elements) |
| 13  | [How do you use `inherit` in CSS?](#13-how-do-you-use-inherit-in-css) |
| 14  | [What does `!important` do in CSS?](#14-what-does-important-do-in-css) |
| 15  | [Explain how CSS specificity works.](#15-explain-how-css-specificity-works) |
| 16  | [How do you apply multiple styles to an element?](#16-how-do-you-apply-multiple-styles-to-an-element) |
| 17  | [What is the use of `float` property in CSS?](#17-what-is-the-use-of-float-property-in-css) |
| 18  | [What is the `position` property in CSS?](#18-what-is-the-position-property-in-css) |
| 19  | [How can you make a background image not repeat in CSS?](#19-how-can-you-make-a-background-image-not-repeat-in-css) |
| 20  | [How do you create a responsive design using CSS?](#20-how-do-you-create-a-responsive-design-using-css) |
| 21  | [What is the `display` property in CSS?](#21-what-is-the-display-property-in-css) |
| 22  | [What does the `clear` property do?](#22-what-does-the-clear-property-do) |
| 23  | [How can you hide an element using CSS?](#23-how-can-you-hide-an-element-using-css) |
| 24  | [What is the difference between `visibility: hidden` and `display: none`?](#24-what-is-the-difference-between-visibility-hidden-and-display-none) |
| 25  | [How do you style a hyperlink to remove the underline?](#25-how-do-you-style-a-hyperlink-to-remove-the-underline) |

### Easy CSS Interview Questions

#### 1. **What is CSS?**

   CSS (Cascading Style Sheets) is a stylesheet language used for describing the presentation of a document written in HTML or XML. CSS defines how elements should be rendered on screen, on paper, in speech, or on other media. It allows you to apply styles such as colors, fonts, and spacing to web documents.

#### 2. **How do you apply CSS to a web page?**

   CSS can be applied to a web page in three ways:
   - **Inline Styles:** Using the `style` attribute within HTML elements.
     ```html
     <p style="color: red;">This is a red paragraph.</p>
     ```
   - **Internal Styles:** Using the `<style>` tag within the `<head>` section of an HTML document.
     ```html
     <head>
       <style>
         p {
           color: blue;
         }
       </style>
     </head>
     ```
   - **External Styles:** Linking to an external CSS file using the `<link>` tag.
     ```html
     <head>
       <link rel="stylesheet" href="styles.css">
     </head>
     ```
 **[⬆ Back to Top](#level--easy)**

#### 3. **What is the difference between class and ID selectors in CSS?**

   - **Class Selector:** Defined with a dot (.) and can be applied to multiple elements.
     ```css
     .example {
       color: green;
     }
     ```
     ```html
     <p class="example">This is green.</p>
     <div class="example">This is also green.</div>
     ```
   - **ID Selector:** Defined with a hash (#) and should be unique to a single element.
     ```css
     #unique {
       color: blue;
     }
     ```
     ```html
     <p id="unique">This is blue.</p>
     ```
 **[⬆ Back to Top](#level--easy)**

#### 4. **How can you include CSS in a web page?**

   CSS can be included via:
   - **Inline styles** (`<p style="color: red;">Text</p>`)
   - **Internal styles** (`<style>p { color: red; }</style>`)
   - **External stylesheets** (`<link rel="stylesheet" href="style.css">`)

 **[⬆ Back to Top](#level--easy)**

#### 5. **What is the box model in CSS?**

   The box model describes the rectangular boxes generated for elements in the document tree and consists of:
   - **Content:** The content of the box, where text and images appear.
   - **Padding:** Clears an area around the content (inside the border).
   - **Border:** A border that goes around the padding (and content).
   - **Margin:** Clears an area outside the border.

 **[⬆ Back to Top](#level--easy)**

#### 6. **Explain the difference between margin and padding.**

   - **Margin:** The space outside the border of an element, used to create space between elements.
   - **Padding:** The space inside the border of an element, used to create space between the element's content and its border.

 **[⬆ Back to Top](#level--easy)**

#### 7. **What is the purpose of the `z-index` in CSS?**

   The `z-index` property specifies the stack order of elements. Elements with a higher `z-index` value will be in front of elements with a lower `z-index` value. It only works on positioned elements (position: absolute, relative, fixed, or sticky).

 **[⬆ Back to Top](#level--easy)**

#### 8. **How do you center a block element horizontally?**

   To center a block element, you can use the following CSS:
   ```css
   .centered {
     margin-left: auto;
     margin-right: auto;
     width: 50%; /* or any other width */
   }
   ```
 **[⬆ Back to Top](#level--easy)**

#### 9. **What are pseudo-classes in CSS?**

   Pseudo-classes are keywords added to selectors that specify a special state of the selected elements. Examples include:
   - `:hover` for when the mouse is over an element.
   - `:focus` for when an element has focus.
   - `:nth-child(n)` for selecting the nth child of an element.

 **[⬆ Back to Top](#level--easy)**

#### 10. **What are pseudo-elements in CSS?**

    Pseudo-elements allow you to style specified parts of an element. Examples include:
    - `::before` to insert content before an element's content.
    - `::after` to insert content after an element's content.
    - `::first-letter` to style the first letter of an element.

 **[⬆ Back to Top](#level--easy)**

#### 11. **How can you make a list not display bullet points?**

    To remove bullet points from a list, you can use the `list-style-type` property:
    ```css
    ul {
      list-style-type: none;
    }
    ```
 **[⬆ Back to Top](#level--easy)**

#### 12. **What is the difference between `inline` and `block` elements?**

    - **Inline Elements:** Do not start on a new line and only take up as much width as necessary (e.g., `<span>`, `<a>`).
    - **Block Elements:** Always start on a new line and take up the full width available (e.g., `<div>`, `<p>`).

 **[⬆ Back to Top](#level--easy)**

#### 13. **How do you use `inherit` in CSS?**

    The `inherit` value specifies that a property should inherit its value from its parent element. For example:
    ```css
    div {
      color: red;
    }
    p {
      color: inherit; /* This will inherit the color red from the parent div */
    }
    ```
 **[⬆ Back to Top](#level--easy)**

#### 14. **What does `!important` do in CSS?**

    The `!important` rule in CSS is used to add more importance to a property/value than normal. It overrides any other declarations, even if they have higher specificity. For example:
    ```css
    p {
      color: red !important;
    }
    ```
 **[⬆ Back to Top](#level--easy)**

#### 15. **Explain how CSS specificity works.**

    Specificity determines which CSS rule is applied by the browser when multiple rules could apply to the same element. It is calculated based on the types of selectors used:
    - Inline styles: 1000
    - ID selectors: 100
    - Class, pseudo-class, attribute selectors: 10
    - Type selectors: 1

 **[⬆ Back to Top](#level--easy)**

#### 16. **How do you apply multiple styles to an element?**

    Multiple styles can be applied to an element by separating each property with a semicolon:
    ```css
    p {
      color: blue;
      font-size: 14px;
      margin: 10px;
    }
    ```
 **[⬆ Back to Top](#level--easy)**

#### 17. **What is the use of `float` property in CSS?**

    The `float` property is used for positioning and formatting content, e.g., allowing text to wrap around an image. Elements can be floated to the left or right:
    ```css
    .image {
      float: left;
      margin: 10px;
    }
    ```
 **[⬆ Back to Top](#level--easy)**

#### 18. **What is the `position` property in CSS?**

    The `position` property specifies the type of positioning method used for an element. Types include:
    - `static` (default)
    - `relative`
    - `absolute`
    - `fixed`
    - `sticky`

 **[⬆ Back to Top](#level--easy)**

#### 19. **How can you make a background image not repeat in CSS?**

    To prevent a background image from repeating, use the `background-repeat` property:
    ```css
    body {
      background-image: url('image.jpg');
      background-repeat: no-repeat;
    }
    ```
 **[⬆ Back to Top](#level--easy)**

#### 20. **How do you create a responsive design using CSS?**

    Responsive design can be achieved using various techniques:
    - Media queries to apply different styles based on the viewport size.
    - Flexible grid layouts using percentages.
    - Responsive images using `max-width: 100%;`.

 **[⬆ Back to Top](#level--easy)**

#### 21. **What is the `display` property in CSS?**

    The `display` property specifies the display behavior of an element. Common values include:
    - `block`
    - `inline`
    - `inline-block`
    - `none`

 **[⬆ Back to Top](#level--easy)**

#### 22. **What does the `clear` property do?**

    The `clear` property specifies on which sides of an element floating elements are not allowed to float. Values include:
    - `none`
    - `left`
    - `right`
    - `both`

 **[⬆ Back to Top](#level--easy)**

#### 23. **How can you hide an element using CSS?**

    An element can be hidden using:
    - `display: none;` (removes the element from the document flow)
    - `visibility: hidden;` (hides the element but it still takes up space)

 **[⬆ Back to Top](#level--easy)**

#### 24. **What is the difference between `visibility: hidden` and `display: none`?**

    - `visibility: hidden;` hides the element but it still takes up space in the layout.
    - `display: none;` removes the element from the document flow, so it does not take up any space.

 **[⬆ Back to Top](#level--easy)**

#### 25. **How do you style a hyperlink to remove the underline?**

    To remove the underline from a hyperlink, use the `text-decoration` property:
    ```css
    a {
      text-decoration: none;
    }
    ```
 **[⬆ Back to Top](#level--easy)**