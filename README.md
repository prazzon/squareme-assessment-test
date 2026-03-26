## FundR (SquareMe) Dashboard

A modern, responsive financial dashboard built with Next.js 15, TypeScript, Redux Toolkit, and Tailwind CSS.

## 🚀 Features

-  **Modern Dashboard**: Clean, professional interface with revenue charts and account metrics
-  **Transactions Management**: Comprehensive transaction listing with filtering and pagination
-  **Responsive Design**: Fully responsive design that works on desktop, tablet, and mobile devices
-  **State Management**: Redux Toolkit for efficient state management
-  **Type Safety**: Full TypeScript implementation for better development experience
-  **Testing**: Comprehensive test suite with Vitest and React Testing Library
-  **Accessibility**: WCAG compliant with proper ARIA labels and keyboard navigation

## 🛠️ Tech Stack

-  **Framework**: Next.js 15 with App Router
-  **Language**: TypeScript
-  **Styling**: Tailwind CSS with custom design system
-  **UI Components**: shadcn/ui component library
-  **State Management**: Redux Toolkit
-  **Charts**: Recharts for data visualization
-  **Testing**: Jest + React Testing Library
-  **Icons**: Lucide React

## 📦 Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd fundr-dashboard
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🧪 Testing

Run the test suite:

```bash
npm test
```

Run tests in watch mode:

```bash
npm run test:watch
```

## 📱 Pages

### Dashboard (`/`)

-  Revenue overview with interactive charts
-  Account details with copy functionality
-  Period selection (Today, Last 7 days, Last 30 days)
-  Responsive chart visualization

### Transactions (`/transactions`)

-  Comprehensive transaction listing
-  Advanced filtering by date range and account
-  Pagination with mobile friendly controls
-  Export functionality
-  Responsive table/card layout

### Other Pages

-  Get Started (`/get-started`)
-  Accounts (`/accounts`)
-  Transfers (`/transfers`)
-  Settings (`/settings`)

## 🎨 Design System

The application uses a custom design system built on Tailwind CSS:

-  **Colors**: Custom FundR brand colors with blue primary palette
-  **Typography**: Inter font family for clean, modern text
-  **Components**: Reusable UI components with consistent styling
-  **Responsive**: Mobile-first approach with breakpoint-specific designs

## 🏗️ Architecture

### Project Structure

```
├── app/                    # Next.js app directory
│   ├── globals.css        # Global styles and design system
│   ├── layout.tsx         # Root layout component
│   ├── page.tsx           # Dashboard page
│   └── [pages]/           # Other pages
├── components/            # React components
│   ├── layout/           # Layout components (Header, Sidebar)
│   ├── dashboard/        # Dashboard-specific components
│   ├── transactions/     # Transaction-specific components
│   ├── common/           # Shared components
│   └── ui/               # shadcn/ui components
├── store/                # Redux store
│   ├── slices/          # Redux slices
│   └── api/             # Mock API
├── types/               # TypeScript type definitions
├── hooks/               # Custom React hooks
└── __tests__/           # Test files
```

### State Management

-  **Redux Toolkit** for global state management
-  **Slices** for dashboard and transactions data
-  **Async thunks** for API calls
-  **Mock API** for development and testing
