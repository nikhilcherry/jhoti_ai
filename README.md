<h1 align="center">
  <br>
  <img src="https://img.icons8.com/color/144/ganesha.png" alt="Jyoti AI" width="100">
  <br>
  Jyoti AI — Cosmic Vedic Astrologer 
  <br>
</h1>

<h4 align="center">A 100% AI-powered Vedic astrology platform driven by <a href="https://deepmind.google/technologies/gemini/flash/" target="_blank">Gemini 2.5 Flash</a>.</h4>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#demo">Screenshots</a> •
  <a href="#how-it-works">How It Works</a> •
  <a href="#tech-stack">Tech Stack</a> •
  <a href="#installation">Installation</a>
</p>

---

## 🔮 Overview

**Jyoti AI** (*Jyoti = light in Sanskrit*) is a modern, 100% AI-driven Vedic astrology platform built with Flutter. Designed primarily for the Indian market, it provides accurate, highly contextual, and personalized daily readings and chat interactions based on Rashi (Moon Sign), Nakshatra, and Panchang data.

Instead of generic horoscopes, Jyoti uses strict system prompting and dynamic API token counting to ensure the AI speaks naturally, concisely, and with accurate astrological grounding.

## ✨ Features

- 🤖 **Gemini 2.5 Flash Integration**: Real-time AI chat built on Google's Generative AI with highly structured system instructions.
- 🧠 **Persistent Local Memory**: The AI remembers the context of the entire conversation. Chat history is securely serialized and stored locally on the device using `shared_preferences`.
- 💸 **Dynamic Token Economy**: Points are deducted dynamically based on the exact token cost of the AI's response (1 point per 15 tokens), enforcing a sustainable viral points loop.
- 🗣️ **Multilingual First**: Users can select how the AI speaks to them (English, Hinglish, Hindi, Telugu/Kannada in English script), dynamically adjusting the AI's generation target.
- 🌙 **Vedic Context**: Implements Daily Readings, Panchang computation, Rashi (Zodiac) tracking, and assigns specific remedies (Mantras, Colors, Numbers).
- 🎨 **Cosmic UI/UX**: Premium dark mode aesthetic with glassmorphic cards, vivid astrological colors, and subtle haptic feedback.

## ⚙️ How It Works (The Viral Loop)

Jyoti AI is designed around a **Viral Points Loop** to drive organic growth:
1. Users get a free **Daily AI Reading**.
2. Chatting with Jyoti costs **Points**, calculated dynamically based on AI processing (tokens).
3. Earning Points happens through user retention (Daily Login Streaks) and, eventually, a referral system (Share to Earn).
4. No hard paywalls initially—just a sustainable economy driven by AI engagement.

## 🛠️ Tech Stack

- **Framework:** [Flutter](https://flutter.dev/) (Dart)
- **AI Engine:** [Google Generative AI SDK](https://pub.dev/packages/google_generative_ai) (Gemini 2.5 Flash)
- **State Management:** [Provider](https://pub.dev/packages/provider)
- **Local Storage:** [Shared Preferences](https://pub.dev/packages/shared_preferences)
- **Environment config:** [flutter_dotenv](https://pub.dev/packages/flutter_dotenv)

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/nikhilcherry/jhoti_ai.git
   cd jhoti_ai
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Configure Environment Variables**
   - Create a `.env` file in the root directory.
   - Add your Gemini API Key:
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```

4. **Run the App**
   ```bash
   flutter run
   ```

---
<p align="center"><i>Made with 🪷 in India</i></p>
