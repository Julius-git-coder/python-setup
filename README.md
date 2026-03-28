 the first thing do is to:
 1. create your folder
 2.secondly you initialise using this code on mac:  uv init -p 3.12
 3.uv add pandas numpy matplotlib jupyterlab notebook ipykernel
 4.uv venv
 5.source .venv/bin/activate
 6. create file :
 test.ipynb
 7. select in the test.ipynb page "select kernel"
 8.python3.12 -m venv .venv
 9.source .venv/bin/activate
 10.python -m pip --version
 11.python -m pip install ipykernel
 12.python -m ipykernel install --user --name python_second --display-name ".venv (Python 3.12.13)
 13. Cmd + Shift + P
 choose : Reload Window