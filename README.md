<h1 align='center'>Upload.ai</h1>

<p align='center'>
  <img src='https://github.com/RayanneRamos/nlw-setup-web/assets/43352880/91b23818-ef2a-45a2-8129-6d126457bec1' alt='upload.ai' />
</p>

<p  align='center'>
  <img src='https://img.shields.io/badge/license-MIT-%23835afd' alt='License' />
  <img src='https://img.shields.io/badge/forks-MIT-%23835afd' alt='Forks' />
  <img src='https://img.shields.io/badge/stars-MIT-%23835afd' alt='Stars' />
</p>

<br>

## 💻 Projeto

[Uploadai](https://upload-ai-o566eeb0b-rayanneramos.vercel.app/) É um projeto desenvolvido durante a Next Level Week apresentado pela Rocketseat nos dias 11 de Setembro a 15 de Setembro de 2023. O projeto consiste numa interface web utilizando a inteligência artificial para fazer a transcrição de um vídeo upado na plataforma e gerar um título ou uma descrição para o YouTube utilizando o chat GPT.

## 🧪 Technologies

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Typescript](https://www.typescriptlang.org/)
- [Prisma](https://www.prisma.io/)
- [Fastify](https://fastify.io/)
- [Dotenv](https://www.npmjs.com/package/dotenv)
- [Ai](https://github.com/vercel/ai)
- [OpenAI](https://openai.com/)
- [Zod](https://zod.dev/)

## 🚀 Instalação

```bash
  # Clone o repositório e entre na pasta do projeto
  $ git clone https://github.com/RayanneRamos/upload-ai-server.git
  $ cd upload-ai-server
  # Instale as dependências
  $ npm install
  # ou
  $ yarn install
  # Execute a aplicação
  $ npm run dev
  # ou
  $ yarn start
```

## 🧩 Rotas do Server

Aqui você encontra todas as rotas disponíveis na aplicação.

- `GET http://localhost:3333/prompts` - Busca todos os prompts
- `POST http://localhost:3333/videos` - Sobe o vídeo para a aplicação
- `POST http://localhost:3333/videos/:videoId/transcription` - Cria a transcrição do vídeo upado
- `POST http://localhost:3333/ai/complete`- Gera o resultado selecionado pelo prompt via inteligência artificial

## 📝 License

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para obter mais detalhes.

---

<p align='center'>Criado by Rayanne Ramos</p>
