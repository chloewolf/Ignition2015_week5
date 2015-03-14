#### Deliverables for week 5 Rails MVC
##### Odin Project Routing Guide Questions:
- What is the "Root" route?
    - "Root" is the root (home) directory of your project.
- What are the seven RESTful routes for a resource?
      - index  
      - show  
      - edit  
      - new  
      - create  
      - update  
      - destroy 
- Which RESTful routes share the same URL but use different verbs?
      - index
      - new
      - show
      - edit
- How do you specify an ID or other variable in a route?
      - id is prepended with a colon, other variables can be prepended with a forward-slash.
- How can you easily write all seven RESTful routes in Rails?
      - resources :posts
- What is the Rails helper method that creates the HTML for links?
      - link_to <br>
##### Odin Project Views Guide Questions:
- What is a layout?
    - layouts are the rendered template in the controller, it holds things that you need in all of your webpages   
- What's the difference between a "view template" and a "layout"?
    - view template is the actual webpage, the layout is common code across the webpages
- What is a "Preprocessor"?
    - preprocessors are run before HTML   
- Why are preprocessors useful?
    - preprocessors provide additional information for the program that can be read as normal css, javascript and html files
- How do you make sure a preprocessor runs on your file?
    - name it with a preprocesser like .erb and rails will read it before the other code    
- What's the outputted filetype of a preprocessed *.html.erb file? What about a *.css.scss file?
    - .html.erb will be read as HTML and .css.scss will be read as CSS
- What is the difference between the <%= and <% tags?
    - <%= displays whatever is returned inside the ERB tags, and <% wont display anthing in your HTML template
- What is a view partial?
    -  partials are just HTML files that aren't meant to be complete (partially complete) but can be shared by other files
- How do you insert a partial into your view?
    - you make a new partial file (?) 
- How can you tell that a view file is a partial?
    - partials just need to be prepended with an underscore
- How do you pass a local variable to a partial?
    - :locals 
- What's the magical Rails shortcut for rendering a User? A bunch of Users?
    - render the user object directly, <%= render @users %> 
- What are asset tags and why are they used?
    - asset tags grab image files 

##### Link to Odin Project Basic Routes, Views and Controllers repo: [my odin repo](<https://github.com/chloewolf/week-5-app>)
##### Link to Hartl's Rails Tutorial Chapter 5 repo: [my hartl's repo](https://github.com/SenorJpolicar/testy-)
