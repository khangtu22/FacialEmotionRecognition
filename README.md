# FacialEmotionRecognition
This project's purpose is to use CNN to detect facial of 7 basic human emotion. We implemented on PyCharm. Using Flask framework to create to built a website provide
user interface to get input (frontface camera). With the help of OpenCV we can easily detect the face and then using that frame we apply CNN model for that frame to detect. 
## Steps
* Make a virtual environment using:
```
pip install pipenv
```
* Install requirement: 
```
pip install -r requirements.txt
```
* Run project: 
```
export FLASK_APP=app.py
```
```
python -m flask run
```
access : http://127.0.0.1:5000/
