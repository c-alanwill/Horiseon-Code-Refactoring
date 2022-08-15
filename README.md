# Horiseon Code Refactoring

## Description

* This repository represents a refactoring of the codebase for the Horiseon website so that it follows accessibility standards and to help optimize it for search engines.  This will help so that people with disabilities can access the website using assistive technologies such as video captions, screen readers, and braille keyboards.

* The website before refactoring had HTML code written without certain HTML tags for accessibility standards and for search engine optimization.  Prior to refactoring, the CSS code was not displayed in the same order as the HTML code.  The refactoring aimed to fix both these parts of the HTML and CSS.

* The refactoring created a logical structure for the elements of the page in creating sections for the header, hero image, content, sidebar and footer and the HTML code within them.

* A header and footer section were added to the HTML code and the code was refactored in those sections.

* The heading attributes were refactored to fall in sequential order.

* A title was added to the head of the HTML page with the company name, "Horiseon Code Refactoring".

* A main section was created in the HTML code to contain a section for the main content of the page and a section for the sidebar of the page.

* Notes were applied to both the HTML and CSS code to identify each section of code for the header, hero image, content, sidebar and footer.

* The refactoring added Alt attributes for each image in the HTML text to provide a description if for some reason the user cannot view the image due to a slow connection, an error in the src attribute, or if the user uses a screen reader.

* In the refactoring, the CSS selectors and properities were consolidated and reordered to match the semantic structure of the HTML elements in newly refactored layout. 

## Installation

* The project is currently running on Github server.  It can be viewed at:

The code used on this page is HTML and CSS.  There is an index.html file to view the code.  Images relating to the page are contained under the "images" folder.

## Usage

The following image demonstrates the web application's appearance and functionality:

  ```md
      ![Horiseon refactored web page](./assets/images/horiseon-webpage.jpg)
  ```
**Note**: This webpage was originally built with layout for desktop viewing. This layout was not changed in this refactoring.  Currently, the elements are not properly spaced if resolution of device has a width smaller than 768px. 

## Credits

N/A

## License

Please refer to the license in the repo.

