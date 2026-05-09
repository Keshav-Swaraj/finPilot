<div align="center">
  <img src="public/logo.png" alt="Welth Logo" width="120" height="120" />
  <h1>Welth - AI-Powered Finance Platform</h1>
  <p>Manage your finances smarter with AI-driven insights, real-time tracking, and automated receipt scanning.</p>

  <p>
    <img src="https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js" alt="Next.js" />
    <img src="https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC?style=for-the-badge&logo=tailwind-css" alt="Tailwind CSS" />
    <img src="https://img.shields.io/badge/Prisma-6-2D3748?style=for-the-badge&logo=prisma" alt="Prisma" />
    <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql" alt="PostgreSQL" />
    <img src="https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge&logo=clerk" alt="Clerk" />
  </p>
</div>

---

<img src="public/banner.jpeg" alt="Welth Banner" width="100%" />

## 🌟 Overview

**Welth** is an intelligent, one-stop finance platform designed to help you take control of your financial life. Whether you're tracking daily expenses, managing multiple bank accounts, or planning a long-term budget, Welth uses advanced AI technology to provide you with actionable insights and simplify your financial management.

## 🚀 Key Features

- **📊 Advanced AI Analytics**: Get deep insights into your spending patterns with AI-powered analytics that help you identify trends and save more.
- **🧾 Smart Receipt Scanner**: Stop manual entry! Simply upload your receipts, and our AI will automatically extract categories, amounts, and dates.
- **📅 Intelligent Budget Planning**: Create and manage budgets with smart recommendations based on your historical spending and financial goals.
- **💳 Multi-Account & Card Support**: Track all your bank accounts and credit cards in a single, unified dashboard.
- **🌍 Multi-Currency Support**: Manage international transactions with real-time currency conversion and global tracking.
- **⚡ Automated Insights**: Receive proactive notifications and recommendations to optimize your finances and avoid overspending.

## 🛠️ Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org/) (App Router, React 19)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Database**: [PostgreSQL](https://www.postgresql.org/) with [Prisma ORM](https://www.prisma.io/)
- **Authentication**: [Clerk](https://clerk.com/)
- **AI Engine**: [Google Gemini AI](https://ai.google.dev/)
- **Workflow & Queue**: [Inngest](https://www.inngest.com/)
- **Email**: [Resend](https://resend.com/) & [React Email](https://react.email/)
- **UI Components**: [Radix UI](https://www.radix-ui.com/) & [shadcn/ui](https://ui.shadcn.com/)
- **Charts**: [Recharts](https://recharts.org/)

## ⚙️ Getting Started

### Prerequisites

- Node.js 18.x or later
- A PostgreSQL database (e.g., Neon, Supabase, or local)
- Clerk account for authentication
- Google Gemini API key

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Keshav-Swaraj/finPilot.git
   cd ai-finance-platform
   ```

2. **Install dependencies:**
   ```bash
   npm install --legacy-peer-deps
   ```

3. **Set up Environment Variables:**
   Create a `.env` file in the root directory and add the following:
   ```env
   # Database
   DATABASE_URL=
   DIRECT_URL=

   # Clerk Auth
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

   # AI & External APIs
   GEMINI_API_KEY=
   RESEND_API_KEY=

   # App URL
   NEXT_PUBLIC_APP_URL=http://localhost:3000
   ```

4. **Initialize the Database:**
   ```bash
   npx prisma generate
   npx prisma db push
   ```

5. **Run the Development Server:**
   ```bash
   npm run dev
   ```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 📁 Project Structure

```text
├── actions/          # Server Actions
├── app/              # Next.js App Router (Pages & API)
├── components/       # Reusable UI Components
├── data/             # Static Data & Constants
├── emails/           # React Email Templates
├── hooks/            # Custom React Hooks
├── lib/              # Utility Functions & Shared Logic
├── prisma/           # Database Schema
└── public/           # Static Assets (Images, Icons)
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
  Built with ❤️ by <a href="https://github.com/Keshav-Swaraj">Keshav Swaraj</a>
</div>
