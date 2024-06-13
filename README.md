[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/x4EMAJ3T)


#### Git repo: https://github.com/gopinathsjsu/team-project-geek

## XP Core Values Implemented
#### 1)Simplicity:  
We evaluated every feature needed for the program as a team and selected the most straightforward yet efficient tools and technologies.
We made sure that our program was efficient in carrying out its intended functions and easy to use by thoroughly assessing each feature and choosing simple yet powerful tools and technologies.   

#### 2)Respect:   
Our team concentrated on the XP Core Value of Respect once a week. We talked about how important it is to respect everyone's role, communicate thoughtfully, and treat each other with respect.
In meetings, we will make sure that everyone feels heard and respected by practicing active listening.

#### 3)Communication:   
Effective communication was a cornerstone of our team's approach throughout the project. Initially, we collaboratively brainstormed the project's concept and distributed tasks among ourselves. We held regular sprint meetings where team members discussed challenges they encountered and conducted retrospectives on aspects that didn't go as planned. This open communication ensured a smooth project workflow and team synergy.

## Tools and Languages:
- Django 4.0.4
- Bootstrap 5.0.2
- jQuery 3.6.0
- Chart.js v3.9.1
- Animate.css 4.1.1
- SQLite3
- HTML
- AWS EC2 Autoscaled group

## Design Decisions
#### Frontend:
JQuery simplifies JavaScript code for DOM manipulation and event handling, while Chart.js creates customizable charts. Bootstrap offers pre-designed components and responsive layouts, and Animate.css adds easy CSS animations. These tools streamline development and enhance user interaction.
#### Backend:
We have chosen Python Django as our backend framework because of its robustness, scalability, and ease of use. Django comes with many built-in features such as ORM, URL routing, and templating that make it easy to develop complex web applications. Additionally, Django provides strong security measures out of the box, which is critical for our Canvas(Learning management system).

#### Database: 
We have selected SQLite as our database management system because of its simplicity, efficiency, and ease of use. SQLite is a lightweight and self-contained database engine that can be easily integrated with Django. As our Canvas(Learning management system) is not expected to have a high volume of transactions, SQLite is a suitable choice for our application.

## UI WireFrames:
https://docs.google.com/document/d/1vrqAj7YE6IBqvAOLKWZnrKUCE4i3k6yB1muvOc8AXrU/edit?usp=sharing

## Diagrams:
#### Architecture Diagram

![image](https://github.com/gopinathsjsu/team-project-geek/assets/64256985/142ee312-2d08-41f9-9a60-f039825310fd)


#### Component Diagram
![image](https://github.com/gopinathsjsu/team-project-geek/assets/64256985/7760dc11-3737-4e35-93e4-d89d88385955)


#### Class Diagram
![image](https://github.com/gopinathsjsu/team-project-geek/assets/64256985/936704fa-5293-423c-b62d-f613a4e7f471)




#### Deployment Diagram
![image](https://github.com/gopinathsjsu/team-project-geek/assets/64256985/0b1127ca-a590-47eb-8017-e5d7fb5a920c)


## Run Locally

1. Clone the project

```bash
git clone https://github.com/sahithi-kalakonda/LMS.git
```

2. Go to the project directory

```bash
cd LMS
```

3. Create a virtual environment and activate it (Windows)

```bash
python -m venv env
```

```bash
env\Scripts\activate
```

4. Install dependencies

```bash
pip install -r requirements.txt
```

> **Note:** If you're using newer versions of python(3.10+), you may need to add the `--use-deprecated=legacy-resolver` option when installing dependencies with `pip` to avoid errors :

```bash
pip install -r requirements.txt --use-deprecated=legacy-resolver
```

5. Make migrations and migrate

```bash
python manage.py makemigrations
```

```bash
python manage.py migrate
```

6. Create admin/superuser

```bash
python manage.py createsuperuser
```

7. Finally run the project

```bash
python manage.py runserver
```

Now the project should be running on http://127.0.0.1:8000/
