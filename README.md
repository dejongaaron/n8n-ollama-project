# n8n-ollama-project
This is my repository for my n8n-ollama-project.

This project is an n8n server that is doing two news aggregator posts daily on Discord using the qwen3:0.6b model which is an Ollama engine.

There are some things that I will post later about this project. Working on the workflow automation and having difficulties setting it up, currently I need to use the sort option due to getting too much data. Working on the fields that I need like title, source, and content.

I will post more about this project and it is a public repository.

The n8n server I am doing is a VPS from Hostinger that I am using on an Ubuntu Server. There are some issues with my workflow that I am working on and will provide more information regarding the three workflows that I am doing.

I added another workflow to provide light-hearted humor with Inca inspired jokes about things like llamas and cocoa leaves since I am using Ollama as my AI.

# update for 10-14-25
I have gotten the Ollama chat dialog, however this is on the Ubuntu Server that I am using to host the VPS on. There are some more workflow items that I have tried and got it to process up to the AI Agent.

Successfully changed the Discord webhook and connected to the Ollama service however I was not successful in getting the right engine. I am wanting to use qwen3:0.6b engine that is available on the Ubuntu Server just not on the VPS.

Created a docker instance for ollama again (had it running but crashed my VPS so this is from the reimage). I am working on the docker exec commands to pull the right engine along with changing the docker_compose.yml file. I will update on the result of my troubleshooting.

# update for 10-15-25
Lessons Learned so Far

Understand Docker and how you need a container of Ollama before connecting the Ollama Chat Model. Understand the Docker and Ollama commands to troubleshoot the n8n VPS. Taking out the docker containers doesn't work unless you reimage the VPS and restart the image.Understand how web scraping and webhooks work and the differences of the two. Understand the docker_compose.yml file and what it does. Understand how n8n workflows work (triggers, modules, etc.)

# update for 10-23-25
I have made the AI Agent function correctly, however I am in a learning more process. This project has turned into more of a hobby project and has allowed me to get more experience and more training on Prompt Engineering, n8n, Docker, and Ollama. I am studying more to get better at these technologies. 

Udemy courses that I am using to gain this knowledge.

Docker for the Absolute Beginner - Hands-on - DevOps - 36% complete

n8n Automation: Build AI Agents, APIs & No-code Workflows - 10% complete

Mastering Ollama: Build Private Local LLM Apps with Python - 14% complete

Complete Prompt Engineering for AI Bootcamp (2025) - 16% complete

As this project is a hobby based project I will be updating the status every once in a while. I will post my prompts and n8n workflows when completed.


