 the first thing do is to:
 1. create your folder
 2.secondly you initialise using this code on mac:  uv init -p 3.12
 3. uv venv
 4.source .venv/bin/activate
 5.uv add pandas numpy matplotlib jupyterlab notebook ipykernel
 6.python -m ipykernel install --user --name=myenv --display-name ".venv (Python 3.12)"
 7. create file :
 test.ipynb
 8. select in the test.ipynb page "select kernel"
 9. Cmd + Shift + P
 choose : Reload Window



 1. create your folder
2. uv init -p 3.12
3. uv venv
4. source .venv/bin/activate
5. uv add pandas numpy matplotlib jupyterlab notebook ipykernel --active
6. python -m ipykernel install --user --name=myenv --display-name ".venv (Python 3.12)"
7. create test.ipynb
8. select kernel
9. Cmd + Shift + P
 choose : Reload Window
