<div align="center">

# Abdur Rahman
### MERN Stack Developer · UI Engineer · Bangladesh 🇧🇩

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3500&pause=1000&color=DC2626&center=true&vCenter=true&width=680&height=60&lines=Building+high-performance+web+applications;React+%7C+Next.js+%7C+Node.js+%7C+MongoDB;Smooth+animations+%26+polished+UX;From+Madrasa+to+Full-Stack+%E2%80%94+Driven+by+Discipline)](https://github.com/abdurrahman253)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-abdurrahman253-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdurrahman253/)
[![Twitter](https://img.shields.io/badge/Twitter-AbdurRahma91153-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/AbdurRahma91153)
[![Email](https://img.shields.io/badge/Email-abrahman5676%40gmail.com-DC2626?style=flat-square&logo=gmail&logoColor=white)](mailto:abrahman5676@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Live-DC2626?style=flat-square&logo=vercel&logoColor=white)](https://github.com/abdurrahman253)
![Open to Work](https://img.shields.io/badge/Status-Open%20to%20Work-22c55e?style=flat-square)

</div>

---

## Who I Am

I'm a self-taught MERN Stack Developer based in Dhaka, Bangladesh. I began coding at the start of 2025, coming from a Qawmi Madrasa background — and that academic foundation gave me something most developers underestimate: the discipline to go deep on difficult subjects, the patience to understand systems fully, and the habit of consistent daily practice.

In under a year, I went from zero programming knowledge to building full-stack applications with authentication, payment integrations, real-time features, and production-grade UX — including animated portfolios, marketplace platforms, and multi-role dashboards.

I build things that are fast, polished, and architected to scale.

---

## Development Philosophy

```ts
const philosophy = {
  code:    "Readable before clever. Simple before complex.",
  design:  "Every pixel and transition should feel intentional.",
  growth:  "Depth over breadth — master the fundamentals, everything else follows.",
  process: "Ship real things. Feedback from production beats theory every time.",
  mindset: "Discipline is the system. Curiosity is the fuel.",
};
```

I don't chase trends. I understand the **why** behind the tools I use — from how GSAP's ticker works under the hood, to why Lenis smooths scroll by overriding native behavior, to how JWT stateless auth differs from session-based systems. That depth shows up in the quality of the work.

---

## Tech Stack

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

### Backend & Database
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![JWT](https://img.shields.io/badge/JWT-D63AFF?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)

### Tooling & Workflow
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-BD34FE?style=flat-square&logo=vite&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![React Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=axios&logoColor=white)

---

## What I Actually Build

I don't build tutorial projects. Every project I've shipped solves a real problem and demonstrates a real capability.

**ScholarStream** — A full-stack scholarship management platform with role-based access control, Stripe payment processing, applicant-organization matching across 500+ scholarships, and a real-time analytics dashboard. Built with the full MERN stack, Firebase Auth, TanStack Query, and React Hook Form.

**CarHub** — A global EV import/export marketplace with a premium dark UI, live chat support, dual authentication (Firebase + JWT), and smooth Framer Motion transitions throughout. The design system is built entirely custom — no component library shortcuts.

**PlayHub** — A gaming discovery platform with GSAP-powered scroll animations, a live winners feed, and DaisyUI components composed into a cohesive dark aesthetic. Performance was a first-class concern throughout.

**This Portfolio** — A production-grade Next.js site with a custom GSAP/Lenis smooth scroll system, a physics-based cursor (dot + ring + glow trail, three-layer), scramble-text animations, scroll-triggered reveals, dark/light theming via `next-themes`, and a contact system wired to EmailJS. Every interaction is deliberate.

---

## Engineering Highlights

Things a code reviewer would notice in my work:

- **Scroll architecture** — Built with Lenis for butter-smooth scroll, coordinated with GSAP ScrollTrigger for precise animation timing. The two systems are synchronized without race conditions.
- **Cursor system** — Three-layer custom cursor (dot, ring, glow blob) animated via GSAP with `overwrite: 'auto'` for conflict-free parallel tweens. Gracefully degrades on touch/mobile via `pointer: coarse` detection.
- **Theme system** — `next-themes` with `suppressHydrationWarning` correctly handled. Token-based color system applied consistently across all components — no hardcoded dark/light values scattered through JSX.
- **Component composition** — Complex UI broken into focused primitives (`Field`, `InfoCard`, `SocialLink`, `Toast`) with clear prop contracts. No god components.
- **Animation cleanup** — Every GSAP context is properly reverted (`ctx.revert()`) on unmount. Every IntersectionObserver is disconnected. No memory leaks.
- **Mobile-first responsive** — CSS Grid layouts with targeted breakpoints. Order manipulation for mobile reflow. No layout shift on resize.
- **Form validation** — Client-side validation with animated error states via Framer Motion's `AnimatePresence`. EmailJS integration with loading, success, and error states fully handled.

---

## AI-Augmented Workflow

Modern development is a collaboration between the developer's judgment and AI capabilities. My workflow reflects that:

- I use AI tools to accelerate implementation of patterns I already understand — not to generate code I can't explain.
- I review, refactor, and own every line that ships. If I can't explain why something works, it doesn't go in.
- I use AI to explore edge cases, think through architecture decisions, and stress-test my own reasoning.
- The result: I ship faster without sacrificing code quality or depth of understanding.

This is the developer profile that matters in 2025 — someone who combines strong fundamentals with effective use of modern tooling.

---

## GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=abdurrahman253&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d0d0d&title_color=DC2626&icon_color=DC2626&text_color=94a3b8&count_private=true&include_all_commits=true" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com?user=abdurrahman253&theme=github-dark-blue&hide_border=true&background=0d0d0d&ring=DC2626&fire=DC2626&currStreakLabel=DC2626&sideLabels=64748b&currStreakNum=f1f5f9&sideNums=f1f5f9&dates=475569" />

<br/>

<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=abdurrahman253&layout=compact&theme=github_dark&hide_border=true&bg_color=0d0d0d&title_color=DC2626&text_color=94a3b8&langs_count=8" />

</div>

---

## Currently

- 🔨 Deepening backend architecture knowledge — REST API design, auth patterns, database modeling
- 📐 Exploring TypeScript for type-safe full-stack development
- 🌱 Open to junior/mid frontend or full-stack roles and freelance projects
- 📬 Available for work — response time under 24 hours

---

## Let's Work Together

If you need a developer who writes clean, production-ready code and cares about the details — from architecture decisions down to animation easing curves — I'd like to talk.

<div align="center">

[![Email Me](https://img.shields.io/badge/Email_Me-DC2626?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abrahman5676@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdurrahman253/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/abdurrahman253)
[![Twitter](https://img.shields.io/badge/Twitter-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/AbdurRahma91153)

**Open to:** Freelance projects · Junior developer roles · Collaborative builds · Remote work

</div>

---

<div align="center">
<sub>Built with discipline. Shipped with intention. Every single day.</sub>
</div>
