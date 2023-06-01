# 📸 Photo Tagging App

A fast-paced photo tagging game built with **React** and **Firestore**. Find hidden characters in large images as quickly as possible — it's a fun challenge to test your attention to detail and memory!

![GIF of project](website.gif)

🎮 [**Live Demo**](https://enigma69.web.app/)

---

## 🚀 Features

- 🌙 Light & dark mode support  
- 📱 Fully mobile responsive  
- 🔐 Google authentication  
- 🔍 Zoomable photos for precision  
- 🆘 "Reveal character" hint (available every 60 seconds)  
- 🗺️ Multiple maps with random character placement  
- 🏆 Global leaderboards per map  
- 🙋 Personalized profile with stats & settings  

---

## 🛠️ Getting Started

### Clone the repository

```bash
git clone git@github.com:enpvivek/find-in-photo.git
```

### Move to project directory

```
cd my-odin-projects/photo-tagging
```

### Install dependencies

```bash
npm install
```

### Launch web app  

```bash
npm start
```

### Create a production build

```bash
npm run build
```
---

## 📌 To-Do

- [ ] Add more maps and characters  
- [ ] Introduce character difficulty ratings + improve scoring formula  
- [ ] Show on-screen feedback when the correct character is clicked  
- [ ] Create private Firestore subcollections per user  
- [ ] Add support for additional login methods  
- [x] Build production version  
- [x] Run performance audit with PageSpeed Insights  

---

## ⚙️ Optimizations

- [ ] Use Redux for smarter global state handling  
  - Fetch user data once on load, reuse throughout app  
  - Update state first, then sync with Firestore  
- [ ] Rework how characters are handled  
  - Avoid saving separate images; crop from map using coordinates  
- [ ] Rewrite in TypeScript for better type safety and scalability  

---

## 💡 Planned Features

- [ ] **Map Creator Tool**  
  Let users upload maps, crop characters, and save them to Firestore  
  (Powered by [Cropper.js](https://fengyuanchen.github.io/cropperjs/))  

- [ ] **Website Tour**  
  Use `react-tour` to guide new users through features

- [ ] **Animated Character Reveal**  
  Add card-flip animation when displaying found characters  
