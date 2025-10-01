# Digital Identity and Protection System

A security-focused educational project designed to help users protect their digital identity on social media (starting with Facebook). The system provides a secure registration process, social media account linking, basic impersonation detection, alerts, and simple reports.

This project is structured to be scalable for future improvements such as AI/ML-based impersonation detection.

🚀 Features

- Secure Registration using National ID (simulated with FAN number).

- Login System for verified users.

- Social Media Linking (Facebook username for now).

- Impersonation Check (Rule-Based ) detects duplicate usernames in the database.

- Alerts & Dashboard to notify users of suspicious activity.

- Report weekly/monthly account security summaries.

- Future Ready: designed to later integrate with Fayda (Ethiopian National ID) and Facebook Graph API.

📚 Project Phases

- Foundation Setup – Project requirements, HTML structure, GitHub repo.

- User Registration – Secure registration & login with FAN number.

- Link Accounts – Add Facebook username and display in dashboard.

- Monitoring & Alerts – Simple rule-based impersonation checks.

- Reports – Summaries and downloadable reports.

- Security & Scalability Prep – Encryption, role-based access, future ML/AI roadmap.

🛠 Tech Stack

- - Frontend: HTML, CSS, JavaScript (React optional for scalability).

- - Backend: Node.js (Express.js)

- - Database: MySQL or PostgreSQL

- - Reports: PDF generation with pdfkit (Node.js)

- - Security: bcrypt for password hashing, HTTPS support

📂 Project Structure
digital-identity-protection/
│── frontend/           # HTML, CSS, JS files
│── backend/            # Node.js Express API
│   ├── routes/         # API routes (auth, accounts, alerts)
│   ├── models/         # Database models
│   └── controllers/    # Business logic
│── database/           # SQL migrations, schema
│── reports/            # Generated reports (PDF or text)
│── docs/               # Documentation, diagrams
│── README.md           # This file

⚡ Quick Start
1. Clone the Repository
```bash
git clone https://github.com/your-username/digital-identity-protection.git
cd digital-identity-protection
```
2. Install Dependencies
```bash
cd backend
npm install
```
3. Setup Database

Install MySQL or PostgreSQL.
```bash
Create a database digital_identity_db.
```
Run the migration file in database/schema.sql.

4. Run the Backend
```bash
npm start
```
5. Open Frontend

Open frontend/index.html in your browser.

🔐 Security Notes

Passwords are hashed using bcrypt.

FAN numbers are simulated (no real Fayda API yet).

Future versions can integrate with Fayda API and Facebook Graph API.

📈 Future Improvements

- Integration with Fayda API for real National ID verification.

- Use Facebook Graph API to monitor real profiles.

- Add image similarity detection for profile photos.

- Role-based admin panel.

- AI/ML-based impersonation detection.

📄 License

This project is for educational purposes only.
You are free to use and modify it for learning, research, or demonstration.

