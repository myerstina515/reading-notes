# Reading Notes class 13

## Local Storage: The past, present, and future

  **1. A brief history**: 
    - User data allows web pages like internet explorer to store up to 64kb originally when Microsoft had the "only" browser. Next came Adobe in 2002, then updates to Adobe through 2008 that worked with JavaScript that would store up to 100kb data in "Local Shared Objects", followed by Google launching Gears that was an open source browser plugin that allowed browsers to store unlimited data after gaining a permission one time.
  
  **2. HTML5 storage**: 
    - Many of the current browsers support browser storage of information, so even when you navigate away from a page it still remembers you when you return. The data is stored under a key, and you can access the value with that same key. The data (value) can store any javaScript type. You can track changes made in the storage area, but it only fires when content is actually stored. It is still possible to exceed storage in HTML5, which is 5MB, and it will throw an error if you try to have more data saved than that. With our projects next week, I assume we will be adding a local storage command, which will save our app and all changes people input if it occurs on the local machine, even if the browser is closed. It will automatically save the "game" and resume once the user returns. SQL is the expected future of web based storage, and there are many different types, but browsers support all of the different versions.
