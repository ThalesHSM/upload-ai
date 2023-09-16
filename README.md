# upload-ai

Project made during NLW IA from rocketseat / Projeto desenvolvido durante NLW IA da Rocketseat


## Features

+ Upload video
+ Transform video to mp3 file
+ Transcribe video audio to text using AI

## Technologies

+ Vite.JS
+ TypeScript
+ Node.JS

## Libraries

+ Radix-ui
+ Tailwind CSS
+ Fastify
+ Axios
+ Prisma
+ OpenAI


## How to start - Backend
1. #### Clone the Repository
2. #### Enter upload-ai-server folder
3. #### pnpm install
4. #### Start prisma:
```
pnpm prisma init --datasource-provider sqlite
```
5. #### Create tables:
```
pnpm prisma migrate dev
```
6. #### Populate prompt:
```
pnpm prisma db seed
```
7. #### pnpm run dev

## How to start - Frontend

1. #### Clone the Repository
2. #### Enter upload-ai-web folder
3. #### pnpm install
5. #### pnpm run dev
