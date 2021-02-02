# django-pre-deploy-checks

[![Build Status](https://github.com/wemake.services/django-pre-deploy-checks/workflows/test/badge.svg?branch=master&event=push)](https://github.com/wemake.services/django-pre-deploy-checks/actions?query=workflow%3Atest)
[![Python Version](https://img.shields.io/pypi/pyversions/django-pre-deploy-checks.svg)](https://pypi.org/project/django-pre-deploy-checks/)
[![wemake-python-styleguide](https://img.shields.io/badge/style-wemake-000000.svg)](https://github.com/wemake-services/wemake-python-styleguide)

Django checks you should run on application deploy


## Features

- Fully typed with annotations and checked with mypy, [PEP561 compatible](https://www.python.org/dev/peps/pep-0561/)
- Add yours!


## Installation

```bash
pip install django-pre-deploy-checks
```


## Example

Showcase how your project can be used:

```python
from django_pre_deploy_checks.example import some_function

print(some_function(3, 4))
# => 7
```

## License

[MIT](https://github.com/wemake.services/django-pre-deploy-checks/blob/master/LICENSE)


## Credits

This project was generated with [`wemake-python-package`](https://github.com/wemake-services/wemake-python-package). Current template version is: [0a5189513a1bbee62c791e990ea7258116adf096](https://github.com/wemake-services/wemake-python-package/tree/0a5189513a1bbee62c791e990ea7258116adf096). See what is [updated](https://github.com/wemake-services/wemake-python-package/compare/0a5189513a1bbee62c791e990ea7258116adf096...master) since then.
