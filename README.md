# Beeboo User Guide

<img width="905" alt="Screenshot 2024-09-16 at 10 54 18 AM" src="https://github.com/user-attachments/assets/614ec9fb-6803-4883-bec8-f87c772997cf">

Beeboo is a easy to use app used to manage your tasks, be it todos, deadlines or events.

## Table of contents

1. [Quick Start](#-quick-start)
2. [Features](#-features)
   - [Todo](#-adding-todo)
   - [Deadline](#-adding-deadline)
   - [List](#-adding-events)
   - [Find](#-list)
   - [Mark/Unmark](#-mark-or-unmark)
   - [Deletion](#-deletion)

### Quick Start
1. Ensure you have Java 17 or above installed in your Computer.
2. Download the latest .jar file from [Beeboo.jar](https://github.com/rubinnn/ip/releases/tag/A-Jar)
2. Double click to open the app, it should immediately open the app for you to use.
### Features

#### Adding Todo
Example:
```
todo read book
```
This will prompt a message telling you that the task is added to the list.As such

```
added: [T][] read book
You have [size of list] tasks in the list
```
#### Adding Deadline
A deadline is a task with a time constraint.So a date and time has to be added to have the constraint.
This is done by adding /by YYYY-MM-DD time.Example:
```
deadline return book/ by 2024-09-30 1900
```
Example output:
```
added: [D][] return book (by 30 sep 2024 6:00pm)
You have [size of list] tasks in the list
```
#### Adding Events
Events are tasks that are from 1 time to another time. So another additional time constraint is added with /from ... /to
Example:
```
event meeting /from 2024-09-30 1800 /to 2000
```
Example output:
```
added: [E][] meeting (from 30 sep 2024 6:00pm to 30 sep 2024 8:00pm)
You have [size of list] tasks in the list
```
#### List
You call list to get your list of tasks
```
list
```
Example output:
```
1. [T][] read book
2. [D][] return book (by 30 sep 2024 6:00pm)
```
#### Find
searching keyword through using 1 of the description words
```
find book
```
Example output:
```
1.[Relevent tasks with book in the description]
```
#### Mark or Unmark
Marking or unmarking the task at a certain index to label it as done or not done.Example:
```
mark 1
```
Example Output:
```
Nice! I've marked this task as done: [task at 1st index]
```
#### Deletion
Deleting the item at a specific index.Example
```
Delete 1
```
Example Output:
```
Ok I have removed the following item
[T][X] read book
You have [size of list] tasks left;
```
