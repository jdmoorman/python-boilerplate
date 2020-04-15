# Python Boilerplate

[![PyPI Version](https://img.shields.io/pypi/v/python_boilerplate.svg)](https://pypi.org/project/python_boilerplate/)
[![Supported Python Versions](https://img.shields.io/pypi/pyversions/python_boilerplate.svg)](https://pypi.org/project/python_boilerplate/)

Python Boilerplate contains all the boilerplate you need to create a Python package.

---

## Installation
**Stable Release:** `pip install python_boilerplate`<br>
**Development Head:** `pip install git+https://github.com/jdmoorman/python_boilerplate.git`

## Quick Start
```python
>>> from python_boilerplate import Example
>>> a = Example()
>>> a.get_value()
10

```

## Citing
If you use our work in an academic setting, please cite our paper:


## Documentation
TODO: readthedocs
For more information, read the docs.


## Development
See [CONTRIBUTING.md](CONTRIBUTING.md) for information related to developing the code.


#### Additional Optional Setup Steps:
* Make sure the github repository initialized correctly at
    * `https://github.com:jdmoorman/python_boilerplate.git`
* Add branch protections to `master`
    * To protect from just anyone pushing to `master`
    * Go to your [GitHub repository's settings and under the `Branches` tab](https://github.com/jdmoorman/python_boilerplate/settings/branches), click `Add rule` and select the
    settings you believe best.
    * _Recommendations:_
      * _Require pull request reviews before merging_
      * _Require status checks to pass before merging_

#### Suggested Git Branch Strategy
1. `master` is for the most up-to-date development, very rarely should you directly commit to this branch. It is recommended to commit to development
branches and make pull requests to master.
3. Your day-to-day work should exist on branches separate from `master`. Even if it is just yourself working on the
repository, make a PR from your working branch to `master` so that you can ensure your commits don't break the
development head. GitHub Actions will run on every push to any branch or any pull request from any branch to any other
branch.
4. It is recommended to use "Squash and Merge" commits when committing PR's. It makes each set of changes to `master`
atomic and as a side effect naturally encourages small well defined PR's.
