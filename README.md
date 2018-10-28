# FirstProject

from flask import Flask

app = Flask(__name__)

@app.route('This is our home page.')

def oktay():
    return "oktay"

if __name__=="__main__":
    app.run()
