## Week Two - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR.

1. What's one difference between ES5 and ES6?

>ES6 has arrow funciton with implicit returns and ES5 does not

2. What's the difference between asynchronous and synchronous JavaScript?

>Synchronus, operates each function one at a time. Async fires all the functions
at once. Only handling the results of each function once the result is available.

3. What are the four pillars of Object Oriented programming?

>Encapsulation, Abstraction, Polymorphism, Inheritance

4. What are some tools available in JavaScript to help you write object oriented code?

>classes with constructor functions, libraries that we can inherit from to use already written code.

5. What are some key concepts to be aware of when refactoring your JavaScript?

>I'm not sure I understand the question. I would assume some of concepts that need to
be taken into consideration for refactoring would be the usualy code smells. Long conditional blocks,
long functions, long parameter list, commented out code...

6. What's a callback function and what are some reasons when we use/need callback functions?

>Callback function is when you call a function with the (). It denotes a function that you want to call in a certain place or order.
They are also useful because you write the function once, and then can use that funciton again and again by calling it somewhere else.

7. What are the different scopes of variables in Javascript? When would you want to define global variables?

>global and local(function). So far I've used global variables for things that I want to have access to in every function.
ie. jQuery libray or other libraries. Calling other files, or assigning the base url for api calls.

8. What's the difference between `==` and `===` in JavaScript?

>`==` is a soft equal.  It will allow '1' to equal 1 because it attempts to make
both sides the same type(string or number) and then compares them. Where as `===` is a strict equal and compares type along with value.

9. Why do front end frameworks exist?

>Add structure to your code/app with complex user interactions.


#### Review

10. Why do people say "HTTP is stateless"?

>Because it is. HTTP doesn't hold state. It 'mimicks' state by passing information in the query params. The server isn't required to hold the states
of the user and its requests over multiple requests. This allows for fast less complex request response cycles.

11. Describe a RESTful API.

>A restful is a data paradigm that is used for convention over configuration. It uses the commom HTTTP verbs to point
to the basic corresponding controller and action from the router.

12. What are some main characteristics of a team following an agile workflow?

>Working code. Not waiting for the entire project to be finished before demo'ing to client. Less documentation in favor of working code.
REsponding to change as collaboration with client/customer changes needs and wants of the app

13. What are some advantages **and** disadvantages to using OAuth to authenticate a user?

>Adv- don't have to hand roll login with security. Secure in the fact that they have tested their authentication against malicious attacks.
DisAdv would be not being able to see what is going on and being able to fix something if it were to break.

