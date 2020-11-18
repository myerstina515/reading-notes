# Reading Notes Class 13

## Sending Form Data

1. Client/server architecture: It begins by going over the response/request cycle as we do every morning in class. On the client side, the action attribute defines where the data gets sent, similar in design to a url. The method attribute defines how data gest sent, for example with "get" or "post". "Get" tells the server, I want this source, while "post" says send me back a result to this data. 
2. Server side: Raw PHP can be returned, python can be used to do the same thing. It just displays the submitted data on the webpage. There are many other languages that do the same thing, such as express, that we have been using, Ruby, Django, and Laravel.
3. The enctype attribute lets you specify the value of the Content-Type HTTP header included in the request generated when the form is submitted. If you want to send files, you have to set method to post, set  enctype to multipart/form-data, and inlduce one or more <input type="file">.
