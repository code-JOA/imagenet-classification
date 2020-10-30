# imagenet-classification
# Author : Joshua Owusu Ankomah

# This project has been deployed with heroku. Moreover git add the vgg19 large files first to your github when creating the repo with git lfs

![Google](https://img.shields.io/badge/Images_From-Google-blue.svg) ![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![requirements.txt](https://img.shields.io/badge/Library-requirements.txt-orange.svg)

• This repository consists of files required to deploy a ___Machine Learning Web App___ created with ___Flask___ .




![](https://forthebadge.com/images/badges/made-with-python.svg)

<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>


# Note:  Beware of Git LFS a.k.a git large files. 
#### Before installation you should first download git lfs which deals with large files in github.


# Downloading Git LFS on mac

```python
brew install git-lfs
```

### Check if it works

```python
git-lfs
```

# Make sure you are now in the directory where you cloned this repo

```python
git init # if you havent initialised already probably you still havent at this point
```

```python
git lfs install # installs lfs inside the repo
```

# This means git lfs should track all large csv files. You can relace it with file name.

# You can also copy the path of the file as well eg "users/desktop/opencv2"

```python
git lfs track "*.csv" 
```

```python
git add .gitattributes  # addes git attributes
```

```python
git add .   # adds everything
```

```python
git commit -m "add your message here"
```

```python
git push
```

```python
git pull
```

```python

```

## Installation.
The Code is written in Python 3.6. However ,version 3.7 is also supported by the modules. 
If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:

# Create a new environment to avoid clashes or errors.
+ For example I can create a new environment called Blablabla with python version 3.6

```python
conda create -n Blablabla python=3.6
```

# To activate the environment.

```python
conda create -n Blablabla python=3.6
```

+ next you can use pip freeze to get the libraries I have used in this project
+ or you can use pip freeze > requirements.txt before typing in the code below

```python
pip install -r requirements.txt
```

# To run the flask App on your local machine.
+ cd into my_flask_app folder then try the code below

```python
pip install -r requirements.txt
```

# To run the flask App on your local machine.
+ cd into my_flask_app folder then try the code below

```python
python app.py
```

```python

```

### Connect with me

[<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/linkedin.png">](https://www.linkedin.com/in/joshua-owusu-ankomah-2b5a9898/)  [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/github.png">](https://github.com/code-JOA)  [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/facebook.png">]() [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/instagram-new.png">](https://www.instagram.com/jay_rockerfella/)


```python

```
