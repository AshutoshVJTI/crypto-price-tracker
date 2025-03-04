# Crypto Price Tracker

This repository contains a simple cryptocurrency price tracker application built with Next.js and its documentation created with Docusaurus.

## Project Overview

The Crypto Price Tracker is a web application that displays real-time cryptocurrency prices. It features a responsive design, live price updates, and search functionality.

Key features include:
- Display of top 5 cryptocurrencies by market cap
- Automatic data refresh every 60 seconds
- Manual refresh button with loading indicator
- Search functionality to filter cryptocurrencies
- Responsive design for all device sizes

## Repository Structure

This repository is organized into two main directories:

- `/web-app` - The Next.js application for the Crypto Price Tracker
- `/docs` - The Docusaurus documentation site

## Getting Started

### Prerequisites

- Node.js 18.0 or later
- npm (comes with Node.js)

### Web App Setup

1. Navigate to the web app directory:
```bash
cd web-app
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:3000`.

### Documentation Setup

1. Navigate to the documentation directory:
```bash
cd docs
```

2. Install dependencies:
```bash
npm install
```

3. Start the documentation server:
```bash
npm run start
```

The documentation will be available at `http://localhost:3000` (or another port if 3000 is already in use).

## Technical Implementation

### Web App

- **Frontend**: Next.js with App Router, React, TypeScript
- **Styling**: Tailwind CSS, HeadlessUI
- **State Management**: React Query
- **API Integration**: Axios with CoinGecko API

### Documentation

- Built with Docusaurus
- Includes comprehensive information about:
  - Project setup
  - API integration details
  - State management approach
  - Challenges & solutions
  - Best practices

## License

This project is licensed under the MIT License. 