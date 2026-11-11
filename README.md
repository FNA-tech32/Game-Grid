# 🎮 Game Grid – Modern Digital Solutions & Agency Platform

[![Next.js](https://img.shields.io/badge/Next.js-15.3.4-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.0.0-blue?style=for-the-badge&logo=react)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.17-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![ShadCN UI](https://img.shields.io/badge/UI-ShadCN_/_Radix-000000?style=for-the-badge&logo=radix-ui)](https://ui.shadcn.dev/)

**Game Grid** is a modern, responsive digital platform and operational web application built with **Next.js 15 (App Router)**, **React 19**, **Tailwind CSS**, and **ShadCN UI / Radix Primitives**. It combines an interactive client-facing marketing website with a comprehensive internal operations dashboard designed for project management, team collaboration, client tracking, and analytics.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Website Pages & Routing](#-website-pages--routing)
  - [Public Marketing Pages](#1-public-marketing-pages)
  - [Authentication Pages](#2-authentication-pages)
  - [Operations & Analytics Dashboard](#3-operations--analytics-dashboard)
- [Project Directory Structure](#-project-directory-structure)
- [Branding & Contact Information](#-branding--contact-information)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Development Server](#development-server)
  - [Build & Production](#build--production)
- [Scripts Reference](#-scripts-reference)
- [Contributing & License](#-contributing--license)

---

## 🌟 Overview

**Game Grid** delivers end-to-end digital solutions, web and mobile application engineering, UI/UX design, and strategic consulting. The application includes both a polished public showcase and an administrative dashboard interface designed with modular components, smooth animations, and clean state handling.

---

## ✨ Key Features

- **Responsive & Modern Design**: Optimized for mobile, tablet, laptop, and ultra-wide desktop viewports.
- **Modern Typography & Glassmorphism**: Tailored color palettes, frosted glass navigation bars, and backdrop-blur cards.
- **Component-Driven Architecture**: Built using accessible Radix UI primitives and ShadCN components.
- **Interactive Widgets**:
  - Floating Live Chat widget with minimized/maximized state.
  - Timed Newsletter signup modal popup.
  - Smooth Scroll-to-Top button.
  - Interactive FAQ accordions and filterable lists.
- **Data Visualization**: Recharts integration for analytics, revenue trends, and activity metrics.
- **Operations Dashboard**: Complete suite for managing clients, projects, team members, reports, and settings.
- **Authentication Flows**: Complete frontend authentication UI for Login, Sign Up, Forgot Password, and Reset Password.

---

## 🛠 Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **Next.js 15** | App Router framework with Turbopack support |
| **React 19** | Component-based UI library |
| **Tailwind CSS 3** | Utility-first CSS styling and responsive layouts |
| **Radix UI / ShadCN UI** | Accessible headless UI primitives (Dialog, Select, Tabs, Dropdowns, etc.) |
| **Lucide React** | Consistent and lightweight vector icons |
| **Recharts** | Interactive charts and visual data graphs |
| **date-fns & React Day Picker** | Date calculation and interactive calendar pickers |

---

## 📄 Website Pages & Routing

### 1. Public Marketing Pages

- [`/`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/page.jsx) – **Home Page**: Hero banner with gradient highlights, key agency metrics, core services overview, portfolio highlights, client testimonials, pricing plans, FAQ, and CTA cards.
- [`/about`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/about/page.jsx) – **About Us**: Company vision, core values, leadership team, agency milestones, and corporate journey.
- [`/services`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/services/page.jsx) – **Services**: Comprehensive breakdown of web engineering, mobile development, UI/UX design, cloud architecture, and digital strategy.
- [`/portfolio`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/portfolio/page.jsx) – **Portfolio**: Filterable case study showcase categorized by Web, Mobile, and UI/UX design projects.
- [`/pricing`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/pricing/page.jsx) – **Pricing**: Tiered packages (Starter, Professional, Enterprise) with feature comparison tables and consultation booking.
- [`/careers`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/careers/page.jsx) – **Careers**: Open positions, department filtering, company culture ("Life at Game Grid"), and employee perks.
- [`/blog`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/blog/page.jsx) – **Blog**: Technology articles, design insights, industry tutorials, search bar, and category filters.
- [`/contact`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/contact/page.jsx) – **Contact Us**: Interactive inquiry form, verified contact details, office location, consultation scheduler, and FAQs.
- [`/terms`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/terms/page.jsx) – **Terms & Conditions**: Terms of service, intellectual property, user responsibilities, and legal team contacts.
- [`/privacy`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/privacy/page.jsx) – **Privacy Policy**: Data governance, security standards, cookie policy, and privacy officer contact information.

### 2. Authentication Pages

- [`/login`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/login/page.jsx) – **Login**: User authentication with credential fields, remember me, and OAuth options.
- [`/signup`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/signup/page.jsx) – **Sign Up**: Account creation with step indicators and password strength meter.
- [`/forgot-password`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/forgot-password/page.jsx) – **Forgot Password**: Password reset request with email dispatch.
- [`/reset-password`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/reset-password/page.jsx) – **Reset Password**: New password setup with verification.

### 3. Operations & Analytics Dashboard

- [`/dashboard`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/dashboard/page.jsx) – **Dashboard Overview**: KPI overview (Active Projects, Total Revenue, Team Members, Completed Tasks), recent activity log, and quick actions.
- [`/dashboard/analytics`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/dashboard/analytics/page.jsx) – **Analytics**: Performance charts, traffic breakdown, conversion statistics, and revenue graphs.
- [`/dashboard/reports`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/dashboard/reports/page.jsx) – **Reports**: Detailed reporting metrics, operational logs, and exportable financial summaries.
- [`/dashboard/projects`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/dashboard/projects/page.jsx) – **Projects List**: Searchable and filterable project grid with deadline and progress meters.
- [`/dashboard/projects/add`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/dashboard/projects/add/page.jsx) – **Add Project**: Project intake form with budget, client selection, priority, and milestone dates.
- [`/dashboard/projects/[id]`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/dashboard/projects/[id]/page.jsx) – **Project Details**: Specific project view with deliverables, milestone progress, and team assignments.
- [`/dashboard/projects/[id]/edit`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/dashboard/projects/[id]/edit/page.jsx) – **Edit Project**: Update project scope, deliverables, and team allocations.
- [`/dashboard/clients`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/dashboard/clients/page.jsx) – **Clients**: Client directory, active contracts, account managers, and contact details.
- [`/dashboard/team`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/dashboard/team/page.jsx) – **Team**: Team member roster, roles, assigned projects, hourly rates, and skill sets.
- [`/dashboard/settings`](file:///c:/Users/QBS%20Accounting/Documents/websites/Game-Grid/src/app/dashboard/settings/page.jsx) – **Settings**: Agency profile settings, notifications, security / two-factor authentication, and password controls.

---

## 📁 Project Directory Structure

```text
Game-Grid/
├── public/                 # Static assets (images, icons, culture photos)
├── src/
│   ├── app/                # Next.js App Router pages and layouts
│   │   ├── about/          # About Us page
│   │   ├── blog/           # Blog and articles page
│   │   ├── careers/        # Careers and job openings
│   │   ├── contact/        # Contact page with interactive form
│   │   ├── dashboard/      # Internal operations & analytics dashboard
│   │   │   ├── analytics/  # Visual chart metrics
│   │   │   ├── clients/    # Client management
│   │   │   ├── projects/   # Project list, detail, and editing
│   │   │   ├── reports/    # Performance reports
│   │   │   ├── settings/   # Profile and agency configuration
│   │   │   └── team/       # Team roster and member cards
│   │   ├── forgot-password/# Recovery page
│   │   ├── login/          # Sign-in page
│   │   ├── portfolio/      # Case studies and showcase
│   │   ├── pricing/        # Pricing plans
│   │   ├── privacy/        # Privacy policy
│   │   ├── reset-password/ # Password reset page
│   │   ├── services/       # Services catalog
│   │   ├── signup/         # Account creation
│   │   ├── terms/          # Terms of service
│   │   ├── globals.css     # Global styles and Tailwind directives
│   │   └── layout.jsx      # Root HTML layout with Header, Footer, Chat, and Modals
│   ├── components/         # Shared React components
│   │   ├── ui/             # Reusable ShadCN / Radix UI components
│   │   ├── header.jsx      # Navigation header with mobile drawer
│   │   ├── footer.jsx      # Site footer with brand info, links, and contact
│   │   ├── live-chat.jsx   # Interactive live chat floating widget
│   │   ├── newsletter-popup.jsx # Timed newsletter modal
│   │   └── scroll-to-top.jsx    # Back-to-top button
│   └── lib/                # Utility helper functions (e.g. cn for Tailwind merge)
├── components.json         # ShadCN component configuration
├── jsconfig.json           # Path aliases (@/* mapping to ./src/*)
├── next.config.mjs         # Next.js build configuration
├── package.json            # Project dependencies and npm scripts
├── postcss.config.js       # PostCSS plugins
├── tailwind.config.js      # Tailwind CSS theme configuration
└── README.md               # Project documentation
```

---

## 🏢 Branding & Contact Information

| Property | Details |
| :--- | :--- |
| **Brand Name** | **Game Grid** |
| **Brand Mark** | **GG** |
| **General & Inquiries** | [contact@gamegrid.com](mailto:contact@gamegrid.com) |
| **Legal Inquiries** | [legal@gamegrid.com](mailto:legal@gamegrid.com) |
| **Privacy Officer** | [privacy@gamegrid.com](mailto:privacy@gamegrid.com) |
| **Phone Number** | [+1 (415) 890-4743](tel:+14158904743) |
| **Office Address** | 750 Battery Street, Suite 400, San Francisco, CA 94111 |
| **Support Hours** | Monday – Friday: 9:00 AM – 6:00 PM EST |

---

## 🚀 Getting Started

### Prerequisites

- **Node.js**: v18.17.0 or later (Node.js 20+ recommended)
- **Package Manager**: `npm`, `pnpm`, or `yarn`

### Installation

1. Clone or navigate to the project directory:
   ```bash
   cd Game-Grid
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   pnpm install
   ```

### Development Server

Run the development server with Turbopack for fast refresh:

```bash
npm run dev
# or
pnpm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

### Build & Production

Create an optimized production build:

```bash
npm run build
npm run start
```

---

## 📜 Scripts Reference

| Script | Command | Description |
| :--- | :--- | :--- |
| `dev` | `next dev --turbopack` | Starts local Next.js development server with Turbopack |
| `build` | `next build` | Compiles and builds the production bundle |
| `start` | `next start` | Runs the compiled production server |
| `lint` | `next lint` | Executes ESLint to verify code quality and formatting |

---

## 🤝 Contributing & License

Contributions, feedback, and pull requests are welcome. This project is free to use and customize for business and personal portfolios.
