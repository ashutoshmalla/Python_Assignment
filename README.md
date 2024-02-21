# Python_Assignment
# Implement s3 file manager using any python web framework(flask/django/...etc).
## functions :
## 1. List content of s3.
## 2. Create/Delete folder + bucket .
## 3. Upload files to s3 + delete file from s3.
## 4. Copy/Move file withing s3.
## Note:
## 1. Make sure your code is readable
## 2. Make sure your app is working properly
## 3. Need basic UI from which we can access app

## Steps:
### First we’ll create an enviornment. It helps a user to create multiple Python environments side by side so that it’ll avoid compatibility issues. We’ll also create a seprate folder for this task
 ```bash
       pip install virtualenv
       mkdir python-Assignment
       python3 -m venv python-Assignment
       source python-Assignment/bin/activate
       cd /python-Assignment
       pip install boto3
       pip install flask
```
