# Movie Sharer Project

<img src="./media/project/imagesharer-home.png" />


## Downloading this repo

#### With git:
```
git clone https://github.com/Prof-Percival/moviesharer.git
```

#### Download the .zip
Download [this file](https://github.com/Prof-Percival/moviesharer/archive/main.zip) and extract it.

## Installation

```
cd moviesharer
pipenv shell
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver 0.0.0.0:8000
```
