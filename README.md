# Student Data Management System

---

A simple desktop application for student data management, featuring a login system and CRUD (Create, Read, Update, Delete) functionalities for attendance and grade data. This application is built using the Tkinter graphical library and manages data in CSV format.

## ✨ Features

* **Login System:** Users must log in with a username and password stored in `login.csv`.
* **Student Data Management (CRUD):**
    * **Show All Data:** Displays all student data from `presensi.csv` in a table.
    * **Delete Data:** Deletes selected student data rows from the table.
    * **Add Data:** Adds new student data to `presensi.csv`, with validation to prevent duplicate NIM (Student ID) or Name.
    * **Replace Data:** Replaces existing student NIM and Name data.
* **Grade Management:**
    * **Input Nilai (Input Grades):** Allows entering exam grades (Exam 1, 2, 3) for students based on NIM and Name, with grade validation (0-100).
    * **Calculate Avg Nilai (Calculate Average Grade):** Calculates the average exam grade for a specific student.
* **Graphical User Interface (GUI):** Built using the Tkinter library for easy interaction.
* **CSV Data Storage:** Login and student attendance/grade data are stored in CSV files (`login.csv` and `presensi.csv`).

## 🚀 Technologies Used

* **Python 3**
* **Tkinter:** Python's standard library for creating graphical user interfaces.
* **`csv` module:** For reading and writing CSV files.
* **`tkinter.messagebox`:** For displaying information and error messages.
* **`tkinter.ttk`:** For modern-styled widgets (e.g., `Treeview` for tables).

## 💻 Installation & Setup

To run this application on your local machine, follow these steps:

1.  **Ensure Python is Installed:**
    Make sure you have Python 3 installed on your system. You can download it from [python.org](https://www.python.org/).

2.  **Clone the Repository:**
    If this project is on GitHub, clone the repository:
    ```bash
    git clone [https://github.com/jeremyfasollasido/Basic-Student-Data-Management.git](https://github.com/jeremyfasollasido/Basic-Student-Data-Management.git)
    cd Basic-Student-Data-Management
    ```
    Alternatively, you can download the project files directly.

3.  **Ensure Dependencies Are Installed:**
    Tkinter and the `csv` module are typically included with standard Python installations. You do not need to install additional libraries for this project.

4.  **Prepare CSV Files:**
    The application requires two CSV files in the same directory as `main.py`:
    * `login.csv`: Contains usernames and passwords for login.
        * Example format:
            ```csv
            admin,password123
            user,qwerty
            ```
    * `presensi.csv`: Contains student data (NIM, NAMA, Nilai Ujian 1, Nilai Ujian 2, Nilai Ujian 3).
        * Example format (important: headers must be exactly as shown):
            ```csv
            NIM,NAMA,Nilai Ujian 1,Nilai Ujian 2,Nilai Ujian 3
            12345,Budi Santoso,80,75,90
            67890,Siti Aminah,90,85,95
            ```
        * Ensure this file has headers exactly as specified (`NIM`, `NAMA`, `Nilai Ujian 1`, `Nilai Ujian 2`, `Nilai Ujian 3`).

5.  **Run the Application:**
    Open your terminal or command prompt, navigate to the directory where `main.py` is located, and then run:
    ```bash
    python main.py
    ```

## 🌐 Usage

1.  The application will display a login window. Enter a username and password found in `login.csv`.
2.  Upon successful login, you will enter the main menu.
3.  Use the available buttons to:
    * View all student data.
    * Add new student data.
    * Delete student data.
    * Replace student data.
    * Input student exam grades.
    * Calculate a student's average grade.
    * Exit the application.

## 📸 Screenshots (Optional)

You can add screenshots here to provide a visual overview of your application.

---
[Image of Login Window]
*A brief description of what this screenshot shows.*

[Image of Main Menu]
*Another brief description.*

[Image of Student Data Display]
*Another brief description.*
---

## 👋 Contributing

Contributions are welcome! If you have suggestions or find issues, please open an issue or submit a pull request.

## 📄 License

This project does not have an explicit license defined. You can add your preferred license (e.g., MIT, GPL) here.

## 📧 Contact

Jeremya Tampubolon - [jeremiatampubolon025@gmail.com](mailto:jeremiatampubolon025@gmail.com) | [LinkedIn](https://www.linkedin.com/in/jeremya-tampubolon-a0681829a/)
