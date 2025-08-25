# Allsafeafrica CTF — Open Repository

> **Welcome!** This repo introduces Capture The Flag (CTF) challenges — what they are, how to play, and why they matter for *everyone* (beginners, students, professionals, employees, orgs & enterprises). It also hosts free training materials and example challenges.

**Partner:** Simulation Labs
**Register for upcoming CTFs:** [https://allsafeafrica.com](https://allsafeafrica.com)

---

## 📚 Table of Contents

* [What is a CTF?](#-what-is-a-ctf)
* [How CTFs are Played](#-how-ctfs-are-played)
* [Why CTFs Matter (for Everyone)](#-why-ctfs-matter-for-everyone)
* [Game Modes & Categories](#-game-modes--categories)
* [Get Started Fast](#-get-started-fast)
* [Learning Path (Levels 1–6)](#-learning-path-levels-16)
* [Example Challenges](#-example-challenges)
* [Write‑ups & Walkthroughs](#-write-ups--walkthroughs)
* [Resources & Tools](#-resources--tools)
* [Repo Structure](#-repo-structure)
* [Contributing](#-contributing)
* [Code of Conduct](#-code-of-conduct)
* [License](#-license)

---

## ❓ What is a CTF?

A **Capture The Flag (CTF)** is a hands-on cybersecurity game. Players solve puzzles, find vulnerabilities, or analyze evidence to uncover a secret text called a **flag** (e.g., `FLAG{you_found_me}`). CTFs simulate real-world security problems in a safe, legal environment.

---

## 🎮 How CTFs are Played

* **Challenges:** Self-contained tasks (web, crypto, forensics, OSINT, reverse engineering, etc.).
* **Flags:** Unique strings you submit to score points.
* **Scoring:** Harder tasks = more points; leaderboards track progress.
* **Solo or Teams:** Play alone or collaborate.
* **Timeboxed Events:** Ranges from 1–48 hours or ongoing practice labs.
* **Platforms:** We host with **Simulation Labs** (no‑code friendly, reliable infra).

---

## 🌍 Why CTFs Matter (for Everyone)

* **Beginners/Students:** Learn by doing; build confidence & curiosity.
* **Professionals/Employees:** Practice incident response, policy-in-action, and secure habits.
* **Organizations/Enterprises:** Team resilience, skills assessment, and culture-building.
* **Career Growth:** Build a portfolio with write-ups & badges; showcase practical skills.
* **Community:** Inclusive, collaborative learning — not gatekept.

---

## 🧩 Game Modes & Categories

* **Jeopardy Style:** Solve independent puzzles; submit flags.
* **Attack/Defense:** Teams defend their service while attacking others (advanced).
* **Awareness Tracks:** Phishing, password strength, cyber hygiene, OSINT basics.
* **Applied Tracks:** Web vulns, forensics, reverse engineering, crypto, cloud.

---

## ⚡ Get Started Fast

1. **Register:** [https://allsafeafrica.com](https://allsafeafrica.com)
2. **Create an account on our CTF platform (Simulation Labs)** — link will be posted in event docs.
3. **Read the rules** (ethics, fair play, no brute‑forcing infra, respect rate limits).
4. **Join our community chat** (link in event page) for hints & announcements.
5. **Pick your level** and start solving. Submit flags as you go.

---

## 🧠 Learning Path (Levels 1–6)

**Level 1 — Cyber Explorer (Easy, 50 pts):** phishing basics, oversharing, strong passwords, inspect element, cyber hygiene.

**Level 2 — Cyber Investigator (100 pts):** fake logins, secure Wi‑Fi, stego lite, breach checks, social engineering responses.

**Level 3 — Cyber Guardian (200 pts):** MoMo scams, deepfake spotting, USB risks, weak hash crack, OSINT trail.

**Level 4 — Cyber Responder (250 pts):** incident reporting, macro malware safety, MITM awareness, link investigation, reset + review.

**Level 5 — Cyber Strategist (300 pts):** phishing campaigns, SQLi demo, password audits, OSINT recon, ethical exploit sim.

**Level 6 — Cyber Commander (400 pts):** enterprise response, server hardening, PCAP analysis, insider threat, policy strategy.

> Full narratives & flags are available in `/writeups/` and `/challenges/` for organizers.

---

## 🧪 Example Challenges

**Awareness/Web (Easy):**

* *Hidden in Plain Sight:* Find `FLAG{Inspect_Element_Pro}` in HTML comments.
* *Phish or Legit?:* Spot a spoofed sender & mismatched link; `FLAG{Always_Check_The_Link}`.

**Forensics (Intermediate):**

* *Stego Lite:* Run `strings` on an image to reveal `FLAG{Hidden_Pixels_Tell_Tales}`.
* *Mini PCAP:* Identify suspicious domain in traffic; `FLAG{Traffic_Analyzed}`.

**Crypto/Hashing (Mixed):**

* *Weak MD5:* Crack `5f4dcc3b5aa765d61d8327deb882cf99` → `password`; `FLAG{Hash_Cracked}`.

**OSINT (Mixed):**

* *Username Pivot:* Reused handle on multiple platforms; decode Base64 → `FLAG{OSINT_Master}`.

> **Note:** Flags in this repo are examples. Event flags will differ.

---

## 📝 Write-ups & Walkthroughs

* Level 1 Walkthrough — `docs/walkthroughs/level1.md`
* Level 2 Walkthrough — `docs/walkthroughs/level2.md`
* Level 3 Walkthrough — `docs/walkthroughs/level3.md`
* Level 4 Walkthrough — `docs/walkthroughs/level4.md`
* Level 5 Walkthrough — `docs/walkthroughs/level5.md`
* Level 6 Walkthrough — `docs/walkthroughs/level6.md`

Each write-up explains the **thinking process**, not just answers — perfect for learning & coaching.

---

## 🧰 Resources & Tools

* **Learning:** OWASP Top 10, Web Security Academy, OverTheWire, PicoCTF, TryHackMe (intro)
* **Utilities:** Burp Suite Community, Wireshark, CyberChef, Hashcat/John, ExifTool
* **Mindset:** Report responsibly, follow event rules, practice safe testing.

---

## 🤝 Contributing

We welcome challenge ideas, fixes, and docs!

* Fork the repo, create a branch, and open a PR.
* Use the PR template.
* Keep spoilers out of public challenge folders; place solution notes in `/solutions/`.

### Good First Issues

* Typos/clarity in docs
* Add beginner-friendly hints
* Localized content (e.g., MoMo scam examples, regional languages)

---

## 📏 Code of Conduct

Be kind, inclusive, and respectful. No harassment, hate speech, or doxxing. Report issues to maintainers.

---

## 🪪 License

MIT License — see `LICENSE` for details.

---

# 📄 Starter Files (drop into your new repo)

## `README.md`

(Use the content of this page.)

## `docs/rules.md`

```
# CTF Rules (Allsafeafrica x Simulation Labs)
- Be ethical. Do not attack infrastructure outside the scope.
- No automated brute force or DDoS.
- Don’t share flags during active events.
- Respect rate limits and other players.
- Report issues via GitHub or event chat.
```

## `docs/setup.md`

```
# Setup & Access
1) Register via Allsafeafrica: https://allsafeafrica.com
2) Create your event profile on our Simulation Labs instance (link shared per event).
3) Read rules and join the community channel (link on event page).
4) Pick your level and start solving. Submit flags on the platform.
```

## `.github/ISSUE_TEMPLATE.md`

```
## Issue Type
- [ ] Bug in challenge
- [ ] Clarity / Wording
- [ ] Hint request
- [ ] Resource suggestion

## Challenge/Doc
Name or path:

## Details
What happened / what to improve:

## Suggested Fix
(Optional)
```

## `.github/PULL_REQUEST_TEMPLATE.md`

```
## Summary
What does this PR add/change?

## Type
- [ ] Docs
- [ ] New challenge
- [ ] Fix

## Notes
Link to related issue(s). Avoid spoilers in public diffs.
```

## `CONTRIBUTING.md`

```
# Contributing Guide
1. Fork and branch from `main`.
2. Write clearly; add hints where helpful.
3. Keep flags unique for events (don’t reuse repo example flags).
4. Add tests/data under `/challenges/<category>/`.
5. Open a PR; CI checks must pass.
```

## `CODE_OF_CONDUCT.md`

```
# Code of Conduct
We are committed to a harassment-free, inclusive community.
- Be respectful and constructive.
- Use inclusive language.
- No harassment or discriminatory behavior.
Violations may result in moderation actions.
```

## `LICENSE`

```
MIT License

Copyright (c) 2025 Allsafeafrica

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

> Questions or collab? Open an issue or ping us via [https://allsafeafrica.com](https://allsafeafrica.com)
