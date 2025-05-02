# HireMe - Job Portal Web Application 🎯

**HireMe** is a web-based job portal designed to help **students** find and apply for job opportunities, while enabling **recruiters** to post job listings and interact with potential candidates.

This full-stack application is built with **Flask** for the backend, **HTML**, **CSS**, and **JavaScript** for the frontend, and **SQLite3** for the database. The platform incorporates secure authentication via **Flask-Login**, ensuring user privacy and safety.

---

## 🧑‍🎓 Student Functionality

1. **Register & Log In Securely**  
   - Students can securely register and log in using hashed passwords stored safely.

2. **Browse Job Listings**  
   - View available job postings with details such as job title, description, salary, and required qualifications.

3. **Apply to Jobs**  
   - Students can apply for jobs directly through the platform. They can manage, update, or withdraw applications as needed.

4. **Manage Profile & Applications**  
   - Update personal details, upload resumes, and track the status of applications (e.g., pending, accepted, rejected).

---

## 🧑‍💼 Recruiter Functionality

1. **Register & Log In as a Recruiter**  
   - Recruiters have their own login system to ensure distinct access control.

2. **Post Job Opportunities**  
   - Create detailed job postings with role descriptions, required qualifications, salary range, and location.

3. **View & Manage Student Applications**  
   - Review student applications, access resumes, and evaluate profiles.

4. **Contact Candidates**  
   - Direct communication with selected candidates via the platform for further steps such as interviews.

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask  
- **Frontend**: HTML, CSS, JavaScript  
- **Database**: SQLite3 (easily upgradable to MySQL/PostgreSQL)  
- **Authentication**: Flask-Login  

---

## 💡 Skills Required

- **HTML**
- **CSS**
- **JavaScript**
- **SQL**
- **Python**

---

## 🧰 Framework & Tools

- **Framework**: Flask  
- **IDE**: Visual Studio Code (VS Code)  

---

## 🌐 Project Pages

- **index** – Homepage
- **student_register** – Student Registration Page
- **student_login** – Student Login Page
- **student_home** – Student Dashboard
- **student_reset_password** – Student Password Reset
- **recruiter_register** – Recruiter Registration Page
- **recruiter_login** – Recruiter Login Page
- **recruiter_home** – Recruiter Dashboard
- **create_job** – Job Posting Page
- **job_details** – Job Description for Students
- **recruiter_job_details** – Job Description for Recruiters
- **recruiter_forgot_password** – Recruiter Password Reset
- **report** – Report Generation/Job Summary
- **database_setup** – DB Initialization Script

---

## 📁 Project Setup

### 1. Clone the repository
```bash
git clone https://github.com/Praniiiii/HireMe.git
cd HireMe
```

### 2. Create and activate virtual environment

- Ubuntu/macOS:
``` bash
python3 -m venv venv
source venv/bin/activate

```
- winodws
```bash
python -m venv venv
venv\Scripts\activate

```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python app.py
```

### 5. Visit in browser
Open your browser and go to: http://127.0.0.1:5000

---

## 📸 Screenshots

### Home Page

![image](https://github.com/user-attachments/assets/f236c92a-e9db-41ae-aded-5fa15d068646)

### Student Registration

![image](https://github.com/user-attachments/assets/2a91ac72-2d99-4cf4-ad6a-2ba0f6773dce)

### Student Login

![image](https://github.com/user-attachments/assets/3d23d822-e83a-4c6d-b063-f097ff8eae39)

### Student Dashboard

![image](https://github.com/user-attachments/assets/3faf4c5d-f441-45a7-9db2-f861b5a47845)

### Student_reset_password

![image](https://github.com/user-attachments/assets/d77621c4-bd38-4417-a894-20289223f92d)

### Recruiter Registration

![image](https://github.com/user-attachments/assets/a811c789-d9f4-4499-b454-b33332cd597f)

### Recruiter Login

![image](https://github.com/user-attachments/assets/dbfa37b8-a592-45f7-80b0-d0009e8318b1)

### Recruiter Password Reset

![image](https://github.com/user-attachments/assets/fb8803d5-b617-46e9-81cd-05f16402bc0b)

### create_job – Job Posting Page

![image](https://github.com/user-attachments/assets/76596418-ec83-43b6-a18c-06a8cf068d14)

### Job Description for Recruiters

![image](https://github.com/user-attachments/assets/3317133a-4cd5-4d62-9c52-0bbe04b7a987)


### Report Generation / Summary

![image](https://github.com/user-attachments/assets/f4362073-67aa-4b50-861d-506d59512d9f)


---

## 🤝 Contributing

Contributions are welcome and appreciated! 🙌

If you'd like to contribute to **HireMe**, follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add your message here'`)
5. Push to the branch (`git push origin feature/your-feature-name`)
6. Open a pull request

Please make sure your code follows best practices and is well-documented.

---

⭐ If you like this project, don't forget to give it a star!
