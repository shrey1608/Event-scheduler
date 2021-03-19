# Event-scheduler

Scheduling tasks for the future is an essential tool for any software developer. While much of the programming we create aims to respond to explicit triggers or user events, background processes performed at regular intervals are just as essential.

Fortunately, this problem has been tackled by a lot of smart people, and a python-native solution is not tough to find. The Event Scheduler Api (APS) is a great option which features an easy, intuitive API.

## Features:
- Schedule a meetinG/Event
- Schedule from anywhere at anytime
- Schedule non overlapping meetings
- Prioritise the meetings

## Technologies Used:
- Django
- Django Rest Framework

## Setup the project locally
- Clone the repo.
    ```
    git clone https://github.com/shrey1608/Event-scheduler
    ```

- Create a virtual environment. Make sure you are not inside the repo when you create the virtual environment.
    ```
    python3 -m venv <your-venv-name>
    ```
 
- Activate the virtual environment. 
    ```
    source <your-venv-name>/bin/activate
    ```
 
- Go inside the repo folder. Now you should be inside a folder called Albums

- Install all the requirements
    ```
    pip3 install -r requirements.txt
    ```

- Create database tables.
    ```
    python manage.py migrate
    ```

- Run your program
    ```
    python manage.py runserver
    ```
    
