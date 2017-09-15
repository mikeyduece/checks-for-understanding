1. How do we make flash messages display on a page?
>Set a flash hash `flash[:notice] = 'Some string!'` and then iterate through in the application layout to be able to describe across the app

2. Where is cart information/temporary information usually stored?
>In a session `session[:cart]` 

3. What might be some reasons not to store cart in our database? Are there any reasons why we would want to persist that information?
>For something as small as what we're working with, it would really slow down the database having to make those calls each time the user wants to look at it. But for something like Amazon, they have super servers and are able to store that database that way you can access your cart on any machine anywhere that has an internet connection.

4. What is the purpose of the asset pipeline?
>To speed up page loading by concatinating css and js.  It also sets flags that let a page now whether or not it has the lastest styling and scripts.

5. Why do we precompile our assets?
>To allow it to be used in the asset pipline.

6. What do each of the following tags do?

```ruby 
<%= stylesheet_link_tag "application" %>
<%= javascript_include_tag "application" %>
<%= image_tag "rails.png" %>
```
>`stylesheet` links to the applicaitons stylesheet in the assets folder unsually.
`javascript` links to the js folder, in the assets folder.
`iamge` links to the image folder where the app can access images that are saved locally in the assets folder

7. What are some of the elements of a great read me? What are some of the benefits of taking the time to update a readme for our project?
>Clear instrutions, maybe some personality. Links to known issues and how to fix them. A good readme, can grab someones attention and have them use your product and be happy with it. A happy customer will tell 1-2 ppl about their experience but an unhappy one will tell at least 10.

8. What are the top four accessibility issues that we as developers should be aware of?
>`alt` images for the visually impaired, Being able to simplify the page for users with something like ADD, and allowing for better navigation without a mouse.

9. `before_save` is an example of a what? Where in our Rails application would we find a `before_save`?
>callback. In terms of what we did yesterday in the exercise, we needed to set an attribute before the record was saved. But didn't have the information needed until it was already entered by a user. `first_name` `last_name` and using the `call_back` to set the `full_name` `before save`.
10. Given the following object, how would we create a scope for all users who are active?

```ruby 
User.create(name: "Happy", active: true)
```
scope :users {active: true}

11. What is the difference between a scope and a class method?
>Scope is only available to those that are scoped into allowing that attribute. Like scoping or namespacing an admin to give them more functionality over a regular user who doesn't have those permissions.
