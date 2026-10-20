# Glide-Chat — Features (Presentation Guide)

## Slide 1 — Idea
- A WhatsApp-like real-time chat app. No phone numbers: just share a room link and everyone who opens it can chat.

## Slide 2 — How chatting works
- After login you get your own room automatically.
- Tap **🔗 Send link** (or **Invite**) and send the link on WhatsApp/Email.
- Your friend opens the link, logs in / signs up and lands in the same room.
- Text, photos and voice messages all work in real time.

## Slide 3 — Features
- 🎤 **Voice messages:** tap the mic, speak, tap again to send (🗑 cancels).
- 👥 **New group** and 📢 **New community** (only the admin can post) — from the ⋮ menu.
- 🟢 **Status:** text or photo, visible for 24 hours.
- 🔳 **QR code:** scan to open the link.
- 🤖 **Glide-Chat AI:** built-in helper (jokes, quotes, time, calculations, app help).
- ⭐ **Favourites**, 🗂 **Archive**, 🔒 **Chat lock** (4–6 digit PIN).
- 🧹 **Clear chat**, 🗑 **Delete chat**, ❓ **Help**, ⚙️ **Settings**.
- Animations on lists, popups, the send button and recording.

## Slide 4 — Technology
HTML + CSS + JS (ES modules) · Firebase Auth + Firestore (real-time onSnapshot) · Cloudinary (photos/voice)

## Demo script (2 minutes)
1. Sign up.  2. Tap "Send link".  3. Open the link in a second browser and sign up another account.  4. Chat: message, photo, voice.  5. Try ⭐ 🔒 🗂.

## Important
- Publish the Firestore Rules from RULES.txt, otherwise messages will not be sent.
- Lock / Favourite / Archive are stored on the current device only.
