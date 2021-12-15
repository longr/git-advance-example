# PRs, Issues, Forking, and Syncing



## Assigner
1. Go to this repo: https://github.com/longr/git-advance-example/
2. To raise an issue:
   1. Click on `Issues` just under the repository name.
   2. Click on `New Issue`, it is green button on the right.
   3. Select one of the 3 template issues by clicking `Get Started` next to them.
   4. Edit the title to add your github username to the end so the title is similar to: `[FEATURE] Add division function USERNAME`
   5. Click `Submit new issue`
3. To assign the issue to someone:
   1. Click on the issue.
   2. On the right it says `Asssignees`.  Click on the cog symbol next to this.
   3. Type the username of the person you wish to assign the issue to in the box.
   4. Click on the desired username in the box that appears (a tick should appear once you click on them)
4. Once assignee has submitted PR, and tests have finished comment on the issue.
5. Once tests pass, approve PR.
  
 1. Raise an Issue on this repo (upstream)
 2. Assign issue to Assignee (or yourself)
 3. Once assignee has submitted PR and tests have finished; Review and comment.
 4. Once assignee has fixed PR, approve PR.
 5. Note PR in issue and close.
 
## Assignee

1. Go to this repo: https://github.com/longr/git-advance-example/
2. Fork repo:
   2. Click on `Fork` near the top right to fork the repository
   2. If it asks "Where should we fork" click on your username
2. Clone repository to local machine:
   1. Go to the repository, it shoudl be https://github.com/YOUR_USERNAME/git-advance-example/
   2. Click on green `Code` button.
   3. Select SSH.
   4. Click on copy button.
   5. On your computer, in a terminal type: `git clone <line copied from github>`
   6. Move (`cd`) into the newly created directory.
3. Follow instructions in issue your are tagged in to fix the code.
4. Use git to `add`, `commit`, and `push` the code.
5. Create pull request:
   1. Go to your forked repository in GitHub.
   2. Click on `Contribute` button.
   3. Click on "Open Pull Request".   Type a meaning full comment.  You can include keywords such as "resolves #issue-number-you-were-assigned in the title or description to link to your issue.
5. Wait for tests to run.
6. Wait for feedback from Assigner and fix code.
   1. On your local machine make the changes needed to the code.
   2. Using git, `add`, `commit`, and `push`
   3. This will update the PR
7. Once PR has been accepted, delete branch from your fork. `git branch -d <local-branch>
8. On your machine, swap to main branch and add upstream repo ` git add remote upstream git@github.com:longr/git-advance-example.git`
8. Fetch updated main on upstream `git pull upstream main`
9. Push changes to your fork `git push origin main`

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
