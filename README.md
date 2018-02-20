# FYP Web Application
This Web App contains all the experiment results conducted during FYP2

## Getting Started
These instructions will get you a copy of the project up and running on your local machine. Or you can visit the live version from this link, ganqitze.github.io/home.html

### Prerequisites
You will need the following to get the web ready.
```
Node.js
NPM
Python
```
### Installing
First, let's install bower via npm
```
npm install -g bower
```
Clone this repo
```
git clone https://github.com/ganqitze/ganqitze.github.io.git
```
Then, cd to the cloned repo and bower install some polymer element
```
bower install --save googlearchive/paper-menu
```
Finally, open up a local server (a python simple http server will do) and play around with the link below.
```
python -m SimpleHTTPServer 8000 (Python 2.x)
python -m http.server --cgi 8000 (Python 3.x)
localhost:8000/home.html
```

## Built With

* Polymer [paper-menu]
* pyLDAvis
* wordclouds
