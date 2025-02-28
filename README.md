# Streamlit

This directory comprise some notes on `Streamlit`: a free and open-source 
framework to rapidly build and share beautiful machine learning and data science 
web apps. It is a Python-based library specifically designed for machine learning engineers.

## Environment

In order to create a new virtual environment and to install 
the required packages one needs to run the following commands.

### **`MacOS` and `Linux`**

```Bash
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

### **`WindowsOS`**

- `PowerShell` CLI :

    ```PowerShell
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

- `Git-Bash` CLI :
    ```
    python -m venv .venv
    source .venv/Scripts/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
