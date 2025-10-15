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
# Lessons Learned so Far
# 1. Understand Docker and how you need a container of
#    Ollama before connecting the Ollama Chat Model.
# 2. Understand the Docker and Ollama commands to 
#    troubleshoot the n8n VPS.
# 3. Taking out the docker containers doesn't work unless 
#    you reimage the VPS and restart the image.
# 4. Understand how web scraping and webhooks work and the
#    differences of the two.
# 5. Understand the docker_compose.yml file and what it 
#    does.
# 6. Understand how n8n workflows work (triggers, modules, 
#    etc.)
