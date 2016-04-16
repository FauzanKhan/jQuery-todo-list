# jQueryTodoList
UI component for a todo list

### Description
* The visitors can simply add and remove tasks.
* Visitors can also mark an incomplete task as complete and a complete task as incomplete task.
* User can mark all tasks as finished or incomplete
* Whenever a user adds a new task the task is kept highlighted for a few seconds
* Users can create a new task either by clicking Add Task Button or by hitting Enter Key
* A notification is displayed whenever users create a task, delete a task or marks a task as complete/incomplete

### Create Task Interaction
* A user can create a task by clicking ```+``` button at the bottom of the list.
* When the ```+``` button is clicked, a panel is displayed for entering new task.
* The panel consist of ```<textarea>``` which is focused by default and is brought into the view port as soon as user clicks on the ```+``` button
* User can enter the description of the new task in ```<textarea>``` and can create the task either by hitting enter or by clicking on the ```Add Task``` button.
* The newly added task is highlighted for a few seconds before it gets mixed with existing tasks.
* A notification is also displayed on successful creation of a new task.

### Dependecies
* jQuery

### Project Structure

```
|---public (contains compiled css & minified JavaScript files)
|    |- --css 
|    |- --javascript
|---src (contains scss files for styling and unminified JavaScript files)
|    |---scss
|    |---javascript
|---index.html
|---gulpfile.js

```

###Customization
* You can easily customize the look and feel of the todo list by changing the variables in the ```theme.scss``` in ```src/scss/``` folder.

* Run ```gulp sass``` to compile your scss

###Demo
visit <a href="http://fauzankhan.github.io/jQuery-todo-list/">http://fauzankhan.github.io/jQuery-todo-list/</a> to see the Todo list in action.
