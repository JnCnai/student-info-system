## Student Information System

A robust, cloud-ready Student Information System built in Python with a clean separation of concerns, persistent JSON data storage, comprehensive logging, and full CRUD capabilities.

## Features Implemented

- **Complete CRUD Operations:** 
  - Add new students with auto-generated unique IDs.
  - View all student records or search for specific students by ID.
  - Update existing student information dynamically.
  - Delete student records securely with confirmation prompts.
- **Data Persistence:** Automated data storage and retrieval using JSON (`data/students.json`).
- **Cloud-Ready Modular Architecture:** Strict separation between the command-line user interface (`main.py`), the backend data engine (`student_service.py`), and data models (`student.py`).
- **Logging & Error Management:** Real-time event tracking and audit trails for all data modifications, backed by robust exception handling for file I/O operations.
- **User Experience Enhancements:** Built-in empty-database validation to prevent invalid queries and guide user interaction.

## Project Structure

```text
student-info-system/
├── src/
│   ├── models/
│   │   └── student.py
│   ├── services/
│   │   └── student_service.py
│   └── main.py
├── data/
│   └── students.json
├── logs/
│   └── app.log
└── README.md
```
