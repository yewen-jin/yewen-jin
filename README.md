## Yewen Jin

Creative Technologist turned Software Engineer based in London. Background in mathematics (NYU), computational arts (Goldsmiths), and architecture (AA/UPenn). I've been building interactive web applications, networked performance tools, and creative software in the past year fews, wearing hats of product manager and UI/UX designer and shipping production work with AI-assisted development workflows (Claude, Codex, Opencode). I recently completed a software development bootcamp from Northcoders because I wanted to understand how to approach code like a software developer and the fundamental methods of how things were built.

[LinkedIn](https://linkedin.com/in/yewenjin) · [portfolio](https://dev.yewenjin.com/)


---

## What I've built
### Alibi // AI Time Reflection App
[GitHub](https://github.com/yewen-jin/alibi-coach) · [Live](https://alibi.day)

  An ADHD-informed AI time journal that turns timers, notes, manual blocks, and timestamped companion chat into a single timeline of what happened,what was intended, and what was actually going through the user’s mind. Built as a “time mirror” for people with time blindness, combining factual start/stop time records with CBT-style intention tracking and reflective chat. 
  
  Agentic workflows classify intent, control timers, request clarification, log structured time blocks, and extract language patterns into behavioral signals such as avoidance, friction, useful drift, emotional context, and intention/action mismatch. Dashboard mirrors separate high-trust block-note evidence from chat-derived patterns, helping users reconstruct their day without treating gaps or silence as failure.

  Stack: Next.js, React, TypeScript, Tailwind CSS, Supabase, Vercel AI SDK,
  OpenRouter, Vercel

### MIDI Relay // Remote MIDI Control Server
[GitHub](https://github.com/yewen-jin/remote-midi) · [Live](https://midi.datadadaist.space/)

  A real-time WebSocket relay that forwards raw MIDI bytes between a sender and
   one or more receivers over the internet — no inbound port access required on
   either end. Built to revive a remote robotic installation workflow that was
  broken by modern NAT/firewall restrictions. Both clients connect outbound to
  a central relay, which routes binary MIDI frames through named rooms with
  sub-50ms added latency. Deployed on a VPS behind Nginx with automatic TLS,
  with browser and Node.js clients supporting auto-reconnection for unattended
  installations.

  **Stack:** 
  Node.js, WebSockets (ws), Web MIDI API, Nginx, Docker
  
### The Body is Obsolete // Interactive Narrative Game

[GitHub](https://github.com/yewen-jin/synthwave-chatroom) · [Live](https://chat.datadadaist.space/docs)

A browser-based interactive fiction experience disguised as a chatroom. Audiences enter what looks like a messaging interface and find themselves inside a branching narrative with generative visuals built in p5.js. I designed, built, and deployed this independently for a live cabaret performance — handling the frontend, backend (Node.js, Socket.io), visual design, and live technical operation on the night. This was built with AI-assisted development before I had any formal web development training.

**Stack:** 
Node.js, Socket.io, p5.js, HTML/CSS, JavaScript

### Job Tracker // Personal Application Dashboard

[GitHub](https://github.com/yewen-jin/job-tracker) · [Live](https://job-tracker.datadadaist.space/)    
A full-stack job application tracker built to stay organized through an active job search. Paste a job URL and AI auto-fills the details; upload your CV and get a match score with gap analysis against any listing. Applications move through a Kanban-style status pipeline with priority levels, daily planning, and rich metadata fields (salary, work mode, culture notes, red flags). Deployed on Vercel with Supabase handling auth, storage, and edge functions — designed so anyone can fork it and self-host their own private instance.

**Stack:**
React 18, TypeScript, Vite, Tailwind CSS, shadcn/ui, Supabase, Firecrawl, OpenRouter

### SpillR // Real-Time TV Show Comment Platform

[Frontend](https://github.com/Ines1299/SpillR-app) · [Backend](https://github.com/yewen-jin/spillr-BE)

A time-synced live TV commentary app. Comment and react with emoji on shows in real time - every message is anchored to the show's timeline, not the clock, so premiere and catchup viewers share the same spoiler-free conversation. Group project at Northcoders. 

**Stack:** 
React Native, Expo, Express, Socket.io, Supabase, PostgreSQL, Jest, GitHub Actions

### Skopetur Interactive Performance Platform

[skopetur.com](https://skopetur.com/)

I co-founded Skopetur Ltd as a creative technology company for networked live performance. During lockdown, I designed an interactive video streaming platform that uses the same core video technology as Zoom but delivers a fundamentally different experience — one designed for watching and participating in live art, not for meetings. I designed the UI/UX in Figma, worked with a developer, and learned to build the frontend in Svelte, with WebRTC for video and Docker for deployment. Separately, I produced Distance Anatomy, a live performance series connecting dancers, musicians, and visual artists across London and New York using Node.js, Google MediaPipe motion capture, and OSC/MIDI networking. Press coverage by ShowStudio News.

**Stack:** Svelte, SvelteKit, Node.js, Docker, WebRTC, Figma

### NC News // Full-Stack Reddit-Style Application

[Frontend](https://github.com/yewen-jin/nc-news) · [Backend](https://github.com/yewen-jin/nc-news-backend) · [Deployed](https://nc-newwwwws.netlify.app/)

Full-stack web application with a RESTful API supporting CRUD operations, parametric queries, sorting, pagination, and error handling. Frontend built in React with responsive design and optimistic rendering. Backend built with Express and PostgreSQL with full test coverage using Jest and TDD methodology throughout. Seeding, migrations, and hosted deployment.

**Stack:** 
React, Express, PostgreSQL, Jest

### Personal Website

[yewenjin.com](https://yewenjin.com/) · [Source](https://github.com/yewen-jin/yewenjin-portfolio)

Portfolio site built with AI-assisted development (Claude) before I started the Northcoders bootcamp. One of the projects that taught me I could ship real things with AI tools and strong design instinct, even without formal engineering training.

**Stack:** 
Next.js

---
## What I'm building currently:


### Pendulum
[GitHub](https://github.com/yewen-jin/pendulum)

A browser-based visual engine with user-friendly interface that connects body gesture/facial expression (Mediapipe）， MIDI CC input (local+remote), Audio input and LLM based image generation workflow.

#### Currently completed:
- a Hypha based visual engine
- the bridge between the browser output with audio input, MIDI input, facial and gesture input, and integrated ModMuPlat user interfact for smartphone control.

#### Next Step:
- explore other visual tools: **three.js**, **p5.js**, create a mode switcher between them
- add physical rules for visualiser based on hand movemet
- connect to open router and other LLM based API for prompt generation
---

### Tech

**Languages & Frameworks**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black) ![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat&logo=react&logoColor=black) ![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=flat&logo=svelte&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)

**Data & Real-Time**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) ![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat&logo=socketdotio&logoColor=white) ![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat&logo=webrtc&logoColor=white)

**Creative & Visual**

![p5.js](https://img.shields.io/badge/p5.js-ED225D?style=flat&logo=p5dotjs&logoColor=white) ![WebGL](https://img.shields.io/badge/WebGL-990000?style=flat&logo=webgl&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)

**Infrastructure & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![Jest](https://img.shields.io/badge/Jest-C21325?style=flat&logo=jest&logoColor=white) ![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat&logo=netlify&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

**AI-Assisted Development**

![Claude](https://img.shields.io/badge/Claude-191919?style=flat&logoColor=white) ![GitHub Copilot](https://img.shields.io/badge/Copilot-000000?style=flat&logo=githubcopilot&logoColor=white)

**Also worked with:** C++ (OpenFrameworks), Java (Processing), C# (Unity), Max/MSP, Python, Grasshopper

---

### Education

||||
|---|---|---|
|**Goldsmiths, University of London**|MA Computational Arts|C++, Processing, Max/MSP, Unity, OOP|
|**Architectural Association / UPenn**|Architecture Studies|Parametric design, Rhino, Grasshopper, Python|
|**New York University**|BA Mathematics & Philosophy|Discrete maths, linear algebra, analysis, logic|
|**Northcoders**|Software Development Bootcamp|Full-stack JS/TS, React, Node, PostgreSQL, TDD|

---

### Beyond code

As a musician, I release on [Chinabot](https://chinabot.bandcamp.com/) and [LIMBS Project](https://limbsproject.bandcamp.com/), perform at places like Café OTO, and co-host a monthly show on [Netil Radio](https://www.netilradio.com/). 

---

djSQL aka SideQuestLegend

<!--### Who is djSQL?

When djSQL plays video games she sweeps through side quests, hence the name side quest legend.

djSQL is a creative technologist currently doing an intensive web development course at Northcoders. She's doing this course because she has been obsessed with making websites and web applications for the past year and maybe even longer ago.



### Stuff she's done in the past

- Created UI/UX design and did a bit front-end for an interactive online space specialised for gigs and performances in 2021

- Produced an event series for cross-continental performance together with dances and musicians from 2 different cities (between New York and London) (2022-2024), managing live coordination between performers and the technical pipeline in the 3 successfully delivered events
  [press](https://www.showstudio.com/news/revolutionising-the-art-of-performance-distance-anatomy)
  [website](https://skopetur.com/projects/distance-anatomy)

- The list keeps going-->




<!--
### Stuff I am currently doing
### Stuff I can do



**yewen-jin/yewen-jin** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
