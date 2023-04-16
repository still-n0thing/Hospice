<!-- PROJECT LOGO -->
<br />
<p align="center">
    <img src="static/img/logo.svg" alt="Logo" width="180" height="180">
  </a>

  <h2 align="center">Hospice</h2>
  <h5 align="center"><em>(Using Flask)</em></h5>
</p>



<!-- ABOUT THE PROJECT -->
## About The Project
Hospice is a web-based hospital management portal that allows healthcare professionals to efficiently manage the patient information, medical records, appointments, and billing details. The project utilizes the Flask web framework to create a simple and intuitive user interface, while SQLite is used as the backend database to store and retrieve data.

One of the main benefits of this project is that it provides a centralized location for healthcare professionals to access patient information, reducing the need for paper-based records and manual data entry. This can help improve the accuracy and efficiency of data management, ultimately leading to better patient outcomes.

By deploying the project to Google Cloud, the portal can be accessed from anywhere with an internet connection, allowing healthcare professionals to access patient information and manage their workload remotely. This can help improve communication and collaboration between healthcare professionals, leading to a more coordinated approach to patient care.

Overall, Hospice a hospital management portal is a valuable tool for healthcare professionals, offering a simple and effective way to manage patient information and streamline administrative tasks.

### Built With

* [Bootstrap](https://getbootstrap.com)
* [JQuery](https://jquery.com)
* [Flask](https://palletsprojects.com/p/flask/)



<!-- GETTING STARTED -->
## Getting Started

Clone the repository to get started

### Prerequisites

* [python](https://www.python.org/)

### Installation

1. Clone the repo
```sh
git clone https://github.com/still-n0thing/Hospice
```
2a. Create a Virtual Environment (Optional)
```sh
python -m venv env
```
2b. Activate the virtual environment 
```sh
env\Scripts\activate
```
3. Install the requirements and dependancies
```sh
pip install -r requirements.txt
```
4. Run the application
```python
flask run
```
5. View the application on localhost
```
http://localhost:5000/
```


### Usage

#### Login Credentials:

* Admin Executive
```sh
Username: 12345678@A
Password: 12345678@A
```

* Pharmacist
```sh
Username: 12345678@P
Password: 12345678@P
```

* Diagnostic Executive
```sh
Username: 12345678@D
Password: 12345678@D
```

*Note While creating new login credentials please set the ending character with accordance to the role of the stakeholder.*

    * Admission Desk Executive/Registration Desk executive: A
    * Pharmacist: P
    * Diagnostic Executive: D
