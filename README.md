# Careconnect

**Careconnect** is a modern **job portal application** built with **Next.js**, **TypeScript**, and **Tailwind CSS**. It connects job seekers with employers through a sleek, responsive interface and offers tools for posting and applying to jobs.

---

## 🌟 Features

* 🔍 Browse and search job listings
* 📝 Apply to jobs online
* 🧑‍💼 Employer dashboard to manage postings
* 🔐 Authentication for users and employers
* 📱 Fully responsive UI
* ⚡ Optimized with Next.js performance features

---

## 🛠 Tech Stack

* **Frontend & Backend**: [Next.js](https://nextjs.org/) (Fullstack React Framework)
* **Styling**: Tailwind CSS
* **Language**: TypeScript
* **Database**: MongoDB
* **Authentication**: JWT (JSON Web Tokens)
* **Deployment**: Vercel

---

## 🚀 Getting Started

### Prerequisites

* Node.js ≥ 14.x
* npm or yarn
* MongoDB (Atlas or local)

### Installation

```bash
git clone https://github.com/Soumyajain15/Careconnect.git
cd Careconnect
npm install  # or yarn install
```

### Environment Variables

Create a `.env.local` file in the root directory:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
NEXTAUTH_URL=http://localhost:3000
```

### Running Locally

```bash
npm run dev  # or yarn dev
```

Then visit: [http://localhost:3000](http://localhost:3000)

---

## 📁 Folder Structure

```plaintext
Careconnect/
├── components/         # Reusable components
├── pages/              # Next.js routing structure
│   ├── api/            # API routes (backend logic)
│   └── auth/           # Authentication pages
├── public/             # Static assets
├── styles/             # Tailwind and global CSS
├── utils/              # Utility functions
├── middleware/         # JWT/role-based protection
├── .env.local          # Local environment variables
├── tailwind.config.js  # Tailwind config
├── tsconfig.json       # TypeScript config
└── next.config.js      # Next.js config
```

---

## 📦 Scripts

```json
"dev": "next dev",
"build": "next build",
"start": "next start",
"lint": "next lint"
```

---
![Screenshot (76)](https://github.com/user-attachments/assets/f21bd510-8196-4f77-9017-49ed4de7c728)

## 🌐 Live Demo

🔗 [careconnect-beta.vercel.app](https://careconnect-beta.vercel.app)

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Let me know if you’d like to include screenshots or add instructions for deployment to Vercel or other platforms!
