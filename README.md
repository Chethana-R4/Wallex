# 👛 Wallex — Smart Expense Tracker & Wealth Intelligence Advisor

**Wallex** is a state-of-the-art, standalone web application designed for personal expense tracking, wealth intelligence, and category budget management in **Indian Rupees (₹)**. Built with React and glassmorphic UI design, Wallex features direct **Supabase PostgreSQL Cloud Database** integration with zero-latency `localStorage` offline fallback.

---

## 🌟 Key Features

### 🇮🇳 1. Native Indian Rupees (₹) Financial Engine
* **`en-IN` Formatting**: Automatically formats all financial metrics, income deposits, expense records, and budget thresholds in Indian Rupees (`₹`).
* **Live Net Cash Flow**: Instant reactive calculation of Net Balance, Monthly Income, Monthly Expenses, and Budget Usage Percentage.

### ⚡ 2. Dual Storage System (Supabase Cloud + LocalStorage)
* **Supabase Cloud Sync**: Direct REST API connection to your own Supabase project tables (`transactions` and `profiles`).
* **Offline Local Storage**: Automatic browser `localStorage` backup ensures zero data loss even when disconnected.
* **1-Click SQL Setup Script**: Embedded SQL generator in the Vault to create tables and configure Row-Level Security (RLS) in 1 click.

### 📊 3. Interactive SVG Donut Pie Chart
* **Visual Expense Analytics**: Interactive SVG donut chart rendering category spending proportions.
* **Hover Inspection**: Real-time arc slice magnification and percentage breakdown on mouse hover.

### 🤖 4. Draggable Voice AI Advisor
* **Financial Assistance**: Interactive floating widget providing instant financial analysis, category breakdown summaries, and saving tips.
* **Voice Speech Recognition**: Speak queries directly to the assistant.
* **Audio Voice Output**: Text-to-speech voice synthesis reads financial advice back to you.

### 🔐 5. Passcode-Gated Financial Vault
* **Confidential Workspace**: Protected by default passcode protection (`vault123`).
* **Session Audit Trail**: Chronological event logging for user logins, transaction entries, deletions, and vault unlocks.
* **Database Backup Export**: 1-click full `JSON` database backup download.

### 👤 6. Authentication & User Profile Management
* **Glassmorphic Auth Portal**: Split-screen interface for `Sign In` and `Create Account`.
* **Session Tracking**: Stores user profile details, organization names, custom monthly limits, and login timestamps.

### 🌗 7. Dynamic Dark & Light Theme Engine
* **Sleek Glassmorphism**: Vibrant gradients, dark mode surfaces, and glowing blur background orbs.
* **High-Contrast Light Mode**: Navy typography (`#0f172a`) ensures high contrast in bright environments.

### 🌐 8. 100% Standalone Single-File Execution
* **Double-Click & Run**: Zero dependencies required. Open `index.html` directly in any web browser without needing `npm` servers or `localhost`.

---

## 🛠️ Technology Stack

* **Frontend Framework**: React 18 (UMD) & ReactDOM 18
* **Database & Cloud**: Supabase JS Client (`@supabase/supabase-js@2`)
* **Styling**: Vanilla CSS3 Glassmorphism with HSL tailored color system
* **Typography**: Google Fonts (`Playfair Display` Serif, `Plus Jakarta Sans` Sans-Serif, `JetBrains Mono` Code)
* **Compiler**: Babel Standalone (In-Browser JSX compilation)

---

## 🚀 Quick Start Guide

1. Clone or download this repository.
2. Double-click **`index.html`** to open it directly in your web browser.
3. To connect your Supabase database:
   - Go to **Financial Vault** (Passcode: `vault123`).
   - Copy the SQL setup script into your Supabase SQL Editor.
   - Enter your **Supabase Project URL** and **Anon API Key** in the Vault settings.
