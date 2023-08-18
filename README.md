## Web App or Application Deployable
make any App or Application deployable on a Web based Platform like Koyeb & Render


* ## Problem -
> As you guys know we can't deploy simple source code of Telegram Bot on web based platforms like Koyeb & Render.
If your try to deploy these Source codes your Deployment will be unhealthy & will stop after sometime.

* ## Reason - 
> Web based platforms requires your app to listen to external ports like 80 , 22 , 7 , etc.
Because of this many deployment on these platforms fails.

* ## Solution - 
> So to solve this problem we will use a python framework called flask to deploy bots on these platforms.

* ## What is Flask ? -
> Flask is a micro web framework written in Python. It is classified as a microframework because it does not require particular tools or libraries. It has no database abstraction layer, form validation, or any other components where pre-existing third-party libraries provide common functions.

* ## Why Flask used in python ? -
> Flask is a lightweight Python web framework that provides useful tools and features for creating web applications in the Python Language. It gives developers flexibility and is an accessible framework for new developers because you can build a web application quickly using only a single Python file.

## Steps
1) Edit your `requirements.txt` file
```
Flask==2.2.2
gunicorn==20.1.0
aiohttp==3.8.4
```
Add these dependencies in your `requirements.txt` file

2) Create a new File named as `app.py`
```
from flask import Flask
app = Flask(name)

@app.route('/')
def hello_world():
    return 'Jay_Bots'


if name == "main":
    app.run()
```

3) Create a new File named as `run cmd.txt`
```
gunicorn app:app & <YOUR-APP-RUN-COMMAND>
```
Change the run command of the `Profile` file to `<your-app-run-command>`

## Here are App or Application is ready to be deployed on any web based platform.

## 😃 Connect me
[🧑‍💻 Telegram](https://telegram.me/JayArmo)

[📢 Update Channel](https://telegram.me/Jay_Bots)

[💬 Support Group](https://telegram.me/Jay_Bots_Support)

[buy me a ☕ coffee](https://www.buymeacoffee.com/jayarmo)


## Enjoy And don't forget to star this repo 🙂


## Credits...
[`JayArmo`](https://github.com/JayArmo)
-----
