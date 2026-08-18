# Talkacademy - AI-Powered Learning Management System

Developed a Learning Management System with an AI-powered voice assistant enabling real-time, personalized Q&A.

## 🚀 Key Achievements

- **AI-Powered Voice Assistant**: Developed a Learning Management System with an AI-powered voice assistant enabling real-time, personalized Q&A via Vapi voice API.
- **Modern, Responsive UI**: Built a responsive UI with Tailwind CSS, shadcn/ui, and TypeScript, focusing on component performance and clean user experience.
- **Secure Authentication**: Integrated Clerk for authentication and access control, enabling secure, personalized dashboards with session history and bookmarks.
- **Continuous Delivery**: Successfully deployed the application on Vercel, ensuring continuous delivery, version control, and production-level performance.

## ⚙️ Tech Stack

- **[Next.js](https://nextjs.org/)** - React framework for fast, scalable web applications
- **[TypeScript](https://www.typescriptlang.org/)** - Static typing for better tooling and code quality
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework for custom user interfaces
- **[shadcn/ui](https://ui.shadcn.com/)** - Customizable component library built on Radix UI and Tailwind CSS
- **[Vapi](https://vapi.ai/)** - Voice AI platform for conversational voice agents
- **[Clerk](https://clerk.com/)** - Authentication, user management, and access control
- **[Supabase](https://supabase.com/)** - Open-source backend-as-a-service platform for database and storage
- **[Sentry](https://sentry.io/)** - Error tracking and performance monitoring
- **[Vercel](https://vercel.com/)** - Cloud platform for static and serverless deployment

## 🔋 Features

👉 **AI Voice Tutors**: Take tutoring sessions with voiced AIs specializing in the topics you want to get better at.
👉 **Authentication**: Secure user sign-up and sign-in with Clerk, including Google authentication.
👉 **Bookmarks and Session History**: Let users organize their learning by bookmarking tutors and accessing previous sessions.
👉 **Create a Tutor**: Create your own AI tutors, choosing a subject, topic, and style of conversation.
👉 **Search Functionality**: Find tutors quickly with robust filters and search bar.
👉 **Cross-Device Compatibility**: Fully responsive design that works seamlessly across all devices.

## 🤸 Quick Start

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone <your-repo-url>
cd Talkacademy
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
# Sentry
SENTRY_AUTH_TOKEN=

# Vapi
NEXT_PUBLIC_VAPI_WEB_TOKEN=

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL=/
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL=/

# Supabase
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
```

Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on: [Supabase](https://supabase.com/), [Clerk](https://clerk.com/), [Sentry](https://sentry.io/), [Vapi](https://vapi.ai/).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## 👨‍💻 Author

**Ravishek Kumar**

- [Author Github](https://github.com/Ravishek-Projects)
- [Project Repository](https://github.com/Ravishek-Projects/Talkademy-AI-Powered-Voice-Based-Learning-Platform)
