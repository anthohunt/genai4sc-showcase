[English](README.md) · **Français**

**Anthony Hunt** · [Fiche du projet sur ingevision.cloud](https://ingevision.cloud/?p=genai4sc) · [LinkedIn](https://www.linkedin.com/in/anthony-hunt-3948a9196) · [Profil GitHub](https://github.com/anthohunt)

> Dépôt vitrine : le code et les données de ce projet sont privés ; ce README le décrit.

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
