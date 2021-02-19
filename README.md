# stock-app

# Watch the tutorial video

[How to build a Stock price web app | Streamlit #20](https://youtu.be/0pHJOzNDdOo)

<a href="https://youtu.be/0pHJOzNDdOo"><img src="http://img.youtube.com/vi/0pHJOzNDdOo/0.jpg" alt="How to build a Stock price web app | Streamlit #20" title="How to build a Stock price web app | Streamlit #20" width="400" /></a>

# Demo

Launch the web app:

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/dataprofessor/stock-app/main/app.py)

# Reproducing this web app
To recreate this web app on your own computer, do the following.

### Create conda environment
Firstly, we will create a conda environment called *stock*
```
conda create -n stock python=3.7.9
```
Secondly, we will login to the *stock* environement
```
conda activate stock
```
### Install prerequisite libraries

Download requirements.txt file

```
wget https://raw.githubusercontent.com/dataprofessor/stock-app/main/requirements.txt

```

Pip install libraries
```
pip install -r requirements.txt
```

###  Download and unzip contents from GitHub repo

Download and unzip contents from https://github.com/dataprofessor/stock-app/archive/main.zip

###  Launch the app

```
streamlit run app.py
```
