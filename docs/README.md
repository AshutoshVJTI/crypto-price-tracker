# Crypto Price Tracker Documentation

This is the documentation site for the Crypto Price Tracker project, built with Docusaurus.

## Overview

This documentation provides comprehensive information about the Crypto Price Tracker application, including:

- Project setup guide
- Technical implementation details
- API integration
- State management approach
- Challenges and solutions
- Best practices

## Getting Started

### Prerequisites

- Node.js 18.0 or later
- npm (comes with Node.js)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/AshutoshVJTI/crypto-price-tracker.git
cd crypto-price-tracker/docs
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run start
```

The documentation will be available at `http://localhost:3000`.

## Building for Production

To build the documentation for production:

```bash
npm run build
```

This will generate static content in the `build` directory that can be served using any static hosting service.

## Project Structure

```
crypto-docs/
├── docs/                 # Documentation markdown files
├── src/                  # React components and custom pages
├── static/               # Static assets
├── docusaurus.config.js  # Docusaurus configuration
└── sidebars.js           # Sidebar configuration
```

## Customization

The documentation site can be customized by editing the following files:

- `docusaurus.config.js` - Main configuration file
- `sidebars.js` - Sidebar structure
- `src/css/custom.css` - Custom CSS
- `docs/` - Documentation content

## License

This project is licensed under the MIT License - see the LICENSE file for details.
