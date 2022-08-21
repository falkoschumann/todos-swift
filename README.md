# Todos

A simple app for managing todos, following the example of [TodoMVC](https://todomvc.com).

## User Stories

### Create Todo

- Focus new todo text field on startup.
- If there are no todos, only display text field for new todo.
- Remove spaces before and after text and only create todo if text is not empty.

### Show Todos

- Show all todos.
- Show only active or completed todos.
- Display number of active todos.

### Edit Todo

- Edit a todo in the list by double-clicking and focus text field.
- When editing a todo, only show text box for editing.
- Save the change with `Enter` or if you lose focus and cancel the change with `Escape`.
- Remove spaces before and after text and delete todo if text is empty.

### Complete Todo

- Mark a todo in the list as completed or active.
- Strikethrough out a completed todo.
- Mark all todos as completed or active.

### Remove Todo

- Remove a todo from the list.
- Hover over todo shows the remove button.
- Remove all completed todos.
- If there are no completed todos, the remove completed button is hidden.

## Messages

### Commands

- Add todo (title)
- Toggle todo (id)
- Toggle all (checked)
- Destroy todo (id)
- Clear completed
- Save todo (id, title)

### Queries

- Select todos -> (id, title, completed)\*

### Notifications

N/A

### Events

N/A
