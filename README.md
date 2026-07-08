<!-- ═══════════════════════════════════════════════════════════
     HAND-CRAFTED SVG HEADER — no external image service needed
     ═══════════════════════════════════════════════════════════ -->
<div align="center">

<svg width="860" height="180" viewBox="0 0 860 180" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   stop-color="#0d1117"/>
      <stop offset="50%"  stop-color="#0f1923"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
    <linearGradient id="line" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#00FF41" stop-opacity="0"/>
      <stop offset="30%"  stop-color="#00FF41"/>
      <stop offset="70%"  stop-color="#00d4ff"/>
      <stop offset="100%" stop-color="#00d4ff" stop-opacity="0"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- background -->
  <rect width="860" height="180" rx="12" fill="url(#bg)"/>

  <!-- animated scan line -->
  <rect x="0" y="0" width="860" height="2" fill="url(#line)" opacity="0.6">
    <animateTransform attributeName="transform" type="translate" from="0,0" to="0,180" dur="3s" repeatCount="indefinite"/>
  </rect>

  <!-- corner brackets -->
  <text x="18" y="34" fill="#00FF41" font-family="monospace" font-size="20" opacity="0.7">┌─</text>
  <text x="810" y="34" fill="#00FF41" font-family="monospace" font-size="20" opacity="0.7">─┐</text>
  <text x="18" y="168" fill="#00FF41" font-family="monospace" font-size="20" opacity="0.7">└─</text>
  <text x="810" y="168" fill="#00FF41" font-family="monospace" font-size="20" opacity="0.7">─┘</text>

  <!-- prompt prefix -->
  <text x="50" y="76" fill="#00FF41" font-family="'Courier New',monospace" font-size="15" filter="url(#glow)" opacity="0.9">$ whoami</text>

  <!-- main name with glow -->
  <text x="430" y="108" text-anchor="middle" fill="#ffffff" font-family="'Courier New',monospace" font-size="38" font-weight="bold" filter="url(#glow)">
    Mina Robir
  </text>

  <!-- animated underline -->
  <line x1="200" y1="116" x2="660" y2="116" stroke="url(#line)" stroke-width="1.5">
    <animate attributeName="opacity" values="0;1;0" dur="2.5s" repeatCount="indefinite"/>
  </line>

  <!-- subtitle -->
  <text x="430" y="146" text-anchor="middle" fill="#00d4ff" font-family="'Courier New',monospace" font-size="15" opacity="0.85">
    Full Stack &amp; Desktop Engineer  ·  Cairo, Egypt 🇪🇬  ·  Open to Remote
  </text>

  <!-- blinking cursor -->
  <rect x="50" y="82" width="10" height="2" fill="#00FF41">
    <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
  </rect>
</svg>

<!-- ANIMATED TYPING -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&pause=900&color=00FF41&center=true&vCenter=true&width=760&lines=%24+whoami+%E2%86%92+Full+Stack+%26+Desktop+Engineer;%24+uptime+%E2%86%92+4%2B+years+in+production+engineering;%24+stack+%E2%86%92+TypeScript+%7C+React+%7C+Node.js+%7C+PostgreSQL;%24+status+%E2%86%92+Open+to+Senior+Engineering+Roles+%F0%9F%9F%A2;%24+deploy+--target+remote+--region+worldwide)](https://github.com/minarob23)

<!-- BADGES -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mina-robir-1392ab241)
![Location](https://img.shields.io/badge/Cairo-Egypt-0d1117?style=for-the-badge&logo=googlemaps&logoColor=00FF41&labelColor=0d1117&color=00FF41)
![Available](https://img.shields.io/badge/Status-Available_Now-0d1117?style=for-the-badge&logo=statuspage&logoColor=00FF41&labelColor=0d1117&color=00FF41)

</div>

---

<!-- ═══════════ PROFILE ═══════════ -->
<details open>
<summary><b>⚡ <code>> system.profile --full</code></b></summary><br>

```typescript
const mina = {
  name    : "Mina Robir Magdy Fawzy",
  role    : "Full Stack Web & Desktop Application Developer",
  location: "Cairo, Egypt 🇪🇬  →  Open to Remote",
  core    : ["TypeScript", "Node.js", "React", "PostgreSQL", "Docker", "AWS"],

  built: {
    webApps     : "5+ scalable full-stack production applications",
    desktopApps : "3 cross-platform Electron systems",
    b2bPlatform : "50+ manufacturers connected, <200ms API latency",
    traffic     : "5,000+ weekly visits, zero degradation",
  },

  impact: {
    pageLoadSpeed  : "-30%   via lazy loading",
    serverResponse : "-25%   via optimized SQL queries",
    userEngagement : "+15%   session duration uplift",
    desktopOps     : "+40%   faster administrative operations",
  },

  education: [
    "B.Sc. Computer Science  —  Arab Open University  (131 credits)",
    "UK Dual Accreditation   —  The Open University, United Kingdom",
    "ALX Africa SE Intensive —  12-month programme  (2023–2024)",
  ],

  spokenLanguages : { Arabic: "Native", English: "Professional B2", German: "Elementary" },
  currentStatus   : "🟢  Available for Senior Backend & Full-Stack roles",
};
```

</details>

---

<!-- ═══════════ TECH STACK ═══════════ -->
## `> ls ./tech-stack/`

<div align="center">

**◈ Languages**

[![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://python.org)
[![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)](https://java.com)
[![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)](https://isocpp.org)
[![Bash](https://img.shields.io/badge/Bash-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)](https://gnu.org/software/bash)
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)](https://postgresql.org)

**◈ Frontend & Desktop**

[![React](https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)](https://react.dev)
[![Vite](https://img.shields.io/badge/Vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev)
[![Electron](https://img.shields.io/badge/Electron-191970?style=for-the-badge&logo=electron&logoColor=white)](https://electronjs.org)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)

**◈ Backend & Databases**

[![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org)
[![Express](https://img.shields.io/badge/Express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)](https://expressjs.com)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)](https://postgresql.org)
[![MySQL](https://img.shields.io/badge/MySQL-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)](https://mysql.com)
[![SQLite](https://img.shields.io/badge/SQLite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)](https://sqlite.org)
[![Drizzle ORM](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black)](https://orm.drizzle.team)

**◈ DevOps & Cloud**

[![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](https://docker.com)
[![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/features/actions)
[![Vercel](https://img.shields.io/badge/Vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com)
[![Render](https://img.shields.io/badge/Render-%2346E3B7.svg?style=for-the-badge&logo=render&logoColor=white)](https://render.com)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://kernel.org)
[![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com)

</div>

---

<!-- ═══════════ ENGINEERING DNA ═══════════ -->
## `> cat ./engineering-dna.md`

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=15&pause=1000&color=00d4ff&center=true&vCenter=true&width=760&lines=I+build+RESTful+APIs+that+don't+break+under+pressure.;I+design+schemas+that+outlive+the+sprint.;I+ship+UIs+that+users+actually+enjoy.;I+write+code+that+the+next+engineer+can+read.;I+turn+complex+problems+into+elegant+solutions.)](https://github.com/minarob23)

</div><br>

<table>
<tr>
<td width="50%" valign="top">

### 🌐 Web Engineering
```
$ run diagnostics --domain web
  ✔  RESTful API design & versioning
  ✔  pnpm Monorepo architecture
  ✔  SPA routing & lazy loading
  ✔  Secure auth flows
  ✔  Responsive UI — Tailwind + React
  ✔  Sub-200ms API response targets
```
</td>
<td width="50%" valign="top">

### 🗄️ Data & Backend
```
$ run diagnostics --domain backend
  ✔  Normalized PostgreSQL schemas
  ✔  Drizzle ORM & query optimization
  ✔  MVC architecture & clean modules
  ✔  SQLite for embedded/offline apps
  ✔  Bulk transaction handling
  ✔  Data integrity & migration safety
```
</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🖥️ Desktop Engineering
```
$ run diagnostics --domain desktop
  ✔  Cross-platform apps via Electron
  ✔  Local DB management (SQLite)
  ✔  Admin dashboards & inventory UIs
  ✔  File system operations & IPC
  ✔  Offline-first architecture
  ✔  Native OS integration
```
</td>
<td width="50%" valign="top">

### ☁️ DevOps & Deployment
```
$ run diagnostics --domain devops
  ✔  Docker containerisation
  ✔  AWS EC2 & S3 deployments
  ✔  GitHub Actions CI/CD pipelines
  ✔  Vercel & Render deployments
  ✔  Linux server administration
  ✔  Zero-downtime release strategies
```
</td>
</tr>
</table>

---

<!-- ═══════════ METRICS ═══════════ -->
## `> ./metrics --production`

<div align="center">

<svg width="760" height="220" viewBox="0 0 760 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="cardBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"  stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#0f1f0f"/>
    </linearGradient>
    <filter id="glow2">
      <feGaussianBlur stdDeviation="2" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <rect width="760" height="220" rx="10" fill="url(#cardBg)" stroke="#00FF41" stroke-width="1" stroke-opacity="0.4"/>

  <!-- top border glow animation -->
  <rect x="1" y="1" width="758" height="2" rx="1" fill="#00FF41" opacity="0.0">
    <animate attributeName="opacity" values="0;0.8;0" dur="3s" repeatCount="indefinite"/>
  </rect>

  <!-- Title -->
  <text x="380" y="32" text-anchor="middle" fill="#00FF41" font-family="monospace" font-size="13" filter="url(#glow2)" opacity="0.9">── PRODUCTION METRICS ──</text>

  <!-- Row 1 -->
  <text x="40" y="65" fill="#00d4ff" font-family="monospace" font-size="13">📦</text>
  <text x="65" y="65" fill="#adbac7" font-family="monospace" font-size="13">5+   full-stack web apps shipped to production</text>

  <text x="40" y="90" fill="#00d4ff" font-family="monospace" font-size="13">🖥️</text>
  <text x="65" y="90" fill="#adbac7" font-family="monospace" font-size="13">3    cross-platform desktop systems deployed</text>

  <text x="40" y="115" fill="#00FF41" font-family="monospace" font-size="13">⚡</text>
  <text x="65" y="115" fill="#adbac7" font-family="monospace" font-size="13">&lt;200ms  API response latency under bulk load</text>

  <text x="40" y="140" fill="#00FF41" font-family="monospace" font-size="13">📉</text>
  <text x="65" y="140" fill="#adbac7" font-family="monospace" font-size="13">-30%    page load time  ·  -25% server response time</text>

  <text x="40" y="165" fill="#00FF41" font-family="monospace" font-size="13">📈</text>
  <text x="65" y="165" fill="#adbac7" font-family="monospace" font-size="13">+15%    user session duration uplift</text>

  <text x="40" y="190" fill="#00d4ff" font-family="monospace" font-size="13">👨‍🏫</text>
  <text x="65" y="190" fill="#adbac7" font-family="monospace" font-size="13">120+    students coached in maths &amp; computational thinking</text>
</svg>

</div>

---

<!-- ═══════════ GITHUB STATS ═══════════ -->
## `> git log --oneline --stat`

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=minarob23&bg_color=0d1117&color=00FF41&line=00d4ff&point=ffffff&area=true&area_color=00FF4120&hide_border=false&border_color=00FF41&title_color=00FF41)](https://github.com/minarob23)

[![GitHub stats](https://github-readme-stats.vercel.app/api?username=minarob23&show_icons=true&bg_color=0d1117&title_color=00FF41&icon_color=00d4ff&text_color=adbac7&border_color=00FF41&count_private=true&include_all_commits=true&rank_icon=github)](https://github.com/minarob23)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=minarob23&layout=compact&bg_color=0d1117&title_color=00FF41&text_color=adbac7&border_color=00FF41&langs_count=8)](https://github.com/minarob23)

</div>

---

<!-- ═══════════ CREDENTIALS ═══════════ -->
## `> cat ./credentials.txt`

<div align="center">

<svg width="680" height="175" viewBox="0 0 680 175" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="credBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#0a1628"/>
    </linearGradient>
  </defs>
  <rect width="680" height="175" rx="10" fill="url(#credBg)" stroke="#00d4ff" stroke-width="1" stroke-opacity="0.5"/>

  <!-- pulse border -->
  <rect x="1" y="1" width="678" height="173" rx="10" fill="none" stroke="#00d4ff" stroke-width="1">
    <animate attributeName="stroke-opacity" values="0.1;0.6;0.1" dur="4s" repeatCount="indefinite"/>
  </rect>

  <text x="340" y="30" text-anchor="middle" fill="#00d4ff" font-family="monospace" font-size="13">── CREDENTIALS &amp; EDUCATION ──</text>

  <text x="30" y="62"  fill="#FFD700" font-family="monospace" font-size="14">🏆</text>
  <text x="55" y="62"  fill="#ffffff" font-family="monospace" font-size="13" font-weight="bold">ALX Software Engineering Certification</text>
  <text x="55" y="80"  fill="#adbac7" font-family="monospace" font-size="12">    ALX Africa  ·  System Design &amp; Operations  ·  Dec 2024</text>

  <text x="30" y="108" fill="#00FF41" font-family="monospace" font-size="14">🎓</text>
  <text x="55" y="108" fill="#ffffff" font-family="monospace" font-size="13" font-weight="bold">B.Sc. Computer Science  —  131 Credit Hours</text>
  <text x="55" y="126" fill="#adbac7" font-family="monospace" font-size="12">    Arab Open University, Cairo  ·  Aug 2025</text>

  <text x="30" y="154" fill="#00d4ff" font-family="monospace" font-size="14">🇬🇧</text>
  <text x="55" y="154" fill="#ffffff" font-family="monospace" font-size="13" font-weight="bold">UK Open University Dual Validation</text>
  <text x="55" y="170" fill="#adbac7" font-family="monospace" font-size="12">    AOU × The Open University, United Kingdom  ·  Aug 2025</text>
</svg>

</div>

---

<!-- ═══════════ CONTACT ═══════════ -->
## `> ping contact --open`

<div align="center">

```bash
$ curl https://api.minarob23.dev/status
{
  "engineer"  : "Mina Robir Magdy Fawzy",
  "available" : true,
  "location"  : "Cairo, Egypt  →  Remote-friendly",
  "seeking"   : ["Senior Backend", "Full-Stack", "Desktop Engineering"],
  "respond_in": "< 24 hours"
}
```

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mina-robir-1392ab241)

---

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=13&duration=3500&pause=1200&color=555555&center=true&vCenter=true&width=680&lines=Clean+code.+Modular+architecture.+Real+impact.;Shipping+since+2021.+Still+accelerating.;Every+commit+is+a+step+forward.)](https://github.com/minarob23)

<!-- SVG FOOTER -->
<svg width="100%" height="60" viewBox="0 0 860 60" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
  <defs>
    <linearGradient id="footerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#00FF41" stop-opacity="0"/>
      <stop offset="30%"  stop-color="#00FF41"/>
      <stop offset="70%"  stop-color="#00d4ff"/>
      <stop offset="100%" stop-color="#00d4ff" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="0" y1="30" x2="860" y2="30" stroke="url(#footerGrad)" stroke-width="1">
    <animate attributeName="opacity" values="0.2;1;0.2" dur="3s" repeatCount="indefinite"/>
  </line>
  <text x="430" y="52" text-anchor="middle" fill="#333" font-family="monospace" font-size="11">© minarob23 · Cairo, Egypt</text>
</svg>

</div>
