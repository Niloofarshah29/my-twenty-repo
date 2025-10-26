# my-twenty-repo
my twenty 
from flask impor Flask
app = Flask(__name__)

@app.route("/")
def home():
    return "Hello from Flask!"

if __name__ == "__main__":
    app.run(debug=True)
