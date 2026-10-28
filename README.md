### Hi, I'm Armaan! Thanks for taking a minute to see what I've been working on:

![Armaan Kolsawala — software engineer](assets/profile-banner-slate-blue.png)

## Incident Copilot

Claude investigates simulated outages across seven services and six fault types using logs, metrics, deployments, and runbooks. The demo shows its diagnosis, supporting evidence, and suggested next steps.

**[Live demo →](https://incident-copilot.fly.dev/#access=475qN7AHUNlRQItTZJFRFVjjpmybe4-vFtpIzUzgix4xHBRtj2_xHDFHYbE_R3Ug)** · **[Code](https://github.com/armaankols/incident-copilot)** · **[Evaluation details](https://github.com/armaankols/incident-copilot/blob/main/results/RESULTS.md)**

**Stack:** Python · FastAPI · Claude · LangGraph · MCP · TF-IDF RAG · SQLite · Docker · Fly.io

- **Agent workflow:** LangGraph coordinates Claude's tool calls through MCP; TF-IDF retrieval finds relevant runbook sections.
- **Evidence and recovery:** Diagnoses cite observations and pass fault-specific checks. Recovery guidance is separate; no service changes are executed.
- **Evaluation:** Seeded cases, ground-truth grading, rule baselines, confidence intervals, and token-cost tracking.
- **Hosted demo:** Saved investigations, link-based access, owner-only Sonnet, and persistent SQLite budget and rate controls.

**Owner-reported synthetic results:** 38/40 correct diagnoses (95%), appropriate abstention on 9/10 undiagnosable cases (90%), and $0.04 average API cost per incident. Run-level records for this batch are not included in the repository; these results do not establish production reliability.

## More of my work

- **[Surplus](https://github.com/armaankols/f22-sustainability-surplus)** — Food inventory app with searchable items, filters, and a virtual fridge. JavaScript and Firebase.
- **[Email Spam Detection](https://github.com/armaankols/email-spam-detection)** — Spam classification project in a Jupyter notebook.
- **[SuperMarioTiles](https://github.com/armaankols/SuperMarioTiles)** — Embedded C/C++ game with tile movement, sound, and button controls.
- **[Nocial](https://github.com/armaankols/Nocial)** — Android app that encourages less social media use through friendly competition. Java, Flask, and MySQL.
- **[WeatherApp](https://github.com/armaankols/WeatherApp)** — Android weather application built with Java.
