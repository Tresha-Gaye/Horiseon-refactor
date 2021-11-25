# Code Refactor Starter Code

The purpose of this project is to refactor the codebase of the Horiseon landing page so that it meets accessibility standards and is optimised for search engines.

View the deployed application by [clicking this link](https://tresha-gaye.github.io/Horiseon-refactor/).

## Goals

**Both goals were achieved by the following methods:**
- by ensuring that all images have `alt` descriptions. 
- by substituting semantic HTML elements such as `section`, `nav`, `header` and `footer` for numerous, non-descriptive `div` elements. 
- by ensuring that all links worked efficiently. 
- by consolidating and reorganizing CSS sectors and properties. 
- by including comments before each element or section of the page.  

## Technologies

**The primary technologies used were:**
1. Visual Studio to create HTML and CSS files.
2. Git Bash command line interface. 

## History

**Header and Navigation**
- I used the semantic `header` tag to demarcate the information at the very top of the page. 
- I used `nav` semantic element to differentiate and encapsulate the hypertext anchors and also ensured checked to make sure the IDs matched source and destination. 

![Horiseon header and navigation bar](./assets/images/horiseon-header.jpg) 

**Hero**
- This presented a challenge because I couldn't find the source image, which was actually located in style.css as an svg file. I broke the page until I located and corrected it in the codebase.

![People in a meeting](./assets/images/hero-pic.jpg)

**Footer**
- The footer was the simplest section to address, by substituting the semantic `footer` for the more wordy elements previously used, minimizing the code. 

![Creator and copyright information](./assets/images/horiseon-footer.jpg)

**Main content section**
- I utilized semantic elements here as well by differentiating the parent `section` from its `div` children to make it easier to read and optimise searches. 
- I utilized common `class` and `id` attributes to consolidate the code.
- I added 'alt' text to the images as an accessibility feature.

![Features](./assets/images/main-content.jpg)

**Lead generation section**
- This section could have been called the 'secondary content' section, but I thought it was more important to specify the actual content. 
- I used emplty 'alt' references so that the text reader would not waste time reading these icons. 

![benefits](./assets/images/lead-gen.jpg)

## Contributing

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)

## Credits

**The following resources were used to complete this project:**
1. UCONN Coding Bootcamp's modules on HTML and CSS
2. README content article [FreeCodeCamp.org] (https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)
3. README style article from [Github Docs] (https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#relative-links) 

## License
[GNU](https://opensource.org/licenses/GPL-3.0)
