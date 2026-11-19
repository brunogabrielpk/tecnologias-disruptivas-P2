# P2 — Containerizando um site estático com Docker

## Objetivo

Containerizar um **site estático** (HTML/CSS/JS) com Docker, de forma que a página possa ser acessada pelo navegador a partir de um container em execução.

## Prazo

Entrega até **26/11 às 14:00**.

## O que entregar

Um repositório contendo:

1. Os arquivos do site estático (`index.html` com CSS/JS/imagens)
2. Um `Dockerfile`
3. Um `README.md` próprio do seu trabalho, com as instruções de uso
4. Evidência de funcionamento (vídeo curto do site aberto no navegador via Docker)

## O que fazer

1. Crie um site estático simples (uma página já é suficiente mas que tenha algum CSS/JS/imagem) **ou** use um site estático que você já tenha.
2. Escreva um `Dockerfile` que sirva esse site (por exemplo, usando **Nginx** ou outra imagem adequada para conteúdo estático).
3. Faça o build da imagem e execute o container, mapeando a porta (ex.: `8080:80`).
4. Acesse `http://localhost:8080` (ou a porta que você escolher) e confirme que a página carrega.
5. Documente no seu `README.md`:
   - comandos para build da imagem;
   - comandos para executar o container;
   - breve explicação, com suas palavras, da diferença entre **imagem** e **container**.

## Fora do escopo

Não é necessário usar volumes, Docker Compose, bancos de dados ou builds multi-stage.

## Observações

- O site deve abrir corretamente no navegador a partir do container.
- O `Dockerfile` deve estar na raiz do projeto (ou em caminho indicado no seu README).
- Não inclua credenciais ou dados sensíveis no repositório.
- Informe a LLM que te auxiliou no processo de desenvolvimento ( ChatGPT, Claude, Gemini, DeepSeek, Qwen, Grok, ou qualquer outro)