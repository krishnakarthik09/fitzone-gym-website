# 🏋️ FitZone Gym Membership Management System

![Project Status](https://img.shields.io/badge/Status-Live-brightgreen) ![Tech](https://img.shields.io/badge/Frontend-HTML%20%7C%20CSS%20%7C%20JS-blue) ![Backend](https://img.shields.io/badge/Backend-Anvil%20Works-orange)

## 🔗 Live Demo

👉 [Click here to visit FitZone Website](https://krishnakarthik09.github.io/fitzone-gym-website/)

---

## 📌 Project Overview

**FitZone Gym Membership Management System** is a full-stack web application that lets users browse gym membership plans and register online. When a user submits the registration form, the system automatically sends **two separate email notifications** — one to the **gym admin/owner** with complete member details, and one to the **user** confirming their registration — making it a real-world, fully automated system.

---

## ✨ Key Features

| Feature                     | Description                                                  |
| ---------------------------- | -------------------------------------------------------------|
| 🎨 Responsive Frontend        | Clean, mobile-friendly gym website                            |
| 💰 Membership Plans           | Basic (₹999), Premium (₹1999), Elite (₹2999)                  |
| 📋 Detailed Registration Form | Captures Name, Mobile, Address, Weight, Personal Training, Plan |
| 🗄️ Database Storage          | Member details saved automatically in database                |
| 📧 Dual Email Notification    | Admin gets full member details + User gets a confirmation email |
| 🚀 Live Deployment            | Hosted on GitHub Pages + Anvil Works                          |

---

## 🔥 How It Works

```
User visits website
       ↓
User clicks "Get Membership" button
       ↓
Registration form opens (Anvil Works)
       ↓
User fills Name, Mobile, Address, Weight, Personal Training need, Plan
       ↓
Data saved to Database automatically
       ↓
Admin receives a detailed Email 📧 (full member info)
       ↓
User receives a Confirmation Email 📧 (registration success)
```

---

## 🛠️ Tech Stack

| Layer         | Technology Used                  |
| ------------- | --------------------------------- |
| Frontend      | HTML, CSS, JavaScript              |
| Backend       | Anvil Works (Python-based)         |
| Database      | Anvil Works Built-in Database      |
| Email Service | Anvil Works Email Module           |
| Deployment    | GitHub Pages + Anvil Works Cloud   |

---

## 📧 Email Notification System (Highlight)

> This is the most important feature of this project — fully automated, two-way communication with zero manual effort.

**📩 Admin Email** — sent instantly to the gym owner with complete registration details:

```
Name: {name}
Mobile: {mobile}
Address: {address}
Weight: {weight}
Personal Training: {personal}
Plan: {plan}
```

**📩 User Email** — sent to the registering user confirming their membership:

```
Hello {name},

Your FitZone Gym membership registration is successful.
Selected Plan: {plan}

Our team will contact you soon.
Thank You.
```

- No manual follow-up needed — both admin and user are notified the moment the form is submitted
- Built using **Anvil Works Email API**
- Improves user trust (instant confirmation) and admin efficiency (all info delivered upfront)

---

## 📸 Screenshots

### Homepage
[View Homepage](https://krishnakarthik09.github.io/fitzone-gym-website/)

### Membership Plans
- Basic Plan — ₹999/month
- Premium Plan — ₹1999/month
- Elite Plan — ₹2999/month

---

## 🚀 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/krishnakarthik09/fitzone-gym-website.git

# Open index.html in browser
open index.html
```
> Note: For backend features (form submission, database storage, and email notifications), visit the live link above — these are powered by Anvil Works and require the hosted backend.

---

## 👨‍💻 What I Learned

- Building a responsive, multi-section frontend website
- Integrating a third-party full-stack platform (Anvil Works) with Python
- Designing forms that capture detailed, structured user data
- Working with a backend database to store and manage registrations
- Implementing **automated, role-based email notifications** (separate templates for admin vs. user)
- Deploying and maintaining a live project using GitHub Pages

---

## 📞 Contact

**Krishna Karthik**

- 📧 Email: krishnakart209@gmail.com
- 📍 Location: Hyderabad, Telangana
- 🔗 GitHub: [krishnakarthik09](https://github.com/krishnakarthik09)

---

## 📄 License

This project is open source and available for learning purposes.

---

⭐ *If you found this project useful, please give it a star on GitHub!*
