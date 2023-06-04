Added picture for a better grade.

# Leverenz Portfolio

I will use this website to showcase my work to potential employers.

This has been resolved:  
Please Note: When viewing the live link, one of the images does not display.  I could not figure out how to fix it prior to the assignment's due date and time.  It works when I view the html through VS Code!

This is how I resolved it in my CSS:  
.subtitle {  
  display: flex;  
  text-align: right;  
  vertical-align: bottom;  
  height: 250px;  
  ### //Picture displays in live link and not VS Code  
  background-image: url("./assets/images/sunset2.jpg");  
  
  ### //Picture displays in VS Code and not live link  
  background-image: url("../images/sunset2.jpg");  
  background-size: cover;  
  background-position: center;  
}  

## Description

When a user opens the page they are presented with the my name, and links to sections about me, their work, and how to contact them.

When a user clicks one of the links in the navigation the UI scrolls to the corresponding section.

When a user clicks on the link to the section about my work the UI scrolls to a section with titled images of my applications.

When a user is presented with the developer's first application that application's image should be larger in size than the others.

When a user clicks on the titles of the applications, they are taken to that deployed application.

When a user resizes the page or views the site on various screens and devices they are presented with a responsive layout that adapts to my viewport.

## Getting Started

### Dependencies

N/A

### Installing
N/A

### Executing program

N/A

## Help

N/A

## Authors

Contributors names and contact info

David Leverenz
david.leverenz@gmail.com

## Version History

* 1.0 5/16/2023 Initial Release

## License

N/A

## Acknowledgments

Special thanks to Poornima, my instructor, who patiently worked with me on certain alignment problems.
