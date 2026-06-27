
# Healthcare Management System

A full-stack Healthcare Management System (HMS) that streamlines interactions between patients and healthcare professionals through two dedicated web applications:

- **Patient Portal** – Enables patients to book appointments, manage their profiles, and access medical records.
- **Doctor Portal** – Allows doctors to manage appointments, configure availability, and maintain patient records.

## Live Demo

- **Patient Portal:** https://hms-patient-portal-nu.vercel.app/
- **Doctor Portal:** https://hms-doctor-portal.vercel.app/

---

## Features

### Patient Portal

- Secure user authentication
- Book appointments based on doctor availability
- View appointment history and upcoming appointments
- Access prescriptions and medical records
- Manage personal profile information

### Doctor Portal

- Secure doctor authentication
- Accept, reschedule, or cancel appointments
- View patient consultation history
- Add consultation notes and prescriptions
- Configure working hours and availability

---

## Technology Stack

| Category | Technologies |
|----------|--------------|
| Frontend | Next.js, Tailwind CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Authentication | JWT |
| Deployment | Vercel |

---

## Project Structure

```text
Healthcare-Management-System/
├── patient-portal/
└── doctor-portal/
```

---

## Installation

### Prerequisites

- Git
- Node.js (v16 or later)
- npm

### Clone the Repository

```bash
git clone https://github.com/Saumyathecoder/Healthcare-Management-System.git
cd Healthcare-Management-System
```

### Install Dependencies

Install dependencies separately for each application.

**Patient Portal**

```bash
cd patient-portal
npm install
```

**Doctor Portal**

```bash
cd ../doctor-portal
npm install
```

---

## Environment Variables

If a `.env.example` file is provided, create a `.env` file by copying it and configure the required environment variables.

```text
cp .env.example .env
```

Typical variables include:

- MongoDB Connection URI
- JWT Secret
- API Keys (if applicable)

---

## Running the Applications

Start both applications in separate terminals.

**Patient Portal**

```bash
cd patient-portal
npm run dev
```

**Doctor Portal**

```bash
cd doctor-portal
npm run dev
```

The applications will be available on the local URLs displayed in the terminal (typically `http://localhost:3000`).

---

## Future Enhancements

- Video consultation support
- Real-time chat between doctors and patients
- Online payment integration
- Email and SMS notifications
- Role-based administration panel

---

## Author

**Saumya Joshi**

GitHub: https://github.com/Saumyathecoder
````
