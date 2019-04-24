![alt text](https://i.imgur.com/Rye4qvw.jpg)

# Simple Radio Website

Live audio streaming website based on flaskr

### Prerequisites

What you need

```
Flask (1.0.2)
Jinja2 (2.10.1)
virtualenv(16.5.0)
```

### Installing & Deployment


```
sudo -i
virtualenv -p $(which python3.7) [folder_name]
cd [folder_name]
source bin/activate
which python
which pip
pip install flask
import flask
export FLASK_APP=[folder_name]
export FLASK_ENV=development
python -m flask run --host=0.0.0.0 --port=80
```



## Built With

* [Flask](http://flask.pocoo.org/) - Microframework for Python based on Werkzeug, Jinja 2


