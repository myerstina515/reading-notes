# Reading Notes Class 11

## ESJ tutorial Video 1-5 (EJS stands for embedded JavaScript)
  1. Intro to: overview: Discussing the video series and the videos (6 at the time of creation). Injecting a variable using express inside a route, using queries, loops, and if/else statements. Using a form to add and edit things, handlebars/layouts, and partials will finish up the videos.
  
  2. Getting started: Building the page from scratch: npm init, npm install some things (express, body-parser, cors, ejs), setup the page as we did in class (require express, etc), 
    app.use(bodyParser); 
    app.set('views', path.join(__dirname, 'views'));
    (dirname means to concatenate the directory name with the string "views")
    app.listen(8000, function() { console.log('heard on 8000')};
    app.get('/', function(req, res) {response.render('index' {
    ); });
  
  3. Injecting values into the views: 
    foo: 'bar'
    <%= %> (means I'm going to evaluate a variable for you in HTML)
    
  4. For Loops and Arrays: 
    people: [{name: 'dave' }
             {name: 'jerry'}]
    \<ul><%= for(var person of people){ %> <li> <%= person.name %> </li> <% } %>
  
  5. If/Else Statements: 
      \index.html
      \<ul> 
      <% if(person.name === 'dave') { %>
      \<li>This is definitely <%= person.name %>!!!
      \</li>
      <% } else { %>
      \<li>This is definitely not dave!! This is <%= person.name %>!!
      \</ul>

  6. EJS tutorial (the second one) is bookmarked and I skimmed through it, though I feel like the video tutorial was more helpful.
