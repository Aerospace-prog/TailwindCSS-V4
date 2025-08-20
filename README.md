# 🌊 TailwindCSS V4 Setup Guide  

Quick & smooth checklist to set up **Tailwind v4** in any project 🚀  

---

## ⚡ 1. Install Tailwind
```bash
npm install -D tailwindcss
```
## ⚡ 2. Create Config
```bash
npx tailwindcss init
```
<code>tailwind.config.js</code>

```bash
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

<code>src/index.css</code>
```bash
 @import "tailwindcss";
```
  
## ⚡ 3. Import CSS in entry file
  <code>In main.jsx (or main.tsx):</code>
  ```bash
  import "./index.css"
  ```
## ⚡ 4. Run The Project
```bash
npm run dev
```
