# flashcard-app-django
A django project which helps you memorize anything. 

# My Django Web App Project

Welcome to my Django web app project! This project is designed to help you memorize anything. <br> On the front page of your web app, you’ll see all your existing cards and be able to create new ones. On each flashcard, you can add a question and an answer,<br> which you can later edit.Once you’ve learned the answer to the card’s question, the card moves to the next box.<> If a flashcard moves to the next box, that doesn’t mean you’re done with it. You’ll still review it periodically to refresh your memory,<br> and it’ll continue progressing through the boxes. Basically, the higher the box number, the more likely that you’ve mastered those concepts.<br> If you don’t know the answer to a card’s question, then the card moves back to the first box. 

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x: [Download Python](https://www.python.org/downloads/)
- Django: Install using `pip install django`

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone <repository_url>
   ```

2. Navigate to the project directory:

   ```bash
   cd <project_directory>
   ```

3. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source venv/bin/activate
     ```

5. Install project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

7. Create a superuser (admin) for the Django admin panel:

   ```bash
   python manage.py createsuperuser
   ```

8. Start the development server:

   ```bash
   python manage.py runserver
   ```

### Usage

#### Open a web browser and navigate to `http://127.0.0.1:8000/` to access the web app.


### Development

Here are some useful commands for development:

- Run tests:

  ```bash
  python manage.py test
  ```

- Create a new Django app within the project:

  ```bash
  python manage.py startapp <app_name>
  ```

- Generate migrations after making changes to models:

  ```bash
  python manage.py makemigrations
  ```

- Apply migrations to the database:

  ```bash
  python manage.py migrate
  ```

- Create a new Django admin user:

  ```bash
  python manage.py createsuperuser
  ```


### Built With

- Django - The web framework used
- HTML
- CSS

### Contributing

Feel free to contribute 

### Authors

- Rohit Kumar


---

Thank you for using my Django web app project! If you have any questions or encounter any issues, please feel free to contact me at [samrohit933@gmail.com].
