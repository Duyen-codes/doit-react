# Todo app

A CRUD app with create, read, update and delete operation

[Live Demo](https://doit-react.vercel.app)

## App's user stories

As a user, I can

- read a list of tasks.
- add a task using the mouse or keyboard.
- mark any task as completed, using the mouse or keyboard.
- delete any task, using the mouse or keyboard.
- edit any task, using the mouse or keyboard.
- view a specific subset of tasks: All tasks, only the active task, or only the completed tasks.

## Built with

- HTML
- CSS
- React
- [Nano ID](https://www.npmjs.com/package/nanoid): unique string ID generator for JavaScript
- Responsive design

## Notes for myself

### Accessibility attributes implemented:

- aria-pressed tells assistive technology (like screen readers) that the button can be in one of 2 states: pressed or unpressed. Setting a value of true means that the button is pressed by default.
- visually-hidden
- role="list" for ul element
- aria-labelledby attribute gives the list a more informative context
- defaultChecked={true} tells React to check this checkbox initially
