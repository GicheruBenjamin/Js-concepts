## JavaScript Concepts

Some JavaScript concepts are kind of confusing but successfully demonstrated in this projects in this repo.

##### Projects
1. [To-Do List]
2. [Stop watch]
3. [Calculator]
4. [Color pallete picker] 


[To-Do List]: ./todo-list
- Closures: The taskManager function creates a closure over the tasks array, keeping the task list encapsulated.
- this Keyword: Inside event listeners, this refers to the button that triggered the event.
- DOM Manipulation: Adding, deleting, and displaying tasks dynamically.

[Stop watch]: ./Stopwatch
- Hoisting: Declaring intervalId before it is used.
- Closures: The stopwatchManager function maintains access to seconds and intervalId.
- Event Loop: Understanding how setInterval and clearInterval work asynchronously.

[Calculator]: ./calculator
- == vs ===: Shows how == allows type coercion, while strict equality (===) avoids it.
- Scope: Ensures proper variable scoping with let and const.
- Immutability: Prevents reassignment of op within the switch block.

[Color pallete picker]: ./colorpallettepicker
- Arrow function: No `this` context issues.
- DOM Manipulation: Dynamically creates and styles elements.
