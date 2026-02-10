# Notes

A web-based note-taking application built with Python and Flask, allowing users to create, edit, and organize personal notes.

## Features

- Create and save notes
- Edit existing notes
- Delete notes
- User authentication
- Responsive design
- Persistent storage

## Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (default) or configurable

## Getting Started

### Prerequisites

- Python 3.7 or higher
- pip (Python package manager)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/jknate/Notes.git
cd Notes
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
python main.py
```

5. Open [http://localhost:5000](http://localhost:5000) in your browser.

## Usage

1. **Sign Up/Login**: Create an account or log in
2. **Create Note**: Click "New Note" to create a new note
3. **Edit Note**: Click on a note to edit its content
4. **Delete Note**: Use the delete button to remove notes
5. **Browse**: View all your notes on the main page

## Project Structure

- `main.py` - Application entry point
- `/website` - Main application package
  - `/templates` - HTML templates
  - `/static` - CSS, JavaScript files
  - `views.py` - Route handlers
  - `models.py` - Database models
  - `auth.py` - Authentication logic
