## Server

### Create a new project

```bash
npm init -y
```

### Install dependencies

```bash
npm install fastify fastify-socket.io ioredis close-with-grace dotenv socket.io @fastify/cors
```

### Install dev dependencies

```bash
npm install --save-dev @types/node tsx typescript @types/ws
```

### Create tsconfig.json

```bash
npx tsc --init
```

## frontend

### Create Next.js app

```base
npm create next-app ui
```

### Install dependencies

```bash
npm install socket.io-client
```

### Install dev dependencies

```bash
npm install @types/ws -D
```

### Install shadcn-ui

```bash
npx shadcn-ui@latest init
```

### Add components

```bash
npx shadcn-ui@latest add textarea button form
```
