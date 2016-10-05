# To Do List | Rails

### Description

* A To Do list with list and task resources.

#### Expectations

* RESTfuls routes and CRUD processes for each resource (list and task)
* Nested routes for tasks
* Partials, redirects, form helpers, route helpers

#### Additional Features:

* On the index page, let users mark tasks as done without deleting them. Think about setting a done attribute when an object is created and then updating the task's done attribute to true when the user designates it's complete.
* Use scopes in the model (class file) to retrieve all of the done and not done tasks. Then call these methods from the view to display the data. In other words, don't put something like Task.where(:done => false) or conditional if statements into your views . Instead, create methods in your model for Task#done and Task#not_done, and then call those methods.

