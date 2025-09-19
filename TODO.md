# Deployment Steps for PythonAnywhere

1. Create a PythonAnywhere account if you don't have one.
2. Upload the entire project folder to PythonAnywhere (use the Files tab or upload via bash).
3. In the Web tab, create a new web app, select Flask, and set the Python version to 3.10 or compatible.
4. Set the WSGI configuration file path to: /home/yourusername/projectname/wsgi.py (replace with your actual path).
5. In the Web tab, under "Environment variables", set ADMIN_USERNAME and ADMIN_PASSWORD_HASH if needed (or use defaults).
6. Ensure the 'uploaded_payslips' and 'temp' directories exist and are writable (use bash: mkdir -p uploaded_payslips temp; chmod 755 uploaded_payslips temp).
7. Reload the web app.
8. Test the app by accessing the URL provided by PythonAnywhere.
