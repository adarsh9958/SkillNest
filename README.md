
---

# 🎓 SkillNest

> **Real-time AI-Powered Teaching Platform**  
> Learn through interactive voice conversations with AI teaching companions

[![Next.js](https://img.shields.io/badge/Next.js-16.0.1-black)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2.0-blue)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9.3-blue)](https://www.typescriptlang.org/)

<cite></cite>

---

## 📖 Overview

SkillNest is a cutting-edge web application that revolutionizes online learning through AI-powered voice interactions<cite></cite>. Users can engage with specialized AI teaching companions across various subjects, creating personalized learning experiences through natural voice conversations<cite></cite>.

**Key Features:**
- 🤖 Browse and interact with AI teaching companions
- 🎙️ Real-time voice-based learning sessions
- ✨ Create custom AI tutors with personalized teaching styles
- 📊 Track learning progress through session history
- 🔍 Filter and search companions by subject and topic
- 🔐 Secure authentication with subscription-based features

<cite></cite>

---

## 🚀 Live Demo

🔗 **[View Live Demo](https://skill-nest-kappa.vercel.app/)** 

<cite></cite>

---

## 🛠️ Tech Stack / Built With

### **Core Framework**
- **Next.js 16.0.1** - React framework with App Router
- **React 19.2.0** - UI library
- **TypeScript 5.9.3** - Type-safe development

### **Authentication & Database**
- **Clerk** - User authentication and subscription management
- **Supabase** - PostgreSQL database for companions and session history

### **AI & Voice Integration**
- **Vapi AI** - Voice AI orchestration
- **OpenAI GPT-4** - Conversational AI

### **UI & Styling**
- **Tailwind CSS** – Utility-first CSS framework  
- **Radix UI** – Accessible component primitives  
- **Shadcn/UI** – Reusable, themeable components built on Radix and Tailwind  
- **Lucide React** – Icon library  
- **React Hook Form + Zod** – Form management and validation


### **Monitoring & Analytics**
- **Sentry** - Error tracking and performance monitoring

---

## 📦 Installation & Setup

### **Prerequisites**

Ensure you have the following installed:
- **Node.js** (v18 or higher)
- **npm** or **yarn** or **pnpm** or **bun**
- **Git**

<cite></cite>

### **1. Clone the Repository**

```bash
git clone https://github.com/adarsh9958/SkillNest.git
cd SkillNest
```

<cite></cite>

### **2. Install Dependencies**

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
``` 

### **3. Environment Variables**

Create a `.env.local` file in the root directory and add the following:

```env
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Supabase Database
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key

# Vapi AI
NEXT_PUBLIC_VAPI_PUBLIC_KEY=your_vapi_public_key

# Sentry (Optional)
SENTRY_AUTH_TOKEN=your_sentry_auth_token
```

<cite></cite>

### **4. Run Development Server**

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

---

## 🎯 Usage / Example Commands

### **Development**

```bash
# Start development server with hot reload
npm run dev
```

### **Production Build**

```bash
# Build for production
npm run build

# Start production server
npm run start
``` 

### **Code Quality**

```bash
# Run ESLint
npm run lint
```

---

## 📁 Folder Structure

```bash
skillnest/
├── app/                          # Next.js App Router
│   ├── layout.tsx               # Root layout with ClerkProvider
│   ├── page.tsx                 # Homepage (popular companions)
│   ├── companions/              # Companion routes
│   │   ├── page.tsx            # Companions library
│   │   ├── [id]/page.tsx       # Individual companion session
│   │   └── new/page.tsx        # Create companion form
│   ├── my-journey/page.tsx     # User profile and history
│   └── sign-in/[[...sign-in]]/page.tsx  # Clerk auth
│
├── components/                   # React components
│   ├── CompanionCard.tsx        # Companion display card
│   ├── CompanionsList.tsx       # List of companions
│   ├── CompanionComponent.tsx   # Voice session UI
│   ├── Navbar.tsx               # Navigation bar
│   └── ui/                      # Radix UI components
│
├── lib/
│   ├── actions/
│   │   └── companion.actions.ts # Server actions (DB operations)
│   └── utils.ts                 # Utility functions
│
├── constants/                    # Static configuration data
├── public/                       # Static assets
│   └── images/                  # Images and icons
├── next.config.ts               # Next.js + Sentry config
├── package.json                 # Dependencies and scripts
└── README.md                    # Project documentation
```

<cite></cite>

---

## 🤝 Contributing

We welcome contributions to SkillNest! Here's how you can help:

### **Getting Started**

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

<cite></cite>

### **Code Style**

- Follow TypeScript best practices
- Use ESLint for code quality
- Write meaningful commit messages
- Add comments for complex logic

<cite></cite>

### **Reporting Issues**

Found a bug or have a feature request? Please open an issue on GitHub with:
- Clear description of the problem/feature
- Steps to reproduce (for bugs)
- Expected vs actual behavior
- Screenshots (if applicable)

<cite></cite>

---

## 👤 Contact / Author

- Adarsh Pathak 
- 🎓 NIT Hamirpur
- 🔗 [LinkedIn](https://www.linkedin.com/in/adarsh-pathak-a8bb5826a/) | 
      [GitHub](https://github.com/adarsh9958)

<cite></cite>

---

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) - The React Framework
- [Clerk](https://clerk.com/) - Authentication & User Management
- [Supabase](https://supabase.com/) - Open Source Firebase Alternative
- [Vapi AI](https://vapi.ai/) - Voice AI Platform
- [Vercel](https://vercel.com/) - Deployment Platform
- [Sentry](https://sentry.io/) - Error Monitoring

<cite></cite>

---

## 📊 Project Status

🚧 **Active Development** - This project is actively maintained and new features are being added regularly.

<cite></cite>

---

**Made with ❤️ by the SkillNest Team**

---