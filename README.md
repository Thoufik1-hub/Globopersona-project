# Globopersona Frontend

A modern email marketing platform built with Next.js.

## Getting Started

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

- `src/app/` - Next.js app router pages
- `src/components/` - Reusable UI components
- `src/data/` - Mock data
- `src/styles/` - Global styles

## Deployment

### Build for Production
```bash
npm run build
```

### Deploy to Vercel
1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Login to Vercel:
```bash
vercel login
```

3. Deploy:
```bash
vercel --prod
```

### Deploy to GitHub Pages
1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Use a static export build

## Features

- Responsive dashboard with metrics
- Campaign management with search and filter
- Contact list management
- Email automation workflows
- Analytics and reporting
- User settings and help