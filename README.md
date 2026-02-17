## Programmer Assessment Q4

This repository contains a broken web app built with Dash. Please follow the tasks below.

1. Fork or clone this repo.
2. Fill missing dependencies and author section in `pyproject.toml`, fix any other problems if exists.
3. Fix bugs prevent the app `main.py` from running, or cause any errors if the app is running.
4. Change port the app ruuning on to `10030`.
5. Update `README.md` with an instruction about how to run this app:
   1. Choose either Arch Linux or Fedora Linux, and don't mess with the system `python` environment.
   2. Use a modern python package manager that respects `pyproject.toml` and `.python-version`, rather than `pip`.
   3. Setup virtual environment, start the app, and access the app.
6. Commit and push all the changes, and provide a link to your own repo in your submission in the last.

## Instruction about how to run this app:
1.  Install a Modern Python Package Manager
   - Use Poetry to manage Python versions and dependencies.
   - Poetry respects pyproject.toml and .python-version, unlike pip.
2. Setup Virtual Environment
   - Install project dependencies:

     poetry install
   - Activate the virtual environment:

     poetry shell
   
   This ensures all dependencies are isolated from the system Python environment.
3. Run the Dashboard
   - Inside the virtual environment:
     
      poetry run python main.py
   - You should see output similar to:
     
      Dash is running on http://127.0.0.1:10030/
4. Access the App
   - Open your web browser and go to:
     
      http://127.0.0.1:10030/
     
      You can now interact with the Clinical Analytics Dashboard.
