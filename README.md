### Boston House Pricing Prediction

### Software And Tools Requirements

1. [Github Account](https://github.com)
2. [VScode](https://code.visualstudio.com)
3. [Heroku Account](https://heroku.com)
4. [Git CLI](https//git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

### Step to Run this Web Application Locally

1. Create a new virtual environment ***venv***:

using conda
```
conda create -p venv python==3.7 -y
```

or 

```
pip install virtualenv
```
#use ```virtualenv -p /usr/bin/python3 venv``` for specific python version to create virtual environment named ***venv*** or just
```
virtualenv venv  
```
#activate the environment env
```
source venv/bin/activate   
```

2. Clone this git repository:

#Clone this git repository using command from terminal
```
git clone https://github.com/mohannn-sys/bostonhousepricing.git
```

3. Install the packages:

#Go inside the folder ***bostonhousepricing*** and install neccessary packeges using command
```
pip install -r requirements.txt
```

4. Run the app Locally:

#Run the web server locally using command
```
python app.py
```
and access at localhost ```http://127.0.0.1:5000/``` from browser.


