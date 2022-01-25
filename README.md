# Accessibility Refactor

## Introduction
The marketing agency, Horiseon, had the desire to refactor their codebase to make it more accessible and optimized for SEO. Kudos to Horiseon for this worthy goal towards long term sustainability! These are two items that all websites should work on regularly to make the internet a better place!

Increasing accessibility on your site is not only a nice feature for your customers who have diabilities, but you can also avoid legal issues that may arise down the road. It also comes with increased functionality in regards to SEO

Specifically, Horiseon requested the following improvements be made:

- Use of semantic html elements
- Elements follow a logical structure
- Use of alt attributes on all icons and images
- Heading attributes fall in sequential order
- Contains a consise, descriptive title


## Improvements
In order to be able to read through the html and css, I've added comments throughout both files. Doing this allowed me to follow the scout rule by leaving the code better than I found it. 

The use of the div element was excessive on this page. Semantic html elements such as header, nav, section, article, aside, and footer have been added in an appropriate order to optimize the site for SEO.

The broken link in the navigation has been repaired and now links to its appropriate section.

Alt tags have been added to all icons and images on the page. I found the hero image to be a little tricky as it's a background image within the CSS file and adding an alt tag isn't as easy when the image is set up like this. I found a work-around by utilizing the aria-label attribute within the appropriate class as this will work for most screen readers.

One of the most time intesive tasks was simplifying the css code. I found the classes to be over-utilized when an id would have worked just a well. I also condensed several classes into one. As the site stands now, I could have removed some of the classes altogether but made the decision to keep them in tact for potential updates to their site in the future. Again, the scout rule!

The title has been updated and is more descriptive of their site. 

![Screenshot](https://user-images.githubusercontent.com/96760168/150904103-1fc06f18-779b-4e63-825c-6cd872e84f66.png)


## Resources

The finished product can be found [here](https://rochelledavis.github.io/accessibility-refactor-c1/)
