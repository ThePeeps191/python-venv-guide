# Python Virtual Environment Guide

1. Create the virtual environment
Run **one** of the following in the project folder:

```bash
python -m venv venv
# or
python3 -m venv venv
```

---

2. Activate the virtual environment

**Windows (PowerShell)**
```bash
venv\Scripts\activate
```

**Windows (Command Prompt)**
```bash
venv\Scripts\activate.bat
```

**Mac / Linux**
```bash
source venv/bin/activate
```

When activated, you should see `(venv)` in your terminal.

---

3. Install dependencies (if applicable to your project)

```bash
pip install -r requirements.txt
```
