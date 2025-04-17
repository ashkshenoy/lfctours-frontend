# 🔴 LFC Tours – Frontend

LFC Tours is a simple CRUD web application that allows users to manage **Liverpool FC fan groups** and view **upcoming events**. This React app serves as the frontend for the LFC Tours platform.

---

## ⚽️ Core Features

- View, create, edit, and delete **fan groups**
- Browse upcoming **events**
- OAuth2-based **user authentication**
- Clean and responsive UI with reusable components

---

## 🧱 Entities & Relationships

The app interfaces with a backend that manages the following core entities:

- **User** – Authenticated via OAuth2
- **Group** – Represents a fan group (e.g., location-based)
- **Event** – Upcoming LFC events tied to fan groups

---

## 🧪 Tech Stack

- **React** (Created using [Create React App](https://create-react-app.dev))
- **React Router**
- **H2 (via backend)** for demo in-memory persistence
- **OAuth2** for authentication

---

## 📁 Key Components

| Component      | Description                        |
|----------------|------------------------------------|
| `GroupList`    | Displays all existing fan groups   |
| `GroupEdit`    | Create or edit a group             |         |
| `Navbar`       | Handles basic navigation/auth info |

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or later)
- Backend running on `http://localhost:8080`

### Installation & Run

```bash
git clone https://github.com/ashkshenoy/lfc-tours-frontend.git
cd lfc-tours-frontend
npm install
npm start
