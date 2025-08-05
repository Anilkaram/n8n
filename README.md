# n8n
n8n is an open-source workflow automation platform that enables you to visually create, automate, and orchestrate tasks and integrations between various apps, services, and APIs with low-code flexibility.

# A simple workflow automation triggering mail based on chat 
- workflow
<img width="1664" height="843" alt="image" src="https://github.com/user-attachments/assets/90297d14-2041-4b19-a8cc-9962eeb76e37" />
- Output
<img width="774" height="766" alt="image" src="https://github.com/user-attachments/assets/01b5997e-514b-4d67-a749-0cfe23792f28" />

# installation 
using Docker : 
  - mkdir -p ~/.n8n
  - sudo chown -R 1000:1000 ~/.n8n
  - sudo chmod -R 755 ~/.n8n
  - docker pull n8nio/n8n
  - docker run -d --name n8n -p 5678:5678 \
  -e N8N_SECURE_COOKIE=false \
  -v ~/.n8n:/home/node/.n8n n8nio/n8n<img width="397" height="180" alt="image" src="https://github.com/user-attachments/assets/08b53081-3a5f-42cf-b326-f59c4348cf72" />

