<div align="center">

# Chloe Joo-yeon Lee

### I design it, I build it, and the AI part is mine too.

<sub><b>M.S. Computer Science @ Columbia Engineering — vision · graphics · robotics</b><br>
B.A. Computer Science / Visual Art @ Columbia · Teaching Assistant, <i>Designing for Generative AI</i><br>
Five years as a fashion &amp; graphic designer before I wrote my first line of production code.<br>
I write the spec, design the screens, build the app, and ship it to real users — alone.</sub>

[![Portfolio](https://img.shields.io/badge/Portfolio-DB6089?style=for-the-badge)](https://s2chloes2.github.io/portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-2D3158?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chloe-jooyeon-lee)
![New York](https://img.shields.io/badge/New_York,_NY-6B6E8F?style=for-the-badge)

</div>

---

## What I am pointed at

**Vision, graphics and robotics** — that is the track, and it is where the coursework, the research
and the internship all sit: neural rendering, deep learning for computer graphics, computer
animation, computer vision, 3D UI. Detection into control (YOLOv8 → PPO/DQN, no access to game
state). Rigs, retargeting and headless Blender pipelines at Claythis. Real-time hand tracking and
soft-body simulation in the browser.

The other half is that I can carry a product the whole way. Research and a demo are not the same
thing as an app on the App Store, and I have done both.

## Things you can open right now

| | | |
|---|---|---|
| <img src="https://raw.githubusercontent.com/S2chloeS2/S2chloeS2/main/assets/tipo_icon.png" width="46"> | **[Tipo](https://apps.apple.com/us/app/tipo-tip-tracker/id6789645296)** — iOS tip tracker &amp; settlement app, **live on the US &amp; Korean App Stores**. Spec, design, build and ship, all solo. 215 commits. | React Native · Expo · Firebase |
| 🖼 | **[From Subject to Dataset](https://ai-photo-kmu3.vercel.app)** — 29 photographs of indigenous peoples run through a vision API. What comes back is not a description of a people, but a record of what the system was trained to see. | Google Cloud Vision · Next.js |
| 🐕 | **[Labor Detection Model](https://ai-photo-eosin-eta.vercel.app)** — score a dog walker's labour from a photograph, then read the longer list of what no vision model can see. | Interactive web · CV |
| 🎧 | **[TranscriptoAI](https://transcripto-ai-bahc.onrender.com)** — transcribes a lecture, summarises it, and answers *only* from what was actually said in the room. Piloted by 50+ students. | Python · Flask · Whisper · AssemblyAI |
| 😄 | **[Humor Project](https://humor-project-chloe.vercel.app)** — teaching a model a *style* of humor via ordered prompt chains, with a [chain authoring tool](https://humor-project-bay.vercel.app) and an [admin](https://human-admin.vercel.app). | Next.js · TypeScript · LLM |
| 🗄 | **[Portfolio](https://s2chloes2.github.io/portfolio/)** — a cabinet of works you walk through rather than scroll. Hand-built, no template. | React Three Fiber · GSAP |
| 🫧 | **[Squish Studio](https://s2chloes2.github.io/squish-studio/)** — a small hand-tracked toy: pinch a jelly and it stretches, make a fist and a wax ball cracks. A weekend-scale piece, but the soft-body deformation, the breakage state machine and the audio are all written by hand. Video never leaves your device. | MediaPipe · Three.js · Web Audio |

<div align="center">
<img src="https://raw.githubusercontent.com/S2chloeS2/S2chloeS2/main/assets/tipo_1_home.png" width="30%">
<img src="https://raw.githubusercontent.com/S2chloeS2/S2chloeS2/main/assets/tipo_2_calendar.png" width="30%">
<img src="https://raw.githubusercontent.com/S2chloeS2/S2chloeS2/main/assets/tipo_3_trend.png" width="30%">
<br><sub>Tipo — three-second logging, earnings heatmap, period comparison</sub>
<br><br>
<img src="https://raw.githubusercontent.com/S2chloeS2/S2chloeS2/main/assets/from_subject_to_dataset.jpg" width="32%">
<img src="https://raw.githubusercontent.com/S2chloeS2/S2chloeS2/main/assets/humor_project.jpg" width="32%">
<img src="https://raw.githubusercontent.com/S2chloeS2/S2chloeS2/main/assets/squish_studio.jpg" width="32%">
<br><sub>From Subject to Dataset · Humor Project · Squish Studio</sub>
</div>

## PLIORA — the one I am most proud of

*Flutter · Dart · Supabase · private repo*

A period diary that presents itself as an ordinary plant app. A decoy passcode opens a harmless
surface — a snake plant you water — while the real records sit behind a second PIN and biometrics.
The threat model **is** the product: it decides the app icon, the copy, the notification wording,
and what the server is allowed to know.

Three disguise strengths, iOS alternate icons, records kept on device, partner pairing where the
other person only ever sees what you turn on, and an assistant that shows you the exact summary it
is about to send before it sends it — and nothing else.

<div align="center">
<img src="https://raw.githubusercontent.com/S2chloeS2/S2chloeS2/main/assets/pliora_1_decoy.jpg" width="31%">
<img src="https://raw.githubusercontent.com/S2chloeS2/S2chloeS2/main/assets/pliora_2_home.jpg" width="31%">
<img src="https://raw.githubusercontent.com/S2chloeS2/S2chloeS2/main/assets/pliora_3_privacy.jpg" width="31%">
<br><sub>The decoy · the real home behind it · "this is all we send"</sub>
</div>

## Vision · graphics · robotics

**You Only Live Once** — a game agent that sees only pixels: RGB frame → YOLOv8 → policy network →
action, with no access to internal game state. Detector reached 0.99+ mAP; deployed on GCP Cloud
Run. Team of three; my part was the reinforcement learning — the PPO/DQN trainer and the agent
module. *PyTorch · Ultralytics · Stable-Baselines3 · Gymnasium · OpenCV*

**Claythis** *(internship, San Francisco)* — Blender CLI automation for headless motion processing,
finger retargeting across differing bone hierarchies, hand rigs optimised for minimum bone count
without losing motion fidelity, and support for joint-detection and auto-rig pipelines for
AI-generated 3D characters. Company work — described, not published.

**VizWall** — StyleGAN3 + e4e face latent-space transformation.
**Finalist, Columbia Visualization Wall Competition — "Art &amp; Futurism" ($500).**

**Coursework** — Neural Rendering · Deep Learning for Computer Graphics · Computer Animation ·
Computer Vision · 3D UI · NLP · Artificial Intelligence.

## Read the code

| Repo | What it is | What it shows |
|---|---|---|
| **[humor-project](https://github.com/S2chloeS2/humor-project)** | Three Next.js apps sharing one auth layer | Prompt chains as first-class data: flavour CRUD, step ordering, live generation. 79 commits |
| **[transcripto-ai](https://github.com/S2chloeS2/transcripto-ai)** | Flask app, deployed | Whisper + AssemblyAI pipeline, grounded Q&A that declines to answer past the transcript, EN/KO |
| **[columbia-computer-animation](https://github.com/S2chloeS2/columbia-computer-animation)** | PA1–PA6 on the course `nemo` framework | Simulation and animation coursework in Python. 94 commits |
| **[columbia-nlp](https://github.com/S2chloeS2/columbia-nlp)** | COMS 4705 | Trigram LM → neural dependency parser → LSTM caption generator → RAG |
| **[squish-studio](https://github.com/S2chloeS2/squish-studio)** | The hand-tracked toy above | Soft-body deformation, a four-stage breakage state machine, procedural audio. ~2,500 lines, no TODO left in it, CDN versions pinned |
| **[portfolio](https://github.com/S2chloeS2/portfolio)** | This site | 3D scene composition, scroll-scrubbed camera work, one config file as the source of truth |

## Also building

Private repos — happy to walk anyone through them.

**NOOK** · *Tauri 2 · React 19 · Canvas 2D · Claude API* — a cat that lives in the corner of your
monitor, drawn procedurally rather than shipped as sprites. Budget: 60 fps only while something
moves, ~6 fps asleep, 0 when hidden, under 2% idle CPU. It never notifies, never dies, no streaks.

**MoneyOS** · *Claude API · Next.js · Prisma* — eight agents each owning one function, turning a
one-line brief into finished output. Model tier routing — Haiku to classify, Sonnet to draft, Opus
to analyse — cut cost sharply without losing quality.

**Daengsaju** · *React Native · Expo · Claude API* — a pet companion and life journal. A local check
intercepts emergencies *before* any message reaches the model and returns a fixed "call a vet"
response, so the assistant can never improvise about a sick animal.

**Haruon** · *Expo · Supabase · TypeScript* — an AI that operates your plans instead of only making
them. Architecture frozen around six core objects.

## Stack

**Vision · graphics · AI** &nbsp;
![PyTorch](https://img.shields.io/badge/PyTorch-DB6089?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-DB6089?style=flat-square&logo=opencv&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-DB6089?style=flat-square)
![Stable Baselines3](https://img.shields.io/badge/Stable_Baselines3-DB6089?style=flat-square)
![Gymnasium](https://img.shields.io/badge/Gymnasium-DB6089?style=flat-square)
![MediaPipe](https://img.shields.io/badge/MediaPipe-DB6089?style=flat-square)
![StyleGAN3](https://img.shields.io/badge/StyleGAN3-DB6089?style=flat-square)
![Blender](https://img.shields.io/badge/Blender-DB6089?style=flat-square&logo=blender&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-DB6089?style=flat-square&logo=threedotjs&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API-DB6089?style=flat-square&logo=anthropic&logoColor=white)

**Mobile** &nbsp;
![React Native](https://img.shields.io/badge/React_Native-2D3158?style=flat-square&logo=react&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-2D3158?style=flat-square&logo=expo&logoColor=white)
![Expo Router](https://img.shields.io/badge/Expo_Router-2D3158?style=flat-square)
![Reanimated](https://img.shields.io/badge/Reanimated-2D3158?style=flat-square)
![Flutter](https://img.shields.io/badge/Flutter-2D3158?style=flat-square&logo=flutter&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-2D3158?style=flat-square&logo=swift&logoColor=white)

**Web** &nbsp;
![TypeScript](https://img.shields.io/badge/TypeScript-6B6E8F?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-6B6E8F?style=flat-square&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-6B6E8F?style=flat-square&logo=nextdotjs&logoColor=white)
![React Three Fiber](https://img.shields.io/badge/React_Three_Fiber-6B6E8F?style=flat-square)
![Zustand](https://img.shields.io/badge/Zustand-6B6E8F?style=flat-square)
![Tailwind](https://img.shields.io/badge/Tailwind-6B6E8F?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend &amp; data** &nbsp;
![Supabase](https://img.shields.io/badge/Supabase-9A9CB5?style=flat-square&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-9A9CB5?style=flat-square&logo=firebase&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-9A9CB5?style=flat-square&logo=flask&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-9A9CB5?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-9A9CB5?style=flat-square&logo=postgresql&logoColor=white)

**Design** &nbsp;
![Figma](https://img.shields.io/badge/Figma-F55288?style=flat-square&logo=figma&logoColor=white)
![Adobe](https://img.shields.io/badge/Adobe_Suite-F55288?style=flat-square&logo=adobe&logoColor=white)
![After Effects](https://img.shields.io/badge/After_Effects-F55288?style=flat-square&logo=adobeaftereffects&logoColor=white)
![Procreate](https://img.shields.io/badge/Procreate-F55288?style=flat-square)

<sub>Every screen, icon and character in the shots above is mine — the design is not outsourced and
neither is the code.</sub>

## Columbia

**M.S. Computer Science** · Columbia Engineering · 2026–2027 · vision · graphics · robotics
**B.A. Computer Science, Visual Art** · Columbia University · 2026 · Dean's List ×4
**Teaching Assistant** · *Designing for Generative AI: The Humor Project* · 2026–

🏆 **Finalist**, Columbia Visualization Wall Competition — *"Art &amp; Futurism"*

<sub>Korean (native) · English (professional working) · Los Angeles → Paris → New York</sub>
