![alt imagem de capa](./.github/wallpaper.png)
# NLW IA - upload.ai Mastery #


O projeto NLW IA Mastery Upload.ai é uma aplicação web desenvolvida durante o evento NLW IA da Rocketseat. Ela utiliza tecnologias avançadas para converter vídeos em áudio, transcrever o conteúdo e criar automaticamente títulos e descrições para vídeos no YouTube. Isso demonstra como a Inteligência Artificial pode melhorar a eficiência em tarefas cotidianas relacionadas à mídia online.

## Stacks utilizadas ##

### BACK-END ###

- [Node.js](https://nodejs.org/)
- [Prisma](https://prisma.io/)
- [Fastify](https://fastify.io/)
- [TypeScript](https://www.typescriptlang.org/)
- [OpenAI](https://openai.com/)
- [Sqlite](https://openai.com/)


### FRONT-END ###

- [Vite.js](https://vitejs.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [FFmpeg](https://www.ffmpeg.org/)
- [shadcn/ui](https://ui.shadcn.com/)
- [Axios](https://axios-http.com/)

## Funcionalidades da Aplicação ##

### - FRONT-END ###

O Frontend da aplicação converte vídeos em áudio e envia esses áudios com prompts e configurações ao Backend. Ele aguarda a resposta do Backend, que inclui título, descrição e transcrição do áudio, úteis para postagens no YouTube.

### - BACK-END ###

O Backend recebe a solicitação do Frontend, envia o áudio para o ChatGPT, que transcreve e cria título e descrição com base no prompt.

## Clonando e executando o app ##

1. Clone o repositório usando o comando:

```bash
git clone https://github.com/Humberto08/upload-ai-nlw.git
```

2. Navegue para o diretório raiz do projeto e instale as dependências (frontend e backend):


3. Instale as dependências do Backend:

```bash
npm install
```

4. Instale as dependências do Frontend:

```bash
npm install
```

5. Certifique-se de configurar as variáveis de ambiente essenciais para o projeto.

6. Execute o Backend:

```bash
npm run dev
```

7. Execute o Frontend:

```bash
npm run dev


```

<div id='contatos' align="center">
  <p align="center">Made with 💜 by Humberto Luciano</p>
  <div id="contatos" align="center">
    <a href="https://www.linkedin.com/in/humberto-luciano/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
</div>





