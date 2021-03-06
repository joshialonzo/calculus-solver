# calculus-solver
Web application where we collect a set of calculus solvers. We automate the step-by-step solution of several math problems that we can find in a high-school calculus course.

## Install development setup

```bash
# create python environment
python3.9 -m venv venv

# activate environment
. venv/bin/activate

# deactivate environment
deactivate

# see the current virtual environment
env | grep VIRTUAL_ENV

# upgrade pip command
pip install --upgrade pip

# install flask
pip install Flask==2.0.3
```

## Run Server

```bash
# Run Flask with flask command
export FLASK_APP=app
flask run

# Run Flask with bash script
bash run_flask.sh
```

## Test Server

```bash
curl -l http://localhost:5000/
```