# my-twenty-repo
my twenty 
from flask import Flask
app = Flask(__name__)

@ap.route("/")
def home():
    return "Hello from Flask!"

if __name__ == "__main__":
    app.run(debug=True)
