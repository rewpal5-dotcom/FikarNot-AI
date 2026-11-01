# FikarNot AI — Android App

**FikarNot AI** — aapka smart AI companion. Chat karein, likhwayein, ideas lein — sab ek app mein.

**Direct APK:** https://github.com/rewpal5-dotcom/FikarNot-AI/releases/latest/download/app-debug.apk

## App mein kya hai

- **Home** — logo, tagline aur 4 quick cards (Explain something · Write a message · Create an image · Give me ideas)
- **Chat** — asli chat screen: bubbles, time, typing dots, AI avatar, photo/camera/voice/generate-image buttons
- **History** — pichli baatein phone mein save
- **Settings** — naam, AI mode (Demo / Gemini), API key, chat clear
- **Voice input** — bol kar likhein (phone ka speech engine)
- **Photo attach** — gallery ya camera se photo chat mein
- **Offline** — app ka UI aur demo AI bina internet chalta hai

## AI kaise kaam karta hai

Do modes hain:

1. **Demo mode (default)** — bina internet bhi jawab deta hai (ready-made smart replies). Key ki zaroorat nahi.
2. **Gemini mode** — Settings → "Gemini lagayein" → apni free API key daalein
   ([aistudio.google.com](https://aistudio.google.com/apikey) se milegi). Phir real AI jawab dega.

Key sirf aapke phone mein save hoti hai (localStorage), kahin bheji nahi jaati.

## Tech

Java + WebView · single-file HTML app (`assets/index.html`) · koi library nahi · minSdk 24 · targetSdk 35

## Build

```bash
./gradlew assembleDebug
```

## License

MIT
