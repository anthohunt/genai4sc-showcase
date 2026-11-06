**English** · [Français](README.fr.md)

**Anthony Hunt** · [Project page on ingevision.cloud](https://ingevision.cloud/?lang=en&p=genai4sc) · [LinkedIn](https://www.linkedin.com/in/anthony-hunt-3948a9196) · [GitHub profile](https://github.com/anthohunt)

> Showcase repository: the code and data of this project are private; this README describes it.

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

End-of-course survey (11 respondents): 9 would recommend the course, 2 are neutral; 100% rate the instructors' presentation skills as excellent.

## What is public

This page is public. The course material, the workflows and the students' terminals remain private.

## Tech stack

- n8n
- Models served by Groq (gpt-oss-120b, llama-3.3-70b); embeddings with Ollama
- Tavily (web search, over MCP)
- `ttyd`, `tmux`, Docker, Traefik, Node.js
- Google Apps Script (quiz and leaderboard)
- Slidev (slides)
