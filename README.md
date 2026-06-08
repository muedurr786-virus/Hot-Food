Hot-Food
Food Delivery Website built with Django and Bootstrap

Demo:
Homepage


Product page


Installation:
1.Clone the Repo
2.Setup pipenv & Install Requirements

pip install pipenv
pipenv install -r requirements.txt
pipenv shell
3.Set Up RabbitMQ Server

sudo apt-get install rabbitmq-server
service rabbitmq-server start
4.Migrate Database

python manage.py makemigrations
python manage.py migrate
5.Start Server

python manage.py runserver
Contributors
Contributions are welcome, and they are greatly appreciated! Every little bit helps, and credit will always be given.

Please star the repo and feel free to make pull requests.
