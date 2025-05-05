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

## 📁 Project Setup Guide
Follow the steps below to set up and run the HireMe application locally.

### 1. Clone the repository
```bash
git clone https://github.com/Praniiiii/HireMe.git
cd HireMe
```

### 2. Set Up a Virtual Environment

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

### 3. Install Required Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python app.py
```

### 5. Visit in browser
Navigate to the following URL in your web browser:

🔗 http://127.0.0.1:5000

---

## 📸 Screenshots

### Home Page

![WhatsApp Image 2025-04-15 at 11 57 06_d0b1f372](https://github.com/user-attachments/assets/5d5cdf8d-1713-47c4-b8f5-3a143327f470)

### Student Registration

![WhatsApp Image 2025-04-15 at 11 57 06_d6d0ef72](https://github.com/user-attachments/assets/1ae2e154-04d8-4b88-a270-90d933fb9dab)

### Student Login

![WhatsApp Image 2025-04-15 at 11 57 07_dd882a9a](https://github.com/user-attachments/assets/5da6ce17-4535-4a1c-94e9-0f3284bd631a)

### Student Dashboard

![WhatsApp Image 2025-04-15 at 11 57 08_33dc3045](https://github.com/user-attachments/assets/e1af1723-7801-4e90-abf6-2aa8c00af80c)

### Student_reset_password

![WhatsApp Image 2025-04-15 at 11 57 07_ae9a39fb](https://github.com/user-attachments/assets/3951f66e-9260-4698-9367-dd0e35817e09)

### Recruiter Registration

![WhatsApp Image 2025-04-15 at 11 57 09_63e29f2c](https://github.com/user-attachments/assets/cdda7f38-3f82-4781-aa2f-71601d514e39)

### Recruiter Login

![WhatsApp Image 2025-04-15 at 11 57 08_9946ae65](https://github.com/user-attachments/assets/26b6f9a9-b1e7-485c-b349-15bb95420e96)

### Recruiter Password Reset

![WhatsApp Image 2025-04-15 at 11 57 09_2e85f11c](https://github.com/user-attachments/assets/82c73a18-eacc-49d6-bdaa-9bd09696d17e)

### Recruiter Home Page

![WhatsApp Image 2025-04-15 at 11 57 10_fe40c7ad](https://github.com/user-attachments/assets/01c1d315-1f24-43a6-92a2-0260b3531245)

### create_job – Job Posting Page

![WhatsApp Image 2025-04-15 at 11 57 10_17704990](https://github.com/user-attachments/assets/0141e565-730b-4bf0-b665-e1ad02faefbe)

### Job Description for Recruiters

![WhatsApp Image 2025-04-15 at 11 57 08_a12e06b0](https://github.com/user-attachments/assets/d5879c23-a442-4aba-98e4-5c1c975f36ef)


### Report Generation / Summary

![WhatsApp Image 2025-04-15 at 11 57 10_1bcaa783](https://github.com/user-attachments/assets/62bffb38-d19d-4050-87a9-32855fecd932)


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
