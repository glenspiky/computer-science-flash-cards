
# CS FlashCards

A simple web application built with Django to help students learn and retain Computer Science concepts through flashcards.

The goal of this project is to make studying CS topics easier by providing a clean interface for creating, organizing, and reviewing flashcards.

## Features

* Create and manage flashcards
* Organize cards by topic
* Review cards using active recall
* Track learning progress
* Search for specific concepts
* Responsive design for desktop and mobile devices

Topics can include:

### Computer Science Fundamentals

* Data Structures
* Algorithms
* Operating Systems
* Computer Networks
* Databases
* Object-Oriented Programming
* Design Patterns
* System Design

### Programming Concepts

* Time & Space Complexity
* Recursion
* Dynamic Programming
* Bit Manipulation
* Sorting Algorithms
* Graph Algorithms
* Language Syntax & Concepts

## Tech Stack

Built with:

* Python 3
* Django
* SQLite (development)
* Bootstrap / Tailwind CSS
* HTML, CSS, JavaScript

## Screenshots

### Dashboard

Manage your flashcards and track your learning progress.

![Dashboard](screenshots/dashboard.png)

---

### Flashcard Review

Study using active recall by viewing the question first and revealing the answer when ready.

![Review](screenshots/review.png)

---

### Create Flashcard

Add new concepts and organize them by category.

![Create Card](screenshots/create-card.png)

## Why This Project?

Learning Computer Science requires repetition and consistent review.

This application was created to help students:

* Remember important concepts
* Prepare for technical interviews
* Reinforce DSA knowledge
* Build long-term retention through repetition

## Running Locally

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/cs-flashcards.git
cd cs-flashcards
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it:

Linux/macOS

```bash
source venv/bin/activate
```

Windows

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run migrations

```bash
python manage.py migrate
```

### 5. Create a superuser

```bash
python manage.py createsuperuser
```

### 6. Start the development server

```bash
python manage.py runserver
```

Visit:

```text
http://127.0.0.1:8000
```

## Future Improvements

* Spaced repetition algorithm
* Flashcard difficulty levels
* Study streaks
* User authentication
* Deck sharing
* Import/Export cards
* Dark mode
* AI-generated flashcards

## Contributing

Contributions, bug reports, and feature requests are welcome.

Feel free to fork the repository and submit a pull request.

## License

This project is open-source and available under the MIT License.

---

Happy Learning 🚀
