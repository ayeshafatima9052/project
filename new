from flask import Flask
import requests



app = Flask(__name__)

@app.route("/",methods=["GET"])
def home():
    return "Hello!"

@app.route("/<name>", methods=["POST"])
def user(name):
    return f"Hello {name} HOPE YOU ARE DOING WELL!"

if __name__ =="__main__":
    app.run(debug=True)

