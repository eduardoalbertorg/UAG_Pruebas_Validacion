# How to use static analysis on a python file

Assuming the user is on Windows 10 OS

1. Install python 3.10+
2. Make sure to add the env variable to path
3. Open a terminal where the file is located
4. Install pylint:
```
python -m pip install pylint
```
5. Run the linter using the sample python file in this repo:
```
python -m pylint static_code.py
```
6. You should be able to see the errors in the code