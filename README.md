🌐

A responsive, theme-toggleable landing page built using **React**, **TailwindCSS**, **DaisyUI**, and structured with modular components for smooth user experience and modern design. Built with help from **ChatGPT**.

---

## 📸 Preview

> ![Dark & Light Mode Demo](./public/assets/preview.png)  
*(Replace with actual screenshot)*

---

## 🚀 Features

- 🌞🌚 Light / Dark mode toggle (persistent using `localStorage`)
- 🎥 Custom pre-loader with animated video background
- 🧩 Modular component-based architecture
- 🖼️ Carousel, Parallax sections, testimonials, and stats
- 🎯 Smooth scroll navigation and mobile responsiveness
- ⚡ Built with utility-first TailwindCSS and styled using DaisyUI

---

## 🧱 Tech Stack

| Technology | Description |
|------------|-------------|
| [React.js](https://reactjs.org) | Frontend JavaScript library |
| [Tailwind CSS](https://tailwindcss.com) | Utility-first CSS framework |
| [DaisyUI](https://daisyui.com) | Tailwind CSS component library |
| [ChatGPT](https://chat.openai.com) | AI Assistant used during development |

---

## 🧩 Project Structure

```plaintext
src/
│
├── App.jsx                    # Main entry with loading video + sections
├── assets/                   # Videos, images
├── components/
│   ├── Navbar/               # Responsive Navbar with dark mode
│   ├── Homepage/
│   ├── CustomerSection/
│   ├── Carousel/
│   ├── Parallex/
│   ├── Showcase/
│   ├── Stats/
│   ├── Testimonials/
│   └── Footer/
└── index.css                 # Tailwind + custom styles
````

---

## 📦 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Aadinath1234/PS1-R1-FBE2.0
   cd vibecoders-landing-page
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Run the development server**

   ```bash
   npm run dev
   ```

4. **Build for production**

   ```bash
   npm run build
   ```

---

## 🌓 Dark Mode Support

Dark mode is toggled by applying the `dark` class to the `<html>` element. It uses Tailwind’s class strategy and stores user preference in `localStorage`.

> ⚠️ Ensure all components have Tailwind’s `dark:` variant classes added where necessary (`bg-white dark:bg-black`, etc.)

---

## 📂 Tailwind Config

```js
// tailwind.config.js
export default {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
    "./public/index.html",
  ],
  darkMode: 'class',
  plugins: [require('daisyui')],
};
```

---

## 💡 Acknowledgements

* UI assisted and debugged using [ChatGPT](https://chat.openai.com)
* [DaisyUI](https://daisyui.com) for beautiful component utilities
* [HeroIcons](https://heroicons.com/) (used in navbar menu)

---
