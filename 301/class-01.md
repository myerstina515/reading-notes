# Reading Assignment 1: Responsive Web Design and Floats

## 1. Shay Howes Intro to RWD

  - A. Responsive Web Design is a website that is designed to work on all sizes of screens, from laptop, to desktop, to mobile phone. Responsive websites changes based on may different factors, while adaptive websites are built to a preset list of factors. Lastly, mobile refers to a separate website built for only mobile devices. RWD is broken into three components: Flexible Layouts, media queries, and flexible media.
  - B. Flexible Layouts: Building a layout with a flexible grid. They are not made to work with fixed measurements like pixels and inches, but rely on percentages and ems (in the form of: target/context = result). By using percentages and ems, it means no matter how large the screen, the container will always be in the same relative positioning from device to device.
  - C. Media Queries: By using at @media rule, it avoids any additional HTTP requests. Media queries each include a media type, such as all, TV, screen, braille, and with HTML5 newer technology such as 3-D glass. "and", "not", and "only" are three logical operators used in media queries and allows extra conditions to be added. Height and width as wel as minimum and maximum values are the most common in media queries. "orientation" specifies if the screen is landscape or portrait, Aspect ratio of a screen is the pixel width/pixel height and is represented with a number (such as 16/9). Resolution refers to the number of dots per pixel or dots per centimeter, 
  - D. Mobile First: Includes styles set for smaller viewports, and advocates design toward a mobile users experience. 
  - E. Viewport: Some websites require a little extra assistance in adapting a website for mobile use, and apple has come up with a meta tag called "viewport" that helps with this. The same things can beb adjusted with viewport, including height/width, resolution, and scale, and values can be combined.
  - F. Flexible Media: Making sure media is flexible in size is important too, as if the website has adjused to different sizes, the media doesn't necessarily follow, but can with max-width of 100%. Unfortunately, embedded media does not follow suit, and requires the embedded content to be placed inside of a parent element, and have the parent element adjusted.
  
## 2. All about Floats

  - A. "Float" is a positioning property that keeps the element in the flow of the page, and text wraps around it, but it gets pushed to one side or the other. It's sister property is "clear" which moves the element to there isn't another one on one side or the other (or both). 
  - B. The Great Collapse: If a parent element contains nothing but floated elements, it will collapse, or have no height, and will appear as a single horizontal line.
  - C. Techniques for Clearing Floats: The empty div method (there is literally an empty div element with the style set to clear: both), the overflow method (setting the overflow CSS property to auto or hidden, and the parent element will expand to contain the floats), and the easy clearing method (which uses a pseudo class selector ":after" and will apply for only a small amount of content).
  - D. Problems with Floats: Floats are a little bit fragile, and has issues that will occur sometimes: 1. "pushdown" happens when the element is wider than it's parent element, it will pushdown what is supposed to appear next to it. Fixed with "overflow: hidden". 2. "double margin bug" if you apply a margin in the same direction as the float, it will double the margin size (fixable with display: inline), 3. "3px jog" moves the float mysteriously by 3px. 4. bottom margin bug, when the bottom margin on child elements will be ignored by the parent element. 
  
## 3. Don't overthingk it Grids

  - A. Bookmarked!
  - B. Most websites are built with a grid of some sort, even if it isn't a grid per se. This page briefly addresses how to create grids and some minor troubleshooting. It's bookmarked in my browser, and I will refer to it as needed!
  
## 4. CSS floats explained by riding an escalator: 

  - A. I have taken and passed 201, but I am reviewing as recommended in the assignment info.
  - B. Floats create "alternate flows". The escalator comparison refers to the page, people can block the entire aisle, which is what happens when you don't use floats. When you use floats, you are staying on your side and people can pass if they choose. "clear: both" refers to resetting the flow of the document so left, right, and center can be applied again for future elements. 
  
## 5. SMACSS documentation:
  - A. Scalable and Modular Archetecture for CSS
  - B. It is bookmarked in my browser now as recommended, but to summarize, it is a style guide and a way to think about the design to create flexibility instead of a rigid framework. 
  - C. By categorizing CSS rules into 5 types, we can see patterns and set practices around them. The five categories are base, layout, module, state, and theme. Each one builds on the previous without overlapping, so Base is the basic things you want to apply across the board, such as margin, a basic color, padding, and the like. 
  - D. Layout refers to the overall layout of the major elemets such as header, footer, and body, moving sidebars and content, as well as navigation bars. Module is the more discrete layout, such as child elements and sometimes modules sit within other modules. States override all other styling, and occur with a change of state, either an element opening after being hidden, or an error. The theme defines the different colors and styles that give your webiste it's feel. 





