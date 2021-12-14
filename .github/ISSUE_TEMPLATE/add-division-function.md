---
name: Add division function
about: Instructions on adding a division function to the calculator package
title: "[FEATURE] Add division function"
labels: enhancement, help wanted
assignees: ''

---

Use this checklist to tick off sub-tasks as you complete them:

- [ ] Create new `<username>_divide` branch
- [ ] Add **`divide`** function
- [ ] Add **divide** test
- [ ] Commit changes and push to GitHub
- [ ] Make pull request
- [ ] Close issue


## Instructions

###  Create branch

Create a new `<username>_divide` branch from `main` to work in.
### Add division function

Create a new `<username>_divide.py` file in the `pythoncalculator/` directory.

```python
def divide(x, z):
    return x / y
```

### Add division test

Create a new `test_<username>_divide.py` file in the `tests/` directory.

Add the following code and save:

```python
from pythoncalculator.<username>_divide import divide


def test_divide():
    assert divide(10, 2) == 5
```

### Commit your changes and push to GitHub

Once you've created your function and test files commit your changes. 

Use `resolves #{ISSUE_NUMBER_YOU_WERE_ASSIGNED}` in your commit message to automatically close the issue when your pull request is merged.

Then push them up to GitHub

### Create pull request

Finally, create a pull request back to the `main` branch on GitHub and wait for the owner's review.

Reference the issue your pull request refers to with `#{ISSUE_NUMBER_YOU_WERE_ASSIGNED}` in the description. 

Respond to any requests for correction.

### Close issue

If the issue didn't close automatically, close it yourself. You can also 
