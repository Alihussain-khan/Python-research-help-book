# Python-research-help-book
Commands and Tools to remember

- python -m pytest -v test_public.py



# installing new libraries in venv 
- python -m venv venv (creates new venv)
- .\venv\Scripts\activate (to activate on powershell)
- pip install matplotlib numpy opencv-python scikit-image jupyter (inside the venv installer)

# to call the local interpreter 
- python -m pip install <package>


# installing from the requirements.txt file 
- .\venv\Scripts\activate
- pip install -r requirements.txt


# convert ipynb to pdf
- jupyter nbconvert --to pdf your_notebook.ipynb
- python -m nbconvert --to pdf notebook.ipynb


## for 3.11 
- py -3.11 -m venv .venv
- .\.venv\Scripts\Activate.ps1

## to run elastisearch 
- .\bin\elasticsearch.bat
