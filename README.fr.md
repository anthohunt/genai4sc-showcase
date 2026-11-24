[English](README.md) · **Français**

# GenAI4SC : agents d'IA pour la supply chain

**Des professionnels de la supply chain construisent des agents d'IA en direct, sans écrire de code.** Mes trois sessions dans GenAI4SC, un cours international en 9 sessions : je les ai préparées et données, deux en binôme.

![Vraies captures des trois sessions en anglais : un agent n8n à huit outils échoue, un agent principal avec des sous-agents réussit, la classe vote sur le rapport, puis Claude Code mène un groupe d'une idée à une carte d'architecture, une maquette et une présentation, pendant que l'architecture du cours s'allume étape par étape](docs/demo.webp)

<details><summary>Version française</summary>

![Vraies captures des trois sessions : un agent n8n à huit outils échoue, un agent principal avec des sous-agents réussit, la classe vote sur le rapport, puis Claude Code mène un groupe d'une idée à une carte d'architecture, une maquette et une présentation, pendant que l'architecture du cours s'allume étape par étape](docs/demo.fr.webp)

</details>

*Démos de l'instructeur enregistrées dans n8n, supports du cours et étapes de conception d'appli sur l'exemple du cours.*

## Sessions

- **Bases des agents.** Quatre exercices dans n8n, d'un premier agent conversationnel à un agent qui consulte une base documentaire (RAG) et cherche sur le web. Le dernier montre pourquoi un agent seul à huit outils échoue là où un agent principal avec deux sous-agents réussit.
- **Orchestration.** Sur une entreprise fictive, un agent principal confie le travail à six sous-agents spécialisés, regroupés en équipes. Le rapport de chaque groupe part dans une galerie commune où la classe vote.
- **Conception d'application.** Chaque groupe ouvre un terminal dans son navigateur avec un seul mot de passe et va, avec Claude Code, d'une idée en une phrase à une carte d'architecture, des pistes de design, une maquette interactive avec ses histoires utilisateur et une présentation en un lien.
- **Quiz à étapes.** L'étape suivante se débloque avec un code projeté par l'instructeur ; un classement s'affiche en direct.

## Architecture

![Architecture de GenAI4SC (en anglais) : les groupes construisent et lancent des agents sur un serveur n8n, où un agent principal délègue à des équipes de sous-agents qui consultent une base documentaire et appellent Groq et Tavily ; le rapport part dans une galerie Apps Script à côté du quiz à étapes ; pour la conception d'appli, chaque groupe ouvre un terminal avec Claude Code qui publie une page publique](docs/architecture.svg)

<details><summary>Schéma en français</summary>

![Architecture de GenAI4SC : les groupes construisent et lancent des agents sur un serveur n8n, où un agent principal délègue à des équipes de sous-agents qui consultent une base documentaire et appellent Groq et Tavily ; le rapport part dans une galerie Apps Script à côté du quiz à étapes ; pour la conception d'appli, chaque groupe ouvre un terminal avec Claude Code qui publie une page publique](docs/architecture.fr.svg)

</details>

## Réalisé

- **Cours.** Donné en entier au printemps 2026, en ligne : 9 sessions de 2 heures.
- **Matériel.** 19 workflows n8n avec un serveur de secours en miroir, quatre terminaux de groupe, un support de 21 diapositives, des tutoriels et des vidéos d'exercices.
- **Retours.** Sondage de l'ensemble du cours, 11 répondants : 9 recommanderaient le cours, 2 sont neutres ; tous jugent excellentes les qualités de présentation des instructeurs (55 % tout à fait d'accord).
- **Aujourd'hui.** Le serveur n8n principal et les terminaux de groupe sont arrêtés ; le serveur n8n de secours de l'école tourne toujours. Le matériel et le travail des participants restent privés.
- **Pile.** n8n, Groq, Tavily, Ollama (embeddings), `ttyd`, `tmux`, Docker, Traefik, Node.js, Claude Code, Google Apps Script, Slidev.

---

**Anthony Hunt** · [ingevision.cloud](https://ingevision.cloud/?p=genai4sc) · [LinkedIn](https://www.linkedin.com/in/anthony-hunt-3948a9196) · [GitHub](https://github.com/anthohunt)
