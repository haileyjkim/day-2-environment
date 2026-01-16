1. Create/clone your project repository and open it in VSCode.
2. Open a new Bash terminal and create a virtual environment:
   ```bash
   python3 -m venv .venv
   ```
3. Activate the virtual environment:
   ```bash
   source .venv/bin/activate
   ```
4. Install a package (pandas) using pip:
   ```bash
   pip install pandas
   ```
5. Create a requirements.txt file to track dependencies:
   ```bash
   pip freeze > requirements.txt
   ```
6. Stage, commit, and push changes to GitHub:
   ```bash
   git add .
   git commit -m "Add pandas and requirements.txt"
   git push origin main
   ```