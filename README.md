# Pixelated Code Lab

i want the theme to be pixelate and computes 0s and 1s and the pixelated designs like the logo with arcade like designs this is my exact logo use this only 

about run01:

🚀 Built Run01 — a browser-based Python IDE that runs a full data

science stack with zero installation.

The problem: spinning up Python environments is slow, and running

arbitrary user code on a server is a real security/cost risk.

The solution: I compiled Python itself to WebAssembly (via Pyodide)

so it executes 100% inside the browser — no server in the loop, no

attack surface, no compute bill per run.

What it can do:

🔹 Run NumPy, Pandas, SciPy, Scikit-learn, Statsmodels, Matplotlib,

  Seaborn & Plotly — fully client-side

🔹 Pull live stock data through a CORS-safe Flask proxy

🔹 Render Matplotlib & interactive Plotly charts inline in the console

🔹 Load near-instantly on repeat visits via a custom Service Worker

  caching strategy (~17MB of CDN assets cached client-side)

Stack: Flask · Pyodide (WASM) · Monaco Editor · Plotly.js · Vercel

This was a deep dive into WebAssembly execution sandboxes, CORS-safe

proxy design, and frontend performance engineering (parallel asset

loading, batched package installs, Service Worker caching).

The fastest path from idea to working mathematical model. That's RUN01.

Zero compute cost — Python runs client-side via WebAssembly. No server bill per execution, near-100% margins.

Zero install — open a tab, full data science stack ready. No setup wall.

A data layer no one else built — full yfinance + 930k+ FRED series, normalized into one clean API call.

Fastest idea-to-visual loop — inline charts, live Desmos graphing, AI-assisted code, all in one tab.

AI that edits, not just chats — surgical code edits applied live, accept/reject, one-click run.

Free-to-scale architecture — zero backend cost means the free tier can grow without burning cash.

run01 is built for thinkers
use the logog and the image inmy site

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/91f70b5f-008a-4ddc-b83b-f0a908e32f74).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
