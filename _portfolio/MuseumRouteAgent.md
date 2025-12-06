---
title: "Museum Route Agent"
excerpt: "A conversational agent that provides routes between different locations in Belo Horizonte, with a primary focus on the city's various museums. Developed as Practical Assignment for the Introduction to Artificial Intelligence course at UFMG. <br/> <br/><img src='/images/astar_route.png' alt='A star route from agent' width='400'> <br/> Image: Route between \"Museu de História Natural da UFMG\" and \"Casa Kubitschek\""
collection: portfolio
---

A conversational agent that provides routes between different locations in Belo Horizonte, with a primary focus on the city's various museums. Developed as Practical Assignment for the Introduction to Artificial Intelligence course at UFMG in the first semester of 2025.

<img src='/images/agent_architecture.png' alt='architecture' width='600'>

Image: Agent Architecture


Code available at [https://github.com/carlabferreira/MuseumRouteAgent](https://github.com/carlabferreira/MuseumRouteAgent)

### Objectives and Key Features:

- Acquisition and utilization of the Belo Horizonte city graph.
- Use of search algorithms for pathfinding.
- Local execution of the Agent, using the ```ollama_chat/qwen3:8b``` model and defined Tools.
- Rendering/Exporting the obtained route as a .png image

<img src='/images/astar_route.png' alt='A star route from agent' width='400'> <br/> Image: Route between "Museu de História Natural da UFMG" and "Casa Kubitschek"

### Technology Stack:
- Ollama Model (qwen3:8b)
- Python libraries (smolagents, networkx, matplotlib, osmnx and more)

### Example
<img src='/images/agent_exec.png' alt='exec' width='600'>

Image: Screenshot showing two route queries and the agent's responses.