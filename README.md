# todo-list
## JavaScript PROJECT: Todo-list
### About 
 *JavaScript Todo List helps you create a list of things you want to do throughout the day ,week or year. Suppose you want to do something throughout the day that you can list here. Whenever you complete that task then you can delete it.*
 ### Assignment
1. Your ‘todos’ are going to be objects that you’ll want to dynamically create, which means either using factories or constructors/classes to generate them.
2. Brainstorm what kind of properties your todo-items are going to have. At a minimum they should have a `title`, `description`, `dueDate` and `priority`. You might also want to include notes or even a checklist.
3. Your todo list should have `projects` or separate lists of `todos`. When a user first opens the app, there should be some sort of ‘default’ project to which all of their todos are put. Users should be able to create new projects and choose which project their todos go into.
4. You should separate your application logic (i.e. creating new todos, setting todos as complete, changing todo priority etc.) from the DOM-related stuff, so keep all of those things in separate modules.
5. The look of the User Interface is up to you, but it should be able to do the following:<br>
 a. view all projects<br>
 b. view all todos in each project (probably just the title and duedate.. perhaps changing color for different priorities)<br>
 c. expand a single todo to see/edit its details<br>
 d. delete a todo<br>
6. You should add some persistence to this todo app using the Web Storage API.<br>
 a.localStorage [docs here](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API/Using_the_Web_Storage_API) allows you to save data on the user’s computer. The downside here is that the data is ONLY accessible on the computer that it was created on. Even so, it’s pretty handy! Set up a function that saves the projects (and todos) to localStorage every time a new project (or todo) is created, and another function that looks for that data in localStorage when your app is first loaded.<br>

