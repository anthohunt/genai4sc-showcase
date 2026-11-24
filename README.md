**English** · [Français](README.fr.md)

# GenAI4SC: AI agents for supply chain

**Supply chain professionals build AI agents live, without writing code.** My three sessions in GenAI4SC, an international 9-session course: I prepared and taught all three, two with a co-instructor.

![Real captures from the three sessions: an n8n agent with eight tools fails, a main agent with sub-agents succeeds, the class votes on the board memo, then Claude Code takes a group from an idea to an architecture map, a mockup and a presentation, while the course architecture lights up step by step](docs/demo.webp)

<details><summary>French version</summary>

![Vraies captures des trois sessions : un agent n8n à huit outils échoue, un agent principal avec des sous-agents réussit, la classe vote sur le rapport, puis Claude Code mène un groupe d'une idée à une carte d'architecture, une maquette et une présentation, pendant que l'architecture du cours s'allume étape par étape](docs/demo.fr.webp)

</details>

*Instructor demos recorded in n8n, course material, and the app-design steps on the course example.*

## Sessions

- **Agent foundations.** Four n8n exercises, from a first chat agent to one that reads a document base (RAG) and searches the web. The last one shows why one agent with eight tools fails where a main agent with two sub-agents succeeds.
- **Orchestration.** On a fictional company, a main agent hands the work to six specialised sub-agents grouped into teams. Each group's brief goes to a shared gallery where the class votes.
- **App design.** Each group opens a terminal in its browser with one password and goes, with Claude Code, from a one-line idea to an architecture map, design directions, an interactive mockup with its user stories, and a one-link presentation.
- **Step-by-step quiz.** The next step unlocks with a code the instructor projects; a leaderboard updates live.

## Architecture

![GenAI4SC architecture: participant groups build and run agents on an n8n server, where a main agent delegates to sub-agent teams that query a document base and call Groq and Tavily; the brief goes to an Apps Script gallery next to the step quiz; for app design each group opens a terminal running Claude Code that publishes a public page](docs/architecture.svg)

<details><summary>French version</summary>

![Architecture de GenAI4SC : les groupes construisent et lancent des agents sur un serveur n8n, où un agent principal délègue à des équipes de sous-agents qui consultent une base documentaire et appellent Groq et Tavily ; le rapport part dans une galerie Apps Script à côté du quiz à étapes ; pour la conception d'appli, chaque groupe ouvre un terminal avec Claude Code qui publie une page publique](docs/architecture.fr.svg)

</details>

## Delivered

- **Course.** Given in full in spring 2026, online: 9 two-hour sessions.
- **Material.** 19 n8n workflows with a mirrored backup server, four group terminals, a 21-slide deck, tutorials and exercise videos.
- **Feedback.** Whole-course survey, 11 respondents: 9 would recommend the course, 2 are neutral; all agree the instructors' presentation skills were excellent (55% strongly).
- **Now.** The main n8n server and the group terminals are stopped; the school's backup n8n server still runs. Material and participants' work stay private.
- **Stack.** n8n, Groq, Tavily, Ollama (embeddings), `ttyd`, `tmux`, Docker, Traefik, Node.js, Claude Code, Google Apps Script, Slidev.

---

**Anthony Hunt** · [ingevision.cloud](https://ingevision.cloud/?lang=en&p=genai4sc) · [LinkedIn](https://www.linkedin.com/in/anthony-hunt-3948a9196) · [GitHub](https://github.com/anthohunt)
