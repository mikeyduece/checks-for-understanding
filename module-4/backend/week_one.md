## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR.

1. What's the most useful thing you learned from completing the intermission week work?

>That I can make the connection between Ruby and JS and apply those changes pretty well.

2. What are some tools to help debug JavaScript code?

>Debugger, console.log(), breakpoints

3. What are some tools you need in order to unit test your JavaScript?
<<<<<<< HEAD

>Mocha, Chai, npm, node modules

4. What is the syntax for invoking a function?

>functionName()

5. What is CORS?

>Cross Origin Resource Sharing, allows resources to be shared to another domain,
outside of the current domain.

6. How do we enable CORS?

>As part of the headers in the ajax call => Access-Control-Allow-Origin

7. What's `this` in JavaScript?

>Similar to ruby self. it refers to the current spot in the code that it is referring to in the scope fo the function.

8. What is Webpack and why is it useful?

>A module bundler. Its main purpose is to bundle JavaScript files for usage in a browser, yet it is also capable of transforming, bundling, or packaging just about any resource or asset.

9. When/why do you want to use event delegation?

>When you may have multiple 'buttons' that require an event listener. This way
you don't have to have the listener on each button, you can set the listener to
the parent element.

10. What's `npm` and what do we use it for?

>Similar to Ruby gems, it allows the use of a library or code written by someone
else so you're not reinventing the wheel  when writing your program. Node Package Manager


#### Review
11. What's the MVC design pattern? Describe each part of MVC.

>Model- The factory that can potentially make the objects and call methods on that object/class.
View- Takes the information provided from the controller, to create the html you're wanting to display
Controller- the traffic cop. it takes the url parameters from the http request,
based on that it goes to a certain controller and action. In that controller and action, it
then calls the model to get any information required from that request. Once that
information is gathered, it sends that to the view to build and populate the html.
The view then sends that back to the controller which then sends all of that back to
the router in an http response.
12. What are a few ways to optimize a Rails application?

> Caching, eager loading, background workers, chron jobs...

13. What's a background worker? When would we want to use a background worker?

>It allows a user to continue browsing your site when they and others have initiated
a ceratin amount code that would normally cause the program to stop and wait for the block of code to
finish running before moving on to the next step since Ruby is single threaded
=======
4. What is the syntax for invoking a function? Give an example.
5. What's `this` in JavaScript?
6. What is Webpack and why is it useful?
7. When/why do you want to use event delegation?
8. What's `npm` and what do we use it for?

#### Review  
9. What's the MVC design pattern? Describe each part of MVC.
10. What are a few ways to optimize a Rails application?
11. What's a background worker? When would we want to use a background worker?
>>>>>>> 621032c32b613355c852f5ffe0f3d8fef36a3691
