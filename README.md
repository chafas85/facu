# jony 
# Technologies Used:
- Python3
- Django Framework
- Tensorflow
- NLTK
- Numpy
- HTML, CSS
- JavaScript

# 
- Install the required packages.
```
pip install -r requirements.txt
```
- First create `secret key` for project
- Requirements for creating new key:
	- Be a minimum of 50 characters in length
	- Contain a minimum of 5 unique characters
	- Not be prefixed with "django-insecure-"

- Now open project directory `/Aapi-Ai-Django-ChatBot/project/` where `settings.py` is located.
- Create new `.env` file and add the newly generated `secret key`
- .env file should look like this:
```
SECRET_KEY = "dlm*zt#1-3g!xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
- Save the .env file
- Do the migrations 
```
python manage.py migrate
```
- And run the project.
```
python manage.py runserver
```
***
- SRS Documentation: [https://drive.google.com/file/d/aapi_chatbot_srs/view](https://drive.google.com/file/d/1AjjONYHkVltQLMO_Tunrch9mOx1jlpmm/view)
- ChatBot image are taken from [flaticon](https://www.flaticon.com/free-icons/bot)
- User image are taken from [freeiconspng](https://www.freeiconspng.com/img/7563)

***
Built with :heartpulse: by Sharing Is Caring
# facu
