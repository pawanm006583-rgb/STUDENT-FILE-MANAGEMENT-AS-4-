# Student File Management System

### Node.js File System Assignment (AS-4)

A simple Node.js application that demonstrates file handling operations using the built-in File System (`fs`) module. This project performs file creation, reading, updating, renaming, and deletion using asynchronous file system methods.

---

## 📌 Project Overview

The Student File Management System is developed as part of the Full Stack Development assignment. It demonstrates how Node.js can interact with files on the local system using the `fs` module.

The application stores student information in a text file and performs various file operations sequentially, with error handling for file-related tasks.

## 🎯 Objectives

* Understand file handling in Node.js.
* Create and write data into a text file.
* Read and display file contents.
* Append new information without removing existing data.
* Rename and delete files programmatically.
* Implement error handling using callbacks.

## 🛠️ Technologies Used

| Technology         | Purpose                                                  |
| ------------------ | -------------------------------------------------------- |
| Node.js            | JavaScript runtime environment                           |
| File System (`fs`) | File creation, reading, updating, renaming, and deletion |
| JavaScript         | Application logic                                        |

## ⚙️ Features & Implementation

| Operation     | Method            | Description                                                    |
| ------------- | ----------------- | -------------------------------------------------------------- |
| File Creation | `fs.writeFile()`  | Creates `student.txt` and writes student details.              |
| Read File     | `fs.readFile()`   | Reads and displays the complete file content.                  |
| Update File   | `fs.appendFile()` | Adds experience and city without overwriting existing content. |
| Rename File   | `fs.rename()`     | Renames `student.txt` to `studentDetails.txt`.                 |
| Delete File   | `fs.unlink()`     | Deletes the renamed file after completing the operations.      |

## 📂 Project Structure

```text
Student-File-Management (AS-4)/
│
├── index.js          # Main application logic
├── package.json      # Project configuration   
└── README.md         # Project documentation
```

**Note:** The text file is created during program execution, renamed to `studentDetails.txt`, and deleted at the end. Therefore, it may not remain in the project folder after successful execution.

## 👨‍🎓 Student Information

The application stores the following information:

```text
Name: Pawan Mishra
Course: Full Stack Development
Technology: Node.js
```

##  How to Run the Project

### Prerequisites

* Node.js installed on your system.
* Visual Studio Code or any code editor.

### Installation & Execution

**Step 1:** Open the project folder in VS Code.

**Step 2:** Open the integrated terminal.

**Step 3:** Run the application using:

```bash
node index.js
```

**Step 4:** Observe the terminal output to verify the file operations.

No additional npm packages are required because the `fs` module is built into Node.js.

## ✅ Learning Outcomes

Through this assignment, I learned how to:

* Perform asynchronous file operations in Node.js.
* Use callbacks to handle successful operations and errors.
* Append data while preserving existing file content.
* Manage file names and remove files programmatically.
* Organize a Node.js project using a separate JavaScript file and documentation.

## 📝 Conclusion

This assignment provided practical experience with the Node.js File System module. By implementing `writeFile()`, `readFile()`, `appendFile()`, `rename()`, and `unlink()`, I gained a better understanding of how to manage files programmatically and handle common file-related errors.

---

**Assignment:** AS-4 — Node.js File System Operations
**Course:** Full Stack Development
**Language:** JavaScript (Node.js)
