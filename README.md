# OrderFlow Marketing Site

A static marketing website for OrderFlow - Complete Order Management for Salesforce CPQ.

## Features

- Responsive design with Tailwind CSS
- Competitive comparison tables
- Pricing information
- Contact form for lead capture
- Salesforce CPQ integration details

## Local Development

```bash
# Install dependencies
npm install

# Start local server
npm run dev

# View site at http://localhost:8080
```

## Railway Deployment

This project is configured for Railway deployment:

1. Connect your GitHub repository to Railway
2. Railway will automatically detect the Node.js configuration
3. The site will be deployed and accessible via Railway's provided URL

## Files

- `index.html` - Main marketing website (serves as homepage)
- `package.json` - Node.js configuration for Railway
- `railway.toml` - Railway deployment configuration
- `README.md` - This file

## Environment Variables

Railway will automatically set:
- `PORT` - Port number for the HTTP server