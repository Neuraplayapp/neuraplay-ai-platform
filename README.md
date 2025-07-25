# NeuraPlay AI Platform

An interactive neuropsychological gaming platform designed to enhance cognitive skills in children through AI-powered games and activities.

## 🌟 Features

### **Games & Activities**
- **Memory Galaxy** - Working memory training with colorful sequences
- **Stop & Go Adventure** - Impulse control and focus exercises
- **Pattern Detective** - Cognitive flexibility and pattern recognition
- **Number Quest** - Numerical skills and problem solving
- **Letter Safari** - Letter recognition and visual processing
- **AI Story Creator** - Creative storytelling with AI-generated content
- **Starbloom Forest Adventure** - Memory challenges and moral decision-making

### **AI-Powered Features**
- **Together AI Integration** - Text and image generation using FLUX.1-schnell-Free
- **Text-to-Speech** - Adjustable speed and replay functionality
- **Dynamic Content** - AI-generated choices and scenarios
- **Personalized Experience** - Age-appropriate content and difficulty

### **User System**
- **XP & Stars** - Gamified learning with progress tracking
- **User Profiles** - Personalized avatars and achievements
- **Progress Analytics** - Detailed game performance metrics
- **Age-Based Content** - Tailored experiences for different age groups

## 🚀 Live Demo

**🌐 Production Site:** https://neuraplaydebug.netlify.app

## 🛠️ Technology Stack

- **Frontend:** React 18 + TypeScript + Vite
- **Styling:** Tailwind CSS
- **AI Services:** Together AI API (FLUX.1-schnell-Free for images, Llama-3.1-8B-Instruct for text)
- **Deployment:** Netlify (Serverless Functions)
- **Voice:** Hugging Face FastSpeech2

## 📁 Project Structure

```
src/
├── components/
│   ├── games/           # Individual game components
│   │   ├── StarbloomAdventureGame.tsx
│   │   ├── MemorySequenceGame.tsx
│   │   ├── InhibitionGame.tsx
│   │   └── ...
│   ├── AIAssistant.tsx  # AI chat assistant
│   ├── AIGame.tsx       # AI story creator
│   └── ...
├── contexts/            # React contexts
├── pages/              # Page components
└── ...
netlify/
└── functions/
    └── api.js          # Serverless API functions
```

## 🎮 Starbloom Forest Adventure

The latest addition to our game collection! This magical adventure game features:

- **15 Interactive Scenes** with memory challenges and moral dilemmas
- **AI-Generated Images** using Together AI FLUX.1-schnell-Free
- **Dynamic Storytelling** with AI-generated choices
- **Cognitive Skill Training** - Memory, Attention, Executive Function
- **Progress Tracking** with XP and stars rewards
- **Text-to-Speech** with adjustable speed

### Cognitive Skills Targeted:
- **Memory** - Remembering sequences and details
- **Attention** - Focusing on specific information  
- **Executive Function** - Making moral decisions
- **Working Memory** - Holding information temporarily
- **Short-term Memory (STM)** - Immediate recall
- **Long-term Memory (LTM)** - Retrieving past experiences

## 🔧 Setup & Development

### Prerequisites
- Node.js 18+
- npm or yarn

### Installation
```bash
git clone https://github.com/Neuraplayapp/neuraplay-ai-platform-v2.git
cd neuraplay-ai-platform-v2
npm install
```

### Environment Variables
Create a `.env` file in the root directory:
```env
VITE_TOGETHER_TOKEN=your_together_ai_token
VITE_HF_TOKEN=your_huggingface_token
```

### Development
```bash
npm run dev
```

### Build
```bash
npm run build
```

### Deploy
```bash
npx netlify-cli deploy --prod --dir=dist
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Together AI** for providing the FLUX.1-schnell-Free image generation model
- **Hugging Face** for FastSpeech2 voice synthesis
- **Netlify** for hosting and serverless functions
- **React & Vite** for the development framework

## 📞 Contact

For questions or support, please open an issue on GitHub or contact the development team.

---

**Made with ❤️ for cognitive development and learning** 