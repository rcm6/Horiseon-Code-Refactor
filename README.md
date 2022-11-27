# 01 HTML CSS Git: Code Refactor 

## Description
The task was to refactor the existing webpage for 'Horiseon Social Solution Services, Inc.' to make it accessible by accomplishing the following: 
* Ensure that all links are functioning correctly.
* Clean up the CSS to make it more efficient by consolidating CSS selectors and properties and organizing them to follow the semantic structure of the HTML elements.
* Including comments before each element or section of the page.

### User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

### Acceptance Criteria

Your website must meet accessibility standards. You can achieve this completing the following:

* Semantic HTML elements can be found throughout the source code
* HTML elements follow a logical structure independent of styling and positioning
* Image and icon elements contain accessible `alt` attributes
* Heading attributes fall in sequential order
* Title elements contain a concise, descriptive title

## Validation
HTML checked with: [https://validator.w3.org/](https://validator.w3.org/)

CSS checked with: [https://jigsaw.w3.org/css-validator/](https://validator.w3.org/)

Colour contrast checked with: [https://webaim.org/resources/contrastchecker/](https://validator.w3.org/)

## Changes
Semantic elements added following logical structure.

Comments added.

Links made functional.

Title added.

Heading attributes arranged in sequential order.

HTML cleaned up, trailing slashes on void elements removed.

CSS cleaned up, styles consolidated.

Alt attributes on decorative image and icon elements given a null text alternative (alt="") as per [WAI guidelines](https://www.w3.org/WAI/tutorials/images/decorative/#example-4-image-used-for-ambiance-eye-candy).

Background color of sidebar failed WCAG 2 Contrast and Color Requirements, changed from [#2589bd](https://webaim.org/resources/contrastchecker/?fcolor=FFFFFF&bcolor=2589BD) to
[#227BAA](https://webaim.org/resources/contrastchecker/?fcolor=FFFFFF&bcolor=227BAA)

## Installation
N/A

## Usage
N/A

## Credits
N/A

## License
N/A