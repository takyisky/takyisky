<!--
  ╔═══════════════════════════════════════════════════════════╗
  ║  takyisky · github profile readme                         ║
  ║  brand: gold #D4AF37 · black #0A0A0B · teal #14B8A6       ║
  ╚═══════════════════════════════════════════════════════════╝
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0A0A0B,50:14B8A6,100:D4AF37&text=Takyi&fontColor=ffffff&fontSize=70&fontAlignY=32&desc=Sports%20Data%20Infrastructure%20for%20Africa&descSize=16&descAlignY=52&animation=fadeIn" width="100%" />

![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=3200&pause=900&color=D4AF37&center=true&vCenter=true&width=700&lines=Founder+%26+Solo+Engineer+%40+SportCache;Live+timing%2C+results+%26+broadcast+for+African+athletics;FastAPI+%C2%B7+Next.js+%C2%B7+Postgres+%C2%B7+scikit-learn;Final-year+Computer+Science+%40+University+of+Ghana)

<p>
  <a href="https://sportcache.com"><img src="https://img.shields.io/badge/SportCache-D4AF37?style=for-the-badge&logoColor=0A0A0B&labelColor=0A0A0B" /></a>
  <a href="https://docs.sportcache.com"><img src="https://img.shields.io/badge/API_Docs-14B8A6?style=for-the-badge&logoColor=white&labelColor=0A0A0B" /></a>
  <a href="mailto:YOUR_EMAIL_HERE"><img src="https://img.shields.io/badge/Get_in_touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0A0A0B" /></a>
</p>

<p>
  <img src="https://img.shields.io/badge/Accra-Ghana%20%F0%9F%87%AC%F0%9F%87%AD-0A0A0B?style=flat-square&labelColor=0A0A0B&color=D4AF37" />
  <img src="https://img.shields.io/badge/Open%20to-Freelance%20%26%20Contract-0A0A0B?style=flat-square&labelColor=0A0A0B&color=14B8A6" />
  <img src="https://komarev.com/ghpvc/?username=takyisky&style=flat-square&color=D4AF37&label=Profile+Views" />
</p>

</div>

---

## <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="28"> whoami

I build the software that runs athletics meets. Live timing ingestion, results, broadcast graphics, and the API other people build on top of. It's called **SportCache**, I'm the only engineer on it, and it's been live at real championships across Ghana and the wider continent.

Most sports data infrastructure was never built with African federations in mind. So I built it.

```ts
const takyi = {
  role:      "Founder & Solo Engineer, SportCache",
  location:  "Accra, Ghana 🇬🇭",
  studying:  "BSc Computer Science, University of Ghana (final year)",
  building:  ["live timing pipelines", "sports APIs", "broadcast overlays", "ML on race data"],
  stack:     ["Python", "TypeScript", "FastAPI", "Next.js", "Postgres"],
  standards: ["World Athletics", "UCI"],
  hardware:  ["Vsports PT-600 photo-finish", "Lynx timing systems"],
  openTo:    "sports tech, data infrastructure, backend & full-stack contracts",
};
```

---

## <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="28"> SportCache

> Data infrastructure for athletics and cycling events across Africa. Built solo, deployed at real meets.

<table>
<tr>
<td width="50%" valign="top">

### 🏟️ Live at real competitions
- Accra Open Championship
- Senior African Athletics Championship
- Cape Coast Open Championship
- PruRide Ghana · Tour du Ghana (cycling)

Partnered with **SEED Afrique** and **Ghana Athletics**.

</td>
<td width="50%" valign="top">

### 🧩 What's under the hood
- Photo-finish ingestion over TCP push and LIF file watching
- World Athletics compliant result models end to end
- Real-time fan-out to overlays and public clients
- Full event management, not just a results board

</td>
</tr>
</table>

### The surface area

| Service | What it does | Stack |
|:--|:--|:--|
| `athletics.sportcache.com` | Live results and event management | Next.js · Node · Postgres |
| `api.sportcache.com` | Public REST API, sport-namespaced and versioned | FastAPI · Postgres |
| `broadcast.sportcache.com` | Real-time TV overlay system for live streams | Next.js · Supabase Realtime · GSAP |
| `docs.sportcache.com` | OpenAPI 3.1 spec, rendered with Scalar | YAML · Scalar |

<details>
<summary><b>Design decisions I'd defend in a room</b></summary>

<br>

**Speak the sport's language, not the database's.** The API uses `performance` instead of `time`, `nationality` instead of `country`, and a `marks` array for record abbreviations. If a technical delegate reads a payload, it should look familiar. Field names are a product decision.

**Model the messy reality.** DNS, DNF, DSQ, NM, NH, OTL, Q and q flags, record markers, combined-event scoring. Athletics is full of edge cases that only exist because someone got injured at 400m. The schema handles them as first-class states, not nulls.

**Elapsed time is the source of truth.** Wall clock is a lie in timing systems. Everything anchors to the start trigger.

**Design tokens before pixels.** Gold `#D4AF37`, black `#0A0A0B`, teal `#14B8A6`. Barlow Condensed for display, Inter for body, JetBrains Mono for code. One system, every surface.

</details>

---

## <img src="https://media.giphy.com/media/dWesBcTLavkZuG35MI/giphy.gif" width="28"> Currently building

**SportCache Analytics** · final year project

An analytics, prediction and anomaly detection layer sitting on top of the live SportCache athletics API. Progression modelling, performance forecasting, and flagging results that don't look right before they reach a record ratification panel.

<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white" />
<img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" />

---

## <img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="28"> Selected work

<table>
<tr>
<td width="33%" valign="top">

### 🍽️ Nexpace POS
Full restaurant management platform. Cashier, kitchen display, dispatch, self-serve kiosk, owner dashboard, and a rider PWA. Real-time order flow across every screen.

`Node` `Express` `Next.js 15` `Postgres` `Socket.io` `Paystack` `Twilio`

</td>
<td width="33%" valign="top">

### 📄 Timing PDF pipeline
Parser for Lynx timing exports across three meet result sets, turning locked PDFs into a structured workbook of 632 athlete rows. Used to run a national invitational selection process.

`Python` `pdfplumber` `openpyxl`

</td>
<td width="33%" valign="top">

### 🥇 Combined events scoring
TypeScript implementation of the World Athletics decathlon and heptathlon scoring formula with the full constants table. Points computed on demand, per event, per performance.

`TypeScript`

</td>
</tr>
</table>

---

## <img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="28"> Tech

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,ts,js,cpp&theme=dark" />

**Backend & Data**

<img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,postgres,supabase,mongodb,sklearn&theme=dark" />

**Frontend**

<img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,figma&theme=dark" />

**Infra & Tooling**

<img src="https://skillicons.dev/icons?i=vercel,docker,git,github,linux,nginx&theme=dark" />

</div>

<div align="center">
<sub>Also: Supabase Realtime · GSAP · Socket.io · Coolify on Hetzner · Scalar / OpenAPI 3.1 · pnpm · Paystack</sub>
</div>

---

## <img src="https://media.giphy.com/media/ZcKASxMSUAAaRWBpxr/giphy.gif" width="28"> Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=takyisky&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&bg_color=0A0A0B&title_color=D4AF37&text_color=E5E5E5&icon_color=14B8A6" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=takyisky&layout=compact&langs_count=8&hide_border=true&bg_color=0A0A0B&title_color=D4AF37&text_color=E5E5E5" />

<img height="165" src="https://streak-stats.demolab.com?user=takyisky&hide_border=true&background=0A0A0B&stroke=D4AF37&ring=D4AF37&fire=14B8A6&currStreakLabel=D4AF37&sideLabels=E5E5E5&currStreakNum=E5E5E5&sideNums=E5E5E5&dates=888888" />

<img src="https://github-profile-trophy.vercel.app/?username=takyisky&theme=darkhub&no-frame=true&no-bg=true&column=7&margin-w=8" />

</div>

---

## <img src="https://media.giphy.com/media/Cn92FbGqQnaLC/giphy.gif" width="28"> Beyond the code

Robotics background, which is where the interest in hardware talking to software started. A stretch of WhatsApp bot work with Baileys before that. Coursework across CCNA routing and switching, image processing, intelligent agents, statistical inference, and data science, most of which ends up feeding back into SportCache one way or another.

I write about the African sports tech space too, because the gap between what federations need and what exists is worth talking about out loud.

---

<div align="center">

## Let's talk

If you're working on sports technology, live data infrastructure, or anything in African tech that needs a backend built properly, my inbox is open.

<p>
  <a href="mailto:YOUR_EMAIL_HERE"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0A0A0B" /></a>
  <a href="https://sportcache.com"><img src="https://img.shields.io/badge/SportCache-D4AF37?style=for-the-badge&logoColor=0A0A0B&labelColor=0A0A0B" /></a>
  <a href="https://linkedin.com/in/YOUR_HANDLE"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0A0A0B" /></a>
  <a href="https://x.com/YOUR_HANDLE"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white&labelColor=0A0A0B" /></a>
</p>

<sub><i>Building the data layer for African sport, one meet at a time.</i></sub>

<img src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=110&color=0:D4AF37,50:14B8A6,100:0A0A0B" width="100%" />

</div>
