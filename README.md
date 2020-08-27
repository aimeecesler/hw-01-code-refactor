# Homework Assignment 1: HW-01-CODE-REFACTOR
This repository contains my refactoring of the Horiseon company website. My goal was to not only create a better functioning website but to also ensure that it is compliant with all ADA requirements.

## Table of Contents
* [Installation](#installation)
* [Usage](#Usage)
* [Refactoring Process](#Refactoring-Process)
* [ADA Compliance](#ada-compliance)
* [What I Learned](#what-i-learned)
* [Acceptance Criteria](#acceptance-criteria)
* [Credits](#credits)
* [Badges](#badges)
* [Links](#Links)
* [License](#license)

## Installation
1. Follow the GitHub Repository Link in the [Links](#Links) section below.
1. Clone the repository using an SSH key.
1. Open GitBash and use "git clone" to clone the repository.

## Usage
Edit using VSCode after [installation](#installation). HTML and CSS files are provided.

HTML

![HTML](HTML.PNG)

CSS

![CSS](CSS.PNG)

## Refactoring Process
During the refactoring process I made the following changes to the HTML and CSS code:
* Updated the title for a more descriptive option
* Changed all div elements to their appropriate corresponding semantic elements for ADA compliance.
    * Header
    * Nav
    * Figure
    * Main
    * Section
    * Aside
    * Footer
* Added alt text to all images on the pages that accurately described each image for ADA compliance.
* Corrected the in-page link for the Search Engine Optimization Navigation Button to function.
* Consolidated CCS selectors and properties where applicable to clean up the CSS document.
* Reorganized all CSS items to follow the HTML elements semantic structure for ease of reading.
* Added descriptive comments to all HTML and CSS items for easier editing.
* Moved the main website image from the CSS page to the HTML page to be consistent with other images.
* Renamed the image class from "hero" to "figure" for better description of the element.
* Updated the background color on the aside section for ADA contrast compliance.

## ADA Compliance
This webpage was run through the [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/) to ensure compliance. There were no errors detected.

![WAVE RESULTS](WAVE.PNG)

## What I Learned
1. I had no idea that there were so many things involved with making a website ADA compliant behind the scenes, it is a very interesting and detailed world that I am sure we have only scratched the surface of!

1. There are also 10,000,000+ ways to do the same thing and none of them are wrong.

1. If you stare at code for long enough, you will always find something you want to change.

## Acceptance Criteria

GIVEN a webpage meets accessibility standards :heavy_check_mark:

WHEN I view the source code :heavy_check_mark:

THEN I find semantic HTML elements :heavy_check_mark:

WHEN I view the structure of the HTML elements :heavy_check_mark:

THEN I find that the elements follow a logical structure independent of styling and positioning :heavy_check_mark:

WHEN I view the image elements :heavy_check_mark:

THEN I find accessible alt attributes :heavy_check_mark:

WHEN I view the heading attributes :heavy_check_mark:

THEN they fall in sequential order :heavy_check_mark:

WHEN I view the title element :heavy_check_mark:

THEN I find a concise, descriptive title :heavy_check_mark:

## Credits
A big thank you to Jon Canales, Sami Sully and the rest of our Discord study group!


## Badges
![badge](https://img.shields.io/github/issues-raw/aimeecesler/hw-01-code-refractor)

## Links
[Repository Link](https://github.com/aimeecesler/hw-01-code-refactor)

[Deployed Application](https://aimeecesler.github.io/hw-01-code-refactor/)

## License
Copyright (c) [2020] [Aimee Corbin Esler]

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
