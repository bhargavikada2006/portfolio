# Premium AI-Powered Full-Stack Portfolio

A high-performance, premium, fully responsive developer portfolio website designed for computer science students and SDE aspirants. Built with **React.js (Vite)**, **Tailwind CSS (v4)**, and **Framer Motion** for premium interactive animations.

## 🚀 Live Demo & Deployment
This website is optimized for performance and is production-ready for deployment on **Vercel** or **Netlify**.
- **Preview Link:** [https://bhargavi-kada-portfolio.vercel.app/](https://bhargavi-kada-portfolio.vercel.app/)

---

## 🎨 Design & Experience Features
- **Modern Color Theme**: Premium dark-mode first design with indigo and violet radial gradients and glassmorphism.
- **Micro Interactions**: Interactive canvas-based drifting background particles, scroll progress indicator, and custom magnet cursor effects.
- **Scroll-Spy Sticky Navbar**: Automatically highlights the active page section as you scroll down.
- **Responsive Layout**: Designed mobile-first for fluid scaling from small smartphones to wide desktop displays.
- **Loading Transition**: Animated glowing loader before site mount.

---

## 📁 Key Sections
1. **Hero Header**: Features an interactive text-typing role cycler, statistics counters, and custom tech floating badges.
2. **Featured Project Card**: Visual spotlight glow effect tracking user pointer coordinates, highlighting the **AI Resume Analyzer & Job Matcher**.
3. **About Me Code IDE**: Visual presentation of biography alongside a mock IDE showing JSON variables.
4. **Interactive timelines**: Professional timeline tracking for both education history and virtual internship milestones.
5. **Interactive Skill Cards**: Category-filtered lists showing progress indicators that animate on viewport entry.
6. **Filterable Certifications**: Credentials gallery separating academic NPTEL certifications and Deloitt/IBM/HP industry simulations.
7. **Contact Form**: Connected with **EmailJS** for instant delivery of inquiry messages.

---

## 🛠️ Technology Stack
- **Framework**: [React.js v19](https://react.dev/)
- **Scaffolding Tool**: [Vite v8](https://vite.dev/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Animations**: [Framer Motion v12](https://www.framer.com/motion/)
- **Icons**: [React Icons](https://react-icons.github.io/react-icons/)
- **Contact Service**: [EmailJS SDK](https://www.emailjs.com/)

---

## ⚙️ Installation & Local Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/portfolio.git
cd portfolio
```

### 2. Install dependencies
```bash
npm install
```

### 3. Configure Environment Variables
Copy the env template or create a `.env` file at the root:
```bash
VITE_EMAILJS_SERVICE_ID=your_emailjs_service_id
VITE_EMAILJS_TEMPLATE_ID=your_emailjs_template_id
VITE_EMAILJS_PUBLIC_KEY=your_emailjs_public_key
```

### 4. Run development server
```bash
npm run dev
```
Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 🛠️ Build & Verification
Compile bundles to ensure everything packages correctly:
```bash
npm run build
```
Verify the production files in the `/dist` folder by previewing locally:
```bash
npm run preview
```

---

## ⚡ Deployment on Vercel
Deploy your portfolio on Vercel in seconds:
1. Push this codebase to **GitHub**.
2. Connect your GitHub repository to [Vercel](https://vercel.com).
3. Set the build commands:
   - **Build Command:** `npm run build`
   - **Output Directory:** `dist`
4. Add the `VITE_EMAILJS_...` environment variables in Vercel's Project Settings dashboard.
5. Click **Deploy**.

---

## 🔮 Future Enhancements
- Integration of a custom ChatGPT-based chatbot to answers recruiters' questions dynamically.
- Interactive terminal dashboard page to play python command-line games.
- PDF generation of Bhargavi's resume directly from the profile data.
