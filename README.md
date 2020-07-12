# django-coverage-action
Github action to check Django project coverage


## Usage

```
- uses: actions/checkout@v2
- uses: matheusvanzan/django-coverage-action@master
- with:
    - django-app: 'myapp'
    - minimum-coverage: '90'
```