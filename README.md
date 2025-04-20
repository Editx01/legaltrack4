
# ⚖️ LegalTrack

LegalTrack is an AI-powered web application designed to modernize and simplify the legal process — from FIR assistance to legal support services — all in one platform. Built for users, police departments, and legal professionals, it combines cutting-edge features such as AI legal section prediction, voice-to-text FIR filing, fuzzy name matching, and real-time lawyer booking.

## 🚀 Tech Stack

### Frontend
- **Framework:** React 19 with Next.js 15
- **Styling:** Tailwind CSS, ShadCN UI, Framer Motion
- **Auth:** Clerk Authentication
- **Forms & Validation:** React Hook Form, Zod

### Backend
- **Runtime:** Node.js
- **AI Services:** OpenRouter (OpenAI Compatible)
- **Fuzzy Matching / Legal Prediction Models**
- **PDF Generation:** jsPDF

---

## 📁 Project Structure

```
legaltrack4/
├── backend/               # Node.js backend logic
│   └── index.js           # Backend server entry point
├── legaltrack4/           # Frontend (Next.js)
│   ├── app/               # Pages, layouts, and routes
│   ├── components/        # UI Components
│   ├── public/            # Static files
│   ├── styles/            # Global styles
│   └── utils/             # Helper functions
└── .env.local             # Environment variables
```

---

## ⚙️ Setup Instructions

### 1. Clone the Repo

```bash
git clone https://github.com/Editx01/legaltrack4.git
cd legaltrack4
```

---

### 2. Install Frontend Dependencies

```bash
cd legaltrack4
npm install
```

---

### 3. Set Up Environment Variables

Create a `.env.local` file inside the `legaltrack4` frontend folder:

```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_Zmx5aW5nLXRlcm1pdGUtNjguY2xlcmsuYWNjb3VudHMuZGV2JA
CLERK_SECRET_KEY=sk_test_bUjW0NL2LNQpJYwqdcJVLFkacyAgvJIqT5ro0qBcgf
OPENROUTER_API_KEY=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
```

---

### 4. Run the Frontend

```bash
npm run dev
```

App will be live at [http://localhost:3000](http://localhost:3000)

---

### 5. Run the Backend

In a new terminal:

```bash
cd backend
node index.js
```

> Make sure your backend uses environment variables or hardcoded APIs if needed. Secure this before production.

---

## 🔐 Backend Auth (Optional)

If your backend uses JWTs or API key authentication, set them as environment variables or include them in a secure config file (never commit them to GitHub).

Example for usage:

```env
API_KEY=9cf576e52c46eb91f35a
API_SECRET=1ba8fc772e3ab70b0ab2d03e2a4cf8962cdc5f7c6df2e937b1f6454cb29ac40e
JWT_TOKEN=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

---

## 🧠 Features

- ✅ **AI Legal FIR Assistance**
- 🗣️ **Voice-to-Text FIR Filing**
- 🎯 **Fuzzy Name Matching**
- 📋 **Legal AI Chatbot**
- 📍 **Location-Aware Services**
- 📞 **Emergency Numbers Integration**
- 📅 **Lawyer Appointment Booking**
- 📊 **Charts & Dashboard Visualizations**
- 🧾 **PDF FIR Generation**
- 🌐 **Responsive, Animated UI**

---

## 📸 Screenshots
https://www.loom.com/share/93f92a77695f4cf89ae099fadd3aafef?sid=580bafd6-36ac-440c-ab99-c93553a9278c


## 🧑‍💻 Author

- [@Editx01](https://github.com/Editx01)

---

## 📄 License

This project is licensed under the **MIT License**.

---

> ⚠️ **Security Notice**: Remove or secure all API keys before pushing public commits. Use `.env` files and Git ignore practices.
