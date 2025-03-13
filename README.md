# Flask Project
## Notes
- This is a Flask project.
- Install the flask 

```

pip install flask


```
To Run the app 

```
python app.py

```
- flask Minimal app
```

from flask import Flask, render_template

app = Flask(__name__)

@app.route('/')
def home():
    return render_template('index.html')

if __name__ == '__main__':
    app.run(debug=True)

```
