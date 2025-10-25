# my-twenty-repo
my twenty 
from flask import Flask
app = Flask(__name__)

@app.route("/")
def home():
    retur "Hello from Flask!"

if __name__ == "__main__":
    app.run(debug=True)
