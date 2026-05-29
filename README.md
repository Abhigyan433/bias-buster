# Bias Buster - AI Powered Bias Detection Platform

## Overview

Bias Buster is an AI-powered web application that analyzes text content and identifies different forms of bias including gender, racial, political, and cultural bias.

The platform provides detailed analysis reports, bias scores, recommendations, and suggested revisions to help users create more balanced and inclusive content.

## Features

- AI-powered bias detection
- Gender bias analysis
- Racial bias analysis
- Political bias analysis
- Cultural bias analysis
- Text-based content analysis
- URL content extraction and analysis
- Detailed bias reports
- Recommendations for improvement
- Analysis history tracking
- Responsive modern UI
- Real-time processing

## Tech Stack

### Frontend

- React 18
- TypeScript
- Vite
- Tailwind CSS
- ShadCN UI
- TanStack Query
- Wouter
- Framer Motion

### Backend

- Flask
- Python 3.11
- GROQ API
- BeautifulSoup
- Flask-CORS

### Database

- PostgreSQL
- Drizzle ORM
- Neon Database

## Project Structure

```text
project/
│
├── client/
│   ├── src/
│   ├── components/
│   └── pages/
│
├── server/
│   ├── routes/
│   ├── services/
│   └── database/
│
├── shared/
│
├── python_backend/
│
├── migrations/
│
└── README.md
```

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/bias-buster.git

cd bias-buster
```

### Install Frontend Dependencies

```bash
npm install
```

### Install Backend Dependencies

```bash
pip install -r requirements.txt
```

## Environment Variables

Create a `.env` file in the root directory:

```env
DATABASE_URL=your_database_url

GROQ_API_KEY=your_groq_api_key
```

## Run Development Server

### Start Python Backend

```bash
cd python_backend

python app.py
```

### Start Frontend

```bash
npm run dev
```

Application will run on:

```text
http://localhost:5000
```

## Available Scripts

```bash
npm run dev
```

Start development server

```bash
npm run build
```

Build production application

```bash
npm run start
```

Start production server

```bash
npm run check
```

Run TypeScript checks

```bash
npm run db:push
```

Push database schema

## API Endpoints

### Health Check

```http
GET /health
```

### Analyze Text

```http
POST /api/analyze
```

Request Example:

```json
{
  "content": "Input text",
  "analysisType": "comprehensive",
  "sensitivity": "standard",
  "inputType": "text"
}
```

## Bias Categories

- Gender Bias
- Racial Bias
- Political Bias
- Cultural Bias

## Future Improvements

- PDF document analysis
- Multi-language support
- Advanced analytics dashboard
- Team collaboration features
- Custom AI model training
- Export reports to PDF

## Screenshots

Add screenshots here

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Push to branch
5. Create a Pull Request

## License

This project is licensed under the MIT License.

## Author

Abhigyan Das

GitHub: https://github.com/Abhigyan433

