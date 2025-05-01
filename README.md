<div align="center">

![NexaCall Banner](https://github.com/yugal1233/nexacall/blob/main/public/images/banner.png)

<div>
  <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logo=typescript&color=3178C6" />
  <img src="https://img.shields.io/badge/-NextJS-black?style=for-the-badge&logo=next.js&color=000000" />
  <img src="https://img.shields.io/badge/-TailwindCSS-black?style=for-the-badge&logo=tailwindcss&color=06B6D4" />
  <img src="https://img.shields.io/badge/-OpenAI-black?style=for-the-badge&logo=openai&color=412991" />
</div>

<h1>NexaCall</h1>
<h3>A Zoom Clone with AI Superpowers</h3>

</div>

---

## 📌 Overview

**NexaCall** is a modern video conferencing platform built as a Zoom alternative, integrated with cutting-edge AI features such as:

- 🔴 **Real-time Live Captions**
- 📝 **Automatic MoM (Minutes of Meeting) Creation**
- 📄 **Full Meeting Transcriptions Stored Securely**

It combines powerful real-time video functionality with intelligent summarization and voice-to-text services, offering a next-gen collaboration experience.

---

## ⚙️ Tech Stack

- **Frontend**: Next.js, TypeScript, TailwindCSS, Shadcn UI
- **Authentication**: Clerk
- **Video Infrastructure**: getstream
- **AI Services**: OpenAI / Whisper (for transcription and summarization)
- **Storage**: Cloud Database (e.g., Firebase, Supabase)

---

## 🚀 Features

### 🎥 Core Conferencing
- Secure authentication (email/password, social)
- Create or join meetings instantly via shareable links
- Schedule and manage future meetings
- Real-time video and audio streams with controls

### 🧠 AI-Powered Enhancements
- **Live Captions**: Real-time transcription of speech using AI
- **Auto MoM Generation**: Intelligent summary and action items at the end of each meeting
- **Transcript Storage**: Persist transcripts in a searchable format

### 💡 Additional
- Emoji reactions, screen sharing, participant management
- Responsive design for all screen sizes
- Personal meeting room with unique links
- View past meetings and recordings

---

## 🤖 AI Capabilities

| Feature | Technology |
|--------|------------|
| Live Captions | Whisper / Deepgram / AssemblyAI |
| MoM Generator | OpenAI GPT-4 Turbo |
| Transcription Storage | Cloud DB with search indexing |

---

## 🛠️ Getting Started

### Prerequisites

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- Clerk & getstream credentials
- OpenAI API key

### 🔧 Installation

```bash
git clone https://github.com/yourusername/nexa-call.git
cd nexa-call
npm install
```

### 📄 Environment Variables

Create a `.env.local` file:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<your-key>
CLERK_SECRET_KEY=<your-key>

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=<your-key>
STREAM_SECRET_KEY=<your-key>

OPENAI_API_KEY=<your-key>
```

### 🚦 Run Locally

```bash
npm run dev
```

Visit `http://localhost:3000` in your browser.

---

## 📂 Project Structure

```
├── app/
├── components/
├── lib/
├── pages/
├── public/
├── styles/
└── utils/
```

---

## 📣 Roadmap

- [x] Live Captioning
- [x] Auto MoM Generation
- [x] Transcript History & Search
- [ ] AI-based speaker diarization
- [ ] Slack/Email integration for MoM delivery

---

## 🤝 Contributing

We welcome contributions! Please fork the repository and create a pull request with a clear description of your changes.

---

## 📃 License

MIT License. See `LICENSE` file for details.

---

## 📬 Contact

Built with ❤️ by Yugal Manwani  
📧 Email: yugalmanwani@email.com  
🌐 [Portfolio](https://yugal-manwani.vercel.app)
