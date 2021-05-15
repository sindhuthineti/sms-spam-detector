# spam sms detector :notebook: &nbsp;[![](https://camo.githubusercontent.com/17fa56d1fbad7bb4082c9711a77b984b85e79446/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f507974686f6e2d332e362d627269676874677265656e2e737667)](https://python.org)
In this repo i have created a SMS Spam Prediction project in machine learning using NLP, and i am using [nltk](https://pypi.org/project/nltk/) Library for NLP. Deployment on Heroku app.

 - [[Jupyter Notebook]](https://github.com/yogeshnile/SPAM-SMS-Prediction)
 - [[Demo]](https://spam-sms-dectector.herokuapp.com/)

# How to run the project? :thinking:
**1).** Run all command manually
  - Clone github repository in your local system  `git clone hhttps://github.com/sindhuthineti/sms-spam-detector.git`
  - Move in spam-sms-detector repository  `cd spam-sms-detector`
  - Create new virtual python environment  `python3 -m venv venv`
  - Activate virtual python environment  `source venv/bin/activate`
  - Install all the libraries mentioned in [requirements.txt](https://github.com/sindhuthineti/sms-spam-detector/blob/master/requirements.txt)  using  `pip install -r requirements.txt`
  - Run FlaskApp file  `python app.py`
  - Go to your browser and type http://127.0.0.1:5000/ in the address bar.
  - Hurray! That's it. <br>


**2).** Run Shell Script
  - Clone github repository in your local system  `git clone https://github.com/sindhuthineti/sms-spam-detector/unix.git`
  - Give execute permission to [spam-sms-detector.sh](https://github.com/sindhuthineti/unix/blob/master/spam-sms-detector.sh) file via  `chmod +x spam-sms-detector.sh`
  - Run spam-sms-detector.sh file using `./spam-sms-detector.sh`
  - Go to your browser and type http://127.0.0.1:5000/ in the address bar.
  - Finished...

# Directory Tree :cactus:
```bash
.
├── app.py
├── corpus.pkl
├── Images
│   ├── 1.png
│   ├── 2.png
│   └── 3.png
├── LICENSE
├── model_creation.py
├── nltk.txt
├── Procfile
├── README.md
├── requirements.txt
├── Spam SMS Collection
├── Spam_sms_prediction.pkl
├── static
│   ├── css
│   │   └── main.css
│   ├── icon
│   │   └── icon.ico
│   ├── js
│   │   └── global.js
│   └── vendor
│       └── jquery
│           ├── jquery.js
│           └── jquery.min.js
└── templates
    └── index.html

8 directories, 19 files
```

# Technology used in Project :hotsprings:
<img target="_blank" src="https://github.com/yogeshnile/technology/blob/master/Heroku.png" width="200">  <img target="_blank" src="https://github.com/yogeshnile/technology/blob/master/Jupyter.png" width="150">    <img target="_blank" src="https://github.com/yogeshnile/technology/blob/master/numpy.png" width="200">       <img target="_blank" src="https://github.com/yogeshnile/technology/blob/master/python_nltk.png" width="150">    <img target="_blank" src="https://github.com/yogeshnile/technology/blob/master/sklearn.png" width="200">    <img target="_blank" src="https://github.com/yogeshnile/technology/blob/master/Flask.png" width="300">    <img target="_blank" src="https://github.com/yogeshnile/technology/blob/master/pandas.png" width="300">

<!--## ScreenShot :camera_flash:
![](https://github.com/yogeshnile/spam-sms-detector/blob/master/Images/1.png)    ![](https://github.com/yogeshnile/spam-sms-detector/blob/master/Images/2.png)    ![](https://github.com/yogeshnile/spam-sms-detector/blob/master/Images/3.png)

## Bug / Feature Request :man_technologist:
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/yogeshnile/spam-sms-detector/issues/new) by including your search query and the expected result.-->
