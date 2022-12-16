# Horiseon Webpage Refactor

## Description

In order to deepen my understanding my understanding of how HTML, I refactored code for the Horiseon webpage for better readability within the HTML and CSS. Within the Horiseon Webpage, I found that many of the HTML elements used were non-semantic. This can make it unclear for other developers to discern different parts of the webpage. By adding semantic HTML elements, I was able to improve upon the readability of base code for the Horiseon. As I made changes to the HTML document, I made sure to reflect the changes within the HTML document as well so that the website looks visibly the same.

Criteria:
- Change non-semantic HTML elements to semantic ones
- Ensure that elements follow a logical structure
- Website meets accessibility standards
- Give the website a concise, descriptive title

## Table of Contents

- [Installation](#installation)
- [Refactoring](#Refactoring)
- [Technologies Used](#TechnologiesUsed)
- [License](#license)

## Installation

N/A, In order to access the website visit: 
https://dbbensan.github.io/Horiseon-code-refactor/

## Refactoring

### Issue #1: Change non-semantic HTML elements to semantic ones
- Throughout the HTML document there were multiple HTML elements that were not semantic nor logically structured. These div class were replaced with a semantic HTML element to improve readability of the code.  

**Before:**<br/>
![Original Non-Semantic HTML elements](https://github.com/DBBENSAN/Horiseon-code-refactor/blob/main/assets/images/refactorImages/nonSemanticHTML.PNG?raw=true)

**After:**<br/>
![Refactored HTML to meet Semantic guidelines](https://github.com/DBBENSAN/Horiseon-code-refactor/blob/main/assets/images/refactorImages/refactoredCode.PNG?raw=true)

### Issue #2: Ensure that elements follow a logical structure
- We see a breakdown of how these HTML heads have been changed to follow a more logical structure: nav, div, and main communicate what each HTML elements content to other developers. 

**Before:**<br/>
![Original non-structured page](https://github.com/DBBENSAN/Horiseon-code-refactor/blob/main/assets/images/refactorImages/LogicalStructureB4.PNG?raw=true)

**After:**<br/>
![Refactored Code to meet logical structure](https://github.com/DBBENSAN/Horiseon-code-refactor/blob/main/assets/images/refactorImages/logicalStructureAFTER.PNG?raw=true)

### Issue #3: Website meets accessibility standards
- The website did not have alt-text for the images being presented in the page. By adding these alt attributes throughout each image, I was able to improve the accesibility of the website. These alt attributes can interact with screen readers and have the description of the image be read outloud.

**Before:**<br/>
![Images with no Accessibility Standards](https://github.com/DBBENSAN/Horiseon-code-refactor/blob/main/assets/images/refactorImages/altAttBefore.PNG?raw=true)

**After:**<br/>
![Refactored to have alt attribute for images](https://github.com/DBBENSAN/Horiseon-code-refactor/blob/main/assets/images/refactorImages/refactoredAltAfter.PNG?raw=true)

### Issue #4: Give the website a concise, descriptive title
- Upon first loading the page, the Title for the page is simply "Website" this is non-descriptive and the company's name was used for the title instead.

**Before:**<br/>
![Original Website Title](https://github.com/DBBENSAN/Horiseon-code-refactor/blob/main/assets/images/refactorImages/Titleb4.PNG?raw=true)


**After:**<br/>
![Website Title Changed](https://github.com/DBBENSAN/Horiseon-code-refactor/blob/main/assets/images/refactorImages/WebsiteTitleAfter.PNG?raw=true)

## TechnologiesUsed

Resources:
https://www.w3schools.com/html/html5_semantic_elements.asp
https://www.w3schools.com/html/html_elements.asp
https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML
https://css-tricks.com/snippets/css/a-guide-to-flexbox/

## License

Copyright <2022> <Daniele Bensan>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
