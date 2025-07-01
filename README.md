# To-Do List Application

A simple desktop-based To-Do List application built using **Java Swing**. It allows users to add and remove tasks in a user-friendly GUI environment.

---

## Features

* **Add Task**: Enter a new task into the list.
* **Delete Task**: Remove a selected task from the list.
* **Interactive GUI**: Built using Java Swing for a responsive and intuitive interface.
* **Task Persistence (in memory)**: Maintains tasks during runtime using an `ArrayList`.

---

## Technologies Used

* Java (JDK 8+)
* Java Swing (for GUI components)
* AWT Event Handling

---

## Project Structure

```
TodoListApp.java  // Main class with GUI and event handling logic
```

---

## How to Run

### Prerequisites

* Java JDK 8 or higher
* IDE (like IntelliJ, Eclipse, NetBeans) or Command Line

---

### Running via IDE

1. Open the project in your Java IDE.
2. Run the `TodoListApp.java` file.
3. The GUI window will appear with task input and buttons.

---

### Running via Command Line

1. Open terminal and navigate to the project folder.
2. Compile the Java file:

   ```bash
   javac TodoListApp.java
   ```
3. Run the compiled class:

   ```bash
   java TodoListApp
   ```

---

## Sample UI Flow

* **Add a Task**:
  Type a task in the input field and click **Add Task** or press **Enter**.

* **Delete a Task**:
  Select a task from the list and click **Delete Selected**.

---

## Future Improvements

* Save and load tasks from a file or database.
* Add deadlines and priority levels to tasks.
* Allow editing of existing tasks.
* Implement task categories and filters.
* Add keyboard shortcuts for faster access.

