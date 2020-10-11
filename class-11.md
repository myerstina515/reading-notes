# Reading Notes Class 11

## 1. Duckett HTML

   - **Chapter 16 "Images" (p406-427)**
      1. You can control all aspects of image presentation including size. Specifying the size helps pages to load better becasue the code ususally loads before the iamges do, so they automatically load at the right size, instead of having to change once it has already loaded. If you have lots of images on the page, giving them classes like small, medium, large, can help to limit the number of sizing changes that need to be done in the CSS. Images can be added on their own or in line with another tag (like paragraph, for example), and they will appear inline with the content. Then they can be moved to the right, left, or center.
      2. The developer can use images as a background as well, either for the entire page or only part of a page. The background-image property also allows things like gradients to be used in the background. An image can also be used over and over in the background or for a border by using the background-repeat property.
      3. Background-position changes the overall position of the image (top, center, or bottom, as well as left, center, or right. The positions get combined to go over 9 different positionings). Images can also be edited with photo editing software to make them lighter and more appropriate for use as a background.
   
   
   - **Chapter 19 "Practical Information" (p476-492)**
      1. Search Engine Optimization: Trying to get your site to show up nearer the top of the search engine results. To do this, there are on and off page techniques. On page, there are 7 places to try to put keywords that will help people find your page better. In the page title, the URL, any headings, the text (repeating keywords at least 2-3 times, but not overusing them), link text, image alt text, and page descriptions (in the head). Off page, linking other related websites to yours, and putting real related text between the "a" tags for the link. It's very helpful to sit down and come up with your keywords before trying to optimize, and plan out exactly what and where in the site they should go.
      2. Analytics: How are people using your site? Google analytics is one method people use to find out exactly what poeple dowhen they come to your site. It will track how many visits, how many unique visits (different people), time spent on site, etc. It will tell you what they are looking at, where they find your page from (external links, search engines, and so many more features.
      3. Domain names and web hosting: In order to put your webpage online, you need a domain name (which usually costs an annual fee). Web hosting refers to web servers, that are special computers that connect to the internet all the time. There are lots of different hosting companies that offer different space, backups, and email accounts.
   
   
## 2. MDN article:

   - **Article on audio and video elements**
      1. In HTML5, there is a way to embed video and audio. To place a video in the HTML for the page, the tag "video controls" is used which gives a space to add video from the local machine or provides a link if the browser is unable to play the video. the HTMLMediaElement API provides features that let you control video and audio players on the screen — for example HTMLMediaElement.play(), HTMLMediaElement.pause(), etc. With these elements, button elements need to be added as well, the appearance of the buttons from CSS is relatively basic and doesn't require much, but the javaScript is more complex to make it functional. In addition to adding the attributes and making things visible or not, a listener is built in to listen for each button click with a function added so the player knows what to do when a button is clicked. 
      2. There are so many small nuances to the coding for a media player that I will need to be bookmarking this article to further refer back when adding media. I feel that reading about it is one thing, but this will need to be practiced before I will have a full understanding of it all. There is a way to add more functionality than discussed in the article, the author uses an example of the time lapsed dsplay breaking if the time reaches longer than one hour, but it is a very interesting article about audio/video insertion to a webpage.
   
   
   
   
   
   
