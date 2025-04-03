# Student Data Management System

A Flask-based web application for managing student records with JSON storage, CRUD operations, real-time search, and Excel integration.

## 🚀 Core Features

### 📂 Student Data Management
- Stores student records in `students_data.json`.
- Basic fields: **Name, Course, Roll Number, Section, Year, CGPA**.
- Supports additional **custom fields**.
- Data persistence using **JSON storage**.

### 🌐 Web Interface (`templates/`)
- `index.html` → **Main form** for adding new students.
- `view_students.html` → **List all students** with search capability.
- `edit_student.html` → **Edit existing student records**.
- `statistics.html` → **View analytics and statistics**.
- `add_field.html` → **Support for custom fields**.

### 🔑 Key Features (`app.py`)
- **CRUD operations** (Create, Read, Update, Delete) for student records.
- **Excel import/export** functionality.
- **Real-time search filtering**.
- **Statistical analysis**:
  - Total students
  - Average CGPA
  - Course/year distribution
- **Custom field support**.

### 🛡️ Data Validation
- **Required field validation**.
- **CGPA range checking** (0-10).
- **File format validation** for Excel imports.
- **Input sanitization** and **type checking**.

### 🎨 UI Features (`static/css/style.css`)
- **Responsive design**.
- **Search functionality**.
- **Sortable tables**.
- **Flash messages** for user feedback.
- **Modern CSS styling with animations**.

## 📌 Installation & Usage

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/student-data-manager.git
   cd student-data-manager
   ```

2. **Create Virtual Environment (Optional)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

   **Create requirements.txt file**
 - Add the following dependencies to your requirements.txt file:
    ```bash
    Flask==3.0.0
    openpyxl==3.1.2
    ```

5. **Run the Application**
   ```bash
   python app.py
   ```
   Open your browser and go to `http://127.0.0.1:5000`

## 🤝 Contributing
Pull requests are welcome! Feel free to contribute and improve this system.

---
💡 Built with **Flask** | 📄 JSON Storage | 📊 Excel Integration


