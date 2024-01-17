
# Goodreads Clone

## Overview
This repository contains a Django-based web application that serves as a clone of the popular book review and recommendation service, Goodreads. It aims to replicate key features of Goodreads, providing users with a platform to explore books, write reviews, and engage with a community of book enthusiasts. This project is built purely to demonstrate my knowledge in building web applications and does not claim any credibility over GoodReads.com


## Technologies/Frameworks used
- Django and Django Rest Framework (DRF).
- HTML, CSS and Bootstrap.
- Celery.
- PostgreSQL.

## Project Features
- Users can register, login and update their profile information and password.
- Users can review books, leave comments and give stars.
- User Profiles: Personalized profiles for users to manage their activities.
- Community Interaction: Engage with other users and share book recommendations.

## Getting Started

### Prerequisites
- Python 3.x
- Django
- Other dependencies listed in `requirements.txt`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/NurulloMahmud/goodreads-clone.git
   ```
2. Navigate to the project directory:
   ```bash
   cd goodreads-clone
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application
1. Make migrations to create the database schema:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```
2. Run the Django development server:
   ```bash
   python manage.py runserver
   ```
3. Open a web browser and navigate to `http://localhost:8000/` to view the application.

## Contributing
Contributions to this project are welcome! Please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
