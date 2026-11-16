[English](README.md) · **Français**

# GenAI4SC : agents d'IA pour la supply chain

**Des professionnels de la supply chain construisent des agents d'IA en direct, sans écrire de code.** Les trois sessions sur les agents de GenAI4SC, un cours international en 9 sessions ; je les ai préparées et données, deux d'entre elles en binôme.

[![La même demande confiée à un agent seul avec huit outils, qui abandonne, puis à un agent principal avec deux sous-agents, qui rend le rapport (cliquer pour la vidéo complète)](docs/demo.gif)](https://drive.google.com/file/d/1bJ8uv2e7hfYDbE_1NuIyIZVNIgUMSoKV/view)

*Démo de l'instructeur dans n8n : un agent seul avec huit outils abandonne ; un agent principal avec deux sous-agents rend le rapport. Vraie exécution, accélérée. [Vidéo complète (1 min 31)](https://drive.google.com/file/d/1bJ8uv2e7hfYDbE_1NuIyIZVNIgUMSoKV/view)*

## Ce qu'on y fait

- **Bases des agents.** Quatre exercices dans n8n, d'un premier agent conversationnel à un agent qui consulte une base documentaire (RAG) et cherche sur le web.
- **Orchestration.** Sur une entreprise fictive, un agent principal confie le travail à six sous-agents spécialisés (analyse, recherche web, base documentaire, graphiques, rédaction du rapport, contrôle qualité), regroupés en équipes.
- **Conception d'application.** Chaque groupe ouvre un terminal dans son navigateur avec un seul mot de passe et va, avec Claude Code, d'une idée à une carte d'architecture, une maquette interactive, des histoires utilisateur et une présentation finale.
- **Quiz à étapes.** L'étape suivante se débloque avec un code projeté par l'instructeur ; un classement s'affiche en direct.

## Architecture

![Architecture de GenAI4SC : les participants construisent des agents sur un serveur n8n qui appelle Groq et Tavily, valident chaque étape dans un quiz Google, et en session 3 ouvrent un terminal de groupe où Claude Code publie leurs livrables](docs/architecture.svg)

## Réalisé

- **Cours.** Donné en entier au printemps 2026 : 9 sessions de 2 heures.
- **Matériel.** 19 workflows n8n avec un serveur de secours en miroir, quatre terminaux de groupe, un support de 21 diapositives, des tutoriels et des vidéos d'exercices.
- **Retours.** 11 répondants : 9 recommanderaient le cours, 2 sont neutres ; tous jugent excellentes les qualités de présentation des instructeurs.
- **Aujourd'hui.** Les serveurs du cours sont arrêtés.
- **Pile.** n8n, Groq, Tavily, Ollama (embeddings), `ttyd`, `tmux`, Docker, Traefik, Node.js, Google Apps Script, Slidev.

---

**Anthony Hunt** · [ingevision.cloud](https://ingevision.cloud/?p=genai4sc) · [LinkedIn](https://www.linkedin.com/in/anthony-hunt-3948a9196) · [GitHub](https://github.com/anthohunt)

Le matériel du cours, les workflows et le travail des participants sont privés.
