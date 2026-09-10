## Ali Ansari

Student at LNMIIT Jaipur, graduating May 2027. Ranked 2nd of 142 in my department, CGPA 8.70.
I work on agentic AI/RAG, ML and backend systems — the common thread is measuring
things properly before claiming they work.

- Micromouse robotics: custom embedded C++ on RP2040, PID control, flood fill. Three national wins.
- Retrieval and ML systems: RAG pipelines, calibrated classifiers, benchmarks I actually publish.
- Full-stack when a system needs a front door: MERN, JWT, Redux Toolkit.
- Competitive programming: 1000+ problems solved. Codeforces 1404, CodeChef 1654, LeetCode 1805.

---

### Projects

**[PitchLens](https://github.com/LycanAlan/PitchLens)** — multimodal RAG over startup pitch decks.
65% of pages across 19 real decks had no PDF text layer, so I built a per-page adaptive extractor
routing image slides to Gemini Vision: deck coverage went 4/19 → 19/19. Hybrid BM25 + FAISS retrieval
fused with reciprocal rank fusion and cross-encoder re-ranking took Recall@3 from 0.78 to 0.95 on a
72-question hand-labelled benchmark. A corpus-fingerprint cache cut cold start from 3.9s to 0.036s.
`Python` `LangGraph` `FAISS` `FastAPI` `Docker`

**[Micromouse Bot](https://github.com/paramveer5404/MicroMouse)** — a 10cm × 8cm maze-solving robot
running flood fill on a Raspberry Pi Pico W. Rewrote the IR sensor path in embedded C++ to cut read
time from 300µs to 20µs, and used PID for 90 ± 0.1° turns. Interrupts, system timers and multicore
for the sensor and control loops. First place at IIT Roorkee Cognizance '25, DTU Invictus '25 and
BITS Pilani Apogee '25.
`C++` `RP2040` `PID` `MPU6050`

**[VoidCart](https://github.com/LycanAlan/VoidCart)** — full-stack e-commerce platform with an admin
dashboard, user profiles and order history. JWT auth, Redux Toolkit cart state, Cloudinary uploads
via Multer, Razorpay payments, single-service deployment on Render.
[Live](https://voidcart-frontend.onrender.com) · `MongoDB` `Express` `React` `Node`

---

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/ali-ansari-5924ab21b/) ·
[Codeforces](https://codeforces.com/profile/LycanAlan) ·
[CodeChef](https://www.codechef.com/users/lycanalan) ·
[LeetCode](https://leetcode.com/u/LycanAlan/) ·
[lycanalan205@gmail.com](mailto:lycanalan205@gmail.com)
