# Django Month's Challenge App

This is a web app built with Django that allows users to take on a different challenge each month.

## Features

- Users can create an account and log in 
- Each month has a new challenge category (fitness, creativity, career etc)
- Users can mark challenges completed and track progress
- Points system and leaderboard for motivation
- Responsive design works on mobile and desktop 

## Getting Started

### Prerequisites

- Python 3.x 
- pip

### Installation

1. Clone repo  
`git clone https://github.com/Sahil811/Django-Month-s-challenge-App.git`

2. Install requirements    
`pip install -r requirements.txt`  

3. Run migrations
`python manage.py migrate`

4. Create admin account  
`python manage.py createsuperuser`

5. Run development server  
`python manage.py runserver`

6. Open http://127.0.0.1:8000/ in browser

## Usage

- Browse challenges and sign up for an account
- Mark challenges as completed to gain points
- Earn badges for milestones and compete on the leaderboard

## Customizing

Challenges are defined in `challenges/models.py`.

Templates are located in `templates/` folder structured based on app/model.

Static files are in `static/`.

## License

This project is open source and available under the MIT License.
