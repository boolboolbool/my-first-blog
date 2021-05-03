# My First Django Girls Blog

A demo repository of the finished project from the Django Girls Tutorial.
See live instance at [boolboolbool.pythonanywhere.com](https://boolboolbool.pythonanywhere.com)

## Installation
Install the required pakages.
```bash
pip install -r requirements.txt
```

On pythonanywhere.
```bash
pip3.8 install --user pythonanywhere

pa_autoconfigure_django.py --python=3.8 https://github.com/boolboolbool/my-first-blog.git
```

## Usage
Running locally.
``` bash
python manage.py runserver
```

On pythonanywhere.
```bash
git pull

# use to update if there are css changes
workon boolboolbool.pythonanywhere.com
python manage.py collectstatic
```

Thanks.
