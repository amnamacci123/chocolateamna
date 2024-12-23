Installation Instructions
1. Clone the repository

git clone https://github.com/your-username/chocolate-house.git

cd chocolate-house

2. Set up a virtual environment

python -m venv venv


3. Install dependencies

pip install -r requirements.txt

4. Run migrations

python manage.py migrate

5. Start the server

python manage.py runserver
Visit http://127.0.0.1:8000/ to view the application.

6.enter user name and password
username: administrator
password: amnal7amna

Set Up Docker
If you prefer to run the app in a Docker container, follow bellow steps:

Build the Docker image:


docker build -t chocolate_house .
Run the Docker container:


docker run -p 8000:8000 chocolate_house
run server at http://localhost:8000/

Usage Instructions
After running the application, you will see a menu with the following options:

Add Flavor
View Flavor
Delete flavor
Update flavor
manage ingredients
add ingredients
update ingredients
customer suggestions
handle allergy concerns
Choose an option by typing the corresponding number.

Technologies Used
Python
SQLite
Docker