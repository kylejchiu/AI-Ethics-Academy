# AI-Ethics-Academy

**Website:** [https://ai-ethics-academy.vercel.app/](https://ai-ethics-academy.vercel.app/)

## Overview

AI-Ethics-Academy is an educational website created for the **Congressional App Challenge (CAC)**.
It helps students, developers, and the public understand the **social and ethical implications of artificial intelligence**, including fairness, transparency, accountability, and safety.
Through lessons, a quiz, and an interactive chatbot, the site encourages critical thinking about responsible AI development.

## Features

* Interactive chatbot for exploring ethical issues in AI
* Educational sections explaining fairness, transparency, and accountability
* A 25-question AI ethics quiz with instant feedback
* Simple, accessible design for all audiences
* Node.js backend for secure API proxying
* Hosted front-end on **Vercel** and backend on **Render**

## Getting Started

**Static Preview:**
Open `index.html` directly in a browser or run a quick local server:

```bash
python3 -m http.server 5500
# open http://localhost:5500/
```

**Backend Setup (for chatbot):**

```bash
npm install
npm start
```

Default port is `8080` or as defined by the `PORT` variable.

## Environment Variables

Create a `.env` file with:

```
OPENROUTER_API_KEY=
OPENROUTER_MODEL=
PORT=
SYSTEM_PROMPT=
```

## Deployment

* Frontend deployed at: [https://ai-ethics-academy.vercel.app/](https://ai-ethics-academy.vercel.app/)
* Backend deployed on Render ([https://ai-ethics-academy.onrender.com](https://ai-ethics-academy.onrender.com))
  You can also deploy the static version on GitHub Pages or Netlify.

## Educational Purpose

AI-Ethics-Academy encourages civic engagement by helping users question how technology shapes society.
It equips students and communities with the knowledge needed to design ethical, transparent, and fair AI systems.