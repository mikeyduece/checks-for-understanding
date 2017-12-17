## Week Three - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR.

1. At a high level, what is Node?

>Node is a JavaScript runtime built on Chrome's V8 engine.

2. What is Express? What is Express similar to in the Ruby world?

>Express is a lightweight framework to help organize your web application into an MVC architecture on the server side.

3. How do we setup a route when creating an API with Node and Express? Please provide a code snippet.

>`app.get('/api/v1/meals/:meal_id/foods/:food_id', data => {
    $('input[type=checkbox]').prop('checked',false);
    $(`table#${mealId} tr:not(:first-child)`).remove()
    mealFoods(data)
    }).then(() => {
        $('tr.all-total').remove()
        allTotalCal()
      })
      .then(() => {
        $('tr.all-rem').remove()
        allRemCal()
    })

})`

4. What do we use Knex for?

>Framework to make queries to the databaase and handle the promises from those queries. (`raw`, `.transaction`, `.insert`). It acts
alot like ActiveRecord in that it assissts you in manipulating the database.

5. How **could** you organize your code to follow the MVC design pattern in your Quantified Self project?

>For QS we did it as model and controller. The controller directory handled the routes and the model acted like a Ruby model class,
Instantiating the meal and food classes.

6. How do you execute raw SQL in node?

> `database.raw('SQL query')`

7. What are some advantages to having your front end and back end code live in separate applications? What are some disadvantages?

>This way they are seperate and if one breaks it won't affect the other one. The downside I think would be that it can get confusing to a
newcomer to JavaScript as to where everything is or where it should go?


#### Review

8. Describe DNS.

> a hierarchical decentralized naming system for computers, services, or other resources connected to the Internet or a private network.
It allows for translation from IP address to a more human readable form. Such as http://localhost:3000 can also be entered as 127.0.0.1 and it
is translated automatically.

9. What does writing clean code mean to you?

>SRP-Single Responsibility Principle. Applying that principle to both functions/methods and classes/files. Clearly defined variable and function/
method names, class names. Allowing for future handlers of your code to be able to understand what is going on and where.

10. If you were building an application that models hotels, what classes would you need? What classes would be responsible for what functionality? Hint: think about what tables you would need in the database, how those records would relate to each other, and good OOP.

>The hotel itself-(has_many rooms, has_many reservations, has_many Employees, has_many events, has_many departments)
 Rooms-(belongs_to a hotel, has many reservations)
 Reservations-(has_many rooms, belongs_to hotel)
 Employees-(belongs_to hotel)
 Events-(belongs_to hotel)
 Departments-(belongs_to hotel)

