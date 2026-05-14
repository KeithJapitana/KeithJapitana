
<style>
body { margin: 0; padding: 0; }
.wrap { border-radius: var(--border-radius-lg); overflow: hidden; border: 0.5px solid var(--color-border-tertiary); }
</style>
<div class="wrap">
<svg viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg" width="100%">
  <defs>
    <radialGradient id="glow1" cx="30%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#1e40af" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#020617" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glow2" cx="80%" cy="50%" r="40%">
      <stop offset="0%" stop-color="#3b82f6" stop-opacity="0.2"/>
      <stop offset="100%" stop-color="#020617" stop-opacity="0"/>
    </radialGradient>
  </defs>

  <!-- Background -->
  <rect width="800" height="200" fill="#020617"/>
  <rect width="800" height="200" fill="url(#glow1)"/>
  <rect width="800" height="200" fill="url(#glow2)"/>

  <!-- Animated grid lines -->
  <g stroke="#1e3a5f" stroke-width="0.5" opacity="0.4">
    <line x1="0" y1="40" x2="800" y2="40"/>
    <line x1="0" y1="80" x2="800" y2="80"/>
    <line x1="0" y1="120" x2="800" y2="120"/>
    <line x1="0" y1="160" x2="800" y2="160"/>
    <line x1="100" y1="0" x2="100" y2="200"/>
    <line x1="200" y1="0" x2="200" y2="200"/>
    <line x1="300" y1="0" x2="300" y2="200"/>
    <line x1="400" y1="0" x2="400" y2="200"/>
    <line x1="500" y1="0" x2="500" y2="200"/>
    <line x1="600" y1="0" x2="600" y2="200"/>
    <line x1="700" y1="0" x2="700" y2="200"/>
  </g>

  <!-- Animated floating particles -->
  <circle cx="50" cy="100" r="1.5" fill="#3b82f6" opacity="0.6">
    <animate attributeName="cy" values="100;60;100" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;1;0.6" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="150" cy="140" r="1" fill="#60a5fa" opacity="0.4">
    <animate attributeName="cy" values="140;90;140" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.8;0.4" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="250" cy="60" r="2" fill="#1d4ed8" opacity="0.5">
    <animate attributeName="cy" values="60;110;60" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;0.9;0.5" dur="6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="380" cy="150" r="1.5" fill="#3b82f6" opacity="0.3">
    <animate attributeName="cy" values="150;80;150" dur="7s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.7;0.3" dur="7s" repeatCount="indefinite"/>
  </circle>
  <circle cx="480" cy="80" r="1" fill="#93c5fd" opacity="0.5">
    <animate attributeName="cy" values="80;40;80" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;1;0.5" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="600" cy="120" r="2" fill="#2563eb" opacity="0.4">
    <animate attributeName="cy" values="120;70;120" dur="5.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.8;0.4" dur="5.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="720" cy="50" r="1.5" fill="#60a5fa" opacity="0.6">
    <animate attributeName="cy" values="50;130;50" dur="6.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0.9;0.6" dur="6.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="760" cy="160" r="1" fill="#3b82f6" opacity="0.3">
    <animate attributeName="cy" values="160;90;160" dur="4.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.7;0.3" dur="4.5s" repeatCount="indefinite"/>
  </circle>

  <!-- Animated accent line -->
  <line x1="0" y1="198" x2="800" y2="198" stroke="#1e40af" stroke-width="2">
    <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" repeatCount="indefinite"/>
  </line>

  <!-- Left divider -->
  <line x1="520" y1="30" x2="520" y2="170" stroke="#1e3a5f" stroke-width="0.5" opacity="0.8"/>

  <!-- NAME block (left) -->
  <text x="40" y="80" font-family="monospace" font-size="28" font-weight="700" fill="#ffffff" letter-spacing="2">KEITH JASPER</text>
  <text x="40" y="112" font-family="monospace" font-size="28" font-weight="700" fill="#ffffff" letter-spacing="2">JAPITANA</text>
  <rect x="40" y="122" width="50" height="2" fill="#1e40af">
    <animate attributeName="width" values="50;120;50" dur="3s" repeatCount="indefinite"/>
  </rect>
  <text x="40" y="148" font-family="monospace" font-size="10" fill="#475569" letter-spacing="3">AI AUTOMATION · FULL STACK · CRM</text>

  <!-- STATS block (right) -->
  <!-- Stat 1 -->
  <text x="560" y="72" font-family="monospace" font-size="32" font-weight="700" fill="#3b82f6" text-anchor="middle">
    5+
    <animate attributeName="opacity" values="0.7;1;0.7" dur="2s" repeatCount="indefinite"/>
  </text>
  <text x="560" y="88" font-family="monospace" font-size="9" fill="#475569" text-anchor="middle" letter-spacing="2">YEARS EXP</text>

  <!-- Stat 2 -->
  <text x="660" y="72" font-family="monospace" font-size="32" font-weight="700" fill="#3b82f6" text-anchor="middle">
    10+
    <animate attributeName="opacity" values="0.7;1;0.7" dur="2.5s" repeatCount="indefinite"/>
  </text>
  <text x="660" y="88" font-family="monospace" font-size="9" fill="#475569" text-anchor="middle" letter-spacing="2">PROJECTS</text>

  <!-- Stat 3 -->
  <text x="760" y="72" font-family="monospace" font-size="32" font-weight="700" fill="#3b82f6" text-anchor="middle">
    3
    <animate attributeName="opacity" values="0.7;1;0.7" dur="3s" repeatCount="indefinite"/>
  </text>
  <text x="760" y="88" font-family="monospace" font-size="9" fill="#475569" text-anchor="middle" letter-spacing="2">COUNTRIES</text>

  <!-- Dividers between stats -->
  <line x1="610" y1="50" x2="610" y2="110" stroke="#1e3a5f" stroke-width="0.5"/>
  <line x1="710" y1="50" x2="710" y2="110" stroke="#1e3a5f" stroke-width="0.5"/>

  <!-- Bottom links -->
  <text x="560" y="145" font-family="monospace" font-size="9" fill="#1e40af" text-anchor="middle" letter-spacing="1">synthtrix.com</text>
  <text x="660" y="145" font-family="monospace" font-size="9" fill="#1e40af" text-anchor="middle" letter-spacing="1">philippines</text>
  <text x="760" y="145" font-family="monospace" font-size="9" fill="#1e40af" text-anchor="middle" letter-spacing="1">google certified</text>
</svg>
</div>

---

## 👋 ABOUT ME

> **I build systems that save time and generate revenue.**

I'm a **Web Developer & AI Automation Specialist** based in the Philippines with **5+ years** of experience working with service businesses, clinics, agencies, and franchises across the US, Canada, and PH.

I don't just build websites. I build the full system around them — automated client journeys, CRM pipelines, ad campaigns, and AI workflows that keep running without anyone babysitting them.

```
🔭 Currently building  →  Synthtrix — AI-powered marketing & automation systems
🤖 Daily tools         →  Claude Code, N8N, Vapi.ai, MCP, GoHighLevel
🌱 Currently learning  →  Next.js 15, AI Agent Frameworks, Supabase Edge Functions
⚡ Core focus          →  Revenue-driven automation, CRM systems, full stack web apps
📍 Location            →  Silay City, Negros Occidental, Philippines
```

---

## 🛠️ TECH STACK

### 🤖 AI & Automation
<p>
  <img src="https://img.shields.io/badge/Claude_Code-D97706?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/N8N-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/Zapier-FF4A00?style=for-the-badge&logo=zapier&logoColor=white" />
  <img src="https://img.shields.io/badge/Make-6D00CC?style=for-the-badge&logo=make&logoColor=white" />
  <img src="https://img.shields.io/badge/Vapi.ai-020617?style=for-the-badge&logo=microphone&logoColor=white" />
</p>

### 🌐 Web Development
<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/Shadcn/UI-000000?style=for-the-badge&logo=shadcnui&logoColor=white" />
  <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

### 🏗️ CMS & Website Builders
<p>
  <img src="https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white" />
  <img src="https://img.shields.io/badge/GoHighLevel-F97316?style=for-the-badge&logo=gohighlevel&logoColor=white" />
  <img src="https://img.shields.io/badge/WooCommerce-96588A?style=for-the-badge&logo=woocommerce&logoColor=white" />
  <img src="https://img.shields.io/badge/Elementor-92003B?style=for-the-badge&logo=elementor&logoColor=white" />
</p>

### 🗄️ Backend & Infrastructure
<p>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/VPS-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

### 📈 CRM, Ads & SEO
<p>
  <img src="https://img.shields.io/badge/HubSpot-FF7A59?style=for-the-badge&logo=hubspot&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_Ads-4285F4?style=for-the-badge&logo=googleads&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_Analytics-E37400?style=for-the-badge&logo=googleanalytics&logoColor=white" />
  <img src="https://img.shields.io/badge/Semrush-F96611?style=for-the-badge&logo=semrush&logoColor=white" />
</p>

### 🎨 Design
<p>
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img src="https://img.shields.io/badge/Adobe_XD-FF61F6?style=for-the-badge&logo=adobexd&logoColor=white" />
  <img src="https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white" />
</p>

---

## 🚀 RECENT PROJECTS

| Project | Stack | Live |
|---------|-------|------|
| 🔷 **Project Liora** | Next.js · Full-Stack · SEO | [liora.synthtrix.com](https://liora.synthtrix.com/) |
| 💎 **Aesthetics Reps** | Next.js · GoHighLevel · SEO | [aestheticreps.com](https://www.aestheticreps.com/) |
| 🏥 **Cura Nova Care** | Next.js · Full-Stack · SEO | [curanovacare.metask.org](https://curanovacare.metask.org/) |
| 🩺 **Med One** | WordPress · SEO | [medone-1.com](https://medone-1.com/) |
| ⭐ **The Five Star Scale** | GoHighLevel · SEO | [fivestarscale.com](https://www.fivestarscale.com/) |

---

## 💼 WORK EXPERIENCE

```
FranchiseFilming          HubSpot & WordPress | Google Ads | SEO       2025 – 2026
The Five Star Scale       GoHighLevel & WordPress | Google Ads          2024 – 2025
MedOne / Metask           WordPress Developer & Automation Expert       2024 – 2025
Investor Campaign LLC     WordPress Developer & Automation Expert       2024 – 2025
Ayo Biomedical Tech       WordPress Developer & Hardware Engineer       2020 – 2023
Stratium Software Group   Freelance Frontend Web Developer              2019 – 2021
```

---

## 📊 GITHUB STATS

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com?user=KeithJapitana&theme=tokyonight&hide_border=true" />

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e40af,100:020617&height=120&section=footer" />

<p>
  <code>© SYNTHTRIX</code> · 
  <a href="https://synthtrix.com">synthtrix.com</a> · 
  <a href="mailto:keithjapitana@gmail.com">keithjapitana@gmail.com</a>
</p>

</div>
