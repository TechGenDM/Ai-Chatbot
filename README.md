# AI Chat App with Agents (GetStream)

A modern AI-powered chat application built with Next.js 15, featuring intelligent agents, real-time messaging, and a beautiful UI powered by shadcn/ui.

## 🚀 Features

- **AI-Powered Chat**: Integrated with OpenAI's GPT models for intelligent conversations
- **Real-time Messaging**: Built on GetStream Chat SDK for instant message delivery
- **Multiple AI Agents**: Support for different AI personalities and use cases
- **Beautiful UI**: Modern, responsive interface using shadcn/ui components
- **Type-Safe**: Full TypeScript support throughout the application
- **Next.js 15**: Built with the latest Next.js features and App Router
- **Dark Mode**: Built-in theme support for better user experience

## 🛠️ Tech Stack

- **Framework**: Next.js 15
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **Chat Infrastructure**: GetStream Chat SDK
- **AI Integration**: OpenAI API
- **State Management**: React Hooks

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- Node.js 18+ 
- npm or yarn or pnpm
- GetStream account and API credentials
- OpenAI API key

## 🔧 Installation

1. **Clone the repository**

```bash
git clone https://github.com/hiteshchoudhary/ai-chat-app-with-agents-getstream.git
cd ai-chat-app-with-agents-getstream
```

2. **Install dependencies**

```bash
npm install
# or
yarn install
# or
pnpm install
```

3. **Set up environment variables**

Create a `.env.local` file in the root directory and add your credentials:

```env
NEXT_PUBLIC_STREAM_API_KEY=your_getstream_api_key
STREAM_SECRET_KEY=your_getstream_secret_key
OPENAI_API_KEY=your_openai_api_key
```

4. **Run the development server**

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

5. **Open your browser**

Navigate to [http://localhost:3000](http://localhost:3000) to see the application.

## 🎯 Usage

1. **Start a Conversation**: Click on the chat interface to begin
2. **Select an Agent**: Choose from different AI agents with unique personalities
3. **Send Messages**: Type your message and press Enter or click Send
4. **Real-time Responses**: Watch as the AI agent responds in real-time
5. **Message History**: All conversations are saved and can be accessed later

## 📁 Project Structure

```
ai-chat-app-with-agents-getstream/
├── app/
│   ├── api/
│   │   └── (API routes)
│   ├── components/
│   │   └── (React components)
│   └── (pages)
├── lib/
│   └── (utility functions)
├── public/
│   └── (static assets)
├── styles/
│   └── (global styles)
├── .env.local
├── next.config.js
├── package.json
└── tsconfig.json
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🙏 Acknowledgments

- OpenAI for the powerful GPT models
- GetStream for the excellent chat infrastructure
- shadcn/ui for the beautiful component library
- Next.js team for the amazing framework

## 📞 Support

If you have any questions or need help, please:

- Open an issue on GitHub
- Join our community discussions
- Check out the [documentation](https://getstream.io/chat/docs/)

---

⭐ If you found this project helpful, please give it a star on GitHub!
