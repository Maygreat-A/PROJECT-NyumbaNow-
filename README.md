# PROJECT-NyumbaNow-
A school midterm project focused on solving the Nairobi house hunting hassle.
---

# **NyumbaNow**

**NyumbaNow** is a tenant-driven web application that connects tenants in Nairobi to landlords and agents. It simplifies house hunting by allowing tenants to post requests, browse listings, and get referrals while ensuring trust, privacy, and community-driven recommendations.

---

## **Table of Contents**

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Tech Stack](#tech-stack)
4. [System Requirements](#system-requirements)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Project Structure](#project-structure)
8. [Contributing](#contributing)
9. [License](#license)

---

## **Project Overview**

NyumbaNow solves the **major pain points tenants face in Nairobi**:

* Difficulty finding verified and available housing.
* Lack of transparent demand information.
* High risk of scams and fake listings.
* Limited community-driven referrals.

With NyumbaNow:

* Tenants can **post private or public housing requests**.
* Landlords/agents can **see requests that match their listings**.
* Tenants can **refer trusted agents or landlords**.
* Admins monitor activity and maintain trust.

---

## **Features**

### **Tenant Features**

* Sign-up / login and profile management
* Browse listings without creating an account
* Post housing requests (private or public)
* Track request status (matched, pending, visited)
* Submit and view referrals for agents/landlords
* In-app chat with landlords/agents
* Rate landlords/agents and report scams

### **Landlord/Agent Features**

* Add/manage property listings (photos, location, rent, availability)
* Respond to tenant requests
* Claim referral profiles
* Verified badge for trusted landlords/agents

### **Admin Features**

* Approve or ban suspicious accounts
* Monitor referrals, listings, and requests
* Dashboard analytics for tenant demand and agent activity

---

## **Tech Stack**

* **Frontend:** React (SPA) + TypeScript / JavaScript
* **Backend:** Node.js + Express
* **Database:** PostgreSQL
* **Other Tools:** Axios (API requests), JWT (authentication), bcrypt (password hashing)

---

## **System Requirements**

### **Functional Requirements**

* Tenant requests (private/public)
* Landlord listings management
* Referrals and reviews
* Matching system between tenants and landlords
* Basic chat/contact functionality
* Admin moderation and analytics

### **Non-Functional Requirements**

* Scalable to 1000+ concurrent users
* Secure user authentication and encrypted data
* 99% uptime with cloud hosting
* Mobile-friendly UI
* Future-ready for mobile app expansion

---

## **Installation**

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/nyumbanow.git
```

2. Navigate to the backend folder and install dependencies:

```bash
cd backend
npm install
```

3. Setup PostgreSQL and create database `nyumbanow_db`. Update `.env` file with credentials.
4. Run backend server:

```bash
npm run dev
```

5. Navigate to frontend folder and install dependencies:

```bash
cd frontend
npm install
```

6. Run frontend server:

```bash
npm start
```

7. Access the app at `http://localhost:3000`

---

## **Usage**

* Tenants can browse listings, post requests, and submit referrals.
* Landlords can add properties and respond to tenant requests.
* Admins can manage users, listings, and view analytics dashboards.

---

## **Project Structure (Suggested)**

```
nyumbanow/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.js
│   └── package.json
│
├── README.md
└── .gitignore
```

---

## **Contributing**

1. Fork the repository
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m "Description"`)
4. Push to the branch (`git push origin feature-name`)
5. Open a pull request

---

## **License**

This project is for **educational purposes** as a midterm project.

---

