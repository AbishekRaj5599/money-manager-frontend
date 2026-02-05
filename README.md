# Money Manager Frontend

A React.js web application for managing personal finances with income and expense tracking.

## Features

- **Dashboard**: View income/expense summaries with monthly, weekly, and yearly filters
- **Transaction Management**: Add, edit (within 12 hours), and categorize transactions
- **Categories**: Support for various categories like fuel, food, medical, salary, etc.
- **Divisions**: Separate office and personal expenses
- **Filtering**: Filter by date range, category, and division
- **Summary Reports**: Category-wise and division-wise breakdowns
- **Responsive Design**: Built with Tailwind CSS

## Tech Stack

- React.js
- Tailwind CSS
- Lucide React (for icons)
- Local Storage (for data persistence)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/money-manager-frontend.git
cd money-manager-frontend
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Build for Production

```bash
npm run build
```

## Deployment

The application can be deployed to:
- Netlify
- Vercel
- GitHub Pages
- Any static hosting service

## Usage

1. Click "Add Transaction" to add income or expenses
2. Use the dashboard filters to view data by period, category, or division
3. Edit transactions within 12 hours of creation
4. View summaries and breakdowns in the sidebar

## Project Structure

```
src/
├── components/
│   ├── Dashboard.js
│   ├── TransactionModal.js
│   ├── TransactionList.js
│   └── Summary.js
├── App.js
├── index.js
└── index.css
```