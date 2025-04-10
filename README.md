# Scrape Design

A powerful web application that transforms website content into shadcn components using AI. This tool combines web scraping capabilities with Google Gemini 2.5 Pro to automatically convert website data into reusable UI components.

## 🚀 Features

- **Web Scraping**: Extract content from any website using ScraperAPI
- **AI-Powered Conversion**: Transform scraped content into shadcn components using Google Gemini 2.5 Pro
- **Live Preview**: Real-time preview of generated components
- **Code Editor**: Built-in Monaco editor for code editing and customization
- **Modern UI**: Built with shadcn/ui components and Tailwind CSS
- **Responsive Design**: Works seamlessly across all devices

## 🛠️ Technology Stack

- **Frontend**: Next.js 15, React 19
- **UI Components**: shadcn/ui, Tailwind CSS
- **AI Integration**: Google Gemini 2.5 Pro
- **Web Scraping**: ScraperAPI SDK
- **Code Editor**: Monaco Editor
- **Type Safety**: TypeScript
- **State Management**: React Hooks

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/scrape-design.git
cd scrape-design
```

2. Install dependencies:
```bash
pnpm install
# or
npm install
# or
yarn install
```

3. Create a `.env` file in the root directory and add your API keys:
```env
SCRAPER_API_KEY=your_scraper_api_key
GOOGLE_AI_API_KEY=your_google_ai_api_key
```

4. Start the development server:
```bash
pnpm dev
# or
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## 🎯 Usage

1. Enter the URL of the website you want to scrape
2. The application will fetch the content using ScraperAPI
3. The content will be processed by Google Gemini 2.5 Pro to generate shadcn components
4. Preview and edit the generated components in the built-in editor
5. Copy the generated code for use in your projects

## 🏗️ Project Structure

```
scrape-design/
├── app/                    # Next.js app directory
│   ├── scraper/           # Scraper page and layout
│   └── page.tsx           # Main page
├── components/            # React components
│   ├── ui/               # shadcn/ui components
│   ├── scraper-form.tsx  # Scraper form component
│   ├── preview.tsx       # Preview component
│   └── editor.tsx        # Code editor component
├── lib/                  # Utility functions
├── types/               # TypeScript type definitions
└── public/              # Static assets
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
