# Smart Receipt Scanner 🧾

A modern web application to scan receipts, extract data automatically, and track your spending. Built with Next.js and Tesseract.js.

![Smart Receipt Scanner Banner](https://images.unsplash.com/photo-1554224155-8d04cb21cd6c?auto=format&fit=crop&q=80&w=1000)

## ✨ Features

- **📸 Instant Receipt Scanning**: Upload receipt images and let the app extract details automatically.
- **🤖 Client-Side OCR**: Uses **Tesseract.js** to run OCR directly in your browser. No data leaves your device!
- **🧠 Smart Analysis**:
  - Automatically detects **Merchant Name**, **Total Amount**, and **Date**.
  - Intelligent **Category Classification** (Food, Transport, Utilities, etc.) based on keywords.
- **📊 Spending Dashboard**:
  - Visual breakdown of expenses by category.
  - Monthly budget tracking.
  - Recent transactions list.
- **💾 Local Storage**: Data is persisted in your browser's local storage.

## 🛠️ Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org/) (App Router)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **OCR**: [Tesseract.js](https://tesseract.projectnaptha.com/)
- **Charts**: [Recharts](https://recharts.org/)
- **Icons**: [Lucide React](https://lucide.dev/)

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Monametsi-s/smart-receipt-scanner.git
   cd smart-receipt-scanner
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the development server**:
   ```bash
   npm run dev
   ```

4. **Open the app**:
   Visit [http://localhost:3000](http://localhost:3000) in your browser.

## 📱 How to Use

1. **Dashboard**: The home page shows your monthly spending summary.
2. **Scan Receipt**:
   - Click the **+** button.
   - Upload a receipt image (JPG, PNG).
   - Wait for the OCR engine to analyze the text.
   - Verify the detected Merchant, Total, and Category.
   - Click **Save Receipt**.
3. **Track Budget**: Watch your spending progress bar on the dashboard!

## 🤝 Credits

Based on the Python concept `idea.py` for a Receipt Scanner & Budget Analyzer.
Ported to a full-stack web application by **Antigravity**.
