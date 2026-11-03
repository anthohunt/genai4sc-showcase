> Showcase repository: the code and data of this project are private; this README describes it. / Dépôt vitrine : le code et les données de ce projet sont privés ; ce README le décrit.

# GenAI4SC course: AI agents for supply chain

An international course for supply chain professionals, in 9 two-hour sessions, for which I prepared and taught the three sessions on agents, two of them co-taught.

## The problem

Supply chain professionals hear about AI agents, but few have built one. This course has them build, live, agents that search documents, query the web and split the work between them. The guiding principle: start from the business decision, not from the technology. Participants do not need to know how to code.

## How it works

- Session on agent foundations: four exercises in n8n, from a first conversational agent to an agent that queries a document base (RAG) and searches the web.
- Session on orchestration: a main agent hands work to six specialised sub-agents (analysis, web research, document base, charts, report writing, quality control), grouped into teams, on a fictional company case.
- Session on application design: each group opens a terminal in its browser with a single password and works with a coding agent through a light pipeline: idea, architecture map, interactive mockup, user stories, final presentation.
- An online step-by-step quiz goes with the exercises: the next step unlocks with a code given by the instructor, and a leaderboard updates live.

## What is built

Course delivered in full: 9 sessions. Material delivered:

- 19 n8n workflows for the first two sessions (exercises, solutions, six sub-agents, six teams), with a mirrored backup server.
- Four web terminals, one per group: the session stays open after a page reload, and only one agent runs per group whatever the number of students.
- A 21-slide deck for the orchestration session, tutorials and exercise videos.

End-of-course survey (11 respondents): 9 would recommend the course, 2 are neutral; 100 % rate the instructors' presentation skills as excellent.

## What is public

This page is public. The course material, the workflows and the students' terminals remain private.

## Tech stack

- n8n
- Models served by Groq (gpt-oss-120b, llama-3.3-70b); embeddings with Ollama
- Tavily (web search, over MCP)
- `ttyd`, `tmux`, Docker, Traefik, Node.js
- Google Apps Script (quiz and leaderboard)
- Slidev (slides)

---

## Version française

# Cours GenAI4SC : agents d'IA pour la supply chain

Un cours international pour professionnels de la supply chain, en 9 sessions de 2 heures, dont j'ai préparé et donné les trois sessions sur les agents, deux d'entre elles en binôme.

## Le problème

Les professionnels de la supply chain entendent parler d'agents d'IA, mais peu en ont construit un. Ce cours leur fait monter, en direct, des agents qui cherchent dans des documents, interrogent le web et se répartissent le travail. Le principe suivi : partir de la décision métier, pas de la technologie. Les participants n'ont pas besoin de savoir programmer.

## Comment ça marche

- Session sur les bases des agents : quatre exercices dans n8n, d'un premier agent conversationnel à un agent qui consulte une base documentaire (RAG) et cherche sur le web.
- Session sur l'orchestration : un agent principal confie le travail à six sous-agents spécialisés (analyse, recherche web, base documentaire, graphiques, rédaction du rapport, contrôle qualité), regroupés en équipes, sur un cas d'entreprise fictif.
- Session sur la conception d'application : chaque groupe ouvre un terminal dans son navigateur avec un seul mot de passe et déroule avec un agent de programmation une chaîne allégée : idée, carte d'architecture, maquette interactive, histoires utilisateur, présentation finale.
- Un quiz en ligne à étapes accompagne les exercices : on débloque l'étape suivante avec un code donné par l'instructeur, et un classement s'affiche en direct.

## Ce qui est construit

Cours donné en entier : 9 sessions. Matériel livré :

- 19 workflows n8n pour les deux premières sessions (exercices, solutions, six sous-agents, six équipes), avec un serveur de secours en miroir.
- Quatre terminaux web, un par groupe : la session reste ouverte après un rechargement de page, et un seul agent tourne par groupe quel que soit le nombre d'élèves.
- Un support de 21 diapositives pour la session d'orchestration, des tutoriels et des vidéos d'exercices.

Résultat du sondage de fin de cours (11 répondants) : 9 recommanderaient le cours, 2 sont neutres ; 100 % jugent excellentes les qualités de présentation des instructeurs.

## Ce qui est public

Cette fiche est publique. Le matériel du cours, les workflows et les terminaux des élèves restent privés.

## Pile technique

- n8n
- Modèles servis par Groq (gpt-oss-120b, llama-3.3-70b) ; embeddings avec Ollama
- Tavily (recherche web, par MCP)
- `ttyd`, `tmux`, Docker, Traefik, Node.js
- Google Apps Script (quiz et classement)
- Slidev (diapositives)
