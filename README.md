# Tech DaiMass
A company that is into web development for now

**Slogan:** _"Building Bold Digital Beginnings."_

Tech DaiMass is a tech startup offering website development for brands and businesses that don’t yet have an online presence—starting with high-impact sites for photographers and videographers.

---

## 🔧 Tech Stack

### Frontend
- **Framework**: Next.js
- **State Management**: Redux Toolkit
- **Styling**: Tailwind CSS
- **HTTP Requests**: Axios
- **Authentication**: NextAuth.js / JWT

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: PostgreSQL
- **ORM**: Sequelize

---

## 🗂️ Folder Structure

### `/client`
```
/components
/pages
  ├── index.tsx
  ├── about.tsx
  └── contact.tsx
/redux
/styles
/utils
tailwind.config.js
next.config.js
```

### `/server`
```
/controllers
/middlewares
/models
/routes
/services
/utils
config/
  └── database.js
index.js
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-repo/tech-daimass.git
cd tech-daimass
```

### 2. Environment Variables

#### Create `.env` for `/client`:
```
NEXT_PUBLIC_API_URL=http://localhost:5000/api
```

#### Create `.env` for `/server`:
```
PORT=5000
DB_NAME=techdaimass
DB_USER=postgres
DB_PASS=yourpassword
DB_HOST=localhost
JWT_SECRET=supersecurekey
```

### 3. Install Dependencies

#### Frontend:
```bash
cd client
npm install
npm run dev
```

#### Backend:
```bash
cd server
npm install
npx sequelize-cli db:migrate
npm run dev
```

---

## ✅ Features (MVP)

- Landing page with service pitch
- Demo portfolio site for creatives
- User signup/login (JWT)
- Contact form (email support)
- Admin dashboard for site deployments

---

## 📈 Roadmap

- [x] MVP Delivery
- [ ] Automated Client Site Creation System
- [ ] Stripe/PayPal Subscription Billing
- [ ] Analytics Panel for Client Sites
- [ ] AI-Powered Template Customization (Optional Phase 2)

---

## 📬 Contact
Want to contribute, collaborate, or suggest improvements?
Email us at: **support@techdaimass.dev**

---

_This project is built and maintained by Tech DaiMass_
