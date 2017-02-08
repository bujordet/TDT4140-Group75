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
python manage.py runserver 8080

# Check it out!
open http://localhost:8080
```


## Setup for use
```
# Activate the environment
cd agnitio
. bin/activate

# Start the server
python manage.py runserver 8080

# Check it out!
open http://localhost:8080
```

## Use of Git
```
# Push to new bransh

git pull origin master
git checkout -b <branch-name>
git add -A (or spesific files)
git status (check that all files are staged)
git commit -m "message"
git push origin <branch-name>
```