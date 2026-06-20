# Frontend Engineering & Interface Portfolio
Hi, welcome to my frontend portfolio showcase! This repository serves as an architectural catalog of my web applications, specifically focusing on complex state management, high data density, and scalable UI architectures. 

> **A Note on Development Context:** The applications featured below are proprietary, active pre-launch systems built entirely as a solo developer and student founder. To protect intellectual property, the source code is kept private. The breakdowns below outline the exact technical decisions, state patterns, and architectural compromises made during active development.

---

## 🚀 Active Systems & Flagships

### 1. Ascendr — Spatial Intelligence Platform
<img width="947" height="434" alt="Ascendr Map View" src="https://github.com/user-attachments/assets/6af8145c-ad0d-46a9-bf7c-f2974ce06895" />
<img width="947" height="538" alt="Ascendr Analytics" src="https://github.com/user-attachments/assets/4f7ef6f0-5c11-40da-b782-bda6d310a7b6" />

**Tech Stack:** Next.js (App Router), React, TypeScript, React Query, Zustand, Tailwind CSS, Mapbox GL

Ascendr began as an AI-driven real estate underwriting and due diligence engine utilizing ethical web scraping and public data registries. Recognizing the power of its UI direction, the core engine was pivoted into a multi-purpose spatial intelligence platform centered around complex data mapping, dynamic state configurations, and Agentic AI metrics processing.

#### Engineering Highlights:
* **Asynchronous Scraped Data Pipeling:** Integrated **React Query** to manage and cache dense, multi-source data payloads streams, maintaining an agile UI layer even during heavy underwriting computations.
* **Centralized Underwriting State:** Engineered global state handling using **Zustand** to bind real-time map layer selections, user valuation inputs, and Agentic AI prompt contexts without component breakdown or lagging.

---

### 2. PortX2 — Local Port Digital Twin Suite
<img width="959" height="539" alt="PortX2 3D Map View" src="https://github.com/user-attachments/assets/d6df40a0-3131-407a-8b46-04d2ba531e2b" />
<img width="959" height="539" alt="PortX2 Data Panel" src="https://github.com/user-attachments/assets/eccfcb02-488c-473d-8c5b-c0ad730c1088" />

**Tech Stack:** Next.js, React, TypeScript, React Query, Zustand, Three.js, WebGL, MapLibre GL, GSAP, Tailwind CSS

The heaviest application in the portfolio. PortX2 is a real-time digital twin designed to track, simulate, and optimize maritime port logistics. It handles continuous data streaming from active API sources while feeding variables into pathfinding models and live tracking modules.

#### Engineering Highlights:
* **Complex Spatial Math & Animations:** Mapped real-world GeoJSON routes directly into precise SVG coordinates to animate vessel tracking states using **GSAP** timelines.
* **WebGL Scene & Asset Optimization:** Optimized heavy 3D industrial assets (cranes, trailers, forklifts) directly out of Blender to keep frame rates steady during canvas re-renders.
* **State-Driven Simulation Playback:** Developed a comprehensive time-scrubbing, playback, and fast-forward mechanics system via **Zustand**, allowing global data states to recalculate metrics dynamically based on varying simulator timelines.

---

### 3. PBeyond — Internship Management System
<img width="1920" height="1080" alt="PBeyond Dashboard" src="https://github.com/user-attachments/assets/0f27948c-7e42-40d4-b91d-33cd795d9fdb" />
<img width="1920" height="1080" alt="PBeyond Task Tracker" src="https://github.com/user-attachments/assets/84663eeb-3bf2-4bc1-b069-2f8e54afaedf" />
<img width="1920" height="1080" alt="PBeyond Reviews" src="https://github.com/user-attachments/assets/da80c265-fcb9-45ac-992c-cce19baea9f0" />

**Tech Stack:** Laravel, Inertia.js, React, JavaScript (ES6+), React Context, Tailwind CSS, MySQL

A highly robust administrative system engineered around precise state synchronization across multi-tenant dashboards (Interns, Mentors, and Administrators). 

#### Engineering Highlights:
* **Role-Based Reactive State:** Orchestrated real-time synchronization across three distinct system views using **Inertia.js** and **React Context** to manage access tokens and pending review items securely.
* **Dynamic Form Architecture:** Constructed multi-tier onboarding steps, secure file uploads, and conditional evaluation forms with strict client-side validations.

---

## 🛠 Professional Progression & Philosophy
My codebase choices reflect a clear technical evolution: advancing from traditional full-stack monolithic patterns (**Laravel/Inertia**) to decoupled enterprise web systems prioritizing robust type-safety (**TypeScript**), intelligent server-state caching (**React Query**), and high-performance frontend graphics/rendering (**Three.js/WebGL**).
