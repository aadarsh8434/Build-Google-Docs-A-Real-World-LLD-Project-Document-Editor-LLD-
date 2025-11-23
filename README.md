# 📝 C++ Document Editor

This project is a simple **Document Editor** implemented in C++.  
It demonstrates the use of **OOP concepts**, including:

- Abstraction  
- Polymorphism  
- Inheritance  
- Composition  
- Strategy Pattern (Persistence Layer)

The editor supports:
- Adding text  
- Adding new lines  
- Adding tab spaces  
- Adding image placeholders  
- Rendering the final document  
- Saving the document to a file  

---

## 📌 Features

### ✔ Add Text  
Add any text string to your document.

### ✔ Add New Line  
Insert a line break.

### ✔ Add Tab Space  
Add a tab (`\t`) before a line.

### ✔ Add Image  
Adds an image **placeholder**:

[Image: picture.jpg]


(Real images cannot be displayed in terminals; they are shown as text.)

### ✔ Save Document  
Automatically saves everything to:



---

## 📂 File Output Example

This is what your editor generates:

document.txt


---

## 📂 File Output Example

This is what your editor generates:



Hello, world!
This is a real-world document editor example.
Indented text after a tab space.
[Image: picture.jpg]


---

## 🚀 How to Run

### 1️⃣ Compile the program

```bash
g++ builddoc.cpp -o builddoc

2️⃣ Run the executable
./builddoc

3️⃣ Generated output file



🧠 Concepts Used

Abstract classes

Virtual functions

Dynamic dispatch

Polymorphism

Strategy Pattern for saving (FileStorage, DBStorage)

Encapsulation of document elements

📌 Future Enhancements (Optional)

Add bold/italic text support

Add PDF export

Implement GUI using Qt/SFML

Add real image rendering using OpenCV

Add undo/redo functionality



