# TDT4140-Group75
============

## Dependencies

* Python3.5
* virtualenv

## Initial setup
```
# Clone the repo
git clone git@github.com:Solveiglu/TDT4140-Group75.git

# Create a virtual environment
python3 -m venv agnitio

# Activate the environment
cd agnitio
. bin/activate

# Perform database migrations
python manage.py migrate

# Collect staticfiles
python manage.py collectstatic

# Start the server
python manage.py runserver 0.0.0.0:8080

# Check it out!
open http://localhost:8080
```
