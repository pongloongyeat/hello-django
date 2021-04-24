# Hello Django!

Just a fun repo to test Django out. Currently, this repo should do the following:

- [ ] UserAuth
  - [ ] Individual
  - [ ] Organisation
- [ ] Add a note
  - [ ] Title
  - [ ] Description (markup?)
  - [ ] Completed?
- [ ] Homepage showing all your notes

## Running locally

To run locally, first clone this repository. Then, `cd` into the project directory and create a new virtual environment with `pipenv`, i.e.

```bash
git clone https://github.com/pongloongyeat/hello-django.git
cd hello-django
pipenv shell
pipenv install
```

Then, apply migrations and run the server with `python manage.py runserver`.
