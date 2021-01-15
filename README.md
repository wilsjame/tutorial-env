# 12.2. Creating Virtual Environments
https://docs.python.org/3/tutorial/venv.html

## Workflow
A common directory location is `.venv`
```
$ python3 -m venv [project-dir/.venv]
```
On Unix or MacOS
```
$ source project-dir/.venv/bin/activate
````
Confirm commands are python3
```
$ python --version
$ pip --version
```
Upgrade package, if needed
```
$ python -m pip install --upgrade pip
```
Install packages
```
$ python -m pip install chess

$ pip show chess
$ pip list
```
List installed packages in the format `pip install` expects
```
$ pip freeze > requirements.txt
```
Remove packages from the virtual environment
```
$ pip uninstall [one or more package names]
```
Shutdown
```
$ deactivate
```
