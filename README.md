<img width="454" height="528" alt="Knipsel" src="https://github.com/user-attachments/assets/0ca41a94-00f9-4cc6-9048-cf5dd364bcfb" />

# 🧭 Alt1 Hard Clue Helper

An **Alt1 Toolkit app for RuneScape** that assists with **Hard Clue Scrolls** by showing the correct **step-by-step images (PNG)** for each clue.

> ⚠️ **Important:** Due to recent RuneScape updates, Alt1 OCR is currently unreliable. See **Current Status** below.

---

## ✨ Features

- 📜 Hard clue scroll support
- 🖼️ Step-by-step clue images
- 🔍 OCR-based clue detection (when supported by Alt1)
- 🛠️ Manual override (emergency mode)
- 🧩 Clean, modular clue data structure

---

## ✅ What works right now

### ✔️ Alt1 App & UI
- Runs correctly inside **Alt1 Toolkit**
- Buttons, status messages and image display work as intended

### ✔️ Clue data & images
- Hard clues are defined in `clues.js`
- Each clue supports multiple steps
- PNG images load and display correctly

### ✔️ Manual override (recommended for now)
- Clues can be **loaded manually**
- Allows full usage even when OCR is broken

### ✔️ OCR-ready architecture
- OCR keyword logic is fully implemented
- Once Alt1 OCR is fixed, automatic detection will work again without refactoring

---

## ❌ What does NOT work currently

### ❌ Automatic OCR clue detection
Because of a **recent RuneScape game update**, the in-game fonts were changed:

- Alt1 OCR cannot reliably read text
- Keywords are not detected correctly
- Automatic clue recognition often fails

➡️ This is **not a bug in this project**, but a known limitation of Alt1 OCR after game updates.

---

## 🛠️ Recommended workaround (temporary)

Use the app in **manual mode**:

1. Open the app in Alt1 Toolkit
2. Open a clue scroll in RuneScape
3. Manually force the correct clue
4. Follow the displayed PNG steps

This keeps the app **fully usable** until OCR is fixed.

---

## 📦 Why no npm / Vite?

This project is intentionally built using:

- Plain HTML
- Plain JavaScript
- Plain CSS

Alt1 Toolkit:
- does **not** run an npm environment
- works best with simple browser-style apps
- does not benefit from build tools for OCR issues

➡️ Using npm or Vite **does not fix OCR** and is not required.

---

## 🔮 Future plans

Once Alt1 OCR is fixed:
- ✅ Automatic clue detection will work again
- ❌ Manual forcing will no longer be necessary
- 🔄 No major code changes required

Possible future improvements:
- More hard clues
- Elite & master clues
- Step navigation UI
- Settings (auto / manual mode toggle)

---

## 📊 Project status overview

| Feature | Status |
|------|------|
Alt1 compatibility | ✅ Working |
Clue images | ✅ Working |
Clue data | ✅ Working |
OCR detection | ❌ Temporarily broken |
Manual override | ✅ Working |
npm required | ❌ No |

---

## ⚠️ Disclaimer

This project depends on **Alt1 Toolkit OCR**, which may break after RuneScape updates.  
Automatic detection will resume once Alt1 updates their OCR system.

---

## ❤️ Credits

- RuneScape & Clue Scrolls © Jagex
- Built for the Alt1 Toolkit community

