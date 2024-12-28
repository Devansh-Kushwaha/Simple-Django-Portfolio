# Simple-Django-Portfolio

A simple portfolio web application built using Django. This project showcases basic information, including personal details, work experience, and a portfolio of projects. 

## Features
- Dynamic content rendering using Django templates.
- Organized structure for scalability.
- Static file handling for images and styles.
- Simple and lightweight design.

---

## Technologies Used
- **Backend:** Django 5.1 (Python framework)
- **Frontend:** HTML, CSS (linked via Django’s static files system)

---

## Installation and Setup

### Prerequisites
- Python 3.10 or later installed on your system.
- Git installed for version control.
- A virtual environment manager (optional but recommended).

### Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Devansh-Kushwaha/Simple-Django-Portfolio.git
   cd Simple-Django-Portfolio
   ```

2. **Create and activate a virtual environment (optional):**
   ```bash
   python -m venv env
   source env/bin/activate   # For Linux/Mac
   env\Scripts\activate      # For Windows
   ```

3. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run database migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

6. **Access the application:**
   Open your browser and navigate to `http://127.0.0.1:8000`.

---

## File Structure
```
Simple-Django-Portfolio/
├── base/
│   ├── migrations/
│   ├── templates/
│   │   └── base.html
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── views.py
│   └── urls.py
├── portfolio/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── static/
│   ├── css/
│   └── images/
├── manage.py
└── requirements.txt
```

## Contributing
Contributions are welcome! Feel free to fork the repository and create a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact
For any inquiries, you can reach me at:  
**Devansh Kushwaha**  
**Email:** [devansh.67.kushwaha@gmail.com]  
**GitHub:** [https://github.com/Devansh-Kushwaha](https://github.com/Devansh-Kushwaha)
