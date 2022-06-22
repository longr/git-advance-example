---
name: Add multiplication function
about: Instructions on adding a multiplication function to the calculator package
title: "[FEATURE] Add multiplication function"
labels: enhancement, help wanted
assignees: ''

---

Use this checklist to tick off sub-tasks as you complete them following these:

- [ ] Create new `<username>_multiply` branch
- [ ] Add **`multiply`** function
- [ ] Add **multiply** test
- [ ] Commit changes and push to GitHub
- [ ] Make pull request
- [ ] Close issue


## Instructions

###  Create branch

Create a new `<username>_multiply` branch from `main` to work in.

Hint: `git checkout -b <branch name>`
### Add multiplication function

Create a new `<username>_multiply.py` file in the `pythoncalculator/` directory.

```python
def multiply(x, y):
    return x + y
```

### Add multiplication test

Create a new `test_<username>_multiply.py` file in the `tests/` directory.

Add the following code and save:

```python
from pythoncalculator.<username>_multiply import multiply


def test_multiply():
    assert multiply(10, 3) == 30
```

### Commit your changes and push to GitHub

Once you've created your function and test files, commit your changes. 

Use `resolves #{ISSUE_NUMBER_YOU_WERE_ASSIGNED}` in your commit message to automatically close the issue when your pull request is merged.

Then push them up to GitHub

### Create pull request

Finally, create a pull request back to the `main` branch on GitHub and wait for the owner's review.

Reference the issue your pull request refers to with `#{ISSUE_NUMBER_YOU_WERE_ASSIGNED}` in the description. 

Respond to any requests for correction.

### Close issue

If the issue didn't close automatically, close it yourself. You can also 
