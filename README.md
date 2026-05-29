# AWS-Hosted Virtual Classroom and Learning Platform

## 📌 Project Overview

The AWS-Hosted Virtual Classroom and Learning Platform is a cloud-based web application developed using Flask and AWS services. The platform enables students to register, log in, and access learning materials uploaded by administrators. The project demonstrates how modern web applications can be deployed and scaled using AWS cloud infrastructure.

---

## 🚀 Features

* User Registration and Login System
* Secure Authentication
* Upload and Access Learning Materials
* Cloud Storage using AWS S3
* MySQL Database hosted on AWS RDS
* Flask-Based Backend APIs
* Responsive User Interface

---

## 🛠️ Technologies Used

### Backend

* Python
* Flask

### Frontend

* HTML
* CSS
* JavaScript
* Bootstrap

### Database

* MySQL (AWS RDS)

### Cloud Services

* AWS EC2
* AWS S3
* AWS RDS

### Other Tools

* Git & GitHub
* MySQL Workbench

---

## 📂 Project Structure

```bash
AWS-hosted-Virtual-Classroom-and-Learning-Platform/
├── Documentation/
│   └── Final document.pdf
├── static/
├── templates/
│   ├── content.html
│   ├── home.html
│   ├── login.html
│   └── register.html
├── app.py
├── README.md
├── requirements.txt
└── tempCodeRunnerFile.py

## 🏗️ System Architecture

### Frontend

* HTML, CSS, and JavaScript pages rendered using Flask templates.

### Backend

* Flask APIs manage authentication, routing, and file operations.

### Storage

* Learning materials such as PDFs are stored in AWS S3.

### Database

* User data and file metadata are stored in AWS RDS (MySQL).

### Deployment

* The Flask application is deployed on an AWS EC2 instance.

## 🔄 Project Workflow

### 1. Create and Configure AWS Services

* Create AWS Account
* Configure AWS S3 Bucket
* Configure AWS RDS MySQL Database
* Launch AWS EC2 Instance

### 2. Develop Flask Application

* Build registration and login routes
* Create frontend templates:

  * `home.html`
  * `register.html`
  * `login.html`
  * `content.html`
* Connect Flask with:

  * AWS S3 using `boto3`
  * AWS RDS using `pymysql`

### 3. Deploy the Application

* Connect to EC2 using SSH
* Clone GitHub repository
* Install required dependencies
* Run Flask application server

### 4. Push Code to GitHub

* Initialize Git repository
* Commit project files
* Push source code to GitHub

## 👨‍🏫 User Scenarios

### Student Registration and Login

Students can:

* Register using the web interface
* Log in securely
* Access learning materials stored on AWS S3

### Admin Uploads Content

Administrators can:

* Upload PDFs and learning resources to AWS S3
* Store file metadata in AWS RDS

### Student Downloads Content

Students can:

* View available learning resources
* Download files directly from AWS S3

## ⚙️ Installation and Setup

### Clone Repository

```bash
git clone https://github.com/Chaitanya-Tambe18/AWS-Hosted-Virtual-Classroom-Learning-Platform.git
```

### Navigate to Project Directory

```bash
cd AWS-Hosted-Virtual-Classroom-Learning-Platform
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Flask Application

```bash
python app.py
```
## ✅ Conclusion

This project demonstrates how cloud technologies can be integrated with web development to create scalable and secure learning platforms. By combining Flask with AWS services such as EC2, S3, and RDS, the system provides a modern and efficient online classroom experience.

## 📎 GitHub Repository

Repository Link:
https://github.com/Chaitanya-Tambe18/AWS-Hosted-Virtual-Classroom-Learning-Platform
