# AWS-Hosted-Virtual-Classroom-Learning-Platform
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

Technologies Used

    Backend: Python, Flask
    Frontend: HTML, CSS, JavaScript, Bootstrap
    Database: MySQL (AWS RDS)
    Cloud Services: AWS EC2, S3, RDS
    Other Tools: Git & GitHub, MySQL Workbench

System Architecture

    Frontend: HTML/CSS/JS served via Flask templates
    Backend: Flask APIs managing user and file routes
    Storage: PDFs stored in S3
    Database: User and file metadata stored in RDS (MySQL)
    Deployment: Flask app hosted on EC2

Project Workflow

    Create and Configure AWS Services:
        AWS Account, S3 Bucket, RDS MySQL, EC2 Instance
    Develop Flask App:
        Build register/login routes
        Create templates: home.html, register.html, login.html, content.html
        Connect to S3 using boto3 and to RDS using pymysql
    Deploy Application:
        SSH into EC2, clone GitHub repo, install dependencies
        Run Flask app using evelopment server
    Push Code to GitHub

👨‍🏫 User Scenarios
Student Registration and Login

    Registers via web form, logs in, accesses course content stored on S3.

Admin Uploads Content

    Uploads PDFs or videos to S3 with metadata stored in RDS.

Student Downloads Content

    Clicks a file link to download directly from S3.

✅ Conclusion

This project showcases how web applications can be effectively deployed and scaled using AWS. With Flask at its core and AWS services powering the backend, it provides a modern, secure, and user-friendly experience for online learning platforms.
