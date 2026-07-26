<!--
  ╔═══════════════════════════════════════════════════════════╗
  ║  takyisky · github profile readme                         ║
  ║  brand: gold #D4AF37 · black #0A0A0B · teal #14B8A6       ║
  ╚═══════════════════════════════════════════════════════════╝
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0A0A0B,50:14B8A6,100:D4AF37&text=Takyi&fontColor=ffffff&fontSize=70&fontAlignY=32&desc=Sports%20Data%20Infrastructure%20for%20Africa&descSize=16&descAlignY=52&animation=fadeIn" width="100%" />

![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=3200&pause=900&color=D4AF37&center=true&vCenter=true&width=700&lines=Technical+Co-founder+%40+SportCache;Live+timing+%26+results+for+athletics+and+cycling;I+build+the+software%2C+and+I+officiate+the+sport;Computer+Science+%40+University+of+Ghana)

<p>
  <a href="https://sportcache.com"><img src="https://img.shields.io/badge/SportCache-D4AF37?style=for-the-badge&logoColor=0A0A0B&labelColor=0A0A0B" /></a>
  <a href="https://api.sportcache.com"><img src="https://img.shields.io/badge/The_API-14B8A6?style=for-the-badge&logoColor=white&labelColor=0A0A0B" /></a>
  <a href="mailto:emmanuelcrash945@gmail.com"><img src="https://img.shields.io/badge/Get_in_touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0A0A0B" /></a>
</p>

<p>
  <img src="https://img.shields.io/badge/Accra-Ghana%20%F0%9F%87%AC%F0%9F%87%AD-0A0A0B?style=flat-square&labelColor=0A0A0B&color=D4AF37" />
  <img src="https://img.shields.io/badge/Open%20to-Freelance%20%26%20Contract-0A0A0B?style=flat-square&labelColor=0A0A0B&color=14B8A6" />
  <img src="https://komarev.com/ghpvc/?username=takyisky&style=flat-square&color=D4AF37&label=Profile+Views" />
</p>

</div>

---

## <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="28"> whoami

I'm Emmanuel Takyi Obodai, technical co-founder of **SportCache**. I build the software that runs athletics and cycling competitions: live timing ingestion straight off photo-finish hardware, results publishing, and the public API other people build on top of.

The part that makes the work different is that I don't just write it. I'm a certified technical official, so I've stood on the track at the same championships my systems were running. The rules the software has to encode are rules I've had to apply under pressure with a stadium waiting.

Most sports data infrastructure was never built with African federations in mind. That's the gap we're closing.

```ts
const takyi = {
  name:      "Emmanuel Takyi Obodai",
  role:      "Technical Co-founder & Engineer, SportCache",
  location:  "Accra, Ghana 🇬🇭",
  studying:  "BSc Computer Science + Statistics, University of Ghana",
  alsoDoes:  "Technical Official, Senior African Athletics Championship",
  building:  ["live timing pipelines", "athletics & cycling APIs", "ML on race data"],
  stack:     ["Python", "TypeScript", "FastAPI", "Next.js", "React", "Postgres"],
  standards: ["World Athletics", "UCI"],
  hardware:  ["Vsports PT-600 photo-finish", "Lynx timing systems"],
  openTo:    "sports tech, data infrastructure, backend & full-stack contracts",
};
```

---

## <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="28"> SportCache

> Data infrastructure for athletics and cycling across Africa. I lead the engineering.

<table>
<tr>
<td width="50%" valign="top">

### 🏟️ Athletics
- Senior African Athletics Championship 2026
- Accra Open Championship
- Cape Coast Open Championship

Built with **Ghana Athletics** and **SEED Afrique**.

</td>
<td width="50%" valign="top">

### 🚴 Cycling
- PruRide Ghana
- Tour du Ghana

Same platform, UCI conventions instead of World Athletics ones.

</td>
</tr>
</table>

### The surface area

| Service | What it does | Stack |
|:--|:--|:--|
| `athletics.sportcache.com` | Live results and event management for meets | Next.js · Node · Postgres |
| `api.sportcache.com` | Public REST API for athletics and cycling, sport-namespaced and versioned | FastAPI · Postgres · OpenAPI 3.1 |

<details>
<summary><b>Design decisions I'd defend in a room</b></summary>

<br>

**Speak the sport's language, not the database's.** The API uses `performance` instead of `time`, `nationality` instead of `country`, and a `marks` array for record abbreviations. If a technical delegate reads a payload, it should look familiar. Field names are a product decision.

**Model the messy reality.** DNS, DNF, DSQ, NM, NH, OTL, Q and q flags, record markers, combined-event scoring. Athletics is full of edge cases that only exist because someone got injured at 400m. The schema handles them as first-class states, not nulls.

**Elapsed time is the source of truth.** Wall clock is a lie in timing systems. Everything anchors to the start trigger.

**One platform, two rulebooks.** Athletics follows World Athletics conventions, cycling follows UCI. Sport-namespaced routes mean neither has to bend to fit the other.

**The rules are not optional.** Medal tables count finals only. Grouping is by country for international meets and by affiliation for domestic ones. Combined Masters categories take the lowest band. Getting these wrong is how a results system loses a federation's trust.

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
<td width="50%" valign="top">

### 🎫 SEED Afrique Membership System
Full-stack platform handling membership requests and approvals for a pan-African organisation. Cut admin turnaround time by 30%. Firebase analytics wired in so decisions run on numbers instead of guesses.

`React` `Node.js` `MongoDB` `Firebase`

</td>
<td width="50%" valign="top">

### 🎓 European School of Business & Diplomacy
Led the full redevelopment of the institution's website. Rebuilt site architecture, tightened security, reworked SEO, and shipped new enrollment and content-management features with academic and admin teams.

`Next.js` `React` `Node.js`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📄 Lynx timing PDF pipeline
Parser that pulled structured data out of locked Lynx timing exports across three meet result sets, producing a 632-row athlete workbook. Used to run a national invitational selection process.

`Python` `pdfplumber` `openpyxl`

</td>
<td width="50%" valign="top">

### 🥇 Combined events scoring
TypeScript implementation of the official World Athletics decathlon scoring formula with the full constants table. Points computed on demand, per event, per performance.

`TypeScript`

</td>
</tr>
</table>

---

## <img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="28"> Tech

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,ts,js,html,css&theme=dark" />

**Backend & Data**

<img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,postgres,supabase,mongodb,firebase,mysql,sklearn&theme=dark" />

**Frontend**

<img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,figma&theme=dark" />

**Infra & Tooling**

<img src="https://skillicons.dev/icons?i=vercel,docker,git,github,linux,nginx&theme=dark" />

</div>

<div align="center">
<sub>Also: OpenAPI 3.1 · Coolify on Hetzner · pandas · NumPy · UI/UX · Agile</sub>
</div>

---

## <img src="https://media.giphy.com/media/l0HlN5Y28D9MzzcRy/giphy.gif" width="28"> Trackside

The credentials that make the software better:

- 🏅 **Technical Official** · Senior African Athletics Championship (2026)
- 🏅 **Discipline Technical Official** · All African Games, Ghana (2024)

I've officiated at the same championships my systems were timing. Every edge case in the schema exists because I've watched it happen on a track.

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

Spent a year and a bit as a robotics tutor and STEM educator, running Saturday sessions teaching kids and senior high students the fundamentals of robotics and programming. Still volunteer where I can: Coolest Projects Ghana, Mobile Web Ghana, and the Ghana Robotics Competition.

That's also where the interest in hardware talking to software started, which is more or less the whole job now.

---

<div align="center">

## Let's talk

If you're working on sports technology, live data infrastructure, or anything in African tech that needs a backend built properly, my inbox is open.

<p>
  <a href="mailto:emmanuelcrash945@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0A0A0B" /></a>
  <a href="https://sportcache.com"><img src="https://img.shields.io/badge/SportCache-D4AF37?style=for-the-badge&logoColor=0A0A0B&labelColor=0A0A0B" /></a>
  <a href="https://linkedin.com/in/YOUR_HANDLE"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0A0A0B" /></a>
  <a href="https://x.com/YOUR_HANDLE"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white&labelColor=0A0A0B" /></a>
</p>

<sub><i>Building the data layer for African sport, one meet at a time.</i></sub>

<img src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=110&color=0:D4AF37,50:14B8A6,100:0A0A0B" width="100%" />

</div>
