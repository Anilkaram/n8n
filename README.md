# n8n
n8n is an open-source workflow automation platform that enables you to visually create, automate, and orchestrate tasks and integrations between various apps, services, and APIs with low-code flexibility.

# A simple workflow automation triggering mail based on chat with attachment
- workflow
<img width="1664" height="843" alt="image" src="https://github.com/user-attachments/assets/90297d14-2041-4b19-a8cc-9962eeb76e37" />

- Output 
<img width="2399" height="466" alt="image" src="https://github.com/user-attachments/assets/73848c9f-83f3-44e0-aa82-c8815ab311af" />


# installation 
using Docker : 
  - mkdir -p ~/.n8n
  - sudo chown -R 1000:1000 ~/.n8n
  - sudo chmod -R 755 ~/.n8n
  - docker pull n8nio/n8n
  - docker run -d --name n8n -p 5678:5678 \
  -e N8N_SECURE_COOKIE=false \
  -v ~/.n8n:/home/node/.n8n n8nio/n8n


