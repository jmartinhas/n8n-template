# n8n-template

Currently using 1.94.1 because of issue described here:
https://community.n8n.io/t/connection-lost-to-n8n-server/125694

```

docker volume create n8n_data

docker run -it --rm --name n8n -p 5678:5678 -e WEBHOOK_URL=https://crispy-rotary-phone-px95rw99wrr276vx.github.dev/ -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n:1.94.1
```
