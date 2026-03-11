# django-hit237-2026-week2-practicals

This repository contains the starter code for the Week 2 Django practicals. A project called `project_blog` has been created using the latest Django release.

## Setup & Installation

Follow these steps to get the project running on your machine:

1. **Clone the repository** and change into the project directory:
   ```powershell
   git clone <repo-url>
   cd django-hit237-2026-week2-practicals
   ```

2. **Create a virtual environment** (if one does not exist) and activate it:
   ```powershell
   python -m venv venv
   .\venv\Scripts\Activate.ps1   # use activate.bat on Windows cmd
   ```

3. **Install dependencies** from `requirements.txt`:
   ```powershell
   pip install --upgrade pip
   pip install -r requirements.txt
   ```

4. **Apply database migrations** (SQLite is used by default):
   ```powershell
   cd project_blog
   python manage.py migrate
   ```

5. **Run the development server**:
   ```powershell
   python manage.py runserver
   ```
   Open `http://127.0.0.1:8000/` in your browser; you should see the Django welcome page.

### Notes

* A `.gitignore` file is provided which excludes the virtual environment, database file, and other common artefacts.
* To recreate the environment on another machine, simply repeat these steps and the same package versions will be installed via `requirements.txt`.
* No app has been created yet; you can start one with `python manage.py startapp <appname>`.

Enjoy building your blog project!
