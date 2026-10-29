#  Smart Certificate Generator (SCG)

A web-based application designed to generate certificates using an HTML frontend and a Python backend.

## About the Project

Smart Certificate Generator (SCG) aims to simplify the certificate creation process by allowing users to enter certificate details and generate certificates in PDF format.

This project is currently under development, with core functionality being implemented and tested.

##  Features

-  Enter certificate details through a web interface.
-  Generate certificates using a customizable layout.
-  Generate and download certificates in PDF format.
-  Python-based backend processing.
-  HTML-based user interface.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python, Flask
- **PDF Generation:** Python PDF library
- **Development Tools:** Visual Studio Code, Git, GitHub

##  Project Structure

```text
Smart-Certificate-Generator/
├── docs/
│   ├── index.html
│   ├── style.css
│   └── script.js
├── backend/
│   ├── app.py
│   └── requirements.txt
└── README.md
```


##  How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/shanmugapriya-MK/Smart-Certificate-Generator.git
cd Smart-Certificate-Generator
```

### 2. Set up the Python backend

```bash
cd backend
python -m venv venv
```

Activate the virtual environment.

**Windows:**
```bash
venv\Scripts\activate
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

### 3. Start the Flask application

```bash
python app.py
```

Open the local frontend in your browser and configure it to communicate with the running Flask backend.

*Make sure the frontend API URL matches the address and port where your Flask application is running.*

##  Deployment

The planned deployment setup is:

- **Frontend:** GitHub Pages
- **Backend:** Render
- **Backend Framework:** Flask

Deployment status: Update this section once the application is successfully deployed.

##  Future Improvements

- Improve certificate templates and customization.
- Add input validation and error handling.
- Improve the user interface and user experience.
- Add more certificate design options.
- Enhance reliability and deployment readiness.

## Developer

**Shanmugapriya MK**

GitHub: [shanmugapriya-MK](https://github.com/shanmugapriya-MK)

##  Project Status

**In Progress** 

This project is being developed to improve my skills in Python backend development, web technologies, and PDF generation.

---

 Thank you for visiting the project!
