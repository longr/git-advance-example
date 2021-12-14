# PRs, Issues, Forking, and Syncing

## Assigner
 1. Raise an Issue on this repo (upstream)
 2. Assign issue to Assignee (or yourself)
 3. Once assignee has submitted PR and tests have finished; Review and comment.
 4. Once assignee has fixed PR, approve PR.
 5. Note PR in issue and close.
 
## Assignee

1. Fork repository
2. Clone repository to local machine
3. Follow instructions in issue your are tagged in.
4. Wait for tests to run.
5. Wait for feedback from Assigner and fix code.
6. Once PR has been accepted, delete branch from your fork.
7. On your machine, swap to main branch and add upstream repo
8. Git pull upstream/main
9. Git push origin main

# python-calculator
Basic calculator functions in python


## Working in a conda environment

Make sure you have [conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) or [miniconda](https://docs.conda.io/en/latest/miniconda.html) installed.
### Create conda environment

```
conda create --name python-calculator python=3.8
```

### Activate conda environment


```
conda activate python-calculator
```


### Install dependencies


```
python -m pip install -r requirements.txt
```

## Install the package

Make sure you have activated your conda environment.

```
conda activate python-calculator
```

Then run:

```
pip install .
```

## Running tests

Make sure you have activated your conda environment. Then run:

```
python -m pytest
```
