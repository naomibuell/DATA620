# Data 620: Web Analytics

This is a repository for publishing Data 620 assignments.

This repo can create a python environment with the below commands:

```
python -m venv data620env
source data620env/bin/activate
pip install -r requirements.txt
```

or

```
.\data620env\Scripts\Activate.ps1
pip install -r requirements.txt
```

To install a new package, it only requires 2 commands:
1. Install the package like normal
2. Update the requirements.txt file

These steps can be done with the commands below:

```
pip install <package_name>
pip freeze > requirements.txt
```