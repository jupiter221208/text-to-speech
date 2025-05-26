# Text to Speech Converter

A modern web application that converts text to speech using Next.js, Tailwind CSS, and OpenAI's Text-to-Speech API.

## Features

- Clean and modern UI with Tailwind CSS
- Real-time text-to-speech conversion
- Error handling and loading states
- Responsive design

## Prerequisites

- Node.js 18.17 or later
- npm (Node Package Manager)
- OpenAI API key

## Setup

1. Clone the repository:

```bash
git clone <repository-url>
cd text-to-speech
```

2. Install dependencies:

```bash
npm install
```

3. Create a `.env.local` file in the root directory and add your OpenAI API key:

```
OPENAI_API_KEY=your_api_key_here
```

4. Start the development server:

```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Usage

1. Enter or paste your text in the textarea
2. Click "Convert to Speech" button
3. The text will be converted to speech and played automatically

## Technologies Used

- [Next.js](https://nextjs.org/) - React framework
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [OpenAI API](https://openai.com/) - Text-to-Speech service

## License

MIT
