# PMChat — Advanced Flutter AI Chat & Calling App & chating app  = super app

A full-featured, production-ready chat application built with **Flutter & Firebase**.

## Features

- 💬 Real-time messaging with read receipts & typing indicators
- 📞 Voice & Video Calls (ZegoCloud) — including **background & killed-state incoming calls**
- 🤖 AI Image Generation in chat
- 💡 Smart Replies & Live Translation (Google ML Kit)
- 🎙️ Voice messages with audio waveform
- 🔔 Push notifications via OneSignal & FCM
- 📁 Media & file sharing (images, videos, PDFs)
- 👥 Contact sync, Group chats, Status/Reels
- 🌙 Dark & Light theme

## Quick Setup

1. Run `flutter pub get`
2. Configure Firebase: `flutterfire configure`
3. Open `lib/utils/app_config.dart` and fill in your API keys:
   - **ZegoCloud** → AppID + AppSign
   - **OneSignal** → App ID + REST API Key
   - **Cloudinary** → Cloud Name + Upload Preset
4. Deploy Firebase Cloud Functions: `firebase deploy --only functions`
5. Run: `flutter run`

📄 See the **Documentation** folder for full step-by-step setup guide.

## Requirements

- Flutter SDK (latest stable)
- Firebase project (Auth, Firestore, Storage, FCM)
- ZegoCloud account (free tier available)
- OneSignal account (free)
- Cloudinary account (free tier available)

---
*Created by [Priyanshu Maurya]*
