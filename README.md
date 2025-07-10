# Jade Multi-Agent Reindeer Rescue 

This project was developed during our Erasmus studies in Granada, Spain, as part of the course **Desarrollo Basado en Agentes** at the University of Granada.
[🎥 Watch Demo Video](https://drive.google.com/file/d/1UPGwCAoNi2u-13-iuFopQV83D7dd4sAX/view?usp=sharing)

## Project Description

This simulation is based on a festive storyline where Santa Claus has lost his reindeer due to a snowstorm in Lapland. Using the **JADE (Java Agent DEvelopment Framework)**, we implemented a system of intelligent agents to coordinate the rescue mission through message-based interactions.

The main learning goals include:
- Multi-agent system design
- Communication using FIPA-compliant protocols
- Trust management between agents
- Heuristic-based pathfinding in grid environments
- Use of intermediate agents (translators) for communication format handling


## Agents and Behaviours

The system involves the following agents:
- **Santa**: Validates the mission and communicates with the team.
- **Rudolph**: Provides coordinates of the lost reindeer.
- **Scout**: Main searching agent who explores the map.
- **Translator**: Interprets between Santa’s formal messages and Gen-Z slang used by Scout.

Core behaviors include:
- `HandleVolunteerRequestBehaviour`
- `HandlePositionRequestBehaviour`
- `RequestSearchBehaviour`
- `TranslationBehaviour`
- `WalkBehaviour`
- `StepBehaviour`

## Environment

The agent operates within a grid-based environment, implemented through:
- `Environment.java`
- `Map.java`
- `Node.java`
- `GridLayoutManager.java`

Search and movement strategies rely on:
- `HeuristicHandler.java`
- `WalkBehaviour.java`

## Technologies Used

- **Java**
- **JADE Framework** for multi-agent development
- **FIPA ACL messages** for inter-agent communication


## Course Info

- **Course**: Desarrollo Basado en Agentes (Agent-Based Design)
- **Instructor**: Manuel Jesús Cobo Martín
- **University**: Universidad de Granada
- **Academic Year**: 2024/2025

## Authors

- **Badi Al-Bahra**
- **Christiana Mousele**
- **Diana Dmitriyeva**
- **Gabriel Tavares**

## 📝 License

This project is for educational purposes only.
