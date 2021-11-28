
## 01 HTML, CSS, and Git: Code Refactor


## Refactoring

**Refactoring** existing code (improving it without changing what it does) to meet a certain set of standards or to implement a new technology.


## Use Case

A marketing agency wanted to refactor their website to make it more aceessible. An increasingly important consideration for businesses, web **accessibility** ensures that people with disabilities can access a website using assistive technologies like video captions, screen readers, and braille keyboards. Accessibility is good for business&mdash;for one thing, accessible sites rank higher in search engines like Google. It also helps companies avoid litigation, which might arise if people with disabilities can't access a website.

Refactoring should also take into consideration **TAM** which stands for "Total available Market" or "Total Addressable Market" to describe business opportunity associated with some action, product or service. Increasing your customer base represent larger opportunity to grow.


## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## CodeBase

Original Code is uplaoded to [Week1 Folder](codebase). The folder includes [original CSS](codebase/Develop/assets/css/style.css) and [original HTML file](codebase/Develop/index.html) and [original photos](codebase/Develop/assets/images)

## Modifications

Transformation of the html code to a sementic one entails adding meaningful tags like \<header\>, \<article\>, \<aside\> and \<footer\>. They will be incorparted into the html structure as parent container included some of the defined \<div\> elements that identiy styling. By doing so, we logically seperated the code into abstracted sections which will give meaning to sections of the page without losing any of the styles used. 

Meta decsription tag is used to enhance the chance of this website to appear in search engines based on keywords used in the description.


```
- Addition of meta description tag to the html code to provide information about website content and increases the likelihood of appearing in search engines.
- Inclusion of <header> tag before the first <div class="header"> to comply with semantic html
- Inclusion of <footer> tag at the very end and modification of its heading to be h4
```

## Second set of Modifications

```
- Modification of title as well to reflect the main of business and its service offerings
- After checking styling and orientation, removal of the <div class="header"> and the use of <header> tag instead
- modification of sytle.css to change the .header to header since style is applied to an element not a class
- Sub-Dividing the html body into <header> <main> and <footer> to compy with semantic html requirements
- Inclusion of the benefit information into <aside> element since they can be taken out of this website and used anywhere else
- to reduce the coding needed, grouping of some css selector together seeing that they share the same values:
	- .benefit.lead , .benefit.brand and .benefit cost
	- .serach-engine-optimization, .online-reputation-management and .social-media.marketing
	- 




