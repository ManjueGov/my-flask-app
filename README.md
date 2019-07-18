#Create a Simple Web Application using python and flask
In this application it will be a simple registration page for an user.

## 1. Setting Up Flask
pip install flask
## 2. Create a file called app.py
## 3. Import flask module and create an app using Flask as
```
from flask import Flask
app = Flask(__name__)
```
## 4. Create a folder called templates
## 5. Add index.html file in templates folder
## 6. Back to app.py file
Now define the basic route / and its corresponding request handler
```@app.route("/")
def main():
    return render_template('registration.html')
```
## 7. Check if the executed file is the main program and run the app
```if __name__ == "__main__":
    app.run()
```
## 8. Save the changes and execute app.py
```python app.py```