# animal_trading_cards


## Table of Contents

* [Project Description](#project_description)
* [Project Specification](#project_specification)
* [Code Description](#code_description)

## Project Description

A simple web page with a picture of animal and some description.
HTML contains at least two things:

- A hyperlink (a element) that links to another web site.
- An image (img element) that includes an image from another web site.


## Project Specification 


Design Specifics
Page resembles card from design prototype.

- The text is italicized for the animal’s interesting fact.
- The labels are bolded for the animal’s list items.
- The dots are removed from the animal's list items.
- Uses border around animal’s name, image, and information (interesting fact, list items, and description).
- Uses border around animal’s information.
- Uses spacing between animal’s name, image, and information.
- Card width should be fixed and include the spacing around the image (Since image is 300px wide, card should be 300px + spacing on either side. Card should not expand with the browser window).

- The placeholder image and information is replaced with favorite animal image and information.
- The image is 300px wide or the image's width is set to 300px.
- The image’s alt is relevant to the animal used.

Code Quality


CSS Classes
- The HTML includes classes that are used for styling.
- Classes are given meaningful names.
- Separation of Concerns
- Separate HTML from CSS by linking to stylesheet.
- HTML code does not include <style> elements or style attributes in the body.

Code Quality

- Code is ready for review, meaning new lines and indentation are used for easy readability.

### Code Description

Separates HTML from CSS by linking to stylesheet.
```
	<link rel="stylesheet" href="styles.css">

```

Use list tag "li" to make a required list.
  
```
<ul>
				<!-- your favorite animal's list items go here -->
				<li><span>Size</span>: 1,8 m long, 0,7 m height</li>
				<li><span>Weight</span>: up to 20 kg</li>
				<li><span>Skull</span>: was up to 25 cm long</li>
				<li><span>Bone outgrowths</span>: stretched along from 4-10 vertebrae</li>
</ul>
```

Dots are removed from the animal's list items (CSS).
```
ul {
    float: left;
    /*The dots are removed from the animal's list items.*/
    list-style: none;
    padding-left: 0;
}
```

The labels are bolded for the animal’s list items.
```
span {
  
    font-weight: bold;
}   
```
Use validator at https://validator.w3.org/ to check code.      
