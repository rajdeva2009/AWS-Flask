Steps:
=====
```
yum repolist all
yum install pip
python3 -m venv my_app/env
source ~/my_app/env/bin/activate
pip install pip --upgrade
pip install boto3 flask
cd my_app|mkdir flask
git clone 
cd /my_app/flask/AWS-Flask/dynamoDB
vi key_config.py| vi dynamoDB_create_table.py
export flask_application=app.py
flask run --host=0.0.0.0 --port=80
access using public IP of EC2
```
