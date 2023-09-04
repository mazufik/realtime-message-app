# Build Realtime App (chatting) Using WebSockets, Redis, Fastify and Next

## Features
1. Send and receive messages
2. Show current connection count

## Tech Stack
1. Fastify - Backend
2. WebSockets - Realtime
3. Next.js - Frontend
4. Tailwindcss (Shadcn UI) - Styling
5. Redis - Pub/Sub
6. Docker/Docker Compose - Containerization
7. Github Action - CI/CD

## Debugging
### Websockets
1. Make sure you are using `wss://` and not `ws://` in production
2. Use debug mode in Caddy server
```
{
    debug
}
```

### Docker
1. List our running docker containers
```bash
docker ps
```
2. Stop a running container
```bash
docker stop <container id>
```

3. Remove a container
```bash
docker rm <container id>
```

4. List out networks
```bash
docker network ls
```

5. Remove a network
```bash
docker network rm <network id>
```
